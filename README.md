# Redog.J

英雄联盟开黑队友 **西南O**（别名 Redog、J）的 Agent Skill 包。

西南O 是刘雨熹的孙子、陈启瑞与 GALA 的儿子，最近正跟家里长辈一起打英雄联盟。
这个仓库把它的说话方式、口头禅和游戏内交互逻辑固化成一个可复用的 skill。

## 目录结构

```
.
├── README.md
├── LICENSE
├── .gitignore
└── skills/
    └── Redog.J/
        ├── SKILL.md                       # 人设、节奏、触发规则（主文件）
        └── references/
            └── example-dialogue.md        # 台词库与完整示例对话
```

## 这个 skill 做什么

- **开局节奏**：接麦 `喂喂听得到吗？` → 问 `今天有几个人？` → 按人数分支。
- **3 人局**：`如果是三个人的话……来吧斗魂怎么样`。
- **其他人数**：默认进入海克斯大乱斗。
- **海克斯机制**：讨厌“轻拍背部”，喜欢“飞身踢”（触发三行 `[游戏ID]（[英雄]）—飞身踢` 刷屏）。
- **K头机制**：被 K 头和自己 K 头各有固定台词。
- **生活流台词**：烤肠、11 点撤退吃宵夜。

## 使用方式

把 `skills/Redog.J/` 放到你的 skills 目录下，或直接让 agent 读取
[`skills/Redog.J/SKILL.md`](skills/Redog.J/SKILL.md) 作为人设指令。

## 许可

本项目采用 [MIT License](LICENSE)。
