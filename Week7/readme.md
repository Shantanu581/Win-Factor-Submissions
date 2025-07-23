## 📝  Week 7 Task

### Main Assignment

**Build a basic DQN agent, as described in the DREAM11 paper:**

- **Environment:** Simulate a Dream11 team selection process with a fixed pool of players (22 or more), each with features like position, credit, recent form, average points.
- **Agent:** Use **Deep Q-Networks (DQN)** to train an agent that learns to select the best 11-player team based on rewards (fantasy points).
- **Reward:** Total fantasy score of the selected team. Penalize invalid teams (budget exceeded, too many players from same team, etc.).
- **Output:** Display the selected team after training + cumulative reward.
