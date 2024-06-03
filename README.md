## 使用jsDelivr加载静态资源
jsDelivr是一个免费的开源CDN服务，它可以提供GitHub仓库中静态文件的CDN支持。

获取GitHub文件的URL路径。这通常是：
`https://github.com/<username>/<repository>/blob/main/path/to/your/font.woff2`

其中 `<username>`  是你的GitHub用户名，`<repository>` 是你的仓库名，`path/to/your/font.woff2` 是文件在仓库中的路径。

将GitHub链接转换为jsDelivr链接。jsDelivr为GitHub项目提供了一个特别的URL格式，用于CDN加速。将上述URL按以下格式改写：

`https://cdn.jsdelivr.net/gh/<username>/<repository>/path/to/your/font.woff2`

