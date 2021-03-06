<h1 align=center>RSSBud</h1>

<p align=center>
<a href="https://developer.apple.com/swift"><img src="https://img.shields.io/badge/swift-5.3-fe562e?style=flat-square"></a>
<a href="https://developer.apple.com/ios"><img src="https://img.shields.io/badge/iOS-14%2B-blue?style=flat-square"></a>
<a href="https://github.com/Cay-Zhang/SwiftSpeech/blob/master/LICENSE"><img src="http://img.shields.io/badge/license-MIT-lightgrey.svg?style=flat-square"></a>
</p>

> RSSBud 是一个 [RSSHub](https://github.com/DIYgod/RSSHub) 的辅助 iOS App，和 [RSSHub Radar](https://github.com/DIYgod/RSSHub-Radar) 类似，他可以帮助你快速发现和订阅网站的 RSS。此外，他还支持 RSSHub 的通用参数 (实现过滤、获取全文等功能)。

[Telegram 群](https://t.me/RSSBud_Discussion) | [Telegram 频道](https://t.me/RSSBud)

<p align=center>
<img src="Readme Assets/RSSBud.jpg" align=center width="375">
</p>

## 下载

<a href="https://apps.apple.com/cn/app/rssbud/id1531443645?itsct=apps_box&amp;itscg=30200"><img src="https://tools.applemediaservices.com/api/badges/download-on-the-app-store/black/zh-CN?size=250x83&amp;releaseDate=1605052800&h=3dc9b44d4b825017f8746f19cec2b07f" alt="Download on the App Store" width="200"></a>

<img src="https://tools-qr-production.s3.amazonaws.com/output/apple-toolbox/dace82ddc6942d582d27ad4d2ba31d58/c6e9f5d0-cee7-4523-ac64-ca89de19e8dc.png" width="200">

订阅 [Telegram 频道](https://t.me/RSSBud) 以获取更新信息。

## 功能
- [x] 检测适用于网页 (或 App 内分享) 的 RSSHub 源 (几乎支持所有 RSSHub Radar 的规则)
- [x] 移动端 URL 适配 (自动展开、常见移动子域名适配)
- [x] 读取剪贴板 URL
- [x] 分享菜单插件 (Action Extension)
- [x] 快速订阅到 Reeder, Fiery Feeds, Ego Reader 和系统默认 RSS 阅读器
- [x] 快速订阅到 Tiny Tiny RSS, Miniflux, Fresh RSS, Feedly, Inoreader, Feedbin, The Old Reader, Feeds Pub 网页端
- [x] 自定义通用参数
- [x] 自定义 RSSHub 域名
- [x] 自动更新 RSSHub Radar 规则
- [ ] 检测适用于网站的 RSSHub 源
- [ ] 主动搜寻 RSS 源

## 参与 Beta 测试
加入 [Telegram 群](https://t.me/RSSBud_Discussion) 以获得 Beta 测试详情。

## 自行编译须知
若要使用分享菜单插件 (Action Extension)，请在 iOS 和 Action Extension 这两个 Target 中设置你自己的 App Group 并修改 `RSSBud.appGroupIdentifier`。

## 规则
RSSBud 和 [RSSHub Radar](https://github.com/DIYgod/RSSHub-Radar) 使用同一份 [规则](https://github.com/DIYgod/RSSHub/blob/master/assets/radar-rules.js)，且均支持自动更新。

[为 RSSHub Radar 和 RSSBud 提交新的规则](https://docs.rsshub.app/joinus/#ti-jiao-xin-de-rsshub-radar-gui-ze)

> 请注意，在 `target` 中使用 `document` 的规则并不适用 RSSBud。RSSBud 并不是一个浏览器插件，他只获取并分析网站的 URL。

> 一些网站的移动端和电脑端页面 URL 不同。由于 RSSHub Radar 的规则是适配电脑端的，在你发现 RSSBud 无法识别 RSSHub Radar 可以识别的网站时，可以尝试使用电脑端的 URL 并在 Telegram 向作者反馈。

## 作者
RSSBud 由 cayZ 制作，在 **[MIT 协议](https://choosealicense.com/licenses/mit/)** 下开源。
