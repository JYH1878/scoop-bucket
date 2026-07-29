# scoop-bucket

[Scoop](https://scoop.sh) bucket for [KimiCodeBar-Windows](https://github.com/JYH1878/KimiCodeBar-Windows) — a Windows system tray app that monitors Kimi Code usage quotas.

KimiCodeBar-Windows 的 Scoop 软件源：Windows 系统托盘上的 Kimi Code 用量监控工具。

## Usage / 用法

```powershell
scoop bucket add kimicodebar https://github.com/JYH1878/scoop-bucket
scoop install kimicodebar/kimicodebar
```

Upgrade / 升级：

```powershell
scoop update kimicodebar
```

> 首次运行可能被 Windows SmartScreen 拦截（应用未购买代码签名证书，属开源软件常见情况）：点击"更多信息" → "仍要运行"即可。
> Windows SmartScreen may warn on first run (the app is not code-signed): click "More info" → "Run anyway".

## Notes

- Installs the portable build; config and cache live in `%APPDATA%\KimiCodeBar\` and survive updates.
- 安装的是便携版；配置与缓存存于 `%APPDATA%\KimiCodeBar\`，升级不受影响。
