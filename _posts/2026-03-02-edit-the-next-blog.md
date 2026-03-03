---
layout: post
title: Python-robotics
subtitle: There's lots to learn!
gh-repo: daattali/beautiful-jekyll
gh-badge: [star, fork, follow]
tags: [test]
comments: true
mathjax: true
author: hs
---

Here's a table:

| Number | Next number | Previous number |
| :----- | :---------- | :-------------- |
| Five   | Six         | Four            |
| Ten    | Eleven      | Nine            |
| Seven  | Eight       | Six             |
| Two    | Three       | One             |

| 算法                              | 特点                           | 复杂度 |
| --------------------------------- | ------------------------------ | ------ |
| **Extended Kalman Filter (EKF)**  | 扩展卡尔曼滤波，处理非线性系统 | 中等   |
| **Particle Filter**               | 粒子滤波，适用于非高斯分布     | 中等   |
| **Histogram Filter**              | 直方图滤波，网格化概率分布     | 简单   |
| **Unscented Kalman Filter (UKF)** | 无迹卡尔曼滤波                 | 较高   |
| **Ensemble Kalman Filter**        | 集合卡尔曼滤波                 | 较高   |

```
PythonRobotics/
├── Localization/        # 定位算法
├── Mapping/            # 建图算法
├── SLAM/               # 同时定位与建图
├── PathPlanning/       # 路径规划 (最大模块, ~30算法)
├── PathTracking/       # 路径跟踪/控制
├── ArmNavigation/      # 机械臂导航
├── AerialNavigation/   # 空中导航 (无人机/火箭)
├── Bipedal/            # 双足机器人
├── InvertedPendulum/   # 倒立摆控制
├── MissionPlanning/    # 任务规划
├── utils/              # 共享工具
└── tests/              # 单元测试 (~70个)
```
