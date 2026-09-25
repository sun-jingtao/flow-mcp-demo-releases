# Flow Demo · Codex 插件下载

在 Codex 中读取 Flow 项目剧本、解析角色/场景/道具，并把生成图片回传到 Flow。

此仓库仅用于发布安装包与安装说明。当前提供 **QA 内部试用版**，连接 Flow QA 环境，需要使用者自己的 Flow QA 账号与项目权限。下载文件公开可用，业务数据仍由 Flow 账号权限控制。

## 轻量版预览（v0.4.0）

[下载通用 ZIP（约 80 KB）](https://github.com/sun-jingtao/flow-mcp-demo-releases/releases/download/v0.4.0/flow-demo-universal-plugin-upload.zip) · [改动与验收状态](https://github.com/sun-jingtao/flow-mcp-demo-releases/releases/tag/v0.4.0)

轻量版使用 Codex 提供的 Node，用户无需安装 Node。要求 Codex 提供宿主运行时查询及本地脚本执行能力；尚未覆盖所有桌面版本。预览版不会自动替换当前推荐版本，测试时请使用上面的指定版本链接。

## 当前推荐版（Latest）

| 电脑 | 安装包 |
| --- | --- |
| Mac · Apple 芯片（M 系列） | [下载 ZIP](https://github.com/sun-jingtao/flow-mcp-demo-releases/releases/latest/download/flow-demo-darwin-arm64-plugin-upload.zip) |
| Mac · Intel 芯片 | [下载 ZIP](https://github.com/sun-jingtao/flow-mcp-demo-releases/releases/latest/download/flow-demo-darwin-x64-plugin-upload.zip) |
| Windows · x64 | [下载 ZIP](https://github.com/sun-jingtao/flow-mcp-demo-releases/releases/latest/download/flow-demo-win32-x64-plugin-upload.zip) |

[当前版本与更新说明](https://github.com/sun-jingtao/flow-mcp-demo-releases/releases/latest) · [历史版本](https://github.com/sun-jingtao/flow-mcp-demo-releases/releases) · [SHA256 校验文件](https://github.com/sun-jingtao/flow-mcp-demo-releases/releases/latest/download/SHA256SUMS.txt)

请下载上面的插件 ZIP；GitHub 自动生成的 **Source code** 压缩包不包含可安装插件。

## 安装与登录

1. 选择推荐版的对应系统 ZIP，或轻量预览版通用 ZIP，**无需解压**。
2. 在 Codex 客户端打开「插件 → 添加 → 上传插件归档」，选择 ZIP；创建完成后点击「安装插件」。
3. 新建任务，输入：**用 Flow Demo 连接 Flow**。
4. 在插件打开的浏览器页面中，使用自己的 Flow QA 账号登录；未自动打开时，点击 Codex 返回的本机登录链接。
5. 成功后回到 Codex 回复「已登录」，让插件确认账号，再选择项目。

当前推荐的 v0.3.0 包含运行环境；v0.4.0 预览版使用 Codex 提供的 Node。用户均无需自行安装 Node.js、npm、Git 或执行终端命令。不要把密码发到对话中。登录令牌保存在当前电脑的用户配置目录，安装包不含预置账号。插件登录与 Flow 网页登录相互独立。

升级时重新下载安装对应系统的 ZIP，确认新版已启用，再新建任务；避免同时启用多份同名插件。版本功能与各平台的实际验证范围见对应 Release 说明。当前安装包不会自动更新。

## 下载链接与版本

上面三个下载地址保持不变，指向最新已发布的试用包；需要固定某一版时，从该版本 Release 下载附件。
每个版本均保留历史附件与 SHA256 校验文件。GitHub 的 Latest 标记表示本仓库推荐下载的版本，不代表插件已用于生产环境。

轻量版发布仍提供原来三个平台文件名作为相同内容的兼容别名。预览版完成客户端安装与使用验收后，才将其设为 Latest。
