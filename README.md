# Drama Skills · short-drama-assets

> **[short-drama-assets](https://github.com/simlpandordinary/short-drama-assets)** —— 飞书《WorkBuddy 视频系列 · 全技能与提示词总目录》里推荐的开源技能，已拆分为独立仓库分发（一个技能一个仓库）。

| 项 | 内容 |
| - | - |
| 上游仓库 | <https://github.com/zenstory-ai/drama-skills> |
| 上游路径 | `skills/short-drama-assets` |
| 上游协议 | MIT |
| 上游 Star | 3.7k+ |
| 拆分方式 | 仅抽取该技能自身文件，独立可用 |

## 技能说明

从短剧剧本拆出人物/造型、地点/视图、道具/状态和跨场连续性，写成创作者可读的视觉设定。用户说“拆角色/场景/道具”“做资产设定”“判断复用还是新变体”“更新造型/道具状态”，或拿现成剧本直接做视觉资产准备时使用；不写图片提示词，不生成媒体。

## 目录结构

```
├── LICENSE
├── README.upstream.md
├── SKILL.md
├── references/
│   ├── asset-review-checklist.md
│   ├── character-and-look.md
│   ├── continuity-delta.md
│   ├── continuity-lock.md
│   ├── era-anchors.md
│   ├── identity-vs-variant.md
│   ├── location-and-view.md
│   ├── occurrence-extraction.md
│   ├── prop-and-state.md
│   ├── stage-contract.md
│   └── voice-direction.md
└── agents/
    └── openai.yaml
```

- `SKILL.md` 是技能入口（触发条件 / 工作流 / 约束），安装时必须位于技能根目录。
- `references/`、`scripts/`、`assets/` 为该技能自带的参考文档、脚本与素材。
- `README.upstream.md` 为上游仓库原始说明，保留出处与版权信息。
- `LICENSE` 为上游许可证原件。

## 安装

WorkBuddy 技能目录为 `~/.workbuddy/skills/short-drama-assets/`：

```bash
git clone https://github.com/simlpandordinary/short-drama-assets.git ~/.workbuddy/skills/short-drama-assets
```

也可以直接对 AI 说：「把 <https://github.com/simlpandordinary/short-drama-assets> 装成 Skill」。

安装后用自然语言触发，例如「Drama Skills · short-drama-assets」「用 short-drama-assets 帮我处理这个任务」。

## 版权

原始作者与版权归上游仓库 `zenstory-ai/drama-skills` 所有。本仓库仅做独立分发与结构整理，未修改技能内容；商用请遵循上游许可证。
