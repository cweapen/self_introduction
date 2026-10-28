# Java Backend · Personal Portfolio

一个可以直接托管到 GitHub Pages 的静态个人主页，参考 Academic Pages 的「左侧个人介绍 + 右侧项目内容」信息架构，但**不是** Academic Pages/Jekyll 官方模板的改版；无需 Ruby、Jekyll、npm 或构建步骤。

## 预览

双击 `index.html` 即可在浏览器本地打开。

## 上线前需要替换

在 `index.html` 中搜索并修改以下占位内容：

- `你的姓名`、`Your Name` 和头像 `DEV`
- `your-email@example.com`
- `https://github.com/` 改为自己的 Github 主页
- `所在地：按需填写`
- 项目介绍与实际公开范围；补充真实的项目仓库链接、截图、量化成果
- 根据真实简历完善学校、学历、时间和可公开的身份资料

**重要**：页面内容根据已聊过的学习内容和项目实践整理，没有经过独立核验；「正在学习」的技术不代表生产级熟练，正式求职前请逐项校对。默认没有公开具体单位、学校、真实地址、邮箱或未公开源码。

## 发布 GitHub Pages（无构建版本）

1. 在 GitHub 新建公开仓库 `你的GitHub用户名.github.io`，以取得根域名 `https://你的GitHub用户名.github.io/`；也可以建普通仓库获得带项目名的 URL。
2. 将 `index.html` 和 `README.md` 上传到仓库的默认分支根目录并提交。
3. 打开仓库 **Settings → Pages**，在 **Build and deployment** 中选择 **Deploy from a branch**，分支选择 `main`、目录选择 `/ (root)`，保存。
4. 等待 GitHub 的 Pages 部署流程完成后，在 Settings → Pages 处查看实际发布 URL。

如果仓库为私有，请先核查账户计划是否支持相应 Pages 发布，以及网站的公开可见性规则；静态站点中的信息不能视为私密内容。

## 后续扩展建议

- 为每个项目添加单独的详细页面、结构图、技术难点和测试证据。
- 将学习笔记变成 Markdown 驱动的博客（可迁移到 VitePress/Jekyll）。
- 加入真实 Github 仓库、在线演示、简历 PDF 链接。
- 扩展中英文双语版本。
