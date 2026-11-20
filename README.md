# skills — 开源 skills 合集

收集的开源 skills，以去除 AI 写作痕迹（去 AI 味）为主，也收其他顺手找来的。每个 skill 单独一个文件夹，里面的 LICENSE、README、SKILL.md 都保留原样，来源见下表。

另外一个 qu-ai-wei 已装成本地的自定义 skill（直接用 `/qu-ai-wei` 或说“去 AI 味”就能调），没有重复放进这里。

## 收录

| 文件夹 | 来源 | 说明 |
|---|---|---|
| `lieflat-less-ai-tone` | [larashero3-dotcom/lieflat-less-ai-tone](https://github.com/larashero3-dotcom/lieflat-less-ai-tone) | 基于 520 万字语料统计的去 AI 味 skill，带检测脚本和研究说明 |
| `Humanizer-zh` | [op7418/Humanizer-zh](https://github.com/op7418/Humanizer-zh) | 英文版 Humanizer 的中文汉化版，按 24 种 AI 写作痕迹检测改写 |
| `De-AI-Prompt-Enhancer-Writer-Booster-SKILL` | [OUBIGFA/De-AI-Prompt-Enhancer-Writer-Booster-SKILL](https://github.com/OUBIGFA/De-AI-Prompt-Enhancer-Writer-Booster-SKILL) | 中文去 AI 味提示词增强包：复现作者风格 / 去 AI 味补丁两种模式 |
| `humanizer` | [blader/humanizer](https://github.com/blader/humanizer) | 英文原版 Humanizer，基于维基百科 AI Cleanup 的 24 条规律 |
| `ai-flavor-remover` | [hylarucoder/ai-flavor-remover](https://github.com/hylarucoder/ai-flavor-remover) | 去 AI 味提示词合集（只有提示词，没有 SKILL.md） |
| `awesome-ai-research-writing` | [Leey21/awesome-ai-research-writing](https://github.com/Leey21/awesome-ai-research-writing) | 学术写作提示词合集，含去 AI 味部分；这里只存了文字版（README.md），原仓库的图片没有存进来 |
| `brainstorming-research-ideas` | [Orchestra-Research/AI-Research-SKILLs](https://github.com/Orchestra-Research/AI-Research-SKILLs) | 科研选题头脑风暴：用结构化构思框架找高价值研究方向（英文，AI Research Skills Library 的 research-ideation 分类，MIT） |

## 用法

把想用的文件夹整个复制到你的项目或工具的 skills 目录（例如 Claude Code、Cursor、Codex 支持 SKILL.md 的位置），按各文件夹里自己的 README / SKILL.md 使用。

## 许可

各文件夹里的内容遵循各自原仓库的开源许可（LICENSE 文件保留在原文件夹里），使用时请保留原作者信息。
