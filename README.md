# Pop-Art Mystery Movie Intro

Turn a single theme into a complete 20–30 second English mystery-film opening. This Skill guides a canvas Agent through concept development, pop-art noir visual design, storyboarding, asset generation, animation, sound design, editing, and final quality control without requiring the user to make decisions at every stage.

## English Introduction

**Pop-Art Mystery Movie Intro** is an autonomous video-production Skill for short cinematic title sequences. The user only needs to enter a theme, such as `a vanished magician`, `the last train at midnight`, or `a letter that arrives twenty years late`.

The Agent expands that theme into an original mystery concept, creates a consistent cast and clue system, and produces a 20–30 second English opening in a striking pop-art noir style. The visual language combines red-and-blue confrontations, angular character silhouettes, evidence-board collages, dossier graphics, screen-print textures, cinematic shadows, and oversized condensed typography. It then generates the shots, animates the poster layers, adds original suspense music and sound effects, assembles the final edit, and checks continuity and text accuracy.

### What the Skill handles automatically

- Original English title, logline, characters, location, clues, and unresolved hook
- Locked visual bible and character continuity
- Seven-shot storyboard with a default 25-second runtime
- 16:9 pop-art noir keyframes and reusable visual assets
- Graphic transitions, parallax, evidence-line animation, and title motion
- English typography overlays, suspense score, and sound design
- Final editing, continuity review, and focused repairs

### Input

Enter one theme only:

```text
A clockmaker who receives a watch from his future self.
```

### Output

A complete 20–30 second, 16:9 English mystery-film opening with a readable title and a final unresolved hook. If the active canvas cannot render video, the Skill returns a production-ready package containing the brief, storyboard, prompts, text overlays, and sound plan.

### Canvas upload compatibility

This repository intentionally contains only `.md` and `.yaml` files. It does not include `assets/icon.svg` or any unsupported image, font, video, or script files, so it follows the upload restrictions shown by the canvas Agent.

---

## 中文介绍

**Pop-Art Mystery Movie Intro** 是一个用于自动生成英文悬疑电影片头的画布 Agent Skill。用户只需要输入一个主题，例如“消失的魔术师”“午夜最后一班列车”或“一封迟到二十年的信”，其余创作和制作流程都由 Agent 自动完成。

Agent 会先将主题扩展成原创英文片名、故事钩子、主角、神秘对手、关键地点和核心证物，再建立统一的角色与视觉设定，并制作一支 20–30 秒的英文悬疑片开头。整体风格融合波普艺术电影海报、黑色侦探片和调查档案界面，通过红蓝对峙、剪影人物、证物拼贴、调查线框、丝网印刷颗粒、电影感阴影和超大窄体标题，快速营造悬疑氛围。

### Skill 会自动完成

- 生成原创英文片名、故事梗概、人物、地点、线索和未解谜题
- 建立统一的视觉风格与角色连续性设定
- 生成默认约 25 秒、由七个镜头组成的完整分镜
- 制作 16:9 波普黑色电影风格关键帧和可复用素材
- 添加图形转场、视差、证物连线和标题动画
- 添加准确的英文字幕、原创悬疑配乐和音效
- 完成剪辑、连续性检查和局部修复

### 输入方式

用户只需要输入一个主题：

```text
一名钟表匠收到了一块来自未来自己的手表。
```

### 输出内容

一支 20–30 秒、16:9 横屏的英文悬疑电影片头，包含清晰可读的英文片名和一个未解开的悬疑钩子。如果当前画布不支持直接生成或剪辑视频，Skill 会自动输出完整创意设定、分镜表、图像提示词、视频提示词、英文文字图层和声音方案，作为可直接制作的备用交付。

### 画布上传兼容性

本仓库只包含画布支持的 `.md` 和 `.yaml` 文件，不包含 `assets/icon.svg`，也不包含图片、字体、视频或脚本，因此不会触发截图中显示的不支持格式问题。

## Suggested invocation

```text
Use $pop-art-mystery-movie-intro to create an English mystery opening about a museum painting that changes every night.
```
