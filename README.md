# T-Dash Web

这是 T-Dash 的公开宣传网站仓库，用于 GitHub Pages 部署。App 主项目保持私有；这个仓库只包含展示页面、截图、演示视频、下载入口和隐私政策。

## 本地预览

在仓库根目录运行：

```bash
python3 -m http.server 8080
```

然后访问 `http://localhost:8080`。

## GitHub Pages 部署

1. 推送当前仓库到 GitHub。
2. 打开仓库 `Settings -> Pages`。
3. `Build and deployment` 选择 `Deploy from a branch`。
4. `Branch` 选择 `main`，目录选择 `/root`。
5. 保存后等待 GitHub Pages 构建完成。

## 下载发布

首页下载按钮指向当前公开展示仓库的最新 Release：

```text
https://github.com/smalleastWang/tesla-dash-web/releases/latest
```

以后发布 App 安装包时，在这个仓库的 GitHub Releases 上传 APK、IPA 或安装说明即可。
