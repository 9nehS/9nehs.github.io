---
layout: post
title: 【搬运】windows下类似linux中的grep命令（findstr）
---

<pre>
C:\Users\Administrator>arp -a | findstr 192.168.1.1
接口: 192.168.1.126 --- 0xb
  192.168.1.1           f0-7d-68-5c-8e-e2     动态
  192.168.1.10          50-e5-49-db-9a-76     动态
  192.168.1.117         90-2b-34-03-ae-d2     动态

--也可使用find命令，注意参数加双引号！
C:\Users\Administrator>arp -a | find "192.168.1.1"
接口: 192.168.1.126 --- 0xb
  192.168.1.1           f0-7d-68-5c-8e-e2     动态
  192.168.1.10          50-e5-49-db-9a-76     动态
  192.168.1.117         90-2b-34-03-ae-d2     动态
</pre>
