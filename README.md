# 短剧制作流水线 · 发布与更新通道

提供短剧制作流水线的发布附件、版本记录和在线更新清单。软件围绕下载、视频合成、人声分离、混音导出和上传等环节组织制作流程。

- [源码、安装和使用说明](https://github.com/1951779219/drama_pipeline_app)
- [最新版本](https://github.com/1951779219/drama_pipeline_release/releases/latest)
- [全部版本与更新记录](https://github.com/1951779219/drama_pipeline_release/releases)
- [问题反馈](https://github.com/1951779219/drama_pipeline_feedback/issues/new/choose)

## 如何下载和更新

1. 打开“最新版本”，先阅读该版本的更新说明。
2. 展开 **Assets**，确认附件是完整安装包还是更新包。
3. 已安装软件时，优先使用软件内的在线更新；手动更新前备份个人配置和任务数据并关闭软件。
4. 初次安装时，请按源码仓库的安装说明操作，或下载明确标注的完整发行包。

文件名含 `_update.zip` 的附件是更新包，应与已有安装配套使用。GitHub 自动提供的 **Source code (zip/tar.gz)** 只包含本发布通道的仓库文件，完整应用源码请到上方源码入口获取。

## 更新清单

软件更新器使用的清单地址：

```text
https://github.com/1951779219/drama_pipeline_release/releases/latest/download/latest.json
```

`latest.json` 是供软件读取的更新元数据，无需双击运行。发布流程会把更新包和清单同步到本仓库的 Releases。

## 使用入口

安装完成后，按源码仓库的说明启动软件，配置所需的本地工具、模型服务或第三方账号，再选择对应制作环节。第三方服务的可用性、凭据和费用由使用者自行配置。


## 许可

本仓库的自有代码和文档按 [MIT License](LICENSE) 提供。应用发行包中的第三方组件、工具和模型仍遵循各自许可。
