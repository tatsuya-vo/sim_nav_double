# sim_nav_double
Simulate and navigate two turtlebot3 simultaneously, on a turtlebot3_world map.

I make it by following this video https://www.youtube.com/watch?v=iyL_hsqjKWI.

## How to run:

1. Run roscore:

        $ roscore
2. Run simulations:

        $ roslaunch double_turtlebot3s_sim main.launch
3. Run navigation:

        $ roslaunch double_turtlebot3s_nav navigation.launch
4. Send goal via topic 2D Nav Goal on Tool Properties.
