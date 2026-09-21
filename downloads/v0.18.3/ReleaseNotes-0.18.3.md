# DeskNest 0.18.3

## 简体中文

- 更新通道：stable
- 构建版本：0.18.3.65535
- 修复退出后桌面图标可能不显示的问题：退出前停止桌面重挂接，并验证图标显示区域已恢复。
- 修复 Windows 11 原生菜单长时间闲置后过早超时并回退旧菜单的问题，改善取消、清理和重试时序；Windows 10 菜单路径保持不变。
- 简化安全与恢复设置，明确区分软件设置与布局备份、桌面文件备份和布局历史。
- 打开备份或恢复操作不再隐式保存其他页面尚未确认的设置，升级继续保留用户配置和数据。

## English

- Channel: stable
- Build version: 0.18.3.65535
- Windows x64 stable release.
- Fixes desktop icons sometimes remaining hidden after exit by stopping desktop reattachment and verifying restoration before shutdown.
- Fixes premature Windows 11 native-menu timeouts and legacy fallback after idle, with safer cancellation, cleanup and retry timing. The Windows 10 menu path is unchanged.
- Simplifies Safety and Recovery settings, clearly separating settings and layout backups, desktop file backups and layout history.
- Opening backup or restore actions no longer implicitly saves unconfirmed settings from other pages. Upgrades continue to preserve user settings and data.
