---
title: 'Google Chrome 调试工具小技巧（10）- 从 Console 面板快速监听事件'
date: 2017-11-15 10:28:48
tags: "Chrome-DevTool-Tips"
---
Chrome DevTools:  从 Console 面板快速监听事件

![使用Google调试工具添加Class](/images/tip10.gif)

- 在 Console 面板中执行 monitorEvents(object [, events])命令，传入你要监听的事件从参数。
- 取消监听的命令为 unmonitorEvents(object [, events])

_ Chrome版本 60.0.3112.101 _