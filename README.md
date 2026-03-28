# Switch大气层整合包
均来自官方Github源，简洁，稳定，插件齐全<br>
<br>
您若喜欢该整合包，请给我点亮⭐Star<br>
若遇到问题可以提交 [issues](https://github.com/Cirrest/NXmode/issues) 或 酷安 Cirrest 反馈。<br>
[酷安同步更新](http://www.coolapk.com/u/2679393)<br>
![](https://img.shields.io/github/downloads/Cirrest/NXmode/total?style=for-the-badge&labelColor=blue&color=ff69b4)  ![](https://img.shields.io/github/v/release/Cirrest/NXmode?include_prereleases&style=for-the-badge)

<br>

> 因为求稳定所以我更新会比较慢，已进行测试并解决相关bug，稳定使用，到手即用。<br>
默认屏蔽虚拟和真实系统序列号和DNS<br>
自带HB APPSTORE/常规超频等很多插件，够大部分人用了<br>

> [!NOTE]  
> 本整合作者从未进行任何收费盈利行为！
> 本项目仅作个人交流学习、研究硬件、备份数据使用，禁止使用该项目进行任何形式商业化、贩卖等使用。不支持也不提供任何违规非法用途支持和使用，请勿用于任何非法用途，请在下载24小时之内删除。

###  *使用* 
***

* Telsa是Ultrahand，减少卡屏等键位冲突
  * Ultrahand按键：`ZL+ZR+ZDDown(左下按键)`
* 内置自调风扇转速调节配置，风扇调整更细腻平衡，降低主机模式闷热问题，或延长掌机模式续航能力
  * 如果你要自定义风扇配置，请使用自带 `NX Fancontrol` 插件调整
* 虚拟系统进入原相册方法:
  * 按 `R` 并打开相册
* 关闭性能监控悬浮窗方法:
  * 按下`左右`两个手柄的摇杆


* 新手小白必读 - Switch新卡开荒、升级系统/整合包&备份恢复存档教程：
[酷安链接](https://www.coolapk.com/feed/57053591?shareKey=YWYyOGZjY2U0YTE5NjY3YWRmMTg~&shareUid=2679393&shareFrom=com.coolapk.market_14.0.3)<br>
  * ~~【推荐】格式化SD卡重做FAT32系统使用最稳定(如果是我上一版本的可以直接覆盖更新)~~<br>
  * [Switch HorizonOS Firmware 点击这里下载](https://github.com/THZoria/NX_Firmware/releases)<br><br>
使用与更新整合包:<br>
* 1.删除SD卡其它所有文件，但请保留SD卡根目录 `Nintendo` 、`emuMMC` 文件夹 以及`你需要保留的文件(如金手指、Mod等）`<br>
* 2.解压整合包zip压缩包，将里面全部文件夹和文件复制到SD卡根目录<br>
* 3.使用并享受<br>
  * 如果没有emuMMC文件夹或没有制作虚拟系统，请在Hekate引导界面选择：<br>
    虚拟系统 - 创建emuMMC - SD卡文件<br>
    等待跑条完毕即可进入虚拟系统<br>

*如果还没学会建议去视频网站搜教程自行看一下*
<br>

> [!WARNING]
> 该整合包支持软破，但因软破不稳定性因素更多，可能在软破及上无法稳定正常使用<br>
> 
> 该问题已在20251202-H21.0.1&20.5.0及以后版本修复~~任天堂HOS20.0.0以后加强了网络连接校验，在虚拟/真实系统中，由于屏蔽了DNS和序列号，连接WIFI会使CPU3满载，造成系统卡顿、耗电，建议非需要时关闭WIFI(呼出Ultrahand-系统功能-WIFI状态 切换为未启用 或 开启飞行模式)~~<br>
> 
> 如果你是 腾讯-任天堂Switch 中国大陆硬件 用户，在升级19.0.1+系统前，可能需要 [切换至全球版本](https://github.com/Cirrest/Tencent-switcher-GUI_Rebulid/releases/)

> [!TIP]
> 该整合包已添加CommonProblemResolver救砖插件 <br> 可Hekate下删除主题和关闭插件自动启动<br>
> 启动路径:hekate启动器-更多设置-CommonProblemResolver <br>
> 进去1是关闭插件自启动，2是删除安装的主题，有效解决进不去HOS系统的故障<br>
> 更详细说明请见[官方说明](https://github.com/zdm65477730/CommonProblemResolver/)


<br>
<br>

###  *超频* 

----
应诸多用户要求，并制作KIP补丁并添加超级OC功能<br>
> [!NOTE]
> 请注意:有用户报告默认OC不稳定，从 20250602 版本开始，整合包不再主动整合超频Kips，OC超频需要自行将 NX-UltraOC_xxx.zip 附件文件下载解压后，将里面`4`个文件夹复制并覆盖至`Switch SD卡根目录`

默认开放以下最高OC频率:<br>
|  | CPU | GPU | MEM |
| ------------- | ------------- | ------------- | ------------- |
| Ultra OC扩展包可超频 | 1963Mhz | 1228Mhz | 3200Mhz |
| 官方最高可超频 | 1785Mhz | 921/768Mhz | 1600Mhz |
| 官方默认 | 1020Mhz | 768/460/384Mhz | 1600/1333Mhz |

 > [!CAUTION]
 > 进阶用户可自定义调整频率/电压/时序。OC超频功能极其危险，会增大发热降低续航，并可能损害你的硬件！<br>
 > 如果想更进一步更激进超频，请自行替换更为激进的 KIP 并替换 `\atmosphere\kips\loader.kip`<br>
 > 不建议普通用户使用或长时间使用，若使用请自负责。


使用方法:<br>
* 打开UltraHnand<br>
* 选择 系统超频 进行操作
<br>
<br>
【进阶超频操作】<br>
* 打开UltraHnand<br>
* 按→键选择 `OC Switchcraft EOS` 进行进阶操作<br><br><br>


###  *进阶*
***
* 默认开启USB3.0，在支持该协议的端口和线缆上使用能有效提高有线传输速度，但会较严重干扰2.4GHz WIFI和蓝牙信号质量和信噪比，并且可能在部分电脑和线材在MTP模式下无法识别设备。如果你遇到上述问题，则需手动编辑 Atmosphere 系统配置文件来禁用此功能，如下所示：
  
<br><br>
根目录/atmosphere/config/system_settings.ini<br>
```
[usb]
usb30_force_enabled = u8!0x0
```
根目录/bootloader/hekate_ipl.ini<br>
```
usb3force=0
```
<br>

♿♿♿如果你的NX无法稳定运行或经常出现安装使用Ubuntu和Android有玄学问题，请考虑你的芯片是否需要更新固件
----
* Hwfly toolbox<br>
hwfly工具箱，hwfly芯片专用，支持不可更新固件的hwfly芯片免拆机更新sdloader<br>
升级正版系统后需再刷sdloader.enc一次，升级虚拟系统不影响<br>
刷完sdloader.enc后支持不插SD卡，开机后按音量+和-进正版系统<br>
解压缩后复制sdloader.enc到SD卡根目录<br>
[Hwfly toolbox](https://github.com/hwfly-nx/hwfly-toolbox/)<br>
[Hwfly toolbox Firmware](https://github.com/hwfly-nx/firmware/)<br>

* Picofly toolbox<br>
树莓派芯片工具箱，rp2040芯片专用，支持免拆机更新sdloader和树莓派固件<br>
升级树莓派固件是根目录update.bin，能正常使用一般不用升级固件<br>
[Picofly toolbox](https://github.com/Ansem-SoD/Picofly/blob/main/Firmwares/picofly_toolbox_0.2.bin)<br>
[Picofly Firmwares](https://github.com/rehius/usk/releases)<br><br>

***

🎉鸣谢(排名不分前后):
----
[Atmosphere](https://github.com/Atmosphere-NX/Atmosphere?tab=readme-ov-file)<br>
[Hekate](https://github.com/CTCaer/hekate)<br>
[wiliwili](https://github.com/xfangfang/wiliwili)<br>
[Lockpick_RCM](https://github.com/Decscots/Lockpick_RCM/releases)<br>
[Ultra-Paw-Overlay](https://github.com/Ultra-NX/Ultra-Paw-Overlay)<br>
[DBI](https://github.com/rashevskyv/dbi)<br>
[DBI中文版 by:时鹏亮](https://shipengliang.com/games/%E7%AB%AF%E5%8D%88%E8%8A%82%E5%84%BF%E7%AB%A5%E8%8A%82%E7%A4%BC%E7%89%A9%EF%BC%9A%E5%85%A8%E7%90%83%E9%A6%96%E5%8F%91-dbi-%E4%B8%AD%E6%96%87%E7%89%88.html)<br>
[aio-switch-updater](https://github.com/HamletDuFromage/aio-switch-updater)<br>
[EdiZon](https://github.com/proferabg/EdiZon-Overlay)<br>
[Fizeau](https://github.com/averne/Fizeau)<br>
[ftpd](https://github.com/mtheall/ftpd)<br>
[Mission Control](https://github.com/ndeadly/MissionControl)<br>
[hb-appstore](https://github.com/fortheusers/hb-appstore)<br>
[JKSV](https://github.com/J-D-K/JKSV)<br>
[Linkalho](https://github.com/impeeza/linkalho)<br>
[Moonligh](https://github.com/XITRIX/Moonlight-Switch)<br>
[NXActivityLog](https://github.com/zdm65477730/NX-Activity-Log)<br>
[NX FanControl](https://github.com/ppkantorski/NX-FanControl/)<br>
[NX Shell](https://github.com/joel16/NX-Shell)<br>
[SwitchThemeInjector](https://github.com/exelix11/SwitchThemeInjector)<br>
[sys-clk](https://github.com/ppkantorski/sys-clk)<br>
[SysDVR](https://github.com/exelix11/SysDVR)<br>
[Thmerzer](https://themezer.net/)<br>
[tinfoil](https://tinfoil.io/)<br>
[CommonProblemResolver](https://github.com/zdm65477730/CommonProblemResolver/?tab=readme-ov-file#commonproblemresolver-cpr)<br>
[NX-OVLLOADER](https://github.com/ppkantorski/nx-ovlloader)<br>
[Ultrahand Overlay](https://github.com/ppkantorski/Ultrahand-Overlay)<br>
[SaltyNX](https://github.com/masagrator/SaltyNX)<br>
[OC-Switchcraft-EOS](https://github.com/halop/OC-Switchcraft-EOS)<br>
[nim patch](https://github.com/fruityloops1/nim-prodinfo-blank-fix/)<br>
[QuickNTP](https://github.com/nedex/QuickNTP/)<br>
[sys-patch](https://github.com/impeeza/sys-patch)<br>
[Tencent-switcher-GUI](https://github.com/CaiMiao/Tencent-switcher-GUI)<br>
[Goldleaf](https://github.com/XorTroll/Goldleaf)<br>
[FPSLocker](https://github.com/masagrator/FPSLocker)<br>
[Status-Monitor-Overlay](https://github.com/masagrator/Status-Monitor-Overlay)<br>
[haku33](https://github.com/StarDustCFW/Haku33/releases)<br>
[ReverseNX-RT](https://github.com/masagrator/ReverseNX-RT)<br>
以及所有让我们NX变的更好玩的人<br><br>

