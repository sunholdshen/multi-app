# 来源与第三方材料

MultiApp 的飞书适配方法参考了公开项目：

- 作者：eggyrooch-blip
- 项目：https://github.com/eggyrooch-blip/feishu-clone
- 参考方法：以等长目录名替换隔离 Chromium 单实例锁，重新签名副本并避免官方自动更新覆盖修改。

上游 README 标注 MIT；查阅时仓库未提供独立 LICENSE 文件，GitHub API 的 license 字段为空。本仓库不复制或分发上游脚本，管理器和构建核心以 Swift 独立实现，特此保留方法来源说明。

仓库没有第三方包依赖。SF Symbols、AppKit 与 SwiftUI 为系统框架；应用图标由本仓库的绘制脚本生成。运行时显示的本机应用图标来自用户已安装应用，不包含在本项目发布包中。

0.1.0-beta.1 曾以 MIT 许可证公开发布，对应历史许可保留于 licenses/MIT-0.1.0-beta.1.txt（安装包内为 MIT-0.1.0-beta.1.txt）。后续版本源码转为私有，不追溯撤回历史版本已授予的许可。MultiApp 的任何许可均不授予飞书客户端、飞书商标或其他第三方材料的权利。
