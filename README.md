# thingsboardTutorial
###### Tutorial of thingsboard，thingsboard 框架教程

###### 本教程的目标是演示最流行的ThingsBoard特性的基本用法。
###### 您将学习如何：
- 在系统中提供资产和设备；
- 定义资产和设备之间的关系；
- 将数据从设备推送到ThingsBoard；
- 构建实时终端用户仪表板；
- 定义阈值和触发警报；
- 通过电子邮件推动有关新警报的通知。
本教程基于一个流行的设施监控用例。
我们将展示如何监测建筑物不同部位的温度，在温度超过一定阈值时提高警报器，并将收集到的数据和警报可视化。

##### 参考下载：
- [下载源码](https://github.com/thingsboard/thingsboard/releases)
- [源码导入教程-相继上一篇，thingsboard的二次开发环境配置和简单的logo替换](https://blog.csdn.net/liuli283/article/details/93466756)
- [下载IDEA社区版](https://download.jetbrains.8686c.com/idea/ideaIC-2019.3.exe)
- [下载postgresql11](https://get.enterprisedb.com/postgresql/postgresql-11.1-1-windows-x64.exe)
- [ThingsBoard源码分析 —— 调试环境搭建](https://blog.csdn.net/julyqian/article/details/88081367)
- [下载psadmin](https://ftp.postgresql.org/pub/pgadmin/pgadmin4/v4.16/windows/pgadmin4-4.16-x86.exe)
##### 参考使用
- [编译的坑1](https://www.cnblogs.com/danny-djy/p/9051714.html)
- [源码研究](https://blog.csdn.net/julyqian/article/details/88081367)
- [Win10环境下安装Thingsboard](https://blog.csdn.net/nebulaly/article/details/85219032)
- [mac 下eclipse安装lombok插件](https://blog.csdn.net/kongtong2004/article/details/80054817)
- [ThingsBoard 开发环境搭建](https://blog.csdn.net/curly_d/article/details/89884604)
- [物联网时代-跟着Thingsboard学IOT架构-MQTT设备协议](https://www.cnblogs.com/sanshengshui/p/11237695.html)
- [开源的物联网技术平台thingsboard安装测试及使用步骤](https://blog.csdn.net/weixin_33835103/article/details/92034895)
- [ThingsBoard使用笔记（2）模拟传感器发送MQTT并显示监控图表](https://blog.csdn.net/ieflex/article/details/97149225)
##### 使用问题
- 如果出现/api/widgetType接口404，代码报Requested item wasn't found!是widgetType表为空
可以：This is the link address for livedemo. https://demo.thingsboard.io/, After you sign in, open the widget library, then select one of the widget , then click the export button in the upper right corner to export the widget , and then import it into your widget library
你注册登录https://demo.thingsboard.io/ 后(要能谷歌机器人验证)，打开部件库，然后选这某个部件，然后点击右上角的导出按钮导出部件，然后再导入导你的部件库
- 默认账号：
ThingsBoard 有三种账号，系统管理员、用户管理员和用户
系统管理员：sysadmin@thingsboard.org / sysadmin
用户管理员：tenant@thingsboard.org / tenant
用户：customer@thingsboard.org / customer
