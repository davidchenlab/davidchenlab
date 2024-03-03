---
title: 分享多個 GMAIL找出 信件指令
categories:
  - GMAIL
tags:
  - GMAIL
abbrlink: b1468c1b
date: 2024-03-03 08:51:44
---
分享多個 GMAIL找出 信件指令
-----------------------------------------------------------------------------------------------
<!--more-->
分享多個 GMAIL找出 信件指令

Instructions:
-----------------------------------------------------------------------------------------------
1.找出未讀信件
label:unread

2.找出重要信件
is:important

3.找出未讀且重要信件
is:important label:unread

4.找出特定年份以前信件 (找出2023年以前信件，不包含2023年)
older:2023

5.找出特定日期信件
before:yyyy/mm/dd
example : before:2024/01/01

6.找出特定檔案容量信件 (語法中的「xx」指的是檔案大小，由於 Gmail 的附件檔案容量上限是 25MB，所以 1MB~25MB 都可以輸入。)
size:xxmb
larger:xxMB
smaller:xxMB

7.找出特定寄信者或收信者信件
from:(xxx@xxx.com)
to:(yyy@yyy.com)

example : from:google

8.刪除促銷內容
點選促銷內容視窗 -> 左上全選 -> 中間選取促銷內容全部 -> 刪除 -> 會慢慢刪除需等待