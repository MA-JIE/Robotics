# RRT
RRT是一种算法以及数据结构,被设计用来高效地在高维空间中进行搜索.它特别适合用于在涉及非完整约束场合下的路径规划问题.<br>
非完整约束: https://www.zhihu.com/question/60778489 <br>
RRT为一种递增式的构造方式,在构造过程中,算法不断地在搜索空间中随机生成状态点,如果该点为无碰撞的,则寻找搜索树中离该节点最近的节点为基准节点,由基准节点出发,以一定步长,朝着该随机节点进行延伸,延长线的终点所在的位置被当做有效节点加入搜索树中.这个搜索树的生长过程一直持续,知道目标节点与搜索树的距离在一定范围内时终止.随后,搜索算法在搜索树中寻找一条连接起点和终点的最短路径.<br>
![rrt](https://github.com/MA-JIE/Robotics/blob/master/%E8%B7%AF%E5%BE%84%E8%A7%84%E5%88%92%E7%AE%97%E6%B3%95/img/rrt1.png) <br>
![rrt](https://github.com/MA-JIE/Robotics/blob/master/%E8%B7%AF%E5%BE%84%E8%A7%84%E5%88%92%E7%AE%97%E6%B3%95/img/rrt2.png) <br>
![rrt](https://github.com/MA-JIE/Robotics/blob/master/%E8%B7%AF%E5%BE%84%E8%A7%84%E5%88%92%E7%AE%97%E6%B3%95/img/rrt3.png) <br>
![rrt](https://github.com/MA-JIE/Robotics/blob/master/%E8%B7%AF%E5%BE%84%E8%A7%84%E5%88%92%E7%AE%97%E6%B3%95/img/rrt4.png) <br>
