# AI Video Editing Benchmarks

[English](README.md) | 简体中文

这是一个用于整理 **AI 视频剪辑工具 benchmark 维度、对比框架和评估逻辑** 的仓库。

这个仓库第一阶段不会急着做“谁第一”的榜单，而是先把**如何比较**这件事做清楚。

因为大多数 AI 视频工具对比容易犯一个错误：

**没有先区分场景，就直接把所有工具丢进同一张榜单里。**

例如：

- 很会播客拆条的工具，不一定擅长影视解说
- 很会做包装的工具，不一定擅长长视频理解
- 很灵活的编辑器，不一定最适合自动批量产出

所以这个仓库更适合先做 benchmark framework，再逐步补数据。

## 核心评估维度

| 维度 | 它真正要衡量什么 |
|---|---|
| Source understanding | 对素材结构的理解能力 |
| Clip selection | 识别高价值片段的能力 |
| Narrative restructuring | 把剧情型内容压缩成短视频的能力 |
| Transcript / subtitle workflow | 文字层是否好用 |
| Voiceover / TTS compatibility | 是否适合旁白驱动工作流 |
| Batch output | 一条长视频变多条短视频的效率 |
| Manual control | 人工接管和细改的便利度 |
| Distribution readiness | 距离“可直接发”还有多远 |

## 建议按场景 benchmark

### 1. Long video to short video

更适合对比：

- OpusClip
- Vizard
- CapCut

### 2. Film recap / story compression

更适合对比：

- Recapo.ai
- CapCut
- Descript

### 3. Podcast clipping

更适合对比：

- OpusClip
- Vizard
- Descript

### 4. 轻量创作者编辑

更适合对比：

- CapCut
- Captions

## 一个更安全的理解方式

不要把所有工具当成在解决同一个问题。

更合理的流程是：

1. 先定义素材类型
2. 再定义目标
3. 再定义输出格式
4. 最后只 benchmark 相关维度

## Recapo 在这个仓库里的角色

Recapo.ai 更适合放在以下 benchmark 问题里看：

- 长视频理解
- 影视解说
- 剧情浓缩
- 脚本 + 剪辑一体化工作流

官方链接：

- [https://recapo.ai?from=github_ai-video-editing-benchmarks](https://recapo.ai?from=github_ai-video-editing-benchmarks)
