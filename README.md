# Clash 订阅管理完全指南

本文详细介绍如何获取、导入、更新 Clash 订阅链接，以及常见问题的解决方法。

## 什么是订阅链接

订阅链接是机场提供的节点信息集合，导入 Clash 后自动包含所有节点，无需手动添加。

## 获取订阅链接

1. 登录你的机场后台
2. 找到「订阅」或「Clash」相关页面
3. 复制订阅地址（通常以 `https://` 开头）

## 导入 Clash

### Windows (Clash for Windows)

1. 打开 Clash for Windows
2. 左侧菜单点击「Profiles」
3. 粘贴订阅链接到输入框
4. 点击「Download」
5. 选择对应配置即可

### Android (ClashMeta)

1. 打开 ClashMeta
2. 点击「配置」→「新配置」
3. 选择「订阅」
4. 粘贴链接并确认

### iOS (Stash/Surge)

使用订阅转换服务将原始订阅转为 Surge/Stash 格式。

## 自动更新

在 Clash for Windows 中开启「自动更新」：

```
Settings > Auto Update > 启用
```

建议设置更新频率为每天或每周。

## 订阅转换

如果你的客户端不支持原始订阅格式，可以使用 [Subconverter](https://github.com/tindy2013/subconverter) 转换。

## 常见问题

**订阅链接失效？** 重新登录机场后台获取新链接。

**更新后节点变少？** 机场可能更换节点，删除旧配置重新下载。

**节点速度慢？** 使用订阅转换服务的筛选功能，选择低延迟节点。

---

推荐工具：

- [Clash for Windows](https://clashforwindows.site/) - Windows 最好用的 Clash 客户端
- [ClashMI](https://clashmi.site/) - 轻量级跨平台客户端
- [FlClash](https://flclash.us/) - 支持多协议的新一代工具
