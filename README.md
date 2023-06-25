# ZJU Radar Dataset

![](./pics/data_collection1.jpg)

## Download Link

[ZJU-Radar](https://zjuteducn-my.sharepoint.com/:f:/g/personal/201706120314_zjut_edu_cn/EmdoE4RvL-5Ppws83K1aSX8BaO4SBryLpSt1VGQ9DZI0tg?e=DXO2JQ)

## DataType

| Type  | Ros Topic Name  | Ros Topic Type          | Frequency(hz) |
| ----- | --------------- | ----------------------- | ------------- |
| Radar | /Navtech/Polar  | sensor_msgs/Image       | 4             |
| LiDAR | /rslidar_points | sensor_msgs/PointCloud2 | 10            |
| IMU   | /imu/data       | sensor_msgs/Imu         | 200           |
| RTK   | /gnss           | sensor_msgs/NavSatFix   | 4             |



## Parameter

ROLM extrinsics
lidar2gnss
[
1.0, 0.0, 0.0, 0.0,
0.0, 1.0, 0.0, 0.0,
0.0, 0.0, 1.0, -0.08,
0.0, 0.0, 0.0, 1.0
]
lidar2imu
[
1.0, 0.0, 0.0, 0.0,
0.0, 1.0, 0.0, -0.261,
0.0, 0.0, 1.0, 0.157,
0.0, 0.0, 0.0, 1.0
]
lidar2radar
[
1.0, 0.0, 0.0, 0.5745,
0.0, 1.0, 0.0, 0.0,
0.0, 0.0, 1.0, 0.0,
0.0, 0.0, 0.0, 1.0
]
lidar2camera
[
0.0, -1.0, 0.0, -0.214,
0.0, 0.0, -1.0, -0.157,
1.0, 0.0, 0.0, -0.02,
0.0, 0.0, 0.0, 1.0
]
camera2imu
[
0.0, 0.0, 1.0, 0.02,
-1.0, 0.0, 0.0, -0.475,
0.0, -1.0, 0.0, 0.0,
0.0, 0.0, 0.0, 1.0
]

## zjg-01

![](./pics/zjg-01.png)

## zjg-02



![zjg-02](./pics/zjg-02.png)

## zjg-03



![zjg-03](./pics/zjg-03.png)

## zjg-04

![zjg-04](./pics/zjg-04.png)

## zjg-05

![zjg-05](./pics/zjg-05.png)

## zjg-06

![zjg-06](./pics/zjg-06.png)

## yq-01

![yq-01](./pics/yq-01.png)

## yq-02

![yq-02](./pics/yq-02.png)

## yq-03

![yq-03](./pics/yq-03.png)

## HUANGLONG

![hl](./pics/hl.png)