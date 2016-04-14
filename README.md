SETUP::

    $ cd ~

    $ git clone https://github.com/fembots-2k16/piberry-launch
    
    ### assuming you already created a catkin_ws from https://github.com/fembots-2k16/configuring-ubuntu
    
    $ cd ~/catkin_ws/src
    
    $ git clone https://github.com/allenh1/p2os
    
    $ cd ~/catkin_ws
    
    $ catkin_make
    
    $ source devel/setup.bash



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

