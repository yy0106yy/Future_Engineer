# Future_Engineer

## electronic components presentation
Move Motor：Drive the rear wheels of the car to control the forward and backward of the vehicle.

Servo Motor：Control the mechanism to make the vehicle turn .

Lithium Battery：Supply motor and motherboard power.

Ultrasonic sensor :to detect the distance.

## Engineering log

**Record Date：2022.1.15**

**Members：CHEN,YO-YU、LI,CHEN-YU**

**Content：**

We read about the rules and think the idea of the robot.The first idea is to use the remote control car.
Change it controller and add our own controller.


**Record Date：2022.1.22**

**Members：CHEN,YO-YU、LI,CHEN-YU**

**Content：**

We lerned how to use arduino to controll our car and how the circuit system operate.

**Record Date：2022.1.29**

**Members：CHEN,YO-YU、LI,CHEN-YU**

**Content：**

We try to controll the move Motor,so we learn how it works.

Digital pin , a high current and a Low current can controll it to forward and reverse.

Analog pin , can change the speed. And we Successfully made the motor move.

![image](https://github.com/yy0106yy/Future_Engineer/blob/main/photos/motor%20code.jpg)

**Record Date：2022.2.5**

**Members：CHEN,YO-YU、LI,CHEN-YU**

**Content：**

We found that the Steering of the remote control car was not very good ,so we decided to use lego to make the car by ourselves.
We use differential to let the speed run faster while it is turning.

![image](https://github.com/yy0106yy/Future_Engineer/blob/main/photos/differential.JPG)

**Record Date：2022.2.12**

**Members：CHEN,YO-YU、LI,CHEN-YU**

**Content：**

We finish our car and motor control,but we haven't got the degree of the motor.So today teacher teach us the way to get the degree.While we are testing ,we encountered some problem.The degree wasn't correct.When the speed goes fast,the degree rises more.It's because processor can't Calculate the angle and 
other thing in the same time.So we use the hardware interrupt .When the Potential is changing,the interrupt will attach.And we can Calculate the 
angle in interrupt.

![image](https://github.com/yy0106yy/Future_Engineer/blob/main/photos/degree%20interrupt.jpg)

**Record Date：2022.2.19**

**Members：CHEN,YO-YU、LI,CHEN-YU**

**Content：**

Today we learned how to use ultrasonic .We have two way to get the vlaue of the ultrasonic.

(1)One is easier,but it will stuck the program because we need to wait for the ultrasonic receive.

(2)Another one is using interrupt.First discharge the ultrasonic,and continue work.When the ultrasonic receive,the program will go to execute the interrupt.And then  we can calculate the distance in it.It won't stuck the program. So we choose the second  idea.

![image](https://github.com/yy0106yy/Future_Engineer/blob/main/photos/US.jpg)

![image]()
