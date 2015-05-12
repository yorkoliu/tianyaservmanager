## 一、开发包 ##
### Client ###
  * python 2.5 +
  * wxpython2.8+
  * rpyc3.0+
  * psyco 1.6+
  * MySQLdb
  * ConfigParser
  * pywin32 for py2.5 (windows only)

### Server ###
  * func
  * certmaster
  * cfengine
  * mysql5.0+
  * rpyc3.0+

### 二、支持平台 ###
> Windows xp/2000/2003
> Linux2.6+
> MacOS

### 三、角色分配 ###
  * 客户端
  * 服务器端

### 四、功能特点 ###
> 跨平台、分级管理、实时监控、及时报警、远程操作、可扩展性、在线升级、安全可靠

### 五、系统架构图 ###
> <img src='http://blog.liuts.com/attachment/201003/1268104499_29299260.png' width='600'></li></ul>

<h3>六、功能截图 ###
  * 客户端登录界面
> > <img src='http://blog.liuts.com/attachment/201003/1268044817_59234a47.png'>
</li></ul><ul><li>客户端主界面<br>
<blockquote><img src='http://blog.liuts.com/attachment/201003/1268044817_2057fb5c.png' width='600'>
<br>
更多截图：<a href='http://blog.liuts.com/post/175/'><a href='http://blog.liuts.com/post/175/'>http://blog.liuts.com/post/175/</a></a></blockquote></li></ul>

<h3>七、服务器端Demo</h3>
<blockquote><a href='http://blog.liuts.com/post/183/'><a href='http://blog.liuts.com/post/183/'>http://blog.liuts.com/post/183/</a></a></blockquote>

<h3>八、模块编写</h3>
<blockquote>XRC（XML Resource）的设计来源于wxWidgets，它的想法很简单，就是将界面设计的工作从程序中独立出来。具体的做法是，创建单独的XML文件，负责 界面设计，程序运行的时候载入，生成界面。这样做的好处是显而易见的。首先，将繁琐的外观设计代码从程序中去掉，程序更清晰易读。其次，XRC文件独立于 程序，程序运行时才调用，因此可以随意更换外观。这种思想并不是wxWidgets的原创，MFC中的RC已经有了，类似的还有HTML和CSS的关系。 wxPython从wxWidgets继承而来，当然也保留了XRC(介绍来源于互联网)。<br>
<br>更多<a href='http://wiki.wxwidgets.org/Using_XML_Resources_with_XRC'><a href='http://wiki.wxwidgets.org/Using_XML_Resources_with_XRC'>http://wiki.wxwidgets.org/Using_XML_Resources_with_XRC</a></a></blockquote>

<h3>九、目录结构</h3>
<blockquote>/VAR/SOFT/SERVMANAGER<br>
├─data 存放服务器分类及一般信息(XML格式)<br>
├─img 系统图片资源<br>
├─Module 系统模块UI资源<br>
├─numbers 系统帐号pem密钥文件,默认只有root.pem。<br>
├─sql 系统表结构<br>
└─tmp 系统临时目录(XML格式)<br></blockquote>

<h3>十、初始化系统</h3>
<blockquote>修改config.py，配置服务器主机、帐号、密码及数据库。<br>
默认帐号：root<br>
默认密码：123456<br>
运行文件ServManager.py即可。<br></blockquote>

<h3>十一、声明</h3>
<blockquote>由于平台目前只在公司内部使用，因些会存在很多不完善的地方，大家在使用过程当中出现问题本人将不负任何责任，软件只供学习与交流用，同时禁止用于任何商业用途。</blockquote>

BLOG：<a href='http://blog.liuts.com'><a href='http://blog.liuts.com'>http://blog.liuts.com</a></a><br>
微博：<a href='http://t.qq.com/yorkoliu'><a href='http://t.qq.com/yorkoliu'>http://t.qq.com/yorkoliu</a></a><br>
交流QQ群：158926355