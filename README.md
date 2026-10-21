# 汤米素材助手

淘宝、天猫主图、SKU图、详情图、视频分类采集与批量下载。

[下载最新安装包](https://github.com/qq1395970680-source/tommy-material-helper-updates/releases/latest/download/tommy-material-helper.xpi)

首次安装：Firefox Developer Edition 142以上，在about:config将xpinstall.signatures.required设为false；在about:addons齿轮菜单选择“从文件安装附加组件”，选择下载的XPI。

安装0.3.2或以上版本后，在插件右上角点“检查更新”，发现新版后点“安装更新”，进入HTTPS安装页，再按页面及Firefox提示确认。Firefox原生更新机制也使用本仓库的HTTPS更新清单和SHA-256校验。保持固定扩展ID，更新不清空本地素材记录。

其他电脑首次安装同一个最新XPI并完成上述Firefox配置即可。素材、队列和网站登录保存在各自电脑，不跨电脑同步。

正式版Firefox需要Mozilla签名；当前为未签名开发者版安装包。不要使用about:debugging临时载入作为长期安装方式。

静态WebP自动转同尺寸PNG；SKU图片按原规格名称命名。视频仅支持页面提供的可访问直链。

此仓库只分发插件及更新元数据，不包含账号、浏览器配置或商品采集记录。
