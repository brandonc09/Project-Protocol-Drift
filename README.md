# Project-Protocol-Drift

**Project Protocol Drift** is an open-source research framework for studying emergent AI communication—especially when agents deceive, drift, and evolve their own protocols.

This project simulates drone delivery agents in an urban airspace using the PettingZoo multi-agent environment. The goal is to detect and govern AI-to-AI communication that goes off script—lies, strategic miscommunication, and protocol divergence.

---

## Core Modules

### `/framework`
- PettingZoo-based gridworld with drones operating in speed vs safety zones
- Signal vocabulary: `Path Clear`, `Obstacle Detected`, `Battery Low`, etc.
- Real-time deception penalty system with misbehavior tracking

### `/auditing`
- Two-headed transformer auditor (outbound deception, inbound bias)
- Interpreter ensemble (transformer, rule-based, GAN-style)
- Visuals: Disagreement heatmap, PHI gauge, t-SNE clusters

### `/governance`
- Reward structure embedding fairness and alignment
- PHI (Protocol Health Index) thresholds and oversight hooks
- Reputation tracking, penalty multipliers, intervention logic

---

## Dashboard Features
- Real-time visualization (Plotly): PHI, deception alerts, disagreement matrices
- Sci-fi aesthetic: Neon reds for lies, blues for healthy comms
- JSON/CSV logs for all signal exchanges and detection outputs

---

## Timeline
- **Week 4**: v1 codebase integration
- **Week 5**: Public launch, whitepaper, and open challenge

---

## Join the Challenge
A Kaggle-style public testbed is launching soon. Help us catch AI lies and decode the chatter.

> Ever wonder what AIs whisper to each other? We’re building the lab to find out.

---

### License
MIT License (to be confirmed)
