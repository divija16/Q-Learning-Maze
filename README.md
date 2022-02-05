# Find the target in a maze using reinforcement learning
A maze is created 8x8 grid using q table. 

# Environment 
The Maze environment is a grid of tiles.

Red rectangle is the explorer object.

Black rectangles are hells, which have to be avoided.     [reward = -1]
Gold bin circle are gold, which is the paradise!        [reward = +1]
All other states are ground.                              [reward = 0]


The environment can be represented as:

* States: tiles

* Actions: Left, Right, Up, Down

* Reward: +1 for gold state, -1 for black state, 0 for others.



# Reinforcement learning Agent


# Running the code
Clone this repository:

```bash
$ git clone https://github.com/divija-swetha/coding-exercise.git
```
In the terminal run `python main.py`

## Results

After 100 episodes, the number of movements get converged to the optimal. The reward also goes to 1. If you run the experiment for 1000 episodes, the agent mostly takes the action to get maximum reward which is 1 but occationally explores other actions as well.

The results are in out folder and the performance of the agent playing the game can is in [screen](./out/screen.txt)

# Contributors

- Divija Swetha Gadiraju <dgadiraj@purdue.edu>

# License
[MIT LICENSE](LICENSE)

