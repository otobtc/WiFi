# 小米刷机教程
前期准备  <br/>
1.数据备份：备份手机内部存贮数据，SD卡的可以不备份。<br/>
  钛备份：可备份应用程序和数据要root。 <br/>
  MIUI备份：备份完成后，把备份后的文件夹都移动到电脑或者OTG U盘。<br/>
2.退出账号：开刷前务必请退出小米账号/谷歌账号后再刷机，否则卡开机验证。同时关闭密码解锁、指纹解锁。 <br/>
3.解BL锁：http://www.miui.com/unlock/index.html  
  前期准备：手机上绑定小米账号-MIUI版本按5下-更多设置-开发者选项-设备解锁-绑定账号和设备（挂7天，168小时） <br/>
4.下载官方线刷或卡刷包  <br/>
波兰版：https://miuipolska.pl/download/  <br/>
国内版：https://www.miui.com/download.html  <br/>
波兰开发版：https://xiaomi.eu/community/  (推荐)<br/>
国际/印度/欧盟/俄罗斯版：http://c.mi.com/miuidownload/index  (推荐国际和欧盟)<br/>
国内线刷版：http://www.miui.com/shuaji-393.html  里面的教程可以下载线刷工具<br/>
补充：正常刷机采用的是卡刷，线刷主要是卡刷出问题变砖后来救砖的！ <br/> 
  即：线刷包（以防意外救砖用）、卡刷包（即你要刷的ROM）<br/>
5.去各自品牌的论坛寻找自己手机型号对应的第三方REC（或官方TWRP、橙狐、SHRP） <br/>
例如：<br/>
     TWRP：https://twrp.me/Devices/  <br/>
     SHRP：https://sourceforge.net/projects/shrp/files/  <br/>
     橙狐OrangeFox：https://orangefox.download/zh-CN  <br/>
     微博@wzsx150：https://pan.hchl.top/#/s/oe4T4 密码：wzsx150 <br/>
6.准备ROOT工具（Magisk或SuperSU卡刷包以及它们的卸载包） <br/>
7.基础知识：https://band.us/band/72801035/post/2892  <br/>
㊟ 版本升級可不雙清, 直刷即可;在卡刷Magisk. <br/>
㊟ 換版本時  (開發版⇌穩定版 或 國際版⇌陸版  互換), 建議三清刷入. <br/>
刷twrp(重啟至recovery)——高級選項>取消強制加密（没有的话可以自动解密了） <br/>
>選擇"格式化data分區" , 輸入" yes" >請再重啟至TWRP.  <br/>
清除>高級清除選項> 作 "三清" 動作(勾選Dalvik/ART Cache和Data、Cache)  <br/>
卡刷卡刷包和magisk  <br/>
  如：电音量下”+“开机键”，进入FASTBOOT（米兔）模式  <br/>
      音量上”+“开机键”，进入RECOVERY刷机模式  <br/>
      双清，三清，四清等  <br/>
W大的包就是普通的国内开发版部分精简以及可选择安装，没有什么特别。不适合我！ <br/>
⓵去除dm校验可以防止卡屏和防止twrp被官方rec覆盖.  <br/>
⓶取消强制加密（也就是FBE加密），然后格式化data就可以永久解密 ；  <br/>
 如果你单纯执行取消强制加密不格式化data，重启后会卡米。(官方系统默认是加密data分区的内置sdcard目录的) 密码：root<br/>
8.卡开机验证的解决办法：通过另一部手机或电脑分享VPN热点来实现登录。  <br/>
9.root--在卡刷刷机包后顺便卡刷magisk。开机后发现root并没有成功，  <br/>
10.在卡刷包里提取boot.img,然后安装，选择boot.img,然后重启rec,安装右下角刷入镜像，
   选boot，刷入magisk_patched.img镜像。然后按正常操作刷入magisk.zip 。  <br/>
11.安装XP  <br/>

<br/>
<br/>
<br/>
谷歌全家桶下载方法：在apkmirror用下面关键词搜索 <br/>

