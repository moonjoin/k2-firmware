# k2-firmware
斐讯K2路由器刷机，固件，breed收集整理
***
京东活动买了三台K2，每台刷了不同系统，以下是心得体会：

**第一步：拿到手就立刻刷官改固件**，不用考虑breed之类，直接无脑刷，刷完官改就直接带breed了。

步骤：下载固件，后台页面上传，搞定。

极其方便简单，官改发布地址：http://www.right.com.cn/forum/thread-208753-1-1.html

刷完官改系统，要是你不爱折腾，可以止步于此，官改的性能和功能足够日常使用。
***
要是你会进breed，那就随便刷吧，怎么刷都能救回来。

[进入 Web 刷机模式]：

电脑网络连接设置为自动获取 IP 地址

打开 CMD，运行 ping 192.168.1.1 -t

按住复位键或者WPS键再给路由通电，如果看到路由器的部分或全部LED连闪4次，或 ping 通即表明进入 Web 刷机模式。
***
下面是你可以再选择的第三方固件：（以下几个固件在仓库有备份）

【推荐】改华硕老毛子Padavan固件：http://www.right.com.cn/forum/thread-161324-1-1.html

【不推荐】openwrt固件：https://archive.openwrt.org/snapshots/trunk/ramips/mt7620/ 上面链接页面查找1208/1218下载固件备用。  
刷openwrt教程：https://zhuanlan.zhihu.com/p/28430178

【不用ss的话推荐】高格固件：http://www.gocloud.cn/bbs/forum.php?mod=viewthread&tid=543&extra=page%3D1    
k2刷高恪固件只能先进入breed，再从breed刷到高恪。  
如果本身就自带breed了，可以在刷机工具里选择机型K2，然后选择 从“breed”升级至“高恪（工具自带版本）”  
如果没有breed，工具提供了带r1016版本breed的k2 163 v1.7版本，可以从K2 ，官改刷到这个版本，然后再进breed刷到高恪（也可以自己从网上刷入k2的breed）

【不推荐】潘多拉：http://www.right.com.cn/forum/forum.php?mod=viewthread&tid=214183&highlight=k2%2B%C5%CB%B6%E0%C0%AD

除此之外可以自行搜索老毛子固件、潘多拉固件、华硕AC1200HP固件、高恪固件，lede和openwrt固件。
***
小插曲：一开始我把网线插到wan口了，导致怎么刷机都不成功，很郁闷。后来网线换到lan口，就一下子顺畅了，低级错误，低级错误。
