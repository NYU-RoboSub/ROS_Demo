# ROS_Demo

## How to run demo

- Make sure you have ROS 2 installed.
- Clone this repo.
- Navigate to the repo's base directory.
- Run ```colcon build --packages-select py_pubsub```
- Open a second terminal, and navigate to the base directory.
- Run ```. install/setup.bash``` in both terminals.
- Run ```ros2 run py_pubsub talker```
- Run ```ros2 run py_pubsub listener``` in another terminal.
- Done!
