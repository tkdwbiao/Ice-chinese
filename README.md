<div align="center">
    <img src="Ice/Assets.xcassets/AppIcon.appiconset/icon_256x256.png" width=200 height=200>
    <h1>Ice</h1>
</div>

Ice 是一款强大的菜单栏管理工具。虽然它的主要功能是隐藏和显示菜单栏项目，但它还涵盖了各种各样的附加功能，力求成为功能最全面的菜单栏工具之一。

![Banner](https://github.com/user-attachments/assets/4423085c-4e4b-4f3d-ad0f-90a217c03470)

[![Download](https://img.shields.io/badge/download-latest-brightgreen?style=flat-square)](https://github.com/jordanbaird/Ice/releases/latest)
![Platform](https://img.shields.io/badge/platform-macOS-blue?style=flat-square)
![Requirements](https://img.shields.io/badge/requirements-macOS%2014%2B-fa4e49?style=flat-square)
[![Sponsor](https://img.shields.io/badge/Sponsor%20%E2%9D%A4%EF%B8%8F-8A2BE2?style=flat-square)](https://github.com/sponsors/jordanbaird)
[![Website](https://img.shields.io/badge/Website-015FBA?style=flat-square)](https://icemenubar.app)
[![License](https://img.shields.io/github/license/jordanbaird/Ice?style=flat-square)](LICENSE)

> [!NOTE]
> Ice 目前仍处于积极开发阶段，部分功能尚未实现。点击[这里](https://github.com/jordanbaird/Ice/releases/latest)下载最新版本，并查看下方的路线图了解即将推出的功能。

<a href="https://www.buymeacoffee.com/jordanbaird" target="_blank">
    <img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me A Coffee" style="height: 60px !important;width: 217px !important;">
</a>

## 安装

### 手动安装

从[最新版本](https://github.com/jordanbaird/Ice/releases/latest)下载 "Ice.zip" 文件，将解压后的应用移入你的 `应用程序` 文件夹。

### Homebrew

使用以下命令安装 Ice：

```sh
brew install --cask jordanbaird-ice
```

## 功能 / 路线图

### 菜单栏项目管理

- [x] 隐藏菜单栏项目
- [x] 「始终隐藏」菜单栏分区
- [x] 悬停在菜单栏上时显示隐藏的菜单栏项目
- [x] 点击菜单栏空白区域时显示隐藏的菜单栏项目
- [x] 在菜单栏中滚动或轻扫以显示隐藏的菜单栏项目
- [x] 自动重新隐藏菜单栏项目
- [x] 当应用菜单与已显示的菜单栏项目重叠时隐藏应用菜单
- [x] 拖放界面以排列各个菜单栏项目
- [x] 在单独的栏中显示隐藏的菜单栏项目（例如带刘海的 MacBook）
- [x] 搜索菜单栏项目
- [x] 菜单栏项目间距（测试版）
- [ ] 菜单栏布局配置文件
- [ ] 独立分隔符项目
- [ ] 菜单栏项目分组
- [ ] 满足触发条件时显示菜单栏项目

### 菜单栏外观

- [x] 菜单栏色调（纯色和渐变）
- [x] 菜单栏阴影
- [x] 菜单栏边框
- [x] 自定义菜单栏形状（圆角和/或拆分）
- [ ] 移除菜单栏背后的背景
- [ ] 圆角屏幕
- [ ] 浅色/深色模式的不同设置

### 快捷键

- [x] 切换各个菜单栏分区
- [x] 显示搜索面板
- [x] 启用/禁用 Ice Bar
- [x] 显示/隐藏分区分隔图标
- [x] 切换应用菜单
- [ ] 启用/禁用自动重新隐藏
- [ ] 临时显示各个菜单栏项目

### 其他

- [x] 登录时启动
- [x] 自动更新
- [ ] 菜单栏小组件

## 为什么 Ice 只支持 macOS 14 及以上版本？

Ice 使用了大量从 macOS 14 才开始提供的系统 API，因此没有计划支持更早的 macOS 版本。

## 截图预览

#### 在菜单栏下方显示隐藏的菜单栏项目

![Ice Bar](https://github.com/user-attachments/assets/f1429589-6186-4e1b-8aef-592219d49b9b)

#### 拖放界面以排列菜单栏项目

![Menu Bar Layout](https://github.com/user-attachments/assets/095442ba-f2d0-4bb4-9632-91e26ef8d45b)

#### 自定义菜单栏外观

![Menu Bar Appearance](https://github.com/user-attachments/assets/8c22c185-c3d2-49bb-971e-e1fc17df04b3)

#### 菜单栏项目搜索

![Menu Bar Item Search](https://github.com/user-attachments/assets/d1a7df3a-4989-4077-a0b1-8e7d5a1ba5b8)

#### 自定义菜单栏项目间距

![Menu Bar Item Spacing](https://github.com/user-attachments/assets/b196aa7e-184a-4d4c-b040-502f4aae40a6)

## 许可证

Ice 基于 [GPL-3.0 许可证](LICENSE) 提供。
