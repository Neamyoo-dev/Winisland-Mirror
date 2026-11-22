<p align="center">
  <img src="resources/info-zh.png" width="350">
</p>

# WinIsland

[English](./README.md) | 简体中文

> [!IMPORTANT]
> **本仓库是个人镜像。** 它是 WinIsland 源码及其完整历史的个人副本，在原始组织不可访问之后保留下来。
>
> 本仓库**不接受任何 PR 和 Issue**。在这里提交的任何内容都会被直接关闭，不做审核。没有支持承诺，也没有发布计划。

WinIsland 为 Windows 带来**灵动岛**体验。

## 下载

本镜像通过 GitHub Actions 发布稳定版本构建。安装包使用自签名证书签名，Windows 首次运行时会显示 SmartScreen 警告，运行前请确认文件来源。这些是个人构建：没有支持承诺，也没有固定节奏。如果不希望安装，可以按下面的步骤从源码构建。

## 构建项目

安装包含 **Cargo** 的 **Rust** 工具链，然后运行：

```cmd
git clone https://github.com/Neamyoo-dev/Winisland-Mirror.git

cd Winisland-Mirror

cargo build --release
```

## 隐私

WinIsland 不收集任何遥测数据。有关其处理的信息及需要联网的功能，请参阅[隐私政策](PRIVACY-zh.md)。

## 许可证

本项目采用 [GNU General Public License v3.0](LICENSE) 许可证。
