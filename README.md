# NodeCrypt

## 🚀 部署说明

一键部署到 Cloudflare Workers

点击下方按钮即可一键部署到 Cloudflare Workers：
[![Deploy to Cloudflare Workers](https://deploy.workers.cloudflare.com/button?projectName=NodeCrypt)](https://deploy.workers.cloudflare.com/?url=https://github.com/limingzxc/NodeCrypt)

- 构建命令：npm run build
- 部署命令：npm run deploy

- 在cloudflare环境变量设置一下:
- Type : Text
- Variable name : AUTH_PASSWORD_HASH
- Value : 你密码的sha256 hex值

访问网站时用户名不输入或者随便输入都行，只要密码输入对就ok
