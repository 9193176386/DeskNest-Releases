# DeskNest 0.16.6

## 简体中文

- 更新通道：stable
- 构建版本：0.16.6.65535
- 修复外观设置遇到刷新时背景图片未保存、再次打开后消失的问题。
- 刷新时保留未变化的 Box，减少无关盒子闪烁并保留映射文件夹导航。
- 改善 Box 拖动和调整大小的流畅度，统一普通盒子与映射文件夹的毛玻璃表现。
- Windows 11 Acrylic 支持跟随系统和自定义外观，安装包内置所需运行库；Win10 保留原有材质路径。
- 修复映射文件夹导航菜单和断开显示器后的布局保护；保留用户数据及预览取消回滚。

## English

- Channel: stable
- Build version: 0.16.6.65535
- Windows x64 stable release.
- Fixes background images not being saved when Box appearance dialogs encounter layout refreshes.
- Keeps unchanged Boxes and portal navigation alive during refreshes to reduce flicker.
- Improves Box dragging and resizing, with consistent Acrylic rendering for collections and folder portals.
- Packages the Windows 11 Acrylic runtime for system-following and custom appearances; Windows 10 keeps its existing material path.
- Fixes portal navigation menus and disconnected-monitor layout protection while preserving user data and preview cancellation.
