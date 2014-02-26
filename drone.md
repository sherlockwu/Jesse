#Drone
##技术准备
###硬件
通信:

- 串行口（uart）
- IIC
- 蓝牙，无线网络：Socket(TCP/IP or UDP),HTTP
- 协议 Mavlink
- PMW

硬件:

- 超声波测距
- 激光雷达
- 陀螺仪，角加速度，磁场，气压计
- GPS 通信
- 摄像头（采集）
- arm板的使用
- 舵机

软件：

 - $$$\mu cos$$$
 - arm linux：
 	- linux使用 bash (freeshell.ustc.edu.cn) ,ssh
 	- linux 编译 (gcc javac ,gdb)
 	- 自己装个Ubuntu
 - 视频压缩与传输
 - Apache2（HTTP服务器）
 - 通信协议(java) << Think in Java>>
 
飞机：
 
 - 了解基本的空气动力学知识一点点：
 	
 	- 螺旋桨
 	- 升力
 	- 三轴控制
 
 - 了解自动控制：
 
  	- PIDs
 
 平台：
 
- 对apm以及px4的目录结构有一定了解