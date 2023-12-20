# A2C (Advantage Actor-Critic):
Combines the benefits of policy-based (Actor) and value-based (Critic) methods.
The Actor proposes actions, and the Critic evaluates the actions using a value function.
Advantage is calculated as the difference between the observed rewards and the expected rewards from the Critic.
Updates to the policy (Actor) and value function (Critic) are performed simultaneously to improve both.
# PPO (Proximal Policy Optimization):
Designed to address issues of policy optimization stability in RL.
Uses a trust region approach to prevent large policy updates.
Balances exploration and exploitation by updating the policy within a "trust region" to ensure gradual changes.
Prevents large policy changes that may lead to catastrophic performance drops.
# DDPG (Deep Deterministic Policy Gradients):
Extends the Actor-Critic architecture to continuous action spaces.
Utilizes a deterministic policy, meaning the policy directly outputs continuous actions.
Employs a separate target network to stabilize training by updating the target values less frequently.
Incorporates experience replay and Ornstein-Uhlenbeck noise to enhance exploration and improve convergence.
