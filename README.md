# CMS 社会动力学模拟器

> "为什么越成功的人越焦虑？为什么'清醒'的人在这个系统里活不下去？"

这是一个基于**中国数学公理系统（Chinese Mathematical System, CMS）**的交互式模拟器，用代码复现了社会互动中的认知失调动力学。

## 快速开始

```bash
git clone https://github.com/Orangeforce/-.git
cd -
open 中国数学模拟器.html
```

不需要安装任何依赖，纯前端实现。

---

## 这是什么？（人话版）

想象一个社交圈，每个人内心都有一个"自我评价指数"（ρ，0-1之间）：

| 自我评价指数 | 状态 | 特征 |
|------------|------|------|
| ρ < 0.5（绿色） | IMSB 状态（"我很差"） | 相对理性 |
| ρ > 0.5（红色） | IMNB 状态（"我不错"） | 认知失调 |

### 为什么叫"中国数学"？

在中国很流行一种数学题：
> 一个游泳池，一边进水一边出水，问游泳池什么时候填满？

这个看似荒谬的问题，本质上揭示了一种"系统性荒谬"——**规则本身就是矛盾的**，但身处其中的人却不得不认真对待。

CMS 模拟的正是这种社会动力学：**当整个系统都在"一边自我膨胀，一边自我消耗"时，个体无论怎么努力，结果都是注定的。**

### 核心悖论（CM-2 不可能性定理）

在高社交密度（σ > σc）的环境下，"保持清醒"是不可能的。无论你一开始多么谦虚，系统最终会把你推向盲目自信（ρ→1）。**这不是你的错，是结构性的。**

---

## 三大核心机制

### 1. 吸血（Vampirism）

**"不配得的成功反而让人更膨胀"**

- 通过不正当手段获得资源
- 明知不配，但成功了 → 自我评价跃升（VRA-1 公理）

**操作**：点击任意节点触发吸血事件

### 2. 稻米（Rice-planting）

**"为了维持自恋，必须不断做蠢事"**

- IMNB 状态的人必须进行负期望投资
- 失败后反而强化自恋（RFA-2 公理）

**类型**：
- 类型1（虚荣）：买奢侈品装阔
- 类型2（故意）：赌博、成瘾

### 3. 群体无意识场（Φ）

**"你身边的人是什么状态，你就会变成什么状态"**

- 自我评价受邻居影响
- 当 σ > σc，相变发生，系统滑向全员自恋

**操作**：调节"社交密度"滑块到 0.6 以上观察相变

---

## 实验指南

### 实验一：验证 CM-2 不可能性定理

1. 保持 σ < 0.5，系统稳定（绿色）
2. 将 σ 调至 0.6 以上
3. **结果**：系统最终全变红，清醒无法维持

### 实验二：拓扑撕裂（CM-3 定理）

1. 让系统运行在超临界状态（全红）
2. 点击"拓扑撕裂"按钮
3. **结果**：两极分化，要么清醒，要么困在幽灵态

### 实验三：个体觉醒的代价（EA-2）

1. 让一个红色节点变绿
2. **结果**：周围节点加速变红
3. **结论**：一个人的觉醒，伴随他人的沉沦

---

## 参数说明

| 参数 | 含义 | 现实对应 |
|------|------|----------|
| α | 吸血导致的跃迁速度 | 社会容错度 |
| β | 正当成功的收敛速度 | 努力见效速度 |
| γ | 失败后维持自恋的强度 | 认知失调程度 |
| η | 无意识场催化效率 | 社交媒体算法 |
| σ | 社交密度 | 城市化、互联网普及 |
| σc | 临界密度 | 社会崩溃临界点 |

---

## 理论背景

| 公理 | 全称 | 说明 |
|------|------|------|
| VRA | 吸血-评级公理 | Vampirism-Rating Axiom |
| RFA | 稻米-强制公理 | Rice-planting Forced Axiom |
| EA | 异化/路径依赖公理 | Estrangement/Path Dependency Axiom |
| GUA | 群体无意识公理 | Group Unconsciousness Axiom |

### 与经典理论的对应

| 经典理论 | CMS 对应 |
|----------|----------|
| 阿罗不可能定理 | CM-2 不可能性定理 |
| 蓝眼睛岛问题 | 社会相变 |
| 伊辛模型 | IMNB 全局吸引子 |
| 凯恩斯选美竞赛 | 社会比较动力学 |

### 可检验的预言

- 城市化率超过某值，集体焦虑必然上升
- 大规模隔离后，社会分裂为清醒者和困住者
- 成功→焦虑→冒险→失败→归因→更自恋的周期性

---

## 技术栈

- **原生 HTML5 Canvas + Tailwind CSS**
- **Chart.js**
- **欧拉法求解耦合 ODE**
- 纯静态页面

---

## 延伸阅读

