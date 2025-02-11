# platoon_aliases
Aliases defined in .bashrc file of ubuntu for platoon project

## Aliases & environment variables:    

```bash
alias ip='hostname -I'
alias s='source ~/.bashrc'
alias open='nano ~/.bashrc'
alias show='cat ~/.bashrc'
alias bringup='ros2 launch turtlebot3_bringup robot.launch.py'
alias btp='ros2 launch robot_bringup bringup.launch.py'
alias go='cd ~/turtlebot3_ws/src/platoon/robot_bringup/'
alias cb='cd ~/turtlebot3_ws/ && colcon build --parallel-workers 1'
alias gocpp='cd ~/turtlebot3_ws/src/platoon/updated_turtlebot3_node/src/'
alias gohpp='cd ~/turtlebot3_ws/src/platoon/updated_turtlebot3_node/include/updated_turtlebot3_node/'
alias opencpp='nano ~/turtlebot3_ws/src/platoon/updated_turtlebot3_node/src/odometry.cpp'
alias openhpp='nano ~/turtlebot3_ws/src/platoon/updated_turtlebot3_node/include/updated_turtlebot3_node/odometry.hpp'
alias showcpp='cat ~/turtlebot3_ws/src/platoon/updated_turtlebot3_node/src/odometry.cpp'
alias showhpp='cat ~/turtlebot3_ws/src/platoon/updated_turtlebot3_node/include/updated_turtlebot3_node/odometry.hpp'

source /opt/ros/humble/setup.bash
source ~/turtlebot3_ws/install/setup.bash
export ROS_DOMAIN_ID=13 #TURTLEBOT3
export LDS_MODEL=LDS-02
export TURTLEBOT3_MODEL=<write-model-here>
export TURTLEBOT3_NAMESPACE=<write-bot-namespace-here>
```
