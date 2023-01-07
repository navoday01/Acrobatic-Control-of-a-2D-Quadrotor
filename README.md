# Acrobatic-Control-of-a-2D-Quadrotor
Acrobatic control of a 2D quadrotor refers to the ability of the quadrotor to perform complex, dynamic maneuvers such as flips and turns. In this project, we designed and implemented two controllers for a 2D quadrotor to enable it to perform acrobatic maneuvers: a Linear-Quadratic Regulator (LQR) controller and an iterative LQR (iLQR) controller with added line search. The LQR controller was designed to maintain a predefined position and follow a predefined trajectory, while the iLQR controller was developed to perform acrobatic maneuvers and avoid local minima. 

<!-- <p align = 'center'>
<img src = "assets/quadrotorcircle.gif">
<img src = "assets/quadrotoracrobatic.gif">  
</p>   -->

![Alt text](assets/quadrotorcircle.gif)|![Alt text](assets/quadrotoracrobatic.gif)
 :--:|:--:
  *Following Trajectory* |*Doing Flip*
  
![alt-text-1](assets/quadrotorcircle.gif "*Following Trajectory*" = 30%x) ![alt-text-2](assets/quadrotoracrobatic.gif "*Doing Flip*" = 30%x)
