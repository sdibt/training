# 周报

  一周过去了，每个周的学习内容都不太一样，但还是一如既往的抽象，讲的东西不太好理解，反正对我来说是这样...听题和写题的感觉也完全不一样，听题听懂了写不一定会写同类型的题，听不懂另说，但写题就不好说了，而且标准和水平是两个水平，It’s extremely striking...对于教的东西吧，思路不太清楚，无法利用起来，可能真要用的话，还得自己弄一遍...

  这周主讲算法Bellman-Ford和SPFA，第一个是寻找源点s到顶点的最短路径长度，一般方式：对于每一条边e(u, v)，如果Distant[u] + w(u, v) < Distant[v]，则另Distant[v] = Distant[u]+w(u, v)。w(u, v)为边e(u,v)的权值； 若上述操作没有对Distant进行更新，说明最短路径已经查找完毕，或者部分点不可达，跳出循环，第二个就是用：初始时，只有把起点放入队列中，遍历与起点相连的边，如果可以松弛就更新距离dis[],然后判断如果这个点没有在队列中就入队标记。出队队首，取消标记，循环，直至队为空。所有能更新的点都更新完毕，dis[]数组中的距离就是起点到其他点的最短距离。最后一个讲的是Floyd，这个比之前两个不太好理解，反正这个我还不太懂...

  下周算法希望讲的稍微具体一点，这样就有时间都想想以前的，不然越积越多就...

 

 

 

 

 