# Dijkstra
Dijkstra算法由荷兰计算机科学家艾兹赫尔·戴克斯特拉（Edsger Wybe Dijkstra）发明，通过计算初始点到自由空间内任何一点的最短距离可以得到全局最优路径.算法从初始点开始计算周围4个或者8个点与初始点的距离，再将新计算距离的点作为计算点计算其周围点与初始点的距离，这样计算像波阵面一样在自由空间内传播，直到到达目标点。这样就可以计算得到机器人的最短路径. <br>
Dijkstra算法是一种经典的广度优先的状态空间搜索算法，即算法会从初始点开始一层一层地搜索整个自由空间直到到达目标点。这样会大大增加计算时间和数据量。而且搜索得到的大量对于机器人运动是无用的. <br>
# 算法特点
![Dijkstra](https://github.com/MA-JIE/Robotics/blob/master/%E8%B7%AF%E5%BE%84%E8%A7%84%E5%88%92%E7%AE%97%E6%B3%95/img/Dijkstra.png) <br>

![Dijkstra](https://github.com/MA-JIE/Robotics/blob/master/%E8%B7%AF%E5%BE%84%E8%A7%84%E5%88%92%E7%AE%97%E6%B3%95/img/Dijkstra2.png) <br>
![Dijkstra](https://github.com/MA-JIE/Robotics/blob/master/%E8%B7%AF%E5%BE%84%E8%A7%84%E5%88%92%E7%AE%97%E6%B3%95/img/Dijkstra3.png) <br>
