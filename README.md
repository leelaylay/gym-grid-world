Grid World Environments
===

Forked from leomao/gym-grid-world and modified to compatible with gym.

## How to Use

```
import gym
import gym_grid_world

env = gym.make('pickput2d-v0')

# configure the enviroments
env.configure(...)

# gym compatible
# obs = env.reset()
# obs, rew, done, info = env.step(action)
```

## Environments

- Eat Bullet `eatbullet2d-v0`
- Pick Put `pickput2d-v0`
- Push Block `pushblock2d-v0`
