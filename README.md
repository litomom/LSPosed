LSPosed 框架
https://github.com/LSPosed/LSPosed/actions/workflows/core.yml?query=event%3Apush+branch%3Amaster+is%3Acompleted https://lsposed.crowdin.com/lsposed https://t.me/LSPosed https://qun.qq.com/qqweb/qunpro/share?_wv=3&_wwv=128&inviteCode=Xz9dJ&from=246610&biz=ka https://github.com/LSPosed/LSPosed/releases/latest https://github.com/LSPosed/LSPosed/releases
介绍
这是一个 Riru / Zygisk 模块，试图提供一个 ART 钩子框架，通过 LSPlant 钩子框架提供与原始 Xposed 一致的 API。
Xposed 是一个框架，允许模块在不触碰任何 APK 的情况下更改系统和应用程序的行为。这非常棒，因为这意味着模块可以在不同的版本甚至 ROM 上工作，而无需任何更改（只要原始代码没有太大变化）。撤销也很容易。由于所有更改都在内存中进行，只需停用模块并重启即可恢复原始系统。还有许多其他优势，但这里只提一个：多个模块可以更改系统或应用程序的同一部分。对于修改过的 APK，你必须选择一个。除非作者构建了具有不同组合的多个 APK，否则无法将它们组合在一起。
支持的版本
Android 8.1 ~ 14
安装
安装 Magisk v24+
（对于 Riru 版本）安装 Riru v26.1.7+
下载 并在 Magisk 应用中安装 LSPosed
重启设备
从通知中打开 LSPosed 管理器
尽情享受 :)
下载
对于稳定版本，请前往 Github 发布页面
对于金丝雀版本，请查看 Github Actions
注意：调试版本仅在 Github Actions 中提供。
获取帮助
仅接受来自最新调试版本的错误报告。
GitHub 问题：问题
（对于中文用户）本项目只接受英文标题的 issue。如果您不懂英文，请使用翻译工具
开发者指南
欢迎开发者使用基于 LSPosed 框架的钩子编写 Xposed 模块。基于 LSPosed 框架的模块与原始 Xposed 框架完全兼容，反之亦然，基于 Xposed 框架的模块也将与 LSPosed 框架良好协作。
Xposed 框架 API
我们使用自己的模块仓库。欢迎开发者提交模块到我们的仓库，然后模块可以在 LSPosed 中下载。
LSPosed 模块仓库
社区讨论
Telegram: @LSPosed
注意：这些社区群组不接受任何错误报告，请使用 获取帮助 进行报告。
翻译贡献
您可以在 这里 贡献翻译。
致谢
Magisk: 使这一切成为可能
Riru: 提供了一种将代码注入 zygote 进程的方法
XposedBridge: 原始 Xposed 框架 API
Dobby: 用于内联钩子
LSPlant: 核心 ART 钩子框架
EdXposed: 叉子源
~SandHook: 用于 SandHook 变体的 ART 钩子框架~
~YAHFA: 之前的 ART 钩子框架~
~dexmaker 和 dalvikdx: 动态生成 YAHFA 钩子类~
~DexBuilder: 动态生成 YAHFA 钩子类~
许可证
LSPosed 采用 GNU 通用公共许可证 v3 (GPL-3) 许可证（http://www.gnu.org/copyleft/gpl.html）。