com.android.vending（谷歌Play商店） 1 <br/>
com.google.android.gms（谷歌Play服务）2  <br/>
com.google.android.gsf（谷歌服务框架） 3 <br/>
com.google.android.gsf.login（谷歌帐号管理程序）4 <br/>
com.google.android.partnersetup（谷歌合作伙伴设置）  <br/>
com.google.android.packageinstaller（软件包安装程序）  <br/>
com.google.android.apps.nexuslauncher（Pixel Launcher）  <br/>
com.google.android.gm.exchange（exchange服务）  <br/>
com.google.android.instantapps.supervisor  <br/>
<br/>
<br/>
电脑和安卓软件下载蓝奏云盘：<br/>
https://www.lanzous.com/b474214  密码：qingqiu  <br/>
http://pan.lanzou.com/u/%E5%BD%AA%E7%85%8Cqq1846055318 『BhVip』<br/>
https://www.lanzous.com/b202139  诗仙阁软件合集  <br/>
https://www.lanzous.com/u/adminqizhu  新世界软件合集  <br/>
https://www.lanzous.com/u/ha16888?t  ha16888    <br/>
https://www.lanzous.com/b244238  jshgou        <br/>
https://www.lanzous.com/u/chudali  chudali     <br/>
https://www.lanzous.com/b818538               <br/>
https://www.lanzous.com/b609827  蓝色飞扬   <br/>


# 公益订阅节点
miles： https://jiang.netlify.com  （V2ray）<br/>
ssrsub：https://raw.githubusercontent.com/ssrsub/ssr/master/v2ray  （V2ray）<br/>
ssrsub：https://raw.githubusercontent.com/ssrsub/ssr/master/ss-sub  （SS）<br/>
ssrsub：https://raw.githubusercontent.com/ssrsub/ssr/master/ssrsub  （SSR）<br/>
ssrsub：https://raw.githubusercontent.com/ssrsub/ssr/master/Clash.yml  （Clash）<br/>
ssrsub：https://raw.githubusercontent.com/ssrsub/ssr/master/Surge.conf  （Surge）<br/>
kitsunebi：https://raw.githubusercontent.com/eycorsican/rule-sets/master/kitsunebi_sub  （V2ray）要用kitsunebi专属App使用<br/>




# 路由器相关知识
斐讯K2
<br/>
斐讯K2P（A1和A2版） MTK版的k2p速度高于博通腾达ac9和博通斐讯k2p 现在能买到的K2p都已经是博通板了
K2P 分a1 a2 b1版本，a1最贵，a2和a1同架构缩水，a1、a2能刷的固件最多，b1架构都改了刷机可选固件少所以最便宜。
3个版本价格都不一样。a2这个价格没啥问题    100--150
<br/>
友华WR1200JS  100左右 购买渠道淘宝、二手市场
<br/>
腾达ac9  210左右 购买渠道淘宝、京东  注意要买博通芯而不是螃蟹芯 没看见屏蔽罩的肯定是螃蟹芯片 200
<br/>
腾达ac10 160左右 螃蟹芯
<br/>
水星D12  85
<br/>
水星MAC1200R
<br/>
CPU：博通 联发科
<br/>
价格：150以下

<br/>
People should not be afraid of their governments.Governments should be afraid of their people.人民不应该害怕他的政府，政府应该害怕它的人民！
<br/>


