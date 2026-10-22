# DeskNest 0.18.5

## 简体中文

- 更新通道：stable
- 构建版本：0.18.5.65535
- Windows 明确报告 Direct3D 独占全屏时，阻止搜索和切换 Box 快捷键弹出界面；注销后的遗留快捷键消息不再触发动作。
- 减少屏幕布局刷新时重复的原生窗口调整，避免意外重新显示隐藏窗口；修复刷新导致桌面图标位置变化的问题。
- 中转站新增紧凑界面、清晰的搜索入口及皮肤设置；Windows 11 提供原生材质，Windows 10 保持兼容材质路径。
- 包含设置、托盘和后台 I/O 改进，以及独立桌面恢复守护；升级继续保留配置和用户数据。
- 针对 Apex 卡顿反馈修复了已确认的干扰风险；尚未完成真实游戏性能验证，不宣称已经解决所有掉帧问题。

## English

- Channel: stable
- Build version: 0.18.5.65535
- Windows x64 stable release.
- Suppresses search and Box-toggle actions when Windows explicitly reports exclusive Direct3D fullscreen, and ignores queued hotkeys after unregistration.
- Avoids redundant native window positioning and unintended showing of hidden desktop surfaces; keeps desktop icon positions stable during refresh.
- Adds a compact Station interface, discoverable search and appearance settings, with native materials on Windows 11 and compatible material paths on Windows 10.
- Includes settings, tray and background I/O improvements and an independent desktop recovery guard. Upgrades preserve settings and user data.
- Addresses confirmed interference risks investigated after Apex reports. Actual game performance remains unverified; this is not a claim that every FPS issue is fixed.
