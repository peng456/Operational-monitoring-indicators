# Operational-monitoring-indicators
朋友询问业内运维监控指标。问大神也没有给什么，有效的信息。然后去谷歌了。在此做些笔记。


运维指标


告警事件数量
平均解决时间（ MTTR ）
平均响应时间（ MTTA ）

http://blog.oneapm.com/apm-tech/289.html

https://juejin.im/entry/5b712e8ff265da2830382588
了20多个监控系统
￼
￼

https://dbaplus.cn/news-134-1490-1.html
1、硬件监控

￼
2、系统监控


3、应用监控
应用服务监控也是监控体系中比较重要的内容，例如： 
LVS、HAProxy、Docker、Nginx、PHP、Memcached、Redis、MySQL、RabbitMQ等，相关的服务都需要使用zabbix监控起来。

4、网络监控
Smokeping 是rrdtool的作者Tobi Oetiker的作品，是用Perl写的，主要是监视网络性能，www服务器性能，DNS查询性能等，使用rrdtool绘图，而且支持分布式，直接从多个agent进行数据的汇总。

5、流量分析

但是，数据始终是在对方手中，个性化定制不方便，于是Google出一个叫Piwik的开源分析工具。

6、日志监控
我们将这三个组合起来的技术称之为ELK Stack，所以说ELK Stack指的是Elasticsearch、Logstash、Kibana技术栈的结合。


7、安全监控

8、API监控
监控API接口GET、POST、PUT、DELETE、HEAD、OPTIONS的请求。可用性、正确性、响应时间为三大重性能指标。

9、性能监控
全面监控网页性能，DNS响应时间、HTTP建立连接时间、页面性能指数、响应时间、可用率、元素大小等。Zabbix提供URL监控：Zabbix Web 监控。


10、业务监控

没有业务指标监控的监控平台，不是一个完善的监控平台，通常在我们的监控系统中，必须将我们重要的业务指标进行监控，并设置阈值进行告警通知。比如电商行业：
 
每分钟产生多少订单、每分钟注册多少用户、每天有多少活跃用户、每天有多少推广活动、推广活动引入多少用户、推广活动引入多少流量、推广活动引入多少利润等，重要指标都可以加入Zabbix上，然后通过Screen展示。 



http://p.primeton.com/articles/59030eeda6f2a40690f03634

https://support-intl.huaweicloud.com/zh-cn/usermanual-aom/aom_02_0017.html





