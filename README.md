# vi_sensor_sdk
Loitor VI Sensor SDK

内容包含:
0. Loitor产品手册
1. VI_SENSOR_SDK 和样例程序
2. ROS驱动
3. IMU校准程序
4. ORB_SLAM2官方开源代码

V1.1.1更新 --2017/3/6

1. 产品手册V0.6中加入了对imu-cmos位置的精确描述
2. 对于“非sudo权限无法打开camera”的问题，增加了“loitor-vi-install.sh” ，其使用方法写在了此次更新的使用手册的11.2
3. 修改了普通用户权限下读取串口的方式，具体方法写在了此次更新的使用手册的11.1
4. 解决了SDK示例程序对opencv2.4.9以上版本的兼容问题
5. 解决了单独左眼camera或者右眼camera打开无图像问题

V1.0
初始版本
