# LangChain JS 中文入门指南示例仓库

欢迎来到 LangChain JS 中文入门指南示例仓库！这个仓库旨在帮助开发者快速上手 [LangChain JS](https://js.langchain.com/docs/) 并熟悉其使用方法。

本仓库是由 [liaokongVFX](https://github.com/liaokongVFX) 编写的 [LangChain 中文入门教程](https://github.com/liaokongVFX/LangChain-Chinese-Getting-Started-Guide) 的 JavaScript 版本。

## LangChain 介绍

[LangChain](https://docs.langchain.com/docs/) 是一个强大的框架，旨在帮助开发人员使用语言模型构建端到端的应用程序。它提供了一套工具、组件和接口，可简化创建由大型语言模型 (LLM) 和聊天模型提供支持的应用程序的过程。LangChain 可以轻松管理与语言模型的交互，将多个组件链接在一起，并集成额外的资源，例如 API 和数据库。

目前官方提供 [Python](https://github.com/hwchase17/langchain) 和 [JavaScript](https://github.com/hwchase17/langchainjs) 两种语言的 SDK。能力上 Python SDK 更为完善。

## 开始使用

1. 首先，克隆本仓库到本地。

2. 接下来，确保您已经安装了 Node.js 和 npm。如果尚未安装，请访问 [Node.js 官方网站](https://nodejs.org/) 下载并安装。

3. 安装项目依赖：`npm install`

4. 为了运行仓库中的样例，您需要安装一个名为 [Node.js Notebooks (REPL)](https://marketplace.visualstudio.com/items?itemName=donjayamanne.typescript-notebook) 的 VS Code 插件。请点击链接，按照插件页面的说明进行安装。

5. 打开 VS Code，然后打开本项目。在项目根目录下，您将看到一个名为 `lab.nnb` 的文件，这个文件包含了多个 LangChain JS 的示例。您可以逐个查看和运行这些示例，学习 LangChain JS 提供的各种功能。

> 注意：请参考 `.env.example` 编写您自己的 `.env` 文件，用于运行相关示例。

## 示例内容

本项目包含以下几个定制示例：

- 直接使用 OpenAI Model 完成一次提问
- 使用 Agent 通过 Google 搜索并返回答案
- 使用 Text Loader 对超长文本进行总结和问答
- 使用内存向量索引数据库构建问答机器人
- 使用 Pinecone 向量索引库构建问答机器人
- 使用 Zapier NLA 发送邮件

以及几个官方示例：

- 使用顺序的任务链
- 使用格式化输出输出
- 使用 Memory 实现带记忆的对话

## 贡献

我们非常欢迎您为本项目作出贡献！如果您在使用过程中发现了任何问题，或者有任何改进的建议，请通过 Issues 或 Pull Requests 与我们联系。

## 许可证

本仓库采用 [MIT License](LICENSE) 授权。
