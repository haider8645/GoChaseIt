# GoChaseIt

Description: This is an exercise project as part of the Robotics Software Engineer Nano Degree Program

Usage:

1) Make sure all dependencies are installed
2) Build the workspace using catkin_make
3) Source the setup.bash file from the devel folder. The devel folder is autogenerated at the workspace root folder
4) run the launch files from the my_robot and ball_chaser packages
5) Insert a white ball in the loaded Gazebo simulation
6) The robot will follow the white ball in its FOV.


Known Issues:

The process_image node loops over each pixel of the 800 x 800 input image. This makes the simulation very slow. A better approach using OpenCV will be implemented as the next version. The current version is submitted as it is because it was not a requirement in the nanodegree project to use OpenCV. 
