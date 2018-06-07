# 34miao_web（网站端）
业余时间用Django开发了三四秒网站 http://www.34miao.com （服务器不用了，所以无法访问）。

网站2015年9月上线的，在这里放出源码，一起学习。

### 1、网站描述
* 自己选了平时阅读的一些站点，然后聚合起来，方便自己阅读。
* 信息涵盖从产品、新闻、设计、开发、营销5个方面。
* 尽量只提供链接，阅读的话跳转到原网站，这样不会劫持他们的流量。

### 2、网站开发要点
* Django。网站整体用的Python的Django框架开发的。
* Scrapy。用Scrapy写了几十个爬虫，用于自动抓取内容。（爬虫这里未放出，怕咬着各位）
* 云服务器ECS。买的是阿里的云服务器，大概40+元一个月，CPU 1核，内存 512 MB，带宽 1Mbps，系统是Ubuntu的因为要满足Python程序的配置，web服务器用的Apache没有用Nginx，数据库是MySQL。
* 用了百度统计。

### 3、存在的问题
* 程序方面。在static资源那一块有些可以公用的图片和模板，需要优化。
* 网站后台方面。因为是爬虫在工作，所以后台没有定制，一直是直接在终端管理数据库的，这方面可以优化。

### 4、网站截图
![image](https://github.com/wsb200514/34miao/blob/master/web_1.png)
![image](https://github.com/wsb200514/34miao/blob/master/web_2.png)
![image](https://github.com/wsb200514/34miao/blob/master/web_3.png)
![image](https://github.com/wsb200514/34miao/blob/master/web_4.png)
![image](https://github.com/wsb200514/34miao/blob/master/web_5.png)
