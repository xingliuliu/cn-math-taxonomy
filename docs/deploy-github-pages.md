# 部署到自己的 GitHub Pages

本项目是纯静态网页，不需要构建步骤或额外依赖。仓库已附带自动部署工作流：向 `main` 分支推送后，GitHub Actions 会发布仓库根目录。

1. Fork 本仓库到自己的 GitHub 账号。
2. 在副本的 **Settings → Pages → Build and deployment → Source** 中选择 **GitHub Actions**。
3. 确认副本的 **Actions** 已启用。之后每次向 `main` 推送，工作流都会自动更新网站。

首次部署完成后，项目站点地址为 `https://<GitHub用户名>.github.io/cn-math-taxonomy/`。GitHub 会在仓库的 **Settings → Pages** 页面显示实际地址和部署状态。

网站的样式、脚本和数据引用均使用相对路径，可部署在这个项目站点子路径下。数据与题目沿用本仓库的 CC BY-NC 4.0 许可；请保留署名和许可说明。
