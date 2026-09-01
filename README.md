# yubei Skills

这是我的个人 Codex Skill 仓库，用来保存、测试和持续维护我创建的 Skills。

## AI 短片创作系统

这套系统用于辅助 AI 自媒体账号生产广告短片与创意短片，按照“拆解—编导—审核”的流程工作。

### 1. 好内容拆解

分析用户已经筛选出的优秀图片、视频画面或故事文本，解释内容为什么有效，并提炼可迁移的创意机制、视觉方法和镜头策略。

[查看好内容拆解 Skill](skills/content-deconstructor/)

### 2. AI 短片编导

接收用户用自然语言描述的创意，先优化并确定剧本，再设计 AI 导演拍摄方案；方案确认后，制作逐镜 AI 视频生成分镜与提示词。

同时考虑人物与场景设计、镜头语言、关键帧控制、连续性、生成风险以及有限预算。

[查看 AI 短片编导 Skill](skills/ai-video-director/)

### 3. 抖音短片审核

分别审核确定剧本、AI 导演拍摄方案和逐镜 AI 生成分镜，检查业务目标、观众理解、抖音观看场景、内容表达、生成风险和总预算。

[查看抖音短片审核 Skill](skills/douyin-content-reviewer/)

## Skill 开发工具

### Skill 需求架构师

从现实任务出发调查用户需求，判断真正需要的专业能力，并协助创建、测试和维护 Skill。

[查看 Skill 需求架构师](skills/skill-requirements-architect/)

## 仓库结构

```text
yubei-skills/
├── README.md
└── skills/
    ├── content-deconstructor/
    │   └── SKILL.md
    ├── ai-video-director/
    │   ├── SKILL.md
    │   └── references/
    │       ├── production-templates.md
    │       └── action-storyboard-case.md
    ├── douyin-content-reviewer/
    │   └── SKILL.md
    └── skill-requirements-architect/
        ├── SKILL.md
        ├── README.md
        └── agents/
            └── openai.yaml
```
