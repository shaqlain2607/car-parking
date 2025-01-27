# AUTONOMOUS CAR PARKING

Autonomous parking management through Multi-Agent Reinforcement Learning.

<p align="center">
 <img  width="400" height="250" src="https://github.com/Robotics-Club-IIT-BHU/gym-carpark/blob/main/media/parking.gif">
 <img  width="400" height="250" src="https://github.com/Robotics-Club-IIT-BHU/gym-carpark/blob/main/media/full-parking.png"><br>
</p>

## Installation Guidelines

Before installing this arena, you need to download certain modules on which it is dependent. We **strongly** recommend using a distribution of **Linux** as your operating system for this event. Windows installations tend to be a hassle and require, in some instances, quite a bit of time and effort to complete.

0. Although not compulsory, we strongly recommend creating a virtual environment specific to this project. This will help in package management and for decluttering your workspace. A simple way to create a virtual environment is as follows:

   ~~~bash
   python3 -m venv <Env_Name>
   ~~~

   Activation and deactivation of your virtual environment, will be done as specified [here](https://docs.python.org/3/library/venv.html). Scroll down to the table where the activation method for various operating systems is provided. Deactivation, in most cases, can be done by simply typing deactivate while being in in the virtual environment.

1. Once you activate your virtual environment, you will have to install the various dependencies of this project. We have simplified this process for you. Just follow the following steps:
   * Download/Clone this repository on to your local machine.
   * Navigate to the root folder of this repository through your terminal.
   * Execute the following command in your terminal.

      ~~~bash
      pip install -e carpark-arena
      ~~~

In case there are problems with the PyBullet installation, you can refer to this [guide](https://github.com/Robotics-Club-IIT-BHU/Robo-Summer-Camp-20/blob/master/Part1/Subpart%201/README.md).

## Using the Arena

0. You will have to import the package vision_arena, which will be available only if you've completed step 1 in the Installation Guidelines. The arena can be initialized by using:

   ~~~python
   env = gym.make("carpark_arena-v0")
   ~~~

   gym.make() itself takes some arguments, which will be elaborated upon further.

1. Then, you will have to create the working loop, as is normally done in pybullet (using `stepSimulation()`).

2. The functions of the environment, available to you for various purposes, are as follows. Please go through the functions themselves in this [file](https://github.com/Robotics-Club-IIT-BHU/gym-carpark/blob/main/carpark-arena/carpark_arena/envs/simpleDrivingEnv.py), if you wish to know their arguments and/or return values.

3. You can also run the file **helper.py** to see the documentation of the different various functions.

4. An example of how the arena works is given in the file **manual_control.py**, which contains the mechanism for controlling the car manually, for testing purposes.

## Made by ✨

<table>
   <td align="center">
      <a href="https://github.com/Ajasra22">
         <img src="https://avatars3.githubusercontent.com/u/60650011?s=400&v=4" width="100px;" alt=""/>
         <br />
         <sub>
            <b>Ajasra Gupta</b>
         </sub>
      </a>
      <br />
   </td>
   <td align="center">
      <a href="https://github.com/Vikhyath08">
         <img src="https://avatars2.githubusercontent.com/u/55887656?s=460&u=182d39459bf2d06f889fb2d6f90e1a400756ad95&v=4" width="100px;" alt=""/>
         <br />
         <sub>
            <b>Vikhyath Venkatraman</b>
         </sub>
      </a>
      <br />
   <td align="center">
      <a href="https://github.com/prince-0911">
         <img src="https://avatars0.githubusercontent.com/u/60649809?s=400&v=4" width="100px;" alt=""/>
         <br />
         <sub>
            <b>Prince Kumar Gond</b>
         </sub>
      </a>
      <br />
   </td>
   <td align="center">
      <a href="https://github.com/amarkeshri28">
         <img src="https://avatars3.githubusercontent.com/u/58410387?s=400&v=4" width="100px;" alt=""/>
         <br />
         <sub>
            <b>Amarjeet Keshri</b>
         </sub>
      </a>
      <br />
   </td>
</table>

## Advisors and Mentors

<table>
   <td align="center">
      <a href="https://github.com/lok-i">
         <img src="https://avatars1.githubusercontent.com/u/54435909?s=460&u=29af076049dab351b2e43621e9a433919bf50fb1&v=43" width="100px;" alt=""/>
         <br />
         <sub>
            <b>Lokesh Krishna</b>
         </sub>
      </a>
      <br />
   </td>
   <td align="center">
      <a href="https://github.com/NiranthS">
         <img src="https://avatars3.githubusercontent.com/u/44475481?s=400&v=4" width="100px;" alt=""/>
         <br />
         <sub>
            <b>Niranth Sai</b>
         </sub>
      </a>
      <br />
   </td>
</table>
