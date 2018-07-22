# MOSAD 期末项目 实验报告

Team ZGenY an Gyak

------------------------

[TOC]



## 组员分工

张根: 主程, 负责从杨赞搭建好的Demo开始开发

杨赞: 首席, 负责写基础部分, 创建可用的Demo

吴志远: 剧本创作, CG制作, 素材整理, 报告攥写, 一切打杂事务



## 开发环境

开发环境: Windows 10 1607/1709, 内核版本号 NT 10.0.14393 / 10.0.16299

开发工具: Visual Studio 2017 Community

游戏引擎: cocos2d-x-3.16

辅助工具: Adobe Photoshop CC 2017, LAME MP3 Encoder, TexturePacker

测试环境: Windows 10 1607/1709, 内核版本号 NT 10.0.14393 / 10.0.16299

使用素材: 金庸群侠传(汉家松鼠工作室, CG, 音乐, 动画, 背景), 太极熊猫2(苏州蜗牛数字科技, 背景), 忍龙(思杰乐创, 背景), 大侠传(天空幻想, 背景)



## 项目阐述

### 项目名称

金庸群侠传

### 项目简介

故事背景: 元末明初, 天有异象, 时空错乱, 主角张无忌逆着时间顺序遇到三部曲中的一行人, 最后与东方不败过招。

登场角色: 张无忌(主角, 操作对象), 郭靖, 黄蓉, 乔峰, 段誉, 东方不败



## 项目功能

### Overview - 概览

菜单, 三个关卡, 每个关卡有Good End, Bad End。对战方式为1v1, 地图上四个方向皆可移动。过场CG提供剧情、对话。

### Concept Design - 概念设计

![1532199938060](.\markdown-rely\1532199938060.png)

(详见moasd-fin-proj-draft.png)

### Scene Manage - 场景管理

MenuScene.cpp/h - 菜单

Scene0~6.cpp/h - 游戏场景/过场CG/结局CG

### Animation Manage - 动画管理

使用Texture/Plist, 通过AppDelegate.cpp载入。

### Transistion CG - 过场CG

使用素材PS而成, 模仿谈话游戏风格





