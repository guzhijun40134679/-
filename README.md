# 求职规划安排2 原型2更新仓库

这个仓库只用于发布安装包和版本更新清单。

应用内「版本更新」页面默认读取：

```text
dist/macos/update-manifest.json
```

当前发布文件：

```text
dist/macos/求职规划安排2-原型2-0.1.0.pkg
dist/macos/update-manifest.json
```

发布新版本时，重新运行：

```bash
npm run package:macos
```

然后把新的 `.pkg` 和 `update-manifest.json` 复制到本仓库同一路径并提交。
