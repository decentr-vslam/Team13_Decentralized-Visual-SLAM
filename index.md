# Data-Efficinet Decentralized Visual SLAM Project

This is a python implementation of a data-efficient approach of Decentralized Visual SLAM. This was implemented by Team 13 (Aishwarya Unnikrishnan, Devesha Tewari, Lu Wen, and Haonan Chang) for the course EECS 568: Mobile Robotics.


## Overview
Multi-robobot decentralized systems are becoming more popular. However, they typically involve exchanging the entire map data between robots. The corresponding complexity thus scales quadratically with robot count. TO overcome this, we implement a data-efficient method by using a compact a  compactimage descriptor leveraging a state-of-the art visual vocabularymethod  and  only  sends  data  for  relative  pose  estimation  fora  single  matched  robot.  This  reduces  the  complexity,  scaling linearly with robot count. State-of-the-art decentralized pose-graph optimization method using a two stage- distributed Gauss-Seidel approach is also implemented.

![image](images/system_overview.PNG)

The above diagram shows the modules of our system, which are executed on each robot. 

## Results
