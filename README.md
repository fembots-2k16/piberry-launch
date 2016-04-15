# SETUP::

## 1. Downloading & setting permissions

    ### assuming you already setup from https://github.com/fembots-2k16/configuring-ubuntu

    $ cd ~

    $ git clone https://github.com/fembots-2k16/piberry-launch
    
    $ sudo apt-get install ros-indigo-hokuyo-node ros-indigo-amcl ros-indigo-map-server ros-indigo-move-base ros-indigo-dwa-local-planner
    
    $ sudo chmod 777 /dev/ttyACM0  ### might have to do this every time or add it to your ~/.bashrc
    
    $ sudo chmod 777 /dev/ttyUSB0  ### same's club
    
## 2. Updating launch file to look at piberry launch directory

    a. change all the path names in navigation.launch to point to /home/<username>/piberry-launch
    
    b. note, this will just involve changing "saturn" in all of those paths to your username



-------------------------------------------------
---------TAB 1------------------------------------

    $ roscore

--------------------------------------------------
---------TAB 2------------------------------------

    $ cd ~/piberry-launch/

    $ roslaunch pioneer.launch

--------------------------------------------------
---------TAB 3------------------------------------

    $ cd ~/piberry-launch

    $ roslaunch navigation.launch

-------------------------------------------------
--------------TAB 3.5----------------------------

    $ rosrun rviz rviz

