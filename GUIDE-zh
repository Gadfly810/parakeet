# Scoop 存储桶模板

<!-- 替换占位符后取消注释以下行 -->
<!-- [![Tests](https://github.com/<username>/<bucketname>/actions/workflows/ci.yml/badge.svg)](https://github.com/<username>/<bucketname>/actions/workflows/ci.yml) [![Excavator](https://github.com/<username>/<bucketname>/actions/workflows/excavator.yml/badge.svg)](https://github.com/<username>/<bucketname>/actions/workflows/excavator.yml) -->

[Scoop](https://scoop.sh)（Windows 命令行安装器）的模板存储桶。

## 我如何使用这个模板？

1.  点击“Use this template”按钮，生成此仓库的副本。
2.  允许所有 GitHub Actions：
    *   导航到 `Settings` - `Actions` - `General` - `Actions permissions`。
    *   选择 `Allow all actions and reusable workflows`（允许所有动作和可复用工作流）。
    *   然后点击 `Save`（保存）。
3.  允许 GitHub Actions 从仓库内部进行写入：
    *   导航到 `Settings` - `Actions` - `General` - `Workflow permissions`。
    *   选择 `Read and write permissions`（读写权限）。
    *   然后点击 `Save`（保存）。
4.  在 `README.md` 中记录此存储桶。
5.  替换 `bin/auto-pr.ps1` 中的占位符仓库字符串。
6.  通过将 `bucket/app-name.json.template` 复制到 `bucket/<app-name>.json` 来创建新的清单文件。
7.  提交并推送更改。
8.  如果您希望您的存储桶在 `https://scoop.sh` 上被索引，请为您的仓库添加 `scoop-bucket` 主题（topic）。

## 我如何安装这些清单？

提交并推送清单后，运行以下命令：

```pwsh
scoop bucket add <bucketname> https://github.com/<username>/<bucketname>
scoop install <bucketname>/<manifestname>
```

## 我如何贡献新的清单？

要贡献新的清单，请阅读 [贡献指南](https://github.com/ScoopInstaller/.github/blob/main/.github/CONTRIBUTING.md) 和 [应用程序清单](https://github.com/ScoopInstaller/Scoop/wiki/App-Manifests) Wiki 页面。
