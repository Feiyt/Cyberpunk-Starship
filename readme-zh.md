# Cyberpunk Yellow-Green Starship 

[English](README.md)
本项目是一个为 [Starship](https://starship.rs/) shell 提示符设计的赛博朋克黄绿配色主题，适用于 Windows、Linux、macOS 等操作系统。主题文件为 `Cyberpunk Yellow-Green Starship.toml`，可直接用于美化你的终端体验。

## 文件结构

- `Cyberpunk Yellow-Green Starship.toml`：主题配置文件，包含配色、图标、模块顺序等详细设置。
- `demo.gif`：主题实际效果预览动画。
- `README.md`：项目说明文档。

## 主要特色

- 赛博朋克风格黄绿色调，夜间观感舒适
- 针对多种操作系统和主流开发语言定制图标与样式
- 支持 Node.js、Python、Rust、Go、Java、PHP 等开发环境
- 目录、Git、时间、虚拟环境等模块均有美化
- 兼容 PowerShell、bash、zsh 等主流 shell

## 使用方法

1. 安装 [Starship](https://starship.rs/guide/#%E5%AE%89%E8%A3%85)
2. 将 `Cyberpunk Yellow-Green Starship.toml` 复制到你的用户主目录下（如 `~/.config/starship.toml` 或 `C:\Users\<用户名>\.config\starship.toml`）
3. 在 shell 配置文件中添加如下内容（以 PowerShell 为例）：

   ```powershell
   Invoke-Expression (&starship init powershell)
   ```

   其他 shell 的配置方法请参考 [官方文档](https://starship.rs/guide/#%E5%90%AF%E7%94%A8-starship)

## 预览

![示例效果图](demo.gif)

## 自定义说明

- 可根据需要修改 `palette`、模块顺序、图标等内容
- 支持多种开发语言和环境的版本显示
- 详细配置项请参考 [Starship 官方文档](https://starship.rs/config/)

## 许可证

本项目采用 MIT License。