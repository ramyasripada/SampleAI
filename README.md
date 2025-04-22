I have generated training data by creating a scenario.
Scenario is we have a 10x10 grid, initial state at (0,0) , goal state at (9,9), obstacles at (1, 2), (1, 3), (2, 3), (3, 3),
            (4, 1), (4, 2), (4, 3), (5,0), (5, 5),
            (6, 5), (7, 5), (7, 6), (7, 7).
I have generated a training data by finding shortest path using BFS algorithm for 30 such scenario grids.

I wanted to train the agent using supervised learning. So data has inputs and label.
