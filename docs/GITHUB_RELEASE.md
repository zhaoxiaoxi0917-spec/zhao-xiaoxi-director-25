# GitHub 发布文案与上传说明

## 仓库信息

**建议仓库名：** `zhao-xiaoxi-director-25`

**中文标题：** 赵小惜导演台 2.5｜AI 短剧导演与分镜工作流

**英文标题：** Zhao Xiaoxi Director 2.5 — AI Short-Drama Directing Skill

**GitHub Description（中文）：**

面向 Seedance 2.5 的 AI 短剧导演 Skill，覆盖剧本研读、动作排演、场面调度、美学摄影、声音设计与连续性返修，交付完整九栏分镜 Prompt。

**GitHub Description（英文）：**

A filmmaking skill for Seedance 2.5 short dramas: script analysis, blocking, visual design, cinematography, sound, continuity, and nine-section storyboard prompts.

**可选 Topics：**

`agent-skills` · `ai-filmmaking` · `seedance` · `storyboarding` · `cinematography` · `film-directing` · `prompt-engineering` · `chinese`

## 可直接发布的介绍

我把日常 AI 短剧制作中使用的导演工作流整理成了「赵小惜导演台 2.5」。它从读懂剧本开始，依次完成动作排演、场面调度、美学设计、摄影光影、声音设计和分镜编写，最终交付可以逐段使用的九栏 Prompt。

这套工作流关注一场戏里的具体问题：人物想从对方那里得到什么，动作怎样发生，观众应该先看见什么，摄影机在哪个瞬间移动，又应该在哪里停下。它把美学落实到场景、色彩、材质和光线，把表演落实到有对象、有触发的行动，并持续核对身份、站位、道具和跨段状态。

目前发布包基于 v1.14，内含 20 份参考模块、164 项视听技法、19 类场景调度案例和完整九栏教学示例。既可以从文学剧本开始设计，也可以用于已有分镜的优化、生成片段的诊断返修，以及影视术语与技巧学习。

默认采用中文制作描述、9:16 画幅和每段 30 秒的制作规划，保留原稿对白与关键剧情结果。技能负责导演分析和 Prompt 编写，生成媒体时再接入相应平台与工具。

希望它能帮助创作者把故事、表演和视听设计连接起来，让每一个镜头都有清楚的观看任务。

——cecil

## Release 文案

**建议 Tag：** `v1.14`

**建议 Release 标题：** `赵小惜导演台 2.5 v1.14｜GitHub 发布包`

**Release 正文：**

本次发布整理了「赵小惜导演台 2.5」v1.14 的完整技能源文件，并补充面向使用者的介绍与上手资料。

- 技能正文、20 份参考资料、界面元数据和图标均保留原版内容。
- 附中文 README、GitHub 中英文简短描述、调用示例与任务输入模板。
- 提供完整九栏教学案例，涵盖导演设计、视觉风格、场景、人设、道具、站位、逐镜描述与段尾状态。
- 默认面向 Seedance 2.5、9:16、每段 30 秒的制作规划；实际平台规格需在制作时核对。

这是对现有 v1.14 的发布整理，技能原文版本日期为 2026-11-11，本发布包整理日期为 2026-11-13。教学案例为文字预演，未包含生成视频或本次平台实测。

## 上传方式

1. 下载并解压 `zhao-xiaoxi-director-25-v1.14-github.zip`。
2. 在 GitHub 创建仓库，仓库名可使用上方建议，将 Description 填入简介栏。
3. 把解压后 `zhao-xiaoxi-director-25` 文件夹**内部的文件和目录**上传到仓库根目录，让首页直接显示 `README.md`。
4. 保持 `skills/zhao-xiaoxi-director-25/` 的完整结构；其他人安装时使用这个技能文件夹。
5. 如果创建 Release，可使用上述 Tag、标题和正文，并将下载包作为附件上传。

说明：本文件提供发布材料，仓库创建和公开发布由发布者完成。包内未预设开源许可证；如需附带许可证，发布时由作者选择。
