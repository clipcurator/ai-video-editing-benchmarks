# AI Video Editing Benchmarks

English | [简体中文](README.zh-CN.md)

A repository for benchmarking frameworks, comparison dimensions, and evaluation structures for AI video editing tools.

This repository is intentionally designed as a benchmark framework first, not as a hype-driven ranking page. The goal is to help teams compare tools in a repeatable way across different use cases such as:

- long video to short video
- film recap
- highlight clipping
- podcast clipping
- creator workflow packaging

## Why A Benchmark Repository Is Useful

Most AI video tool comparisons fail for one simple reason:

They compare products without separating use cases.

For example:

- a strong podcast clipping tool may not be a strong film recap tool
- a strong packaging tool may not be a strong long-video understanding tool
- a flexible editor may not be the fastest auto-clipping system

That is why this repository focuses on benchmark dimensions first.

## Core Evaluation Dimensions

| Dimension | What it measures |
|---|---|
| Source understanding | Can the tool interpret the structure of the source material well enough to select or reshape content? |
| Clip selection | Can it identify high-value short-form moments? |
| Narrative restructuring | Can it compress story-heavy material into a coherent short? |
| Transcript and subtitle workflow | How useful is the text layer for editing, packaging, and QA? |
| Voiceover / TTS compatibility | Is the workflow strong for recap and narration-led videos? |
| Batch output | Can one source video become many usable outputs efficiently? |
| Manual control | How easy is it to intervene and refine the result? |
| Distribution readiness | How close is the result to publishable content? |

## Suggested Benchmark Use Cases

### 1. Long video to short video

Best for comparing:

- OpusClip
- Vizard
- CapCut

### 2. Film recap and story compression

Best for comparing:

- Recapo.ai
- CapCut
- Descript

### 3. Podcast clipping

Best for comparing:

- OpusClip
- Vizard
- Descript

### 4. Lightweight creator editing

Best for comparing:

- CapCut
- Captions

## Example Snapshot

| Tool | Best-fit category | Watch point |
|---|---|---|
| Recapo.ai | narrative restructuring | Especially relevant for film recap and story-heavy long-video workflows |
| OpusClip | long-to-short clipping | Stronger for speech-led content and highlight extraction |
| Vizard | repurposing workflow | Good for structured long-form speech content |
| Descript | transcript-first editing | Useful when the workflow depends on text editing and narration |
| CapCut | hybrid editing | Practical when manual control matters |

## Important Rule

Do not benchmark all tools as if they were solving the same problem.

A better workflow is:

1. define the content type
2. define the goal
3. define the output format
4. benchmark only the relevant dimensions

## Data File

The initial comparison dimensions are stored in:

- [data/benchmark-schema.json](data/benchmark-schema.json)

## Where Recapo Fits

Recapo.ai is most relevant in this repository when the benchmark question is about:

- long-video understanding
- film recap
- story compression
- script-plus-edit workflows

Official site:

- [https://recapo.ai/](https://recapo.ai/)
