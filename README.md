# DeepSleep

## About

- DeepSleep is a Xposed module. It can limit the background behavior of apps and reduce the power consumption of apps in the background.
  - Block acquire [wakelock](https://developer.android.com/training/scheduling/wakelock) and [alarms](https://developer.android.com/training/scheduling/alarms) to prevent redundant wake-ups.
  - Block start [services](https://developer.android.com/guide/components/services) to reduce memory consumption.
  - Block [sync](https://developer.android.com/training/sync-adapters?hl=zh-cn) to prevent redundant wake-ups.

- EDxposed/LSPosed scope Select the application to be limited.

- Serious warning
  - Using deepsleep is not recommended if your device has no standby power consumption problems.
  - Using deepsleep to limit the application may cause unusual problems with the application.
    - IM may experience message delays
    - Music player may not play on the lock screen
    - Other exceptions caused by restricting the background behavior of the app.

---

- DeepSleep 是 Xposed 模块.可以限制应用后台行为,节省待机电量消耗.
  - 禁止申请 [唤醒锁/wakelock](https://developer.android.com/training/scheduling/wakelock) 和 [闹钟/alarms](https://developer.android.com/training/scheduling/alarms),防止多余唤醒.
  - 禁止启动 [后台服务/Service](https://developer.android.com/guide/components/services),减少内存消耗.
  - 禁止 [同步/sync](https://developer.android.com/training/sync-adapters?hl=zh-cn),防止多余唤醒.

- EDxposed/LSPosed 作用域 选择需要限制应用.

- 严重警告
  - 如果您的设备没有待机耗电问题并不推荐使用 deepsleep.
  - 使用 deepsleep 限制应用,可能会导致应用出现异常问题.
    - 聊天应用 可能出现消息延迟
    - 音乐播放器 可能无法锁屏播放
    - 其他等因限制应用后台行为导致的异常.

## Features

- Beta:
  - ~~wakelock/alarm/service/sync restriction~~
  - ~~Data backup and recovery~~
  - ~~help/about fragment~~
  - ~~black/white list/regex support~~
  - ~~dark/light theme switch~~
  - broadcast restriction

---

- ~~Beta~~:
  - ~~wakelock/alarm/service/sync 限制~~
  - ~~帮助/关于界面~~
  - ~~黑白名单/正则支持~~
  - ~~深色/浅色主题切换~~
  - ~~备份/还原支持~~
  - 广播限制

## Compatibility

- Android N ~
- Edxpoed LSPosed

---

- Android N 及以上
- Edxposed LSPosed 支持

## Installation

- [Github releases](https://github.com/Jasper-1024/DeepSleep/releases), alpha/bate/Released.
- [酷安](https://www.coolapk.com/apk/260112), bate/Released
- [Play] waiting

## Support

- Only DeepSleep downloaded from the above channels is supported
- Please submit [ISSUE](https://github.com/Jasper-1024/DeepSleep/issues)

---

- 只支持从上述渠道下载的 DeepSleep
- bug 或 功能建议等可以提交 [ISSUE](https://github.com/Jasper-1024/DeepSleep/issues) / 酷安评论区 / Play(等待审核)

## Contributing

- [Jasper Hale](https://github.com/Jasper-1024)

## License

- DeepSleep is released under GNU GPLv3 ([License](https://github.com/Jasper-1024/DeepSleep/blob/master/LICENSE)).
- DeepSleep 以 GNU GPLv3 开源
