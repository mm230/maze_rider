# Maze Rider
Reinforcement Learning project: Maze Rider

For this project, our environment will be a maze. The idea is pretty simple: our agent starts at one end of the maze and must reach a certain goal at the other end. To make things spicier, the agent must also avoid pits scattered in the environment.
At each step the agent can perform one of this four actions: move to the left, to the right, up or down:
- If the agent reaches an empty cell, it gets a reward of  0 .
- If the agent tries to cross a wall, nothing happens and it also gets a reward of  0 .
- If the agent reaches the goal, the episode ends and it gets a reward of  1 .
- If the agent falls into a pit, the episode ends and it gets a reward of  −1 .

The walls will stay the same between each episode, however, the agent's starting position as well as the positions of the goal and the pits will be randomly picked between a small number of candidates at each episode.
