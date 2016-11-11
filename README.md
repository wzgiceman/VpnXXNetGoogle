# VpnXXNetGoogle
翻墙遇到google

##背景

  一直使用的是天行的翻墙浏览器（chrome内核）默默的帮助我在天朝使用google；但是突然今天早上我来到公司不好用了，心中···················（各种修改都没法复原看来是被墙了）对我来说没有google简直就是要了我的命（别和我说baidu）

  放弃了，同学很久以前给了我一个收费的vpn云梯，好用；但是为啥要全局代理，能翻墙了，但是访问国内网站为啥那么慢（死慢死慢的）；

  又放弃了，手动切换太麻烦了，有木有方法和我之前的天行一样可以自动切换代理，设置代理地址等等呢*，总要是免费-于是研究了他的内核，其实是基于goagent的；那就简单了，自己搞一个不就行了！

  本篇和技术无关，只是自己探索的记录！

##抱怨

本来想放在CSDN博客里面让更多的人使用，但是还是太年轻了，第二天就被强制删除了，天朝你懂的！

##结果
是的，成功了！windows和mac都可以使用，亲测可以用！

![这里写图片描述](https://github.com/wzgiceman/VpnXXNetGoogle/blob/master/img/20161109162603583.png)

##准备

####1.[下载chrome浏览器](http://rj.baidu.com/soft/detail/14744.html)
####2.[下载xxnet插件](http://download.csdn.net/detail/u014610664/9677919)

##安装：

###1.下载完毕后解压缩文件夹，运行文件夹中start.vbs文件

![](https://github.com/wzgiceman/VpnXXNetGoogle/blob/master/img/1.png)

###2.如果弹出管理员权限请求（用户账户控制），请允许

![](https://github.com/wzgiceman/VpnXXNetGoogle/blob/master/img/2.png)

###3首次运行可能会弹出防火墙警告，请允许访问

![](https://github.com/wzgiceman/VpnXXNetGoogle/blob/master/img/3.png)

###4.启动XX-Net后，右下角会出现托盘图标。右键单击托盘图标，点击“全局PAC智能代理”即可。

![](https://github.com/wzgiceman/VpnXXNetGoogle/blob/master/img/4.png)

###5打开XX-Net/SwitchyOmega文件夹；打开浏览器的扩展程序页面 chrome://extensions 。把SwitchyOmega.crx文件拖放到浏览器扩展程序页面安装。


###6.跳过跳过教程 ，导入bak文件

![](https://github.com/wzgiceman/VpnXXNetGoogle/blob/master/img/5.png)
文件地址
![](https://github.com/wzgiceman/VpnXXNetGoogle/blob/master/img/6.png)

###7.点击情景模式中的 XX-Net自动切换 ,跳过教程

![](https://github.com/wzgiceman/VpnXXNetGoogle/blob/master/img/7.png)

###8.把XX-Net切换为“取消全局代理”，就可以畅游网络了

![](https://github.com/wzgiceman/VpnXXNetGoogle/blob/master/img/8.png)