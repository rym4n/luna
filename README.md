# luna

**把终端、服务器文件、数据库和 Kafka 放进同一个桌面工作区。**

[下载安装](https://github.com/rym4n/luna/releases) · [反馈问题](https://github.com/rym4n/luna/issues)

## 终端与远程连接

- 同时使用本地终端和 SSH，支持密码、私钥及私钥口令。
- 用多标签、分组和分屏组织会话，保存工作区并在下次启动时恢复。
- 搜索终端输出、复制内容、调整外观，使用快捷命令和自定义提示符。
- 管理 SSH 隧道与代理连接，在同一工作区切换多台服务器。

## 文件与服务器管理

- 浏览本地文件和远程 SFTP、FTP、FTPS 文件，上传、下载、重命名和调整权限。
- 管理文件传输进度，通过本地应用打开远程文件，并在保存后回传。
- 查看服务器 CPU、内存、磁盘、网络、进程与日志，辅助日常排查。

## 数据库工作台

- 连接 MySQL / MariaDB、PostgreSQL、SQLite、SQL Server、Redis、MongoDB、ClickHouse、DuckDB 等数据库。
- 浏览对象、编写查询、查看和编辑数据，使用支持的导入导出、结构比较与数据传输功能。
- 为 Redis 提供键浏览、值编辑、监控、慢日志和内存分析。
- 为 MongoDB 提供集合与文档管理，为 Qdrant、Milvus、Weaviate、ChromaDB 提供向量数据与检索界面。
- 不同数据库展示各自支持的操作，连接方式和功能以应用界面为准。

## Kafka 管理

查看集群、Topic、分区、消息、消费组和 ACL，在消息检索与连接管理之间快速切换。

## 按你的习惯组织工作

使用可调整大小的面板、多种布局预设、明暗主题和中英文界面。连接资料与密钥可统一管理，凭据保险库支持密码解锁及系统可用的 Touch ID / Windows Hello。

## 下载安装

前往 [Releases](https://github.com/rym4n/luna/releases)，选择对应安装包：

| 系统 | 安装包 |
| --- | --- |
| Windows x64 | `*-setup.exe` |
| macOS Apple Silicon | `*_aarch64.dmg` |
| macOS Intel | `*_x64.dmg` |

版本使用发布日期与小时，例如 `v26102116` 表示 2026 年 10 月 21 日 16 点发布的版本。

当前安装包未签名。首次打开可能收到系统确认提示；请确认安装包来自上面的发布页面。macOS 可在“系统设置 → 隐私与安全性”中允许打开，Windows 可在 SmartScreen 提示中选择“更多信息 → 仍要运行”。

## 反馈

请在 [Issues](https://github.com/rym4n/luna/issues) 中描述系统、luna 版本、复现步骤和预期结果。提交截图或日志前，请遮盖密码、令牌与服务器地址等敏感信息。
