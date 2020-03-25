# HWSDK IOS 

本文档是IOS版变现SDK，当前版本 `V3.1`

## 下载地址

SDK 下载地址：[v3.1](https://github.com/artwl/hwsdk_ios/releases/tag/V3.2)

## 接入文档

接入请参考：[SDK接入文档](https://github.com/artwl/hwsdk_ios/wiki/SDK%E6%8E%A5%E5%85%A5%E6%96%87%E6%A1%A3)

## 需要帮助？

请先查看接入文档和常见问题，还有问题可联系对接人寻求技术支持

## 本版特性 (3.1 - 2020年3月)

详细内容请查看更新记录，有完整的更新内容列表。
- **3.2 新特性（2020年3月25号）**
 - 新增加一家追踪平台
  
- **3.1 新特性（2020年3月17号）**
  - 添加banner是否加载的接口，添加banner加载成功的回调；当激励视频播放失败，抛这个回调 hwAdsRewardedVideoPlayFail，不给奖励恢复游戏逻辑
  
- **3.0 新特性（2020年3月12号）**
  - 添加插屏，激励回调；当广告缓存时间过长，播放该广告会触发播放失败当回调

- **2.7 新特性（2020年3月5号）**
  - 添加激励显示接口；添加推广人员需要打点的api；优化sdk内部变现打点

- **2.6 新特性（2020年1月19号）**
  - 添加插屏回调的接口，目前暴露了显示，关闭的回调

- **2.5 新特性**
  - 支持banner的接口，有banner的最好用这个版本

- **2.4 新特性**
  - 升级sdk，修复无网络进入时，卡主的bug

- **2.3 新特性**
  - 升级sdk，修改了2个接口，初始接口，仅仅需要传项目id的数字就行了

- **2.2 新特性**
  - 升级一家sdk，修复内部打点方式的bug

- **2.1 新特性**
  - 修复插屏控制逻辑的bug

- **2.0 新特性**
  - 支持广点通，穿山甲，Sigmob
