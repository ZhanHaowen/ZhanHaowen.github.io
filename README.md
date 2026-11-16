# Haowen Zhang · 张皓文

个人学术主页，参考单栏学术主页的布局重新实现，内容来自个人简历与本人补充。

- 网站：https://zhanhaowen.github.io/
- 编辑器：https://zhanhaowen.github.io/editor.html
- 发布源：`main` 分支的仓库根目录，GitHub Pages 自动发布。

## 更新方法

1. 打开 `editor.html`，修改资料、论文状态、链接或头像。
2. 点击“导出网站 HTML”，下载新的 `index.html`。建议同时“导出 JSON”备份。
3. 在本仓库选择 **Add file → Upload files**，上传新的 `index.html` 并提交到 `main`。
4. 等待 Pages 部署完成，刷新公开主页。

编辑器的草稿只保存在当前浏览器。导出文件本身不会更新线上站点；只有向本仓库提交更新后才会发布。

编辑器在联网打开时会从当前 `index.html` 读取资料；同一浏览器已有草稿时优先恢复草稿。换设备请导入自己导出的 JSON 备份。

`profile-backup.json` 是本次发布的资料备份，修改这个备份文件不会自动改变主页。

编辑器恢复旧草稿或导入旧备份时，会移除本人已要求删除的两条匿名在审记录，保留其余资料；日后手动新增的其他论文不受影响。

## 文件说明

- `index.html`：公开主页，照片、样式与交互脚本全部内嵌，不依赖 ChatGPT。
- `editor.html`：本地表单编辑与导出工具。访客即使打开它，也不能向仓库提交更改。
- `.nojekyll`：直接发布静态文件。
- `profile-backup.json`：本次发布的资料备份。

不需要购买域名或云服务器。GitHub Pages 的网络可达性由访问者所在地及运营商线路决定。
