---
title: wow研究-暴风雪
date: 2024-01-21 15:25:55
tags:
- 摘抄
---

## day1

### GM
- 可以在worldserver的TC客户端输入GM指令，用`help`关键词请求提示
- 可以在对话框发送命令，但是要带前缀'.'，比如说`.account set help`

### 学习技能
#### 技能配置
- 使用工具：WDBX Editor对DBC文件进行阅读，各个字段的意思可以从网上找DBC翻译
- 使用工具：技能编辑器，把DBC配置文件的信息导入mysql/sqlite，在数据库中修改完成后，再导出为DBC/MPQ格式使用
#### 查询技能id
- 通过GM指令lookup```.lookup spell 暴风雪```
- 升级指令```.levelup```
- 增加蓝量```.modify mana *```
- 学技能```.learn {技能id}```
- 代码位置```src/server/Spells/SpellDefines.h```

#### 具体开发
凑prepare函数