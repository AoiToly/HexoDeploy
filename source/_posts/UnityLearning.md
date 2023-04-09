---
title: UnityLearning
date: 2023-03-29 16:02:07
tags: 
---

# 参考教程

[M_Studio -- Unity开发教程：3D RPG Course | Core 核心功能](https://space.bilibili.com/370283072/channel/collectiondetail?sid=2985)

# M_Studio -- Unity开发教程：3D RPG Course | Core 核心功能

## 将普通项目升级为URP项目

1. 在Package Manager中安装Universal RP包
2. 在Project窗口中，点击加号->Rendering->Universal Renderer Pipeline->Pipeline Asset
3. 创建Pipeline Settings文件夹，将步骤二中创建的资源放入其中统一管理
4. 将内部资源转换成URP的资源
   低版本：Edit->Render Pipeline->Universal Render Pipeline->Upgrade Project Materials to UniversalRP Materials
   高版本：Windows->Rendering->Render Pipeline Converter，选择Built-in to URP，勾选前两个，Initialize Converters，Convert Assets

## 调整URP



# 一些名词解释

## 根骨骼动画/运动（Root Motion）

根骨骼动画：当动画中角色发生位移后，动作坐标原点跟随角色移动。例如一个向前跳跃的动画，如果在场景中重复该动画，能够看到角色一路往前跳跃，位置一直在前进。适用于有位移的放技能动作等。

非根骨骼动画：当动画中角色发生位移后，动作坐标原点始终保持在原地不变。例如一个向前跳跃的动画，如果在场景中重复该动画，能够看到角色往前跳跃后，完成一次该动画后角色的位置又会重置回去。适用于不能改变角色位置的动画，如闲置动作Idle。

[参考资料](https://www.bilibili.com/read/cv13605889)

# 一些实用技巧

## 快捷键V

顶点吸附，帮助环境布置

## 常用快捷键

QWERTY

## 快速调整相机视角

在Scene场景中调整视角到合适的位置，然后选择对应的Camera，按下CTRL+SHIFT+F，相机会同步到Scene的视角

# 一些资源获取途径

[mixamo--角色模型&动画](www.mixamo.com)
