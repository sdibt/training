## 本周学习

- 学了最小生成树和拓扑排序，最小生成树多适用于无向图，也是一种贪心算法；拓扑排序一般只适用于有向无环图按规则排序。比如按胜负排名次、选修课排序等。

## 下周计划

- 把vj题会做的做完，继续补博客...（感觉得补一个学期才补完）

## 本周感想

- 因为上党课耽误了不少空...本周vj还没来得及做...
- 对Kruskal算法自我理解即为把各个点看做n个单独的小树，所有边从短到长排序，从最短边开始把两个不相互连接的树连在一起组成新的树，把所有单独的小树都连接在一个树上即树上有n-1条边时结束。这也是一种贪心算法。对Prim算法自我理解为从一个起点开始找与起点相连的最短的边，并且与这条边相连的节点不能在树中，如果在，将这条边舍去，否则将这条边及与其相连的节点加入树中，直到将所有的点加入进去为止。个人感觉Kruskal更简单些吧。