</p><div class='clear'></div><p class='st3'><span>1.aroma package<br/>值得一提，它是Open GApps 最近放出的一种版本，该版本具备图形化安装界面，在刷入过程中可自行选择需要安装的 GApps 组件，十分好用。（经过个人测试，只适用于在可以触摸操作的recovery下刷入，一般不建议使用。）<br/>2.stock package完整包<br/>完整包里面包含了Nexus手机里所有的谷歌服务,也就是谷歌的核心服务，主要都有以下Google Play应用：<br/>Google Gallery图库<br/>Live Wallpaper动态壁纸<br/>Google Drive云端硬盘<br/>Google Earth谷歌地球<br/>Google Play Books图书<br/>Google Play Games游戏<br/>Google Play Video电影<br/>Google Play Music音乐<br/>Google Play Newsstand新闻与天气<br/>Google Play services服务<br/>Google Search搜索<br/>Gmail邮箱<br/>Maps地图<br/>Google+<br/>TalkBack<br/>YouTube<br/>Quickoffice<br/>Google Keep<br/>语音搜索<br/>街景服务<br/>…………<br/>这个版本会用 Chrome 、 Google Now Launcher 、 Google Keybord 等 Google 应用替换掉原固件或ROM 中那些基于 AOSP 代码的相关应用。原固件或ROM越接近原生Android，替换掉的应用及功能就越多。如：<br/>Chrome(替代自带的浏览器) <br/>Calendar(替代自带的日历)<br/>Camera(替代自带的相机)<br/>Google Keyboard(替代自带的输入法 )<br/>Google Now 即时桌面(替代自带的UI桌面) <br/>Google Text-to-Speech (替代自带的Pico TTS引擎) <br/>…………<br/>3.full modular package全模块包<br/>与 stock完整版所包含的内容相同，但是不包含：Google 相机, Google 输入法, Google Gallery², 并且不会替换掉自带的启动器，输入法，浏览器，短信应用，或者Pico TTS服务。此外全模块包还包含Google Bookmarks 同步服务。如果你想体验Nexus手机的谷歌服务，并且想继续使用原手机自带的启动器等服务，全模块包是最好的选择。<br/>4.mini package轻量包<br/>包含了完整的 Google 服务框架和主流 Google 应用，去掉了 Google Docs 等文档处理应用，适合不太经常使用谷歌应用的人。轻量模块包包含有：谷歌核心服务, Google Bookmarks 同步服务, 以及以下的Google Play应用：<br/>Google 日历(替换自带的日历) <br/>Google Now 启动器<br/>Google Play services服务<br/>Google 搜索<br/>Google Text-to-Speech<br/>Gmail<br/>Google+<br/>YouTube<br/>Hangouts<br/>谷歌地图<br/>谷歌地图街景服务<br/>5.micro package迷你模块包<br/>这个包是专为喜欢简约的用户准备的。它包含有：谷歌核心服务, Google Bookmarks 同步服务, 以及以下的Google Play应用：<br/>Google 日历(替换自带的日历) <br/>Google Now 启动器<br/>Google Play services服务<br/>Google 搜索<br/>Google Text-to-Speech<br/>Gmail<br/>6.nano package超小模块包<br/>虽说是超小，但也包含了完整的 Google 服务框架，并不包含多余的 Google 应用。<br/>这个包适合那些不想占用太大内存，但是又想体验到原生的谷歌搜索服务的机友。超小模块包包含有：谷歌核心服务, Google Bookmarks 同步服务， Google 日历同步服务, 以及以下的Google Play应用：<br/>Google Play services服务<br/>Google 搜索<br/>7.pico modular package核心模块包<br/>包含了最基础的 Google 服务框架，体积最小，适合仅仅想给系统装个Play商店的同学，其他的Google play应用可以自己下载。核心包包含有：谷歌核心服务, Google Bookmarks 同步服务, Google 日历同步服务, 以及Google Play services服务应用。（但是一些依赖完整 Google 框架的应用，如 Google Camera将无法运行。）<br/>（我只个搬运工）<br/></span></p>



<blockquote><p>
  本文章用于「氡·OpenGApps」 中相应 GApps 不同版本的区分。<br />
  This archive is used for 「Rn·OpenGApps」to distinguish between different versions of OpenGApps.
</p></blockquote>
<h1>aroma</h1>
<p>与 <code>super</code> 版所包含的 GApps 相同，但是在 Recovery 中引入了图形化界面，可以自行选择安装哪些 GApps。<br />
The same as <code>super</code> version, but has GUI in recovery，you can choose what you want.<br />

<h1>super</h1>
<p>包含了所有 GApps ，像韩语日语中文拼音中文注音输入法等。（请注意：如果你是用的是基于原生的 ROM ，本版本会替换相机，通讯录等等所有有关应用）<br />
Include all of GApps, just like Google Korean(Japanese/Chinese/Zhuyin) Input. (NOTICE: If you use the ROM based on AOSP, this one will replace CAMERA, CONTACT app and so on.)<br />

