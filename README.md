# Taxi-Problem
The Taxi Problem is a reinforcement learning task where an agent navigates a grid to pick up and drop off passengers efficiently. The goal is to maximize rewards using RL techniques, with a solved benchmark of 9.7 average return over 100 trials.
Getting Started
We are working with the Taxi-v3 environment from OpenAI Gym. Your goal is to train an AI agent to navigate a taxi efficiently using reinforcement learning.

Files in the Project
agent.py → Modify this file to improve your AI agent.

monitor.py → Runs tests to check how well your agent learns.

main.py → Runs the entire project and reports the agent's performance.

Running the Project

Use this command in the terminal:
python main.py

This runs 20,000 episodes where your agent interacts with the environment and learns over time.

Performance Metrics
avg_rewards → Keeps track of the average rewards in chunks of 100 episodes.

best_avg_reward → The highest recorded average reward across all episodes.

Your Task
Modify agent.py to improve the AI agent:

Initialize Variables → Define required variables like epsilon (for an epsilon-greedy policy).

Choose Actions → Implement the select_action() method to make smarter action choices instead of random selection.

Update Learning → Modify the step() method to improve learning using reinforcement learning techniques.

Goal
You "solve" the problem if your agent achieves an average return of 9.7 over 100 consecutive trials.
