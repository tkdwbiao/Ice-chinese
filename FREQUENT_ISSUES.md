# 常见问题 <!-- omit in toc -->

- [项目被移到「始终隐藏」分区](#items-are-moved-to-the-always-hidden-section)
- [Ice 移除了某个项目](#ice-removed-an-item)
- [Ice 不记得项目的顺序](#ice-does-not-remember-the-order-of-items)
- [如何解决 `Ice 无法在自动隐藏的菜单栏中排列菜单栏项目` 错误？](#how-do-i-solve-the-ice-cannot-arrange-menu-bar-items-in-automatically-hidden-menu-bars-error)

## 项目被移到「始终隐藏」分区 {#items-are-moved-to-the-always-hidden-section}

默认情况下，macOS 会把新项目添加到菜单栏最左侧，而那里也正是 Ice 的「始终隐藏」分区所在的位置。大多数应用都会配置为记住其项目的位置，但也有一些不会。macOS 每次都会把这些应用的项目当作新项目处理。因此，即使这些项目之前曾被移动过，它们也会出现在「始终隐藏」分区中。

Ice 目前并不管理单个项目，事实上在当前版本中也无法做到这一点。一旦 [#6](https://github.com/jordanbaird/Ice/issues/6) 和 [#26](https://github.com/jordanbaird/Ice/issues/26) 这两个 issue 得以实现，Ice 就能监控菜单栏中的项目，并将其识别出的项目移回它们之前的位置，即便 macOS 重新排列了它们。

## Ice 移除了某个项目 {#ice-removed-an-item}

Ice 没有能力移动或移除项目。该项目很可能是被 macOS 放到了「始终隐藏」分区中。按住 Option 并点击 Ice 图标以显示「始终隐藏」分区，然后按住 Command 把该项目拖到其他分区。

## Ice 不记得项目的顺序 {#ice-does-not-remember-the-order-of-items}

这不是 bug，而是一个尚未实现的功能。它正在 [#26](https://github.com/jordanbaird/Ice/issues/26) 中跟踪。

## 如何解决 `Ice 无法在自动隐藏的菜单栏中排列菜单栏项目` 错误？ {#how-do-i-solve-the-ice-cannot-arrange-menu-bar-items-in-automatically-hidden-menu-bars-error}

1. 打开 Mac 上的 `系统设置`
2. 进入 `控制中心`
3. 如下方图片所示，选择 `从不`
4. 在 `Ice` 中更新你的 `菜单栏项目`
5. 将 `自动隐藏和显示菜单栏` 恢复为你偏好的设置

![关闭菜单栏自动隐藏](https://github.com/user-attachments/assets/74c1fde6-d310-4fe3-9f2b-703d8ccb636a)
