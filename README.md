# Robot-wiring
## Question
布线区域分成m*n的方格阵列。要求确定连接方格S到方格D的最短布线方案。布线的时候，电路只能沿着直线或者直角布线，有障碍的方格做了封锁标记（X），其他线路不允许穿过被封锁的方格。

![image](https://raw.githubusercontent.com/XLN-nwafu/Robot-wiring/main/img/line.jpg)

## Abstract
通过QT展示界面，使用并查集算法或从文件读取生成待布线的地图，可以有多条路径，自动布线时对迷宫采用BFS算法选出最短路径，动画展示过程和布线结果；手动布线时展示第一视角图片。布线成功后进行文件输出相关信息。

## 示例 ##
5 5

S0000

00000

00000

00000

0000D
