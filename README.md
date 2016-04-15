# SETUP::

## 1. Downloading & setting permissions

    ### assuming you already setup from https://github.com/fembots-2k16/configuring-ubuntu

    $ cd ~

    $ git clone https://github.com/fembots-2k16/piberry-launch
    
    $ sudo apt-get install ros-indigo-hokuyo-node ros-indigo-amcl ros-indigo-map-server ros-indigo-move-base ros-indigo-dwa-local-planner
    
## 2. Updating launch file to look at piberry launch directory

    a. change all the path names in navigation.launch to point to /home/<username>/piberry-launch
    
    b. note, this will just involve changing "saturn" in all of those paths to your username



-------------------------------------------------
---------TAB 1------------------------------------

    $ roscore

--------------------------------------------------
---------TAB 2------------------------------------

    $ cd ~/piberry-launch/

    $ sh enableRobot.sh

    $ roslaunch pioneer.launch

--------------------------------------------------
---------TAB 3------------------------------------

    $ cd ~/piberry-launch

    $ roslaunch navigation.launch

-------------------------------------------------
--------------TAB 3.5----------------------------

    $ rosrun rviz rviz

