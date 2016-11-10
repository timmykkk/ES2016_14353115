#  在linux下安装ROS
 ***
1 ROS全称Robot operation system, 底层需要硬件驱动，可能还需要传感器驱动。  

2 安装步骤  
（1）设置sources.list，以接受来自packages.ros.org的软件。  

` sudo sh -c 'echo "deb http://packages.ros.org/ros/ubuntu $(lsb_release -sc) main" > /etc/apt/sources.list.d/ros-latest.list'`  
（2）设置钥匙。 

`sudo apt-key adv --keyserver hkp://ha.pool.sks-keyservers.net:80 --recv-key 0xB01FA116`  
（3）确保Debian软件包已经更新。 

`sudo apt-get update`  
（4）安装ROS桌面完整版 

`sudo apt-get install ros-jade-desktop-full`  
（5）初始化rosdep  
`sudo rosdep init` 

`rosdep update`  
（6）环境设置  
`echo "source /opt/ros/jade/setup.bash" >> ~/.bashrc`  

`source ~/.bashrc`

3 安装成功截图  
![](https://raw.githubusercontent.com/timmykkk/ES2016_14353115/master/ros.png)
