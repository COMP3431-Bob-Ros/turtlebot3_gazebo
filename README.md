# Instructions

Replace your current turtlebot3_gazebo folder with this repository to get the COMP3431 gazebo maze environment.

cd ~/catkin_ws/src/turtlebot3_simulations
rm -rf turtlebot3_gazebo
git clone https://github.com/stathiw/turtlebot3_gazebo.git
cd ~/catkin_ws/src
git clone http://robolab.cse.unsw.edu.au:4443/comp3431-rsa/ comp3431-rsa.git
cd ~/catkin_ws/
catkin_make
