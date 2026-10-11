# Forensic-Tool

取证工具（实验品）。

## 最新版本

**v2.0.0-20261011（2026-10-11，离线翻译修正版）**：[下载完整 Windows 包](https://github.com/hxyz486/Forensic-Tool/releases/download/v2.0.0-20261011/HXY-Tool-2.0.0-20261011-win64.zip) · [发布说明与签名附件](https://github.com/hxyz486/Forensic-Tool/releases/tag/v2.0.0-20261011)

压缩包约 1.88 GB，解压内容约 2.72 GB，包含程序、插件、完整 Hy-MT2 1.8B Q4_K_M 模型和运行组件。完整解压后进入 `tool` 目录运行 `HXY-Tool.exe`。

本次修复实际打包桌面版的翻译引擎初始化异常，改为独立进程加载并复用模型；继续完全离线运行，保留原激活机制。10 月 9 日版的相关检查未覆盖真实桌面窗口初始化环境，建议使用本修正版。

`HXY-Tool-2.0.0-20261011-win64.zip` SHA256：

```text
ef8b4db01be5c6d9f2de9f2819bfcfaf16b3020010e5caedf252120bd91b4f13
```

```powershell
Get-FileHash .\HXY-Tool-2.0.0-20261011-win64.zip -Algorithm SHA256
```

发布附件提供压缩包和文件清单的 PGP 分离签名、SHA256 清单及公钥。公钥指纹：`0C8FA55396F256282194542D7656D4CB3357D9B7`。包内附模型官方许可证及来源说明。

激活码可联系 QQ：3453614267。

[10 月 9 日版](https://github.com/hxyz486/Forensic-Tool/releases/tag/v2.0.0-20261009) · [历史 v2.0.0](https://github.com/hxyz486/Forensic-Tool/releases/tag/v2.0.0) · [全部版本](https://github.com/hxyz486/Forensic-Tool/releases)
