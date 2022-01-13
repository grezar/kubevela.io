---
title: 回收应用部署的环境
description: 操作应用从某个环境回收，释放占用的资源。
---

当你需要将应用在某个环境的部署资源回收，即关闭应用时，参考下述操作。

![pod list](../../../resources/pod-list.jpg)

如上图所示，完成部署的环境视图下回出现 `Recycle` 按钮，点击该按钮确认后即可将该环境部署的资源进行回收删除。

> 请注意，回收意味着对应的资源将删除，对于需要有状态存储的应用，该操作会导致数据丢失。纯无状态应用可通过重新部署后恢复。

### 删除应用和环境的绑定关系

应用如果成功从该环境回收后，操作区域将存在 `Delete` 按钮，点击该按钮即可删除应用与环境的绑定关系。