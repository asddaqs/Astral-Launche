下载下方 **AstralLauncher.exe**（约 8.1 MiB）即可首次使用或升级，无需另下完整便携包。优先复用系统 WebView2；缺失时从微软官方下载、验证签名后准备。

## 本次发布

- **圆角优化**：支持的 Windows 使用原生平滑圆角，改善硬裁切锯齿，去掉浅色外描边；最大化和恢复正常。
- **EasyTier 联机**：六位房间号或二维码，默认免费社区节点，支持自定义节点。房主开放局域网后创建房间，好友加入并使用固定地址进服。
- **玩家工具**：模组批量更新、服务器收藏、截图相册、磁盘空间管理。
- **主页外观**：紧凑滑动开关切换圆形 / 方块地球，支持独立草方块外观及滑动光晕；开关位于实例数量上方。
- 保留 AI 聊天助手、聚合资源下载、实例加载器切换、整合包导入导出和存档备份恢复，并优化后台刷新与预览资源清理。

## 使用与验证

首次联机另需下载约 32 MB 官方 EasyTier 组件，并允许组网助手的管理员授权；启动器和游戏不随之提权。免费社区节点的可用性及中转速度取决于提供者，双方需要相同节点设置。

已通过组件哈希、真实进程本地 / 公共节点发现、房间隔离、游戏端口转发、浏览器大 / 小窗口及单 EXE 启动测试。实际管理员授权、TUN 网卡创建和跨设备 Minecraft 进服仍需首次交互验证。

## 文件说明

| 附件 | 用途 |
| --- | --- |
| AstralLauncher.exe | 首次使用及升级的主程序 |
| AstralLauncher.exe.sha256 | 程序 SHA256 校验值 |
| update.json | 启动器自动更新清单 |

GitHub 自动生成的 Source code 不是启动器安装包。升级前正常退出启动器，保留原有 `Astral`、`.minecraft` 和外部实例目录；本机文件名为 `Astral Launcher.exe` 时保持原名替换。

[使用指南](https://github.com/asddaqs/Astral-Launche/blob/main/docs/使用指南.md) · [联机说明](https://github.com/asddaqs/Astral-Launche/blob/main/docs/EasyTier联机.md) · [完整更新记录](https://github.com/asddaqs/Astral-Launche/blob/main/CHANGELOG.md)
