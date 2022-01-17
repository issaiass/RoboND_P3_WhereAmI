# RoboND_P3_WhereAmI


<details open>
<summary> <b>Brief Review<b></summary>

This project includes all necessary files reproduce a simulation of the the robotics nanodegree project 3 (Where Am I) it setups the visualization for the AMCL using navigation package and topics like scan for localice the robot in an unkonwn environment, the robot is sometimes controlled by the teleop key if you want to make some basic operations.


Below an example of the outcome

<p align="center">
<img src = "doc/gif/WhereAmI.gif?raw=true" center="true" width="55%"/>
</p>

The project tree:

<p align="center">
<img src = "doc/img/tree.PNG?raw=true" width="55%"/>
<img src = "doc/img/amclcapture.PNG?raw=true" width="55%"/>
</p>

The project is now divided in several folders and now you can easily excecute effectively each file.

</details>

<details open>
<summary> <b>Using The Package <b></summary>

NOTE:  *If you experience gazebo craching or rviz crashing, remember to add the ros gazebo models from the source repository of open robotics to .gazebo/models and also add my models from the RoboND_P1_Gazebo/model folder*.

- Follow the next steps to replicate the outcome
~~~
    cd ~
    mkdir -p catkin_ws/src
    cd catkin_ws
    catkin_make
~~~
- Clone this repo in the `~/catkin_ws/src` folder by typing:
~~~ 
    cd ~/catkin_ws/src
    git clone https://github.com/issaiass/RoboND_P3_GoChaseIt.git
    cd ..
~~~
- Next source the repository
~~~
    source ~/catkin_ws/devel/setup.bash
~~~
- Launch the amcl.launch file, it will launch neccesary configuration for ROS to start the map server, the amcl by the navigation stack and publish/subscribe to the topics
~~~
    roslaunch robot_navitation amcl.launch
~~~
- Run the teleop key package
~~~
    rosrun teleop_twist_keyboard teleop_twist_keyboard.py
~~~
- Now use the keys to navigate or select a 2D Goal to navigate (2D Goal is on the rviz window above on the panel toolbox)
- See how you go to the desired position

<details open>
<summary> <b>Results<b></summary>

We will made a youtube video later

<p align="center"> </p>
</details>



<details open>
<summary> <b>Issues<b></summary>

- None

</details>

<details open>
<summary> <b>Future Work<b></summary>

- Coordinate and tune the amcl and planners

</details>

<details open>
<summary> <b>Contributing<b></summary>

Your contributions are always welcome! Please feel free to fork and modify the content but remember to finally do a pull request.

</details>

<details open>
<summary> :iphone: <b>Having Problems?<b></summary>

<p align = "center">

[<img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" />](https://www.linkedin.com/in/riawa)
[<img src="https://img.shields.io/badge/telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white"/>](https://t.me/issaiass)
[<img src="https://img.shields.io/badge/instagram-%23E4405F.svg?&style=for-the-badge&logo=instagram&logoColor=white">](https://www.instagram.com/daqsyspty/)
[<img src="https://img.shields.io/badge/twitter-%231DA1F2.svg?&style=for-the-badge&logo=twitter&logoColor=white" />](https://twitter.com/daqsyspty) 
[<img src ="https://img.shields.io/badge/facebook-%233b5998.svg?&style=for-the-badge&logo=facebook&logoColor=white%22">](https://www.facebook.com/daqsyspty)
[<img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" />](https://www.linkedin.com/in/riawe)
[<img src="https://img.shields.io/badge/tiktok-%23000000.svg?&style=for-the-badge&logo=tiktok&logoColor=white" />](https://www.linkedin.com/in/riawe)
[<img src="https://img.shields.io/badge/whatsapp-%23075e54.svg?&style=for-the-badge&logo=whatsapp&logoColor=white" />](https://wa.me/50766168542?text=Hello%20Rangel)
[<img src="https://img.shields.io/badge/hotmail-%23ffbb00.svg?&style=for-the-badge&logo=hotmail&logoColor=white" />](mailto:issaiass@hotmail.com)
[<img src="https://img.shields.io/badge/gmail-%23D14836.svg?&style=for-the-badge&logo=gmail&logoColor=white" />](mailto:riawalles@gmail.com)

</p

</details>

<details open>
<summary> <b>License<b></summary>
<p align = "center">
<img src= "https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-sa.svg" />
</p>
</details>
