# WebMaster is Magic feed/魔法分享

[English](https://github.com/ShinChven/ShareMoments/blob/master/README.md#a-tool-for-you-to-master-your-web-contents)

[中文](https://github.com/ShinChven/ShareMoments/blob/master/README.md#%E9%AD%94%E6%B3%95%E5%88%86%E4%BA%AB---web%E5%86%85%E5%AE%B9%E5%88%86%E4%BA%AB%E5%8A%A9%E6%89%8B)

## New updates

- ver.1.7.0:
  - Gallery is out, now you can browse all images you downloaded within gallery. All files are in your `picture/ShareMoments/` directory.
  - If you found some image you downloaded previewsly can not be loaded, please remove them in other file manager due to a file name bug. `?` are not allowed in filename, and I made a mistake that I did not replace them in early versions.
  - 新增内置图片浏览器，现在大家可以从app里面直接查看下载过的图片。这些图片都存在了`picture/ShareMoments/` 文件夹中。
  - 如果发现有图片显示不出来，那是由于写了一个bug，没有把`?`号替换掉而直接写到文件名里面。图片文件路径不支持`?`号，因此请从其他的文件管理器中将它们重命名或者删除掉。

## A tool for you to master your web contents

Most contents we enjoy and share each day on internet and mobile are hosted on the web, and they are made up of texts and media files. I developed this app so that we can dig a little bit deeper into the web html and make the most use of them.

## Share a link like a pro

We share links every day, but raw URLs are sometimes hard for people to understand. So normally we'll have to type in some description so that our receivers can understand the URL at first sight without open it.
If you know something about the html, then you'll probably know such things like title, description, cover image and etc. are all there for you to reach.
To help you master the web, WebMaster can parse the title, description and pictures from a web link. Copy them by 1 single touch, you'll get a well composed message to share a link.

## Save your feed across apps

Each app has its own bookmarks, but why can't we just save everything together and search everything we saved in one place?
Save your URLs in WebMaster and make a feed list for yourself. When you need them again, just go back to WebMaster and find them. All URLs you saved in WebMaster will listed in a good looking feed.
By using the Chrome CustomTabs, you can open every link within it's own app.

## Grab images from web

- If you are interested in some images from one web, WebMaster can do batch download and batch forwarding for you.
- If you are interested in some particular images from one web, WebMaster can send it to Google for you to search image by image.

## Share a link via QRCode

Don't bother if you want share a link without adding someone to your contacts. Just show the QR Code.

## 魔法分享 - Web内容分享助手

在我们每天都使用的App和网站中有很多精彩的内容，它们大部分都承载在🌐Web中。很多时候，我们如果只是单单分享一个🔗Web链接，还需要花很长时间向别人说明我们在分享什么内容。于是我制作了这个App，让你能轻松地从Web Link中获取标题、描述和图片，以分享给朋友。

## 特色功能

- 💬 微信链接卡片：如果你是微信的用户，它能帮你生成一个优雅的分享卡片，让你分享的链接能马上抓住别人的眼球；
- 🖼️ 批量图片分享：如果你喜欢Web中的图片，你可以批量分享给你的朋友，当然你也可以批量下载它们；
- 🔍 图片逆向搜索：如果你喜欢Web中的一张图片，你还可以以图搜索，做逆向图片查找（由Google提供）；
- ⭐ 智能链接收藏夹：你所分享过的链接会存在你的手机中，你随时可以重新浏览、查找和分享；

## What‘s new on 1.6.x 🎉

- 媒体文件浏览器：可查看Web页面上的静态媒体文件地址，可打开浏览或者复制地址；
- 本地数据备份与恢复；
- Chrome Custom Tabs；
- 新的Feed视图；

## Web内容解析规则

- 优先读取Web页面中的OpenGraph标识以获取标题、介绍和封面图片；
- 再在页面查找图片；
- 针对Twitter、Instagram、Deviant、Bilibili这些热门的站点，编写了专门的解析方案，让你能更准确地的获取相关内容；

## 下载

- [Google Play Store](https://play.google.com/store/apps/details?id=net.atlassc.shinchven.sharemoments)（推荐，可加入beta频道，抢先试用新功能）
- [酷安](https://www.coolapk.com/apk/net.atlassc.shinchven.sharemoments)

## 联系我

- Twitter [@ShinChven](https://twitter.com/ShinChven)可以找到我；

## 内容声明

- 本应用不提供任何内容，仅为用户提供链接分享、收藏和网页内容感知功能，不对用户操作的内容负责。
- 所有用户在使用本应用分享网页链接时，应当遵守当地法律法规，不得散布危害社会安定和国家统一的言论。

## Privacy Policy

### camera

- This app uses camera to scan QR CODE.

### storage

- This app uses storage to cache and download images.

### analytics

- This app will anonymously report user's usage actions to let developer know how and how many times users are using its function. user's personal information and content will not be recorded.
- App 会使用Firebase Analytics 匿名记录用户的操作习惯，以帮助开发者更好的了解用户是否使用或者了解App里面的各种功能以及使用频率，但不会上传任何用户的个人信息和用户访问过的内容（链接、图片等）。


## OPEN SOURCE LICENSE

[OPEN SOURCE CREDITS](OpenSourceCredits.md)
