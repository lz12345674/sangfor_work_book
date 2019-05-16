---
description: RHCE考试题目总结
---

# 环境介绍

## 环境介绍

您在考试中的两个系统信息如下： servce30.example.com 是一个主要的服务器 ,desktop30.example.com 主要用作客户端 两个系统的root密码为redhat，系统的IP地址由DHCP提供，您可以视其为正常，也可以按照以下信息重新设置为静 态IP： 

servce30.example.com 172.16.30.130/24 

desktop30.example.com 172.16.30.30/24 

您的系统是DNS域example.com的成员，所在域中的系统都在子网172.16.30.0/24中，所有要求配置的服务都必须能 被example.com中的系统访问 .

Ldap.example.com提供了集中认证的服务域example.com，两个系统server30与desktop30已预先配置成此域的客户 端，此域提供用户账户guest2001, guest2002, guest2003,密码为redhat

 防火墙默认是打开的，您认为合适的时候可以关闭，其他关于防火墙的设置可能在单独的要求中。系统重启要要求 能自动进入合适的多用户级别，而无需人工协助，如果考试用的虚拟机不能启动或者不能正常启动，将被计零分。

 可以使用[http://ldap.example.com/dvd/配置您的YUM仓库](http://ldap.example.com/dvd/配置您的YUM仓库) 您将会注意到一些要求明确不允许被域my133t.org访问，这个域中的系统在172.16.1.0/24的子网中。 

您没有物理机的root密码，普通用户已经自动登录到您的物理机。

