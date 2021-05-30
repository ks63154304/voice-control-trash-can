# voice-control-trash-can
## Overview
* This project aimed to the Implementation and Test of Movable Voice Control Trash Can
### Motivation
In view of the improvement of the overall environmental quality of the office in recent years, in order to save the time it takes for office workers to throw away wastes, so that they can have more time to focus on the content of the work, there is the idea of turning the trash can into sound control to realize wisdom.
## Realization
* flow chart

    ![image](https://user-images.githubusercontent.com/79617402/120102162-4e60bc00-c17c-11eb-97ce-8ad1de065f0f.png) 

* framework

    ![image](https://user-images.githubusercontent.com/79617402/120102177-591b5100-c17c-11eb-9688-2aa85cea6041.png)
## Planned Speed
### Himax WE-I Plus Board
We've done training in the website "Edge Impulse", which give us a package of design, training data, and output features in C language
* Process in Edge impulse(already done)
![image](https://user-images.githubusercontent.com/79617402/120102426-83b9d980-c17d-11eb-8eef-83dced374bbe.png)

Now we could use imgs(features) we've got from "Edge impulse" , after that we could get a feature after training. By using microphone on Himax WE-I Plus to collect data from enviroment, then we could get a response accuracy rate from machine.

## Difficulties and Innovation
* Not able to enhance the accurancy while training multiple data
* Not able to training voice and picture together (We're working on it!)
* Too much problem we met while installing the enviroment
