<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="light.png">
  <source media="(prefers-color-scheme: light)" srcset="dark.png">
  <img src="dark.png" alt="ovo" width="112" height="112">
</picture>

# ovo

Windows 上的本机工具启动面板：将各类日常常用的渗透工具统一集合到一个面板来管理，双击即启动。

单文件免安装 · Tauri 2 + Vue 3

![platform](https://img.shields.io/badge/platform-Windows_10%2B-0078D4?style=flat-square)
![version](https://img.shields.io/badge/version-2.1.0-2c2c2c?style=flat-square)
![size](https://img.shields.io/badge/单文件-5.2%20MB-brightgreen?style=flat-square)
![license](https://img.shields.io/badge/license-MIT-blue?style=flat-square)

</div>

<table>
  <tr>
    <td width="50%"><img src="docs/theme-light.png" alt="浅色主题"></td>
    <td width="50%"><img src="docs/theme-dark.png" alt="深色主题"></td>
  </tr>
  <tr>
    <td align="center">浅色主题</td><td align="center">深色主题</td>
  </tr>
</table>

## 使用方法

1. **下载运行**：Releases 里取 `ovo.exe`，放到任意目录双击。首次运行 Windows 可能弹 SmartScreen 提示——没有代码签名，属正常。
2. **加运行环境**（只有 Java / Python 类工具需要）：点顶栏的运行环境图标 → 添加 → 选目录。Java/Python选安装根目录。
3. **新建工具**：右上角「新建工具」→ 填名称、选类型、选文件（Web 类型直接填 URL）→ 挑运行环境与分组 → 保存。
4. **启动**：双击卡片；或右键用菜单（启动 / 以管理员身份运行 / 编辑 / 打开工作目录 / 删除）；也可从托盘菜单启动。
5. **顶栏其余入口**：新建分组、切换主题、导出配置、导入配置，以及「关闭窗口时最小化到托盘」开关。

配置与图标都写在程序同目录 `data\` 目录里；运行日志在 `data\logs\app.log`，托盘菜单可直接打开。

许可见 [LICENSE](LICENSE)。
