# **_Sahayak Bot_**



## Welcome the eYRC 2020's Sahayak Bot theme !!!  

Please find the base package for this theme from this repository. 



> This package is tested on **Ubuntu 18, ROS-Melodic**. We recommend you to use this OS and ROS distribution only.



## Installation

###  ROS installation

- Follow the Official Installation instruction from the [ROS-Melodic](http://wiki.ros.org/melodic/Installation/Ubuntu) website. We recommend to use the following command for **step 1.4**. This will ensure all the basic package availability and possibly avoid any missing packages errors.

```bash
sudo apt install ros-melodic-desktop-full
```

For those who are familiar with debugging in ROS, may use  `ros-melodic-*` of their choice.

- **Or** you can follow the instruction from the Task Books (mdbook) available on the [eYRC portal](https://portal.e-yantra.org/login).

### Additional Packages 

- Teleop package to control from your terminal. For those who have install `ros-melodic-desktop-full` don't need to install this package, since it already available. 

```bash
sudo apt-get install ros-melodic-teleop-twist-keyboard
```



### Cloning this repository

Inside your `cakin_ws/src`, enter the following command to clone (download) this repository. 

```bash
git clone https://github.com/vishalgpt579/sahayak_bot.git
```

> Note: Earlier in task 1, few files size made the entire package about 200 MB+. We have utilise the Github's LFS(large file system) to tackle this problem. 

