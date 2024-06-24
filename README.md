# scout_mini_urdf
with ZED2 &amp; Unitree LiDAR

cd colcon_ws/src
git clone https://github.com/nirali3931/scout_mini_description.git
cd ~/colcon_ws
colcob build
source install/setup.bash
ros2 launch scout_mini_description view_robot.launch


