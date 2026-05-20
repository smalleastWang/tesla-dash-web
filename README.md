# T-Dash GitHub Pages 站点

这个目录是 T-Dash 的静态介绍网站，可以直接用于 GitHub Pages。

## 本地预览

直接打开 `docs/index.html` 即可预览。也可以在仓库根目录运行：

```bash
python3 -m http.server 8080 -d docs
```

然后访问 `http://localhost:8080`。

## GitHub Pages 部署

1. 把 `docs/` 提交并推送到 GitHub。
2. 打开仓库的 `Settings`。
3. 进入 `Pages`。
4. `Build and deployment` 选择 `Deploy from a branch`。
5. `Branch` 选择 `main`，目录选择 `/docs`。
6. 保存后等待 GitHub Pages 构建完成。

下载按钮现在指向仓库的最新 Release：

```text
https://github.com/smalleastWang/tesla_dash/releases/latest
```

以后发布 APK、IPA 或安装说明时，只需要在 GitHub Releases 里上传资源，页面链接不用改。
