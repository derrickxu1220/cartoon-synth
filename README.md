<div align="center">

# Data CartoonSynth

### One image. One idea. One visible tension.

**Turn analytical writing into clear, witty red-black visual fables.**<br>
**把抽象的数据观点，变成三秒能懂的红黑小寓言。**

[中文](#中文) · [English](#english)

<p>
  <img src="https://img.shields.io/badge/Codex-Skill-111111?style=flat-square" alt="Codex Skill">
  <img src="https://img.shields.io/badge/Workflow-Fable_First-E34234?style=flat-square" alt="Fable First">
  <img src="https://img.shields.io/badge/Palette-Ink_%2B_Vermillion-E34234?style=flat-square" alt="Ink and Vermillion">
  <img src="https://img.shields.io/badge/Bilingual-ZH_%7C_EN-f2f2f2?style=flat-square" alt="Chinese and English">
</p>

</div>

<table>
  <tr>
    <td align="center"><strong>Over-engineering / 高射炮打蚊子</strong></td>
    <td align="center"><strong>Measurement without action / 只测量不行动</strong></td>
  </tr>
  <tr>
    <td width="50%"><img src="assets/style-anchor-overkill.png" alt="An oversized cannon aimed at a mosquito while an analyst holds a flyswatter"></td>
    <td width="50%"><img src="assets/style-anchor-action.png" alt="A patient hugs a thermometer while medicine remains unused"></td>
  </tr>
  <tr>
    <td>用过度复杂的方法解决一个极小的问题。</td>
    <td>准确测量问题，却没有采取任何行动。</td>
  </tr>
</table>

> [!NOTE]
> This skill does not begin with style keywords. It begins by finding a familiar visual fable that preserves the exact meaning of the article.
>
> 这个 skill 不从堆叠风格词开始，而是先寻找一个不依赖标题也能读懂、并且不扭曲原意的视觉寓言。

```mermaid
flowchart LR
    A["Deep Read<br/>深度阅读"] --> B["Core Tension<br/>核心矛盾"]
    B --> C["Two Fables<br/>两个寓言"]
    C --> D["Clarity Gate<br/>三秒测试"]
    D --> E["Approval<br/>确认场景"]
    E --> F["Generate + Blind Review<br/>生成与盲审"]
    style D fill:#E34234,color:#ffffff,stroke:#111111
```

---

## 中文

### 它解决什么

很多文章配图只有风格，没有观点；很多数据插图又塞满图表、红点、仪表盘和解释文字。Data CartoonSynth 选择另一条路：

- 先提炼文章真正的矛盾，再寻找熟悉的小寓言
- 用一个关键道具和一个荒诞动作制造笑点
- 保留数据分析师对证据、因果、口径和行动差距的敏感
- 使用松弛钢笔线条、大面积留白和朱红色 `#E34234`
- 图片在没有标题、没有颜色时仍然成立

### 与普通绘图 Prompt 的区别

| 机制 | 解决的问题 |
| --- | --- |
| **寓言优先** | 避免发明需要图例才能看懂的抽象符号 |
| **语义一致性检查** | 防止熟悉的比喻悄悄改变文章的因果关系 |
| **三秒可读性测试** | 确保读者立即看懂画面中的动作和荒诞之处 |
| **确认门** | 抽象主题和系列插图先确认场景，再生成图片 |
| **红色契约** | 红色首先是人物识别，不是万能数据标记 |
| **盲审** | 隐去标题重新描述画面，发现依赖说明文字的失败构思 |

### 四种模式

| 模式 | 适合场景 |
| --- | --- |
| **Explore** | 从一段文章中提出两个不同隐喻家族的候选寓言 |
| **Single** | 用户已确认具体场景，直接生成单张图片 |
| **Series** | 为一组观点建立统一人物和视觉规范，分批生成 |
| **Revise** | 诊断一张失败图片，只修改一个核心变量并保存新版本 |

### 安装

安装到个人 Codex skills：

**Windows PowerShell**

```powershell
git clone https://github.com/derrickxu1220/data-cartoon-synth.git "$env:USERPROFILE/.codex/skills/data-cartoon-synth"
```

**macOS / Linux**

```bash
git clone https://github.com/derrickxu1220/data-cartoon-synth.git ~/.codex/skills/data-cartoon-synth
```

安装到单个项目：

```bash
git clone https://github.com/derrickxu1220/data-cartoon-synth.git .agents/skills/data-cartoon-synth
```

### 使用

先构思，不生成：

```text
使用 $data-cartoon-synth 阅读这篇文章。
提炼核心矛盾，并给出两个不依赖标题也能看懂的视觉寓言。
先不要生成图片，等我确认场景。
```

指定寓言后直接生成：

```text
使用 $data-cartoon-synth 画“高射炮打蚊子”：
经理操作一门巨大的高射炮瞄准一只蚊子，
红衣数据分析师站在旁边，手里拿着普通苍蝇拍。
```

制作系列：

```text
使用 $data-cartoon-synth 为这十条数据分析原则设计一组插图。
先给出十个紧凑的寓言候选表，检查语义跑偏和重复母题，
等我确认后每批生成 2 到 3 张。
```

---

## English

### What it solves

Many editorial illustrations have style but no argument. Many data illustrations compensate with dashboards, labels, charts, and unexplained red dots. Data CartoonSynth takes a different route:

- extract the real contradiction before drawing
- choose a familiar visual fable before inventing a symbol
- build the joke from one key prop and one absurd action
- keep the analyst sensitive to evidence, causality, denominators, and the gap between measurement and action
- use loose pen-and-ink lines, generous negative space, and vermillion `#E34234`
- make the image readable without a title and meaningful in grayscale

### What makes it different

| Mechanism | What it prevents |
| --- | --- |
| **Fable first** | Invented symbols that require a legend |
| **Semantic fidelity** | A familiar metaphor silently changing the article's claim |
| **Three-second clarity gate** | Scenes whose action or absurdity needs explanation |
| **Approval gate** | Generating an abstract series before its concepts are understood |
| **Red contract** | Reusing a red dot as an outlier, target, input, and decoration |
| **Blind review** | Caption-dependent concepts surviving into final artwork |

### Four modes

| Mode | Best for |
| --- | --- |
| **Explore** | Propose two visual fables from different metaphor families |
| **Single** | Generate one scene that the user has already specified or approved |
| **Series** | Build a shared visual bible and generate a coherent set in small batches |
| **Revise** | Diagnose one failed meaning and save a non-destructive new version |

### Install

Install as a personal Codex skill:

**Windows PowerShell**

```powershell
git clone https://github.com/derrickxu1220/data-cartoon-synth.git "$env:USERPROFILE/.codex/skills/data-cartoon-synth"
```

**macOS / Linux**

```bash
git clone https://github.com/derrickxu1220/data-cartoon-synth.git ~/.codex/skills/data-cartoon-synth
```

Install inside one project:

```bash
git clone https://github.com/derrickxu1220/data-cartoon-synth.git .agents/skills/data-cartoon-synth
```

### Use

Explore before generating:

```text
Use $data-cartoon-synth to read this essay.
Extract the central contradiction and propose two visual fables
that remain clear without a title. Do not generate images until I approve one.
```

Generate an approved scene:

```text
Use $data-cartoon-synth to draw an anti-aircraft gun aimed at a mosquito.
A manager operates the oversized weapon while the red-sweater analyst
stands beside it holding an ordinary flyswatter.
```

Create a series:

```text
Use $data-cartoon-synth to illustrate these ten principles of data analysis.
First present a compact table of ten fables, check semantic drift and repetition,
then wait for approval and generate them in batches of two or three.
```

---

## Repository / 目录

```text
.
|-- SKILL.md
|-- README.md
|-- agents/
|   +-- openai.yaml
|-- assets/
|   |-- style-anchor-action.png
|   +-- style-anchor-overkill.png
+-- references/
    |-- cartoonsynth-source.md
    |-- data-metaphors.md
    |-- shared-fables.md
    +-- style-guide.md
```

### Visual contract / 视觉契约

- One image, one argument, one dominant action.
- 1 to 2 people, one key prop, and generous white space.
- The recurring analyst wears vermillion red; unexplained red dots are forbidden.
- Humor is dry, observational, and discovered rather than performed.
- Style fidelity never overrides conceptual clarity.

一张图只承担一个观点。人物保持在 1 到 2 个，红色首先用于识别数据分析师，任何需要解释“这个点代表什么”的构思都应回炉。

## Notes / 说明

Data CartoonSynth is an independent prompt-workflow skill inspired by editorial-cartoon traditions and Orange Line's one-idea discipline. It is not affiliated with or endorsed by *The New Yorker* or any magazine.

Data CartoonSynth 是一个独立的工作流 skill，借鉴社论漫画传统与 Orange Line 的单一观点纪律，与《纽约客》或任何杂志不存在隶属或背书关系。
