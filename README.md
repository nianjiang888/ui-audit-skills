# 中文 UI/产品审计技能

1 个自包含 Agent 技能：围绕界面做六维审计，叠加微信小程序 / Ant Design / iOS 规范、各平台投稿画幅、中文排版与反 AI 味文案体检，输出带整改建议的中文审计报告。

共 **1** 个技能包，全部自包含（包内即可跑通，无需额外依赖）。

## 技能一览

| # | 技能包 | 名称 | 做什么 |
|---|---|---|---|
| 1 | `cn-ui-audit` | 中文 UI/产品审计助手 | 中文产品/UI 审计。触发词：UI 审计/界面体检/设计评审/页面好不好/改改这个界面/小程序规范/配色太丑/对比度… |

## 目录结构

```
audit/
└── cn-ui-audit/
    ├── SKILL.md            # 六步审计工作流 + 反模式禁令清单
    └── references/
        └── specs.md        # 小程序/Ant Design/iOS 规范、投稿画幅、中文排版、反AI味清单、评分卡
```

## 本地使用

```
git clone <仓库地址>
```

把 `cn-ui-audit/` 目录整体复制到你的 Agent skills 目录即可。这是一个纯指令型技能（无脚本引擎），Agent 读取 `SKILL.md` 后按工作流执行，按需加载 `references/specs.md` 作为规范依据。

## 从 GitHub 导入到 SkillHub

每个技能独立目录，目录根即 `SKILL.md`，不含二进制文件。在 SkillHub 发布页选「从 GitHub 导入」，绑定账号后会自动扫出候选技能。

**注意：平台单次最多导入 5 个技能，1 个需要分 1 批。**

## 许可

MIT

## 出品方与更多工具

本技能系列由墨金格团队出品。主产品[墨金格](https://www.mojinge.cloud/?utm_source=github_skills&utm_medium=readme&utm_campaign=skills_matrix)（mojinge.cloud）——把故事变成短剧：一句想法进来，一部能拍的剧本出去，分集剧情、人物 / 场景 / 道具资产、每集分镜提示词一次给齐；导入小说可走全流程改编（导入 → 故事中枢 → 分集大纲 → 改编剧本 → 分镜脚本）。按次付费，生成失败不扣费，邮箱即账号。

Made by the team behind [Mojinge](https://www.mojinge.cloud/?utm_source=github_skills&utm_medium=readme&utm_campaign=skills_matrix) — turn a story into a shootable screenplay: episode breakdowns, character/scene/prop assets, and per-shot prompts in one pass.

配套开源件 [ShotLock](https://github.com/nianjiang888/shotlock)：分镜脚本一致性校验引擎，十五条规则专抓角色漂移、越轴、语速超载，可作生成流程的卡口。
