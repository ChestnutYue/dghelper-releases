# DGHelper Releases

DGHelper（Draw & Guess 自动绘画 / 自动猜词插件）的**发布仓库**。

- 本仓库不含源码，源码见 [dghelper-mod](https://github.com/ChestnutYue/dghelper-mod)
- 每个版本对应一个 Release，资产为 Windows x64 安装包（zip）与校验文件
- 更新清单 latest.json 位于仓库根目录，随每次发布自动更新

## 客户端获取更新清单

- GitHub raw：https://raw.githubusercontent.com/ChestnutYue/dghelper-releases/main/latest.json
- jsDelivr：https://cdn.jsdelivr.net/gh/ChestnutYue/dghelper-releases@main/latest.json
- CDN 反代：https://<部署的 Worker 域名>/latest.json（见源仓库 cdn/README.md）

安装包下载优先使用清单中的 platforms.<平台>.mirror，失败时回退到 url（GitHub 直链）。