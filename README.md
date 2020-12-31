基于netty4.0实现的shadowsocks服务器端
====

使用
---
1.maven打包，生成shadowsocks-netty-server-0.2.0-alpha-bin.zip包<br>
2.解压zip包，conf/config.xml进行相关配置<br>
3.执行shell文件夹中的bat/sh文件启动服务<br>


huangzf 2020.12.11
存在bug：（还没有能力修复， 留个坑）
内存会一直飙升，大概一周左右升到1.5g


可参照：
Netty堆外内存泄露排查盛宴
https://tech.meituan.com/2018/10/18/netty-direct-memory-screening.html


--有空参照这篇文章再看看
Netty堆外内存泄漏排查，这一篇全讲清楚了
https://juejin.cn/post/6844904036672471048


