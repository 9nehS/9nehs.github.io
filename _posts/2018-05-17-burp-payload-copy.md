---
layout: post
title: 【搬运】Payload复制（Copy other payload）
categories: Burp
---

Payload复制（Copy other payload）——这种类型的Payload是将其他位置的参数复制到Payload位置上，作为新的Payload值，通常适用于多个参数的请求消息中，它的使用场景可能是： 1.两个不同的参数需要使用相同的值，比如说，用户注册时，密码设置会输入两遍，其值也完全一样，可以使用此Payload类型。 2.在一次请求中，一个参数的值是基于另一个参数的值在前端通过脚本来生成的值，可以使用此Payload类型。 它的设置界面和参数比较简单，如下图所示，其中Payload位置的索引值就是指向图中Payload set的值。
<br>
![_config.yml]({{ site.baseurl }}/images/pentest/burp_intruder_payloadcopy.png)
