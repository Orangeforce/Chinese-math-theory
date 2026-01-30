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

Note: No dependencies required. Pure static HTML implementation - just double-click to open.

## What Is This? (Plain Language Version)

Imagine a social circle where each person has a self-esteem index ρ (0 ≤ ρ ≤ 1):

- **ρ < 0.5 (Green)**: IMSB State ("I'm not good enough") — Cognitively sober, though painful, they are in a rational state.
- **ρ > 0.5 (Red)**: IMNB State ("I'm pretty great") — Cognitive dissonance, generating entropy-seeking behaviors to maintain false confidence.

### Core Paradox (CM-2 Impossibility Theorem)

In high social density environments (σ > σ_c), "staying sober" is impossible. No matter how humble you start, system dynamics will eventually push you toward blind narcissism (ρ → 1).

## Three Core Mechanisms

### Vampirism

**Principle**: Undeserved success makes people more inflated.
Gaining resources through illegitimate means, succeeding despite knowing you don't deserve it → Self-esteem leap (VRA-1 Axiom).

**Operation**: Click any node to trigger a "Vampirism" event.

### Rice-planting

**Principle**: To maintain narcissism, one must constantly do stupid things.
People in IMNB state must make negative-expectation investments, and after failure, reinforce narcissism through "compensation" (RFA-2 Axiom).

**Examples**: Vanity consumption, addictive gambling.

### Group Unconsciousness Field (Φ)

**Principle**: You become like the people around you.

**Phenomenon**: When σ > σ_c, a "phase transition" occurs, and the system slides into a red ocean of universal narcissism.

---

## Experiment Guide

### Experiment 1: Verify CM-2 Theorem

1. Keep σ < 0.5, and the system remains relatively stable (more green dots).
2. Drag the "Social Density" slider above 0.6.
3. **Observation**: The system rapidly turns completely red.

### Experiment 2: Topological Tearing (CM-3 Theorem)

1. Run the system in supercritical state (all red).
2. Click the "Topological Tearing" button.
3. **Observation**: The system undergoes polarization — either becoming completely sober or falling into an "ghost state" where interaction is impossible.

---

## Parameter Description

| Parameter | Meaning | Real-world Correspondence |
|-----------|---------|---------------------------|
| α | Vampirism transition speed | Social tolerance for unearned success / get-rich-quick opportunities |
| β | Legitimate convergence speed | Feedback speed of effort |
| γ | Narcissism maintenance intensity | Stubbornness of cognitive dissonance |
| η | Unconscious field efficiency | Manipulation power of social media algorithms |
| σ | Social density | Urbanization level, internet penetration |
| σ_c | Critical density | Threshold for social consensus collapse |

---

## Theoretical Background

- **VRA (Vampirism-Rating Axiom)**: Vampirism-Rating Axiom
- **RFA (Rice-planting Forced Axiom)**: Rice-planting Forced Axiom
- **EA (Estrangement Axiom)**: Alienation/Path Dependency Axiom
- **GUA (Group Unconsciousness Axiom)**: Group Unconsciousness Axiom

### Correspondence with Classical Theories

| Classical Theory | CMS Equivalent |
|------------------|----------------|
| Arrow's Impossibility Theorem | CM-2 Impossibility Theorem |
| Blue Eyes Island Problem | Social phase transition trigger mechanism |
| Ising Model | IMNB Global Attractor |

---

## Tech Stack

- **Frontend**: HTML5 Canvas, Tailwind CSS
- **Engine**: Euler Method (solving coupled ODEs)
- **Chart**: Chart.js

---

## License

MIT

---

## Disclaimer

This project is a demonstration of sociological theory models. The name "Chinese Mathematics" originates from the literary characterization of specific dynamical mechanisms.
