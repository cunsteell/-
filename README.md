# 个人作品集网站

中文静态个人网站演示，包含 8 个页面、3 个概念项目案例和交互示例。人物、经历、项目均为虚构演示内容。

## 文件结构

- `index.html`：网站首页
- `projects.html`：项目总览与筛选
- `reading.html`：拾光 AI 阅读助手案例
- `walking.html`：慢游城市漫步案例
- `planning.html`：一页行动规划案例
- `notes.html`：探索笔记列表
- `note-validation.html`：产品验证方法文章
- `about.html`：关于我与联系说明
- `assets/site.css`、`assets/site.js`：共享样式与交互
- `personal-site.zip`：可直接上传的完整网站包

## 本地预览

在仓库根目录运行 `python -m http.server 8000`，访问 http://localhost:8000 。无需安装依赖或构建。

## 腾讯云 EdgeOne 部署

可以选择“导入 Git 仓库”，选择本仓库和 `main` 分支。使用静态站点或 Other 配置，无需构建命令；网站目录为仓库根目录（`.`）。具体字段以控制台当前界面为准。

也可以选择“直接上传”，上传 `personal-site.zip`，或解压后上传全部网站文件。请保持 `index.html` 位于部署目录根部，并保留 `assets` 文件夹。

## 自定义域名

在托管平台中添加已购买的域名，然后按该平台实际提供的 DNS 记录配置解析。仓库未放置 `CNAME` 文件，以免未经配置影响其他平台。

## 演示边界

交互使用预设示例，不调用 AI、不保存输入。邮箱为占位信息。当前 `robots.txt` 和 HTML 设置阻止搜索收录；替换为真实个人资料后再调整。支持减少动态效果设置。已检查页面链接、脚本和关键交互，尚未进行实际浏览器视觉验收。
