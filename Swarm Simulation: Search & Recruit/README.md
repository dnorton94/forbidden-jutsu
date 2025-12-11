## 🔍 Swarm Simulation: Search & Recruit

This simulation demonstrates how a swarm of agents can:

- Move cohesively using flocking dynamics (alignment, cohesion, separation)
- Explore an environment through randomized drifting
- Detect a target using local sensing
- Spread information through short-range broadcasts
- Converge as a group through a recruitment cascade

The result is an emergent, decentralized search strategy where the swarm organically finds and gathers at a target, with no leader and no central brain.

### Agent States

- **SEARCHING (blue)**: normal flocking and wandering
- **FOUND (red)**: agent directly detects the target
- **RECRUITED (green)**: agent receives a signal and biases movement toward the target

### Features

- Fully client-side and interactive
- Real-time rendering and animation
- Adjustable parameters for flocking and search behaviors
- Clean, modular code structure for easy experimentation
