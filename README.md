# my_first_pkg
This package contains the URDF file of a diff drive robot and launch files to launch it in gazebo and rviz.

## Usage
1. Clone this repository to your ROS2 workspace:
   ```shell
   git clone https://github.com/robofuntastic/my_first_pkg.git
2. Build the ROS2 package:
   ```shell
   cd  learn_ros2_ws
   colcon build --symlink-install
   source install/local_setup.bash
3. Launch the robot in RVIZ2
   ```ros2 launch my_first_pkg display.launch.py```
4. Launch the robot in Gazebo
   ```ros2 launch my_first_pkg gazebo.launch.py```
5. Open another terminal and use
   ```ros2 run teleop_twist_keyboard teleop_twist_keyboard```\
   Move your robot around

# [Watch the Complete Tutorial](https://youtu.be/Vbh3--etiwg)
## [Udemy Course](https://www.udemy.com/course/ros2-for-beginners-build-your-first-robot-with-esp32/?referralCode=F34735B28D1210013C61)
## License
This project is licensed under the MIT License.
