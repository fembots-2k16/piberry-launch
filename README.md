SETUP::

    $ cd ~

    $ git clone https://github.com/fembots-2k16/piberry-launch
    
    $ sudo apt-get install ros-indigo-hokuyo-node ros-indigo-amcl
    
    $ sudo chmod 777 /dev/ttyACM0  ### might have to do this every time or add it to your ~/.bashrc
    
    $ sudo chmod 777 /dev/ttyUSB0  ### same's club
    
    ### assuming you already setup from https://github.com/fembots-2k16/configuring-ubuntu



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

