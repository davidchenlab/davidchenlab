---
title: How To Solve Ftp_Put() CanNot Open That File NoSuch File Or Directory
description: "用 FTP 上傳 WordPress 外掛時出現 ftp_put() can't open that file 錯誤？原因是 000webhost 的 Inode 使用量達到 100%，刪除不用的外掛與佈景主題即可解決。"
categories:
  - WordPress
tags:
  - WordPress
  - Website
  - FTP
  - 000webhost
abbrlink: f29c18d3
date: 2021-10-28 15:08:04
---
<!--more-->
這篇介紹How To Solve Ftp_Put() CanNot Open That File NoSuch File Or Directory。

### Reason & Solution
```sh
Reason:用FTP上傳目錄至WordPress的Plugin，上傳到一半會出現Ftp_put(): Can’t Open That File: No Such File Or Directory.

原因是000webhost的Dashboard中的Inode Usage Quota用到100%.

解決方法:刪除用不到的Plugin、佈景主題以及文章…來降低數量
```
