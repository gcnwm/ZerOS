# 关于

**[English](../README.md) | 简体中文**

**免责声明：此项目不会对任何潜在风险或损失负责。请自行斟酌使用。**

ZerOS 是 Windows11 的修改版，为游戏玩家和开发者定制。
**ZerOS 仅在 Windows 11 22H2 build 22621.963 测试过**

# 主要特征
- .NET Framework 3.5
- 移除大量无用组件 (详见 [removed_contents](../README/removed_contents.md))
- 移除 Windows 嵌入的追踪
- 应用组策略来减少数据收集

# 已知问题

- Windows Hello Face

# 使用方法

1. 获取最新的 Windows 11 镜像
2. 下载并安装 [NTLite](https://www.ntlite.com/) (至少需要 Home 版).
3. 导入预设 [ZerOS_v011b.xml](../res/ZerOS_v011b.xml) 并应用.
4. 添加 [ZerOS.reg](../res/ZerOS.reg) 中的注册表文件