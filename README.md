# Auto-Renew-Serv00-Single

Auto-Renew-Serv00-Single 是一个自动化项目，旨在通过定期登录Serv00面板来实现自动续期。本项目使用GitHub Actions自动执行脚本，定期登录Serv00面板并回显登录成功


## 功能
- 每60天自动登录Serv00面板。
- 检查单个账户的登录状态。
- 在执行记录中打印登录情况。

## 环境变量设置
在开始之前，请确保你已经在GitHub仓库的`Settings` -> `Secrets and variables` -> `Actions` -> `New Repo Secrets`中添加了以下Secrets：

- `USERNAME1`
- `PASSWORD1`
- `PANEL_INDEX1`
