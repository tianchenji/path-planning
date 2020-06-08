# path-planning
Collision avoidance path planning project for robots.
## Prerequisite
1. [CasADi](https://web.casadi.org/)
## Quick Start
1. `from navigator import MPC`
2. Inputs of `MPC class`:
    * current state of ego robot
    * current state & predicted future states of surrounding agents
3. Output of `MPC class`:
    * current control action of ego robot
