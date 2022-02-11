---
title: git复习
date: 2022-02-11 16:33:46
tags: git
categories:
 - work-tool
 - git
---
{% markmap 900px %}
# git内容

- 暂存区增删改
  - 增 git add [-p] [file]
  - 删 git rm [--cached] [file]
  - 改 git mv [file-origin] [file-newname]
- 分支操作
  - 查: git branch -a
  - 切换到: git chechout [branch]
  - 增
    - 新建并切换到: git chechout -b [branch-name]
    - 新建local-branch并与remote-branch关联: git branch --track [branch] [remote-branch]
    - 新建remote分支: git push origin [new-origin-branch-name]
  - 删
    - 删本地分支: git branch -d [branch-name]
    - 删远程: git push origin --delete [branch-name]
  - 改
    - 合并某branch到当前: git merge [branch]
    - 建立local-branch与remote-branch关联: git [push|branch] [--set-upstream]
    - 用某个commit创建分支：git branch [branch-name] [commit]
    - 合并某commit: git cherry-pick [commit]
- tag
  - 打tag: git tag [tag]
  - 查看tag: git tag
  - 删tag: git tag -d [tag]
  - 提交tag: git push --tags
- local-repo | index | worktree 撤销
  - index -> work : git checkout
  - (file) index -> work : git chechout [file]
  - (file) local-repo/commit -> index & work : checkout [commit] [file]
  - (file) local-repo/HEAD ->index : reset [file]
  - local-repo/HEAD -> index & work : git reset --hard
  - local-repo/commit -> local-repo/HEAD & index : git reset [commit]
  - local-repo/commit -> local-repo/HEAD & index & work : git reset --hard [commit]
  - local-repo/commit -> local-repo/HEAD : git reset --keep [commit]
- git revert
- git stash [pop]
- git archive
- git commit
{%endmarkmap%}