<h1>stock</h1>
<p>类似于 Google Pixel 出厂内置的 GApps ，相比 <code>super</code> 版少了其他语种的输入法以及 Google 地球等。（请注意：如果你是用的是基于原生的 ROM ，本版本会替换相机，通讯录等等所有有关应用）<br />
This one has the GApps that Google Pixel includes. Compared <code>super</code> version, this one does not have other languages` input software and Google Earth and so on.(NOTICE: If you use the ROM based on AOSP, this one will replace CAMERA, CONTACT app and so on.)<br />

<h1>full</h1>
<p>与 <code>stock</code> 版所包含的内容相同，但此版本不会替换手机原本的应用。<br />
The same as <code>stock</code> version, but it will not replace the apps of your phone.<br />

<h1>mini</h1>
<p>包含基础的 Google 服务框架，以及一些影响力较大的 GApps ，相比 <code>full</code> 版去掉了 Docs 等应用。<br />
Include the basic Google Service Framework and other GApps which are famous. Compared <code>full</code> version, it does not have Docs and so on.<br />

<h1>micro</h1>
<p>包含基础的 Google 服务框架和 Gmail 等常见 GApps。<br />
Include the basic Google Service Framework and some common GApps like Gmail.<br />

<h1>nano</h1>
<p>包含基础的 Google 服务框架，但不会有其他 不必要的 GApps。<br />
Include the basic Google Service Framework, but does not have other GApps.<br />

<h1>pico</h1>
<p>包含最迷你的 Google 服务框架，但由于框架并非完整，部分 GApps可能无法运行。<br />
Include the MINI Google Service Framework. Because the framework is not complete, maybe some GApps will not work.<br />


插线板：突破TC0601、小米插线板、公牛 GN-B303U 插线板、公牛GN-B6330
插线板品牌：小米&青米&突破-爱国者（一伙的）、公牛（不太推荐，主要原因是为所欲为）、飞利浦&得力（贴牌的）<br />
浏览器：Chrome|Brave|Via|<br />




FongMi影视、TVBox、猫影视配置文件

1. tvbox配置：

（1）0707.json  Fengmi影视多线配置接口,仅适用于Fengmi影视；

（2）0821.json  大而全的配置，在饭太硬配置的基础上添加了若干优质点播源、直播线路和解析；

（3）0822.json  极简配置，OK大佬的jar，还包括几条路飞、俊于的源。

（4）0825.json  小而精的配置，jar包来源于Panda Groove的go包，其中泥巴、星星等，需要替换成自己的代理url；

（5）0826.json  完全来源于饭太硬的jar包和配置；

（6）0827.json  jar包和配置来源于fongmi；

（7）js.json  jar包来源于Panda Groove的go包，资源来源于道长drpy(js)仓库；

（8）XBPQ.json  XBPQ源，jar包和配置来源于小米小爆脾气；

（9）XYQ.json  XYQ源，jar包和配置来源于香雅情；

（10）/cat/js/config_open.json  cat源，资源来源于网络各路大佬。配合猫影视可直接食用。

2. APP推荐:

（1）FongMi版本  项目地址：https://github.com/FongMi/TV 支持直播多线路、自动换源、直播倍速，手机投屏；

（2）新版猫影视   项目地址：https://github.com/catvod/CatVodOpen 界面简洁，支持多平台。

3. TVBox各路大佬配置（排名不分先后）：

（1）okjack：https://999740.xyz/https://raw.githubusercontent.com/okcaptain/okjar/rm/ok.jsonp

（2）Fongmi：https://999740.xyz/https://raw.githubusercontent.com/gaotianliuyun/fongmi/main/json/config.json

（3）俊于：http://home.jundie.top:81/top98.json

（4）饭太硬：http://饭太硬.top/tv

（5）肥猫：http://我不是.肥猫.love:63/接口禁止贩卖

（6）霜辉月明py：https://999740.xyz/raw.githubusercontent.com/lm317379829/PyramidStore/pyramid/py.json

（7）小米小爆脾气：http://xhww.fun:63/小米/DEMO.json

（8）小雅：http://drpy.site/js1

（9）菜妮丝：https://tvbox.cainisi.cf

（10）运输车：https://github.moeyy.xyz/https://raw.githubusercontent.com/52670576/tvbox/main/ysc.json

（11）多多：https://yydsys.top/duo

（12）南风：https://agit.ai/Yoursmile7/TVBox/raw/branch/master/XC.json

（13）神器：https://神器每日推送.tk/pz.json

（14）巧技：http://pandown.pro/tvbox/tvbox.json

（15）那里花开：http://hz752.love:63/tk.json

（16）吾爱有三：http://52bsj.vip:98/0805

（17）潇洒：https://download.kstore.space/download/2863/01.txt

（18）佰欣园：https://999740.xyz/https://raw.githubusercontent.com/chengxueli818913/maoTV/main/44.txt

（19）胖虎：https://notabug.org/imbig66/tv-spider-man/raw/master/配置/0801.json

（20）云星日记：http://itvbox.cc/tvbox/云星日记/1.m3u8

（21）Yoursmile7：https://agit.ai/Yoursmile7/TVBox/raw/branch/master/XC.json

（22）Ray：https://999740.xyz/https://raw.githubusercontent.com/dxawi/0/main/0.json

（23）甜蜜：https://kebedd69.github.io/TVbox-interface/py甜蜜.json

（24）月光宝盒：https://jihulab.com/ygbh1/box/-/raw/main/月光宝盒

（25）好人：https://xhdwc.tk/0

（26）唐三：https://gh.t4tv.hz.cz/newtang.bmp

4. 随机轮换壁纸：

（1）https://jianbian.chuqiuyu.workers.dev 自制极简渐变壁纸

（2）http://www.kf666888.cn/api/tvbox/img

（3）https://picsum.photos/1280/720/?blur=10

（4）http://刚刚.live/图 

（5）http://饭.eu.org/深色壁纸/api.php,

（6）https://www.dmoe.cc/random.php

（7）https://api.btstu.cn/sjbz/zsy.php

（8）https://api.btstu.cn/sjbz/?lx=dongman

（9）http://api.btstu.cn/sjbz/?lx=meizi

（10）http://api.btstu.cn/sjbz/?lx=suiji

（11）https://pictures.catvod.eu.org/

（12）https://bing.img.run/rand.php

