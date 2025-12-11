# forbidden-jutsu
A browser-based exploration of emergent swarm intelligence.

## Overview

forbidden-jutsu is an experimental playground for decentralized multi-agent intelligence.
The project explores how simple, local rules can produce complex global behaviors—flocking, searching, coordination, and collective decision-making—without any central controller.

## Background: Swarm Models
Swarm intelligence studies how large groups of simple agents can coordinate and solve complex tasks without centralized control. Swarms rely on **local interactions** and **simple behavioral rules** to produce emergent global behaviors.

### Common Swarm Behaviors
- **Flocking / Cohesion**: Agents align their motion with neighbors, maintain group cohesion, and avoid collisions. Inspired by birds and fish.  
- **Exploration / Random Drift**: Agents move with slight randomness to spread out and cover space efficiently.  
- **Sensing & Local Response**: Agents detect nearby objects, obstacles, or other agents and react based on simple rules.  
- **Information Propagation**: Knowledge of a discovery can spread through short-range signals, enabling decentralized coordination.  
- **Recruitment / Aggregation**: Once a task or target is identified, agents bias their movement toward it, causing the swarm to converge.

### Agent States in Swarm Systems
Swarm models often assign simple states to agents to control behavior:  
- **SEARCHING**: Default state for exploration and flocking  
- **ENGAGED / ACTIVE**: Agents reacting to local information or stimuli  
- **RECRUITED / FOLLOWING**: Agents influenced by other agents or signals, converging toward a goal

### Features of Swarm Systems
- Fully decentralized decision making  
- Emergent collective behaviors from local interactions  
- Robustness to individual failures or environmental changes  
- Scalable to large numbers of agents

Swarm models are widely used in robotics, AI research, environmental monitoring, and generative simulations to study collective behavior and decentralized problem solving.

## Use Cases & Inspiration
Swarm intelligence simulations provide insight into behaviors relevant to:  

- Search and rescue robotics  
- Environmental monitoring  
- Distributed sensor networks  
- Bio-inspired computation  
- Generative motion and visual effects  
- Education on swarm intelligence concepts

## Contributing
Contributions are welcome!  
Add new swarm behaviors, improve the UI, enhance the physics, or evolve the codebase by opening an issue or submitting a pull request.

## License
MIT License — open for personal, academic, and commercial use.
