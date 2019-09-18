# RL-Argumented-GA-For-TSP

Hello!

This is Ziyan Lin, a graduate student from Johns Hopkins University, majoring in applied math and statistics.

In this repository, there is a group project to find solution of a TSP (Travelling Salesman Problem) by using deep reinforcement learning on local search for TSP, in cooperate with Jinchang Fan, Han Wang, and Xiaoyu Qiao.

One of classical approaches to solve TSP is Genetic Algorithm applying with Lin-Kernighan heuristic. This method generates relatively high accuracy for solutions, but it is limited by the number of iterations in 2-opt heuristic. The efficiency of current algorithm only allows small datasets to implement. After touching material about deep learning and reinforcement learning, we try to improve the efficiency by combining deep reinforcement learning with Genetic Algorithm and Lin-Kernighan heuristic in TSP, which is our purpose for this project.

The key step of improvement is to find out a proper 2-opt of current route to perform GA and LKH. The popular way is to go through all points following the order of distance, but our idea is to check points based on probability gained from a RL model. The final results show that our approach has is more effective than the traditional way when carry out with small-size TSP (about 50 points) and has nearly same terms of target value (total cost of route)

This repository contains [all parts of code](), and one [final report](https://github.com/lzykaren/RL-Argumented-GA-For-TSP/blob/master/Final%20Report%20-%20JFan%2CHWang%2CXQiu%2CZLin.pdf). If you have any question or suggestion, please feel free to contact me. Thank you very much.

My email address: ziyanlin3@gmail.com
