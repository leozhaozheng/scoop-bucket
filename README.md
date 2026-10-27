# Leo 的 Scoop 软件源

[![Tests](https://github.com/leozhaozheng/scoop-bucket/actions/workflows/ci.yml/badge.svg)](https://github.com/leozhaozheng/scoop-bucket/actions/workflows/ci.yml) [![Excavator](https://github.com/leozhaozheng/scoop-bucket/actions/workflows/excavator.yml/badge.svg)](https://github.com/leozhaozheng/scoop-bucket/actions/workflows/excavator.yml)

我的个人 [Scoop](https://scoop.sh) 软件源（bucket），用于分发我维护的 Windows 应用清单。

## 如何安装这些应用？

添加软件源并安装应用：

```pwsh
scoop bucket add leo https://github.com/leozhaozheng/scoop-bucket
scoop install leo/textus
scoop install leo/winshun
```

## 当前收录的应用

- [textus](bucket/textus.json) —— 下一代 Markdown 编辑器，内置 AI 写作助手。
- [winshun](bucket/winshun.json) —— 免费开源的 Windows 搜索启动器：拼音文件搜索、全文搜索、剪贴板历史与 MCP 服务。

## 如何贡献新的清单？

如需贡献新的应用清单，请阅读 [Contributing Guide](https://github.com/ScoopInstaller/.github/blob/main/.github/CONTRIBUTING.md) 和 [App Manifests](https://github.com/ScoopInstaller/Scoop/wiki/App-Manifests) wiki 页面。
