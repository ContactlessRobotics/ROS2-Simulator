
ROS2 - Humble

sudo apt install ros-humble-twist-mux
sudo apt install ros-humble-controller-manager


Gazebo classic! New gazebos broken with some packages for what we're doing

Step 1:
Humble install
https://docs.ros.org/en/humble/Installation/Ubuntu-Install-Debians.html


Install colcon


Optional:
Auto source ros

https://docs.ros.org/en/humble/Tutorials/Beginner-CLI-Tools/Configuring-ROS2-Environment.html

sudo apt install ros-humble-gazebo-ros-pkgs

Test it
gazebo /usr/share/gazebo-11/worlds/seesaw.world


make the dev folder:
mkdir ~/Desktop/__
colcon build --symlink-install # makes folders
cd build # Go into right folder

clone the github in src folder make it




build the packages

source the overlay:
source install/setup.bash



Running it:
ros2 launch articubot_one launch_sim.launch.py 

ros2 run teleop_twist_keyboard teleop_twist_keyboard 