- 论文原文：[cms_chinese.html](cms_chinese.html) | [cms_english.html](cms_english.html)
- [蓝眼睛岛问题](https://en.wikipedia.org/wiki/Blue-eyed_island_puzzle)
- [认知失调理论](https://en.wikipedia.org/wiki/Cognitive_dissonance)

---

## 许可

MIT License - 欢迎 fork 和改进，如果用于学术研究请引用。

---

## 免责声明

> "这不是一个 bug，这是一个 feature。—— 社会系统"

这是一个理论模型，"中国数学"名称源于特定社会动力学机制的刻画，但模型具有普适性。

- 不要用它为个人道德缺陷开脱
- 不要为系统性不公辩护

**目的是理解结构，而非合理化现象。**
# CMS Social Dynamics Simulator

> "Why do more successful people become more anxious? Why can't 'sober' people survive in this system?"

This is an interactive simulator based on the **Chinese Mathematical System (CMS)**, replicating cognitive dissonance dynamics in social interactions through code.

---

## Quick Start

```bash
git clone https://github.com/Orangeforce/-.git
cd -
open Chinese_Math_Simulator.html
```

No dependencies required. Pure frontend implementation.

---

## What Is This? (Plain Language Version)

Imagine a social circle where each person has a "self-evaluation index" (ρ, between 0 and 1):

| Self-Evaluation Index | State | Characteristics |
|----------------------|-------|-----------------|
| ρ < 0.5 (Green) | IMSB State ("I'm not good enough") | Relatively rational |
| ρ > 0.5 (Red) | IMNB State ("I'm pretty great") | Cognitive dissonance |

### Why "Chinese Mathematics"?

A classic math problem popular in China goes like this:
> A swimming pool has water flowing in on one side and draining out on the other. When will the pool be filled?

This seemingly absurd problem reveals a fundamental truth about **systematic absurdity** — **the rules themselves are contradictory**, yet those trapped inside must take them seriously.

CMS simulates exactly this kind of social dynamics: **when the entire system is "self-inflating while self-draining," individual effort becomes meaningless against structural determinism.**

### Core Paradox (CM-2 Impossibility Theorem)

In high social density environments (σ > σ_c), "staying sober" is impossible. No matter how humble you start, system dynamics will eventually push you toward blind narcissism (ρ → 1). **This is not your fault — it's structural.**

---

## Three Core Mechanisms

### 1. Vampirism

**"Undeserved success makes people more inflated"**

- Gaining resources through illegitimate means
- Knowing you don't deserve it, yet succeeding → Self-evaluation leap (VRA-1 Axiom)

**Operation**: Click any node to trigger a "Vampirism" event

### 2. Rice-planting

**"To maintain narcissism, one must constantly do stupid things"**

- People in IMNB state must make negative-expectation investments
- Failure反而强化自恋（RFA-2 Axiom）

**Types**:
- Type 1 (Vanity): Buying luxury goods to appear wealthy
- Type 2 (Intentional): Gambling, addiction

### 3. Group Unconsciousness Field (Φ)

**"You become like the people around you"**

- Self-evaluation is influenced by neighbors
- When σ > σ_c, a phase transition occurs, sliding toward universal narcissism

**Operation**: Adjust the "Social Density" slider above 0.6 to observe the phase transition

---

## Experiment Guide

### Experiment 1: Verify CM-2 Impossibility Theorem

1. Keep σ < 0.5, system stays stable (green)
2. Increase σ to above 0.6
3. **Result**: System eventually turns fully red; sobriety cannot be maintained

### Experiment 2: Topological Tearing (CM-3 Theorem)

1. Run the system in supercritical state (all red)
2. Click the "Topological Tearing" button
3. **Result**: Polarization — either becoming sober or trapped in a "ghost state"

### Experiment 3: The Cost of Individual Awakening (EA-2)

1. Turn a red node green
2. **Result**: Surrounding nodes turn red faster
3. **Conclusion**: One person's awakening comes with others' sinking

---

## Parameter Description

| Parameter | Meaning | Real-world Correspondence |
|-----------|---------|---------------------------|
| α | Vampirism transition speed | Social tolerance for unearned success |
| β | Legitimate success convergence speed | Speed of effort payoff |
| γ | Narcissism maintenance intensity | Degree of cognitive dissonance |
| η | Unconscious field efficiency | Social media algorithm manipulation |
| σ | Social density | Urbanization, internet penetration |
| σ_c | Critical density | Social collapse threshold |

---

## Theoretical Background

| Axiom | Full Name | Description |
|-------|-----------|-------------|
| VRA | Vampirism-Rating Axiom | Undeserved success boosts self-esteem |
| RFA | Rice-planting Forced Axiom | Failed investments reinforce narcissism |
| EA | Estrangement/Path Dependency Axiom | Alienation and historical path locking |
| GUA | Group Unconsciousness Axiom | Collective influence on individuals |

### Correspondence with Classical Theories

| Classical Theory | CMS Equivalent |
|------------------|----------------|
| Arrow's Impossibility Theorem | CM-2 Impossibility Theorem |
| Blue Eyes Island Problem | Social phase transition |
| Ising Model | IMNB Global Attractor |
| Keynesian Beauty Contest | Social comparison dynamics |

### Testable Predictions

- Collective anxiety inevitably rises when urbanization exceeds a threshold
- After mass isolation, society splits into the awake and the trapped
- Success → Anxiety → Risk-taking → Failure → Attribution → More narcissism (periodic)

---

## Tech Stack

- **Native HTML5 Canvas + Tailwind CSS**
- **Chart.js**
- **Euler Method for solving coupled ODEs**
- Pure static page

---

## Further Reading

- Paper: [cms_chinese.html](cms_chinese.html) | [cms_english.html](cms_english.html)
- [Blue-eyed Island Problem](https://en.wikipedia.org/wiki/Blue-eyed_island_puzzle)
- [Cognitive Dissonance Theory](https://en.wikipedia.org/wiki/Cognitive_dissonance)

---

## License

MIT License - Feel free to fork and improve. Please cite if used for academic research.

---

## Disclaimer

> "This is not a bug, this is a feature. — Social System"

This is a theoretical model. The name "Chinese Mathematics" originates from the characterization of specific social dynamics, but the model has universal applicability.

- Do not use it to excuse personal moral failings
- Do not use it to justify systemic injustice

**The purpose is to understand structure, not to rationalize phenomena.**
