1、首页
wiki.isbg.cn
最新更新	网址	更新时间
gm630卡20%	http://wiki.isbg.cn/web/#/5/27	2021年7月27日
税务网站问题处理	http://wiki.isbg.cn/web/#/5/29	2021年7月22日
网页、网站、IP打开慢,无法访问	http://wiki.isbg.cn/web/#/5/54	2021年8月2日
光猫终端卡40%	http://wiki.isbg.cn/web/#/5/55	2021年8月3日
H62G语言配置	http://wiki.isbg.cn/web/#/5/57	2021年8月12日
ZXHN F673AV9语言配置	http://wiki.isbg.cn/web/#/5/62	2021年8月31日
GS3202语言配置	http://wiki.isbg.cn/web/#/5/67	2021年9月23日
H2-3S语音配置	http://wiki.isbg.cn/web/#/5/72	2021年10月25日
华为HS8546V5语言配置	http://wiki.isbg.cn/web/#/5/75	2021年12月17日
E900V22C(创维)-卡loading画面	http://wiki.isbg.cn/web/#/5/77	2022年2月9日
E900V22C(创维)-卡工厂模式界面	http://wiki.isbg.cn/web/#/5/78	2022年2月9日
关于2022年2月17日海伦国际机顶盒卡顿的处理案例	http://wiki.isbg.cn/web/#/5/80	2022年2月17日
华为HS8545M5语言配置教程	http://wiki.isbg.cn/web/#/5/82	2022年2月23日
[服务器提供商：蓝队云](https://www.landui.com?refer_host=lanMjIzODU2dWk "服务器提供商：蓝队云")
2、导航
安管 http://10.174.244.103
3、光猫
3.1、GM220S
3.1.1、基础配置
[TOC]
一、光猫登陆：
浏览器输入：192.168.1.1 
超级用户登录：
用户名：CMCCAdmin
密码：aDm8H%MdA
二、上网模式修改
（规范为路由模式，如没有特殊要求，请勿随意更改）**
路由模式改桥接模式
登陆到光猫页面—>网络—>选中41VLAN，然后拉到底部，点击“删除”

先选择新建，点击“模式”处的下拉框，选中“桥模式”：
{{:1.光猫:gm220s:pasted:20210701-184629.png}}
点击“业务模式”处的下拉框，选中“改写”并在“VLANID”处填写41
（PPP即为路由模式，桥模式即为桥接模式）
填写完，点击“创建”。
桥接模式改路由模式
开始的删除操作和“路由转桥接”的删除操作基本一致，具体配置如下图所示：
三、无线网配置
超级用户登陆：在“网络”—>WLAN网络配置—>WLAN参数配置中配置：
普通用户登录：
普通用户名：user
密码：，默认配置密码，光猫的铭牌上。
四、宽带语音配置
点“应用”—>宽带电话设置中设置
（移动语音注册ip：211.139.26.77（昭通））
语音账号设置，具体配置如下图所示：
五、关闭强弹
关闭强弹方法:
在”网络”中找到”远程管理”,点开选择”LOID”,页面中有”一键设置已注册”,点击即可,页面显示如下图所示:
六、设备恢复出厂设置
3.1.2、来电显示不全的问题
来电显示不全的问题
修改来电显示获取方式为：优先从PAI获取 
3.1.3、语言配置
1.登陆设备192.168.1.1
2.查看网络装态，45是否获取到IP

3.如果未获取到，按照图下配置

4.配置语言配置

5.配置账号、密码

6.查看语言注册状态，如未注册成功，检查密码或者重启光猫
3.2、GM228-S
3.2.1、语言配置
[TOC]
一、登陆设备192.168.1.1

二、检查vlan 45是否获取到IP地址

三、未获取到ip，可以删除重建45

四、配置语言账号和密码

五、查看语言注册状态，失败一般重启

3.3、GM630
3.3.1、GM630卡20%
[TOC]
GM630卡20%APP优化工具操作手册
目前新一批到货的GM630注册卡20%的问题已经有了解决方案，目前发现两种故障表现： 1、设备注册卡20%无法安装；
2、设备安装成功后重启数据掉线客户无法使用；目前以上故障出现都不是绝对的，所以请按供应商给出手册属故障批次内的设备在安装前都按手册度设备进行参数修改，目前确定的是中兴C300下出现概率较高，其它OLT设备也可能出现同样故障，所以为避免重复上门的情况出现请各位注意告知装维人员全量该批次设别都进行参数修改操作。
备注：需优化网关为 GM630 中设备铭牌带有如下字母 XW 标志。

1、用安卓手机浏览器扫描二维码下载安装 APP 优化工具

APK下载地址，点击下载
2、连接网关 GM630 WIFI

3、打开 APP 优化工具扫描网关 GM630 零配置二维码 3、打开 APP 优化工具扫描网关 GM630 零配置二维码

4、等待设备自动重启后重新注册
3.4、HG6145D1
3.4.1、语言配置
一、登陆设备192.168.1.1

二、检查vlan 45是否获取到IP地址

三、配置语言信息

四、配置语言账号和密码

五、查看语言注册状态，失败一般重启

3.5、H10E-01
3.5.1、语音配置
（H10e-01）专网开通ims和商务FTTB+LAN融合语音网关配置教程
备注：请勿使用设备自带的公网接入ims语音，会导致语音不稳定掉话，必须使用此方法配置专网接入！
登录设备：
用户名:CMCCAdmin 密码:aDm8H%MdA
1.配置通道
Internet连接-新建VLAN 45通道 
2.查看通道是否配置成功
WAN口侧状态-查看45通道获取到语音IP 
3.配置语音
宽带电话设置-宽带电话基本设置 
4.查看语音注册状态
设备信息-语音口状态：注册成功 
5.现场摘机测试
3.6、H1S-3
3.6.1、语言配置
[TOC]
H1S-3配置语言
1、查看45是否获取到IP，如果未获取到，删除Vlan45 新建VOIP

2、设置SIP，保存，配置语音账号，保存

3、拨号测试
3.7、H2-3
3.7.1、语言配置
H2-3-语言配置
1、vlan 45使能关闭
2、删除45，新建45

3、配置语言设置

4、语音注册成功

3.8、H2-3S
3.8.1、升级手册
H2-3S升级
1.浏览器输入192.168.1.1
登入超级 用户账号CMCCAdmin 密码aDm8H%MdA 
2.点击回车进入web页面
3.浏览器输入192.168.1.1/bd/vermod.asp进入隐藏网页，按图操作即可

4.温馨提示升级用浏览器最好是使用ie浏览器，谷歌浏览器，火狐浏览器
S505 最新版 下载：DZ-RTL-CMCC-H2-3s-V2.1.1.00.01-S505D1907251458.tar
S455(版本不提供，使用S505) 下载：S455.tar
解决LAN2口顶盒地址分配问题、解决语音嘟嘟声问题、解决IPV6地址分配问题和班班通测速问题
3.8.2、语音配置
一、登录设备192.168.1.1，CMCCAdmin，aDm8H%MdA
二、查看是VLAN 45是否获取到了IP

三、如果未获取到，侧按照以下图片配置VLAN 45

四、配置语音设置

五、配置语音账号和密码
、
六、查看语音注册成功

3.9、H10G-13
3.9.1、配置
1. 网关测配置
1.1 激活 先扫码激活机顶盒，然后再开始安装
1.2 设备注册 手机或者电脑接入设备WIFI（查看设备背部标签），浏览器地址栏输入http://192.168.1.1，点击设备注册


注册100%即完成
2. 机顶盒配置
以下操作使用遥控器点击操作即可

注明：对接平台选择自己地州对应的平台：华为平台（昆明、大理、丽江、保山、德宏、怒江、迪庆、临沧）；中兴平台（楚雄、昭通、曲靖、玉溪、红河、文山、普洱、版纳）
如遇到配置问题请联系工程师：
    关乐  18377104654

   许吉昌15887752583

   苏海龙15288311752
PS：如果发现登陆电视账号后电视界面提示109、104错误代码请联系数联工程师：江海洋15080403656
3.10、GM619
3.10.1、手动数据视频配置
官渡分公司中移物联终端GM619手动数据视频配置教程2018年1月31日
流程步骤（配置过程中切勿先插机顶盒，最后再接上，避免数据冲突）： 1、网管做数据，进行组播仿真测试有流量(可选) 2、GM619终端，设备注册（进度20%以上，卡住也算，既可以登录） 3、中移物联工具：关闭注册页面，确认业务配置成功。 4、插上机顶盒，网络设置，确认获取IP 5、查看高清台，确认数据正确 注：之前配置过数据，一定要恢复出厂设置!
1、网管做数据，进行组播仿真测试有流量
①网管做数据 SVLAN：2400 内层VLAN：2400 VLAN切换：translate and Add CLVAN：41 上、下行流量：1000M 组播VLAN：2999 ②仿真测试流量（可选） 
2、GM619终端，设备注册（进度20%以上，卡住也算，既可以登录）

3.注册OLT过后，大于20%进度，既可以。
①确保电脑已经有线连接至LAN口或者WIFI已经连接上光猫。（window 电脑才能使用，安装过微软netframe work） 使用工具，配置。先解压包，选择mTools.exe，选中关闭强制注册。 点击下载:手动配置GM619.rar 出现：保存设置，设置注册状态完成即可。
4、插上机顶盒，网络设置，确认获取IP

5、查看高清台，确认数据正确

3.11、CM112Z
3.11.1、语言配置
[TOC]
语言配置
一、账号确认
1、空号：客户经理重新查看IMS产品信息。 2、关机/忙音/打不通 3、密码确认
二、进入光猫
先配置LOID，宽带能正常上网，再往下操作！ 使用管理员密码进入光猫 用户名telecomadmin 密码admintelecom
三、查看是否获取到语音ip地址、语音信息
1、获取成功截图 2、如果VLAN 45没有获取到IP，重新设置VLAN 45 3、检查语音账号信息，格式如下： 用户名：+86871XXXXXXXX 鉴权用户名：86871XXXXXX@ims.yn.chinamobile.com

四、确认是否收到下发的数据
进入应用-宽带电话设置，确认信息是否和以下图片一致： 配置信息 语音账号信息 
五、删除系统下发的错误格式用户名和鉴权用户名

六、手动更改用户名、鉴权用户名格式
端口1新建用户名、鉴权用户名，格式如下： 用户名：+86871XXXXXXXX 鉴权用户名：86871XXXXXX@ims.yn.chinamobile.com
七、保存设置、查看登录状态

八、现场拨接电话测试。滴滴滴滴。
3.12、HG8240系列
3.12.1、语言配置
ONU语音数据配置
（备注：语音VLAN已经由43换成45，请注意） 本教程适用于使用华为FTTH型单口、多口ONU配置IMS语音，FTTB型多口ONU配置方法与此类似。 1、ONU设备接电，开机 2、连接网线 网线一头连接ONU设备任意网口，网线另一头连接电脑； 3、设置电脑本地连接IP IP地址192.168.100.2，掩码255.255.255.0 4、设备登录 在浏览器地址栏输入http://192.168.100.1 ”（“192.168.100.1”为ONU的缺省IP地址），然后按回车键，浏览器弹出登录窗口。如下图 语言：中文用户名：telecomadmin密码：admintelecom 登录成功后进入到以下页面： 点击“新建”按钮。出现如下界面 − 使能WAN连接：使能（打勾即可）− 连接类型：路由 − 服务列表：  VOIP− 使能VLAN  使能（打勾即可） − VLAN ID： 45 − 802.1p：6 − 获取IP方式： DHCP 然后点击“应用” 6、配置SIP协议语音接口参数 点击主菜单上”语音”进行SIP协议语音接口参数的配置，实现对Outbound服务器，端口号，归属域名，本地端口，信令端口等信息进行配置，最终实现连接语音服务器的需求。 设置语音接口参数如下： − Outbound服务器地址：          211.139.26.36（默认值） − Outbound服务器端口号：        5060（默认值） − 主用服务器地址：211.139.26.36 − 主用端口号：5060 − 归属域名：ims.yn.chinamobile.com（默认值） − 本地端口：5060（默认值） − 注册周期：60 − 国家及地区：CN-中国 − 信令端口：（选择上面配置的语音WAN接口名字） 1_VOIP_R_VID_43 − 媒体端口：（选择上面配置的语音WAN接口名字） 1_VOIP_R_VID_43   完成后点击“应用”按钮。   7、配置SIP协议语音用户参数 URI：+86871XXXXXXXX 注册用户名：+86871XXXXXXXX 关联端口名：按实际需求填写 鉴权用户名：86871XXXXXXXX@ims.yn.chinamobile.com（注意前面没有+） 密码：XXXXXXXXXXXX 8、配置传真高级参数 点击右上侧的“语音高级设置”，在弹出的窗口中检查高级配置是否如下： 9、检验配置 点击“状态”–“VoIP信息”，查看请问是否注册成功，并进行语音通话测试。 在右侧信息栏页面中，单击“重启语音”。 10、设备保存（重要） 在测试连接通讯正常后，选择“系统工具”-“配置文件”，点击保存配置。 将之前做的操作保存起来，否则一旦断电后客户信息将丢失。 11、故障处理之测试IMS账号是否正确 当ONU上出现IMS业务无法正常注册时，我们可以从账号问题或网络配置问题两方面寻求解决。为便于处理故障，经常需要判断IMS账号是否正常，可使用如下两种方法测试： （1）、使用手机拨打：使用维护人员手机拨打所开户的IMS号码，如66040001，会有如下提示。 提示关机：业务开通成功，但未进行任何SIP注册。 提示空号、停机：IMS号码有误。 正常响铃，但现场SIP未注册成功：账号已在其他地方注册，建议修改密码 (务必在语音高级设置中开启：来电显示) 备注： 配置流程 先申请配置LOID，在光猫中ONT认证中填写即可。不用其他设置，需要数据中心网管平台开启端口上网。 语音需要等数据中心在网管平台配置好VLAN后，才能在光猫中设置以上数据，不能提前设置，否则无法使用。
3.13、F663NV3A(ZTE)
3.13.1、中兴来电显示不全
中兴来电显示不全的问题
修改来电显示获取方式为：优先从PAI获取

3.14、H62G
3.14.1、语言配置
[TOC]
一、登陆设备192.168.1.1
二、检查vlan 45是否获取到IP地址

三、未获取到ip，可以删除重建45

四、配置语言账号和密码

五、查看语言注册状态，失败一般重启，此款光猫需要关机10分支，在开启。

3.15、ZXHN F673AV9
3.15.1、语言配置
1.登陆设备192.168.1.1

2.查看网络装态，45是否获取到IP

3.如果未获取到，按照图下配置

4.配置语言配置

5.配置账号、密码

6.查看语言注册状态，如未注册成功，检查密码或者重启光猫

3.16、GS3202
3.16.1、语言配置
此教程由罗永顺提供
1、查看是否获取到45 语言IP

2、语言VLAN 设置，按照以下配置，获取到IP

3、语言配置

4、新建电话和密码

5、输入账号和密码

6、查看语言注册状态，成功

3.17、华为HS8546V5
3.17.1、语言配置

1.登陆设备192.168.1.1
2.查看网络状态，45是否获取到IP
3.如果未获取到，按照图下配置

4.配置语言配置

5.配置账号、密码

6.查看语言注册状态，如未注册成功，检查密码或者重启光猫
用户名：+86871XXXXXXXX 用户名：86871XXXXXX@ims.yn.chinamobile.com 密码:xxxxxxxx
3.18、华为HS8545M5
3.18.1、语言配置
1.登陆设备192.168.1.1

2.查看网络状态，45是否获取到IP

3.如果未获取到，按照图下配置

4.配置语言配置、配置账号、密码

5.查看语言注册状态，如未注册成功，检查密码或者重启光猫

3.19、SK-D848(创维)
3.19.1、语言配置
1.登陆设备192.168.1.1

2.查看网络装态，45是否获取到IP

3.如果未获取到，按照图下配置

4.配置语言配置

5.配置账号、密码

6.查看语言注册状态，如未注册成功，检查密码或者重启光猫

4、ONU
4.1、华为MA-5620
4.1.1、华为onu交换机配置
串口通信配置
BOARD INFORMATION : CPU: ARM Integrator - Cortex A9 (ARM). Processor running at 400Mhz

199M bytes DDRAM, 64M bytes flash memory installed on board

Baudrate of serial channel is 9600bps

Board's LAN IP address is 10.11.104.2

Board's LAN Subnet mask is 255.255.255.0

Board's LAN MAC address is 34:00:A3:27:0F:76

9600 8 1 NONE 1
编辑
开始：
root mduadmin n

enable config

vlan service-profile profile-id 2

user-bridging enable

commit

quit

vlan 2 smart

vlan bind service-profile 2 profile-id 2

multi-service-port vlan 2 port 0/1 1-8 USer-VLAN UNTAgged RX-cttr 6 TX-cttr 6 y

save data

save configuration

quit
清空配置重启恢复出厂
era flash data

y

reboot system

y
5、机顶盒
5.1、联系人
中兴机顶盒售后:18387478434； 返修统一找终端公司（电话：4001888186） cm101s/cm201-2/cm211-2(朝歌)售后请联系:18983628990 cm201-2/cm211-2(中国制造：CH长虹)帅强 13890145754 cm101s-2/cm201-2(YS 易视)售后请联系:兰光飞18185275507 企业网关：方工: 手机号码 18320980311 公司名称 星网锐捷
咪视通：15287176171 李师
物联网售后M301H售后请联系: (BYT/cw创维)18314149337 黄工 (cw创维)15623324616 祁工 (zn兆能)13924651543 徐工
蓝牙遥控器售后服务电话4001888186。
浪潮售后：4008122330 张工:18615236134； 烽火联系人,凌炯:18387188468。 烽火终端售后 段飞飞 18987688736 烽火终端返修 张志强 15969582363 
海信售后：刘工18661767629；谭工13012506462； 没有本地台联系银河平台的石师 石师：18383137261
5.1、CM201-YS
5.1.1、卡loding页面
关于CM201-2 YS机顶盒卡loading 问题的处理方案
处理办法：
1.卡在白色字母Loading或海报页，需要等待三分钟，未进入系统界面，物理恢复出厂（reset键)设置。
操作步骤：
第一步：先关机； 第二步：按住Reset键不松手，开机键按一下开机，按住Reset键至少5秒以上（Reset键：用牙签、回形针等尖锐物） 第三步：电视机上出现“系统正在初始化”后，松开reset键即可，等待系统自动启动即可； 如按照此方案操作故障无法排障建议走和装维APP换机流程。 超出一年换机需要收取用户费用，用户不愿意付费的情况下，可与用户沟通将原机返回到如下地址进行免费维修处理。
邮寄方式：顺丰物流到付 云南省昆明市西山区理想红树湾23栋1单元1401 兰光飞18185275507
附：寄送时请注明寄回信息，机顶盒的账号和密码 
5.2、M301A（华为）
5.2.1、回滚WIFI
回滚WIFI
百度网盘下载 主用 链接：https://pan.baidu.com/s/1CpcdRxd_R7s2ZGUKQJi11w 提取码：glwb
备用 链接: https://pan.baidu.com/s/1Zy4fUO1EtZ03Gd62kMalUg 提取码: 4j31
升级手册
5.3、IP906H海信
5.3.1、升级
央广银河——华为平台（IP906H_50M1软件升级包）
百度网盘链接：https://pan.baidu.com/s/10bI8NbXfQjO8mHUBHgAS_w 提取码：6i2e
5.4、IPBS9505浪潮
5.4.1、升级
央广银河——华为平台（浪潮盒子机型IPBS9505 软件升级包）
移动和彩云链接:https://caiyun.139.com/m/i?0P5CsLHJZDo8m提取码:7woO
只用下载红色框压缩包，下载后解压缩，解压后里边有一个升级包，一个MD5，放在空U盘内进行刷机。刷机过程中的疑问可以联系浪潮机顶盒的技术售后电话 0531-85105318。
5.5、E900V22C(创维)
5.5.1、卡loading开机画面
机顶盒型号

故障画面

处理方案
操作方法：开机的同时迅速按遥控器左键 连续按直到出现画面以后选择恢复出厂设置或者恢复出厂版本即可恢复 1、开机的同时重复持续按遥控器左键（是开机的同时，不是开机后），出现画面以后选择恢复出厂设置或者恢复出厂版本
5.5.2、卡工厂模式界面
故障画面:卡工厂模式

解决方案:返修
移动返修邮寄地址:
联系人：刘少成 电话：13759494960 地址：云南昆明官渡区太平村295号云南荣华物资仓储基地厂房
6、路由器
6.1、YR1900G
6.1.1、配置
YR1900G无线桥接过程步骤:
第一步:高级设置-设备管理-工作模式切换为路由模式 第二步:高级设置-wifi设置-WDS无线桥接开启
视频教程
http://player.youku.com/embed/XNDgyMjI4ODEzMg?client_id=70425dd755d80061&password=&autoplay=false#doc.isbg.cn
6.2、AH-LINK022
6.2.1、配置说明
AH-LINK022配置说明
1.先不连接光猫，先将路由器上电，路由器上电2分钟后接入光猫，光猫插一口。 2.此时访问192.168.10.1或者andwifi.10086.cn，结合机贴信息按照普通路由器进行配置即可。 3.如果路由器上电之前已经接入光猫，则需要重置路由器，然后再次按照前面所说进行配置。`
AH-LINK022（标准版）支持Andlink协议，路由器出厂设置为桥接模式。将上级网关有线直连，网线建议连在网关1口（千兆口）。
场景一：上级网关为中国移动智能网关（机壳上印有和家亲APP和配置二维码标识），通电2分钟内会自动同步为智能网关的WiFi名称和密码，同时路由器自身的WiFi名称消失，此时访问192.168.10.1不成功。终端此时接入需选择网关无线名称，同时输入网关的无线密码即可。
说明：
路由器上电前，需要与智能网关做好网线连接，否则路由器上电后未能检测到智能网关，路由器将会自动切换“路由模式”。若切换“路由模式”，可按照「场景二」配置方法进行配置。 2.若用户需要对路由器配置进行修改，可手动关闭智能网关的WiFi信号，此时仍能搜到网关的WiFi（实则路由器发出），可通过智能网关的WiFi密码进行连接。WiFi连接成功后，可以通过路由器管理平台域名 andwifi.10086.cn 登录路由器配置界面，管理密码需参考路由器背面机贴默认无线配置密码。 3.路由器仅在首次上电时会对智能网关、联网状态进行检测，后续断电、重启、修改配置均不会再次自动促发模式切换或WiFi同步。若用户进行“恢复出厂”操作，则会重复场景一过程。 场景二：上级网关为非智能网关（机壳上无和家亲APP和配置二维码标识），路由器将保持桥接模式。 初次连接请参照路由器背贴，输入WiFi名称及密码进行连接。WiFi连接成功后，可以通过路由器管理平台域名 andwifi.10086.cn 登录路由器配置界面，管理密码需参考路由器背面机贴默认无线配置密码。
常见功能
我想换个网络模式，在哪里更换？ 答：用户在主页点击“网络-网络模式”进行修改。
2.我网络是PPPoE拨号的，在哪里拨号？ 答：用户在主页点击“快速配置-上网设置”页面选择WAN接入类型，选择PPPoE类型，并输入运营商给出的用户名和密码。
3.我配置完成后，想再次更换WiFi名称，在哪里更换？ 答：用户在主页点击“快速设置-无线设置”，修改WiFi名称及密码。
4.我想更换我的管理密码，在哪里更换？ 答：用户在主页点击“管理-密码设置”，输入用户名（默认user），新密码并确认密码。
常见问题
1.192.168.10.1地址登录不了，怎么配置？ 答：此时客户网络环境处于中国移动智能组网模式下，可以使用andwifi.10086.cn进行登录。 2.跳转到指定页面，但找不到操作按钮，怎么办？ 答：用户使用鼠标上下滑动网页，即可出现。 3.路由器信号不够强，如何加强？ 答：①路由器WAN口需连接在光猫的“1千兆口”处。 ②建议用户连接路由器的2.4g信号。 ③将路由器放在离过道较近的地方或者开阔处，保证四周无明显物品遮挡。 ④将无线信息输出功率换成穿墙模式。 4.路由器上有些灯为什么都不会一直亮呢？ 答：①PWR及WiFi灯正常情况下是常亮的。 ②LAN1/2/3灯是需要当前端口与设备用网线连通后才会亮，如果此时有数据进行传输，那么对应灯就处于闪烁状态。 ③WPS灯需要用户进行WPS配对时候才会亮。 5.路由器WAN口灯变红？ 答：①配置过程中，路由器的网络模块进行重启自检，此时灯为红色。 ②光猫与路由器连接的接口指示灯（光猫上）是否为常亮，若不常亮则证明未连接成功，建议重新连接一下，如果不行就换个插口。 ③检查家中宽带是否欠费，若欠费则光猫上层无网络，此时路由器没有网络信号。 ④智能组网场景下，如果路由器信息未能同步成功，会出现WAN灯变红情况，建议断电重启路由器恢复查看，若此时还是未能成功，建议在路由器接口面找到“WPS/RESET”孔，用尖细物长按8S以上进行重置。恢复出厂设置后所有配置参数将全部清除，需要您重新配置。 6.如何将路由器恢复出厂设置？ 答：在通电状态下，用细尖状物体按住“WPS/RESET”孔（路由器接口面）8秒，松开后指示灯同时亮起。恢复出厂设置后所有配置参数将全部清除，需要您重新配置。 7.手机、平板、笔记本、或其他网络终端设备无法上网怎么办？ 答：①请确认手机登无线设备的无线功能已经开启。 ②请确认终端进行无线连接连接时，选择的无线名称及输入的密码是否正确。 ③请登录到192.168.10.1或andwifi.1008.cn查看当前设备是否已经被列入黑名单。 ④若上述操作仍无法解决问题，建议将路由器恢复出厂设置并重新配置，同时检查上层网络是否通畅。 8.在配置过程中，输入的密码太复杂？ 答：密码具有一定的复杂性，可以有效防止外部某些app破解您的家用无线路由器。某些工具破解您的路由器后，轻则仅是蹭网，重则控制您的家用物联网设备。也请您勿用XX钥匙之类的app进行配置，直接用手机原始无线连接即可。 9.路由器是否可以刷其他品牌的固件？ 答：不支持。目前路由器的整体软硬件已经调至最优，且配置足够家庭常规使用，不建议用户刷其他品牌的固件，因为刷机本身存在风险，弄不好就容易成砖如果出现因客户不当操作，我方是不支持退还后及保修。 10.路由器支持配置参数新旧更换么？ 答：不支持，路由器配置信息储存在路由器本身，不可移植。建议用户按照说明书重新配置一次。
6.3、H3C华三路由器
6.3.1、基础配置
1、连接
console口连接 端口(O):COM1 波特率(B):9600 数据位(D):8 奇偶校验（A）:none 停止位(S):1
2、登陆
enter登陆
system-view display current interface ethert0/0 ip add 192.168.1.1/24
ip http enable ip https enable
local-user admin admin smiple 123456 qu
dhcp dns-pool 1 dns-pool 1 dhcp enable
7、生态产品
7.1、摄像头
7.1.1、岭雁 LYC25-Note 
岭雁 LYC25-Note
备注:此设备不绑定宽带账号，有网络即可安装，最好使用移动网络。
一、产品外观


二、设备安装
1.准备两根网线，并确保使用的网络正常 2.将一根网线插入电源POE口和设备网口, 将另一根网，线插入电源LAN口和路由器 
三、使用“和家亲”添加设备
这款岭雁LYC25-Note网络摄像头是与中国移动和家亲合作的，所以首先需要在应用商店下载“和家亲APP”并注册登录账户。然后按照提示准备两根足够长的网线，分别用网线连接POE口和摄像机的网口，用网线连接LAN口和路由器的LAN口。
打开APP，点击添加新设备，此时正在扫描附近的设备，当扫描到新设备后会自动连接成功。如果扫描不到，我们可以用扫码绑定，扫描包装盒上或摄像机侧面的二维码也可绑定。 

四、成功添加摄像头后，我们就可以在“和家亲”APP对摄像头进行管理了，包括画面与声音、消息推送、休眠时间、移动侦测等功能的设置。

7.2、门铃
8、数据制作
8.1、山海湾小区物管监控开通手册
[TOC]
用户侧：
1、登录光猫
![] 电脑配置IP： 自动获取即可 或者 192.168.1.50/255.255.255.0 网址：http://192.168.1.1 账号：CMCCAdmin 密码：aDm8H%MdA
2、选中网络-宽带设置-VLAN 41，取消lan3端口绑定，保存应用。

3、新建vlan 44，类型桥接bridge，绑定lan 3，取消dhcp服务器，vlan id ：44保存应用。
OLT侧：
1、新增上网vlan，44，外层20，切换translate，确定应用


配置成功后连接状态！
9、网络教程
9.1、税务网站问题处理
[TOC]
云南省税务局yunnan.chinatax.gov.cn访问满，打印发票慢
很多客户投诉这个软件无法使用，原因在于这个软件中使用的域名与他们的网站是同一个域名，网站支持IPV6，但是APP不支持IPV6，因此导致支持IPV6的客户端无法正常使用软件进行报税。
解决办法:1.禁用电脑上的IPV6，即可恢复正常。

解决办法:2.修改本地hosts文件，即可恢复正常。（不推荐使用）
路径:系统盘一般为C盘 C:window/system32/drivers/etc/hosts 拷贝hosts文件至桌面，添加以下代码，将网站强制访问电信服务器IP，在拷贝回etc目录
116.52.12.162  yunnan.chinatax.gov.cn
禁用后，还是无法使用，重启光猫、电脑即可。
9.2、wireshark抓包
[TOC]
使用wireshark手机、电脑抓包
wireshark软件安装
window平台
一、电脑抓包
1、安装对应版本的Wireshark 32/64位。 2、开启Wireshark应用和需要抓包的电脑程序、网址等（其他程序全部关闭，仅开启需要被抓包的软件）。 3、选择抓包网卡： 4、选择开始鲨鱼鳍图标，运行一段时间停止正方形。 5、保存抓包数据,文件后缀为：pcapng 保存文件名字：w13888xxxxx游戏：XX，olt：XX，2019年8月13日 11点
二、手机WIFI抓包
1、安装对应版本的Wireshark 32/64位。 2、电脑网卡正常上网，使用360WIFI共享助手，建立WIFI，让手机接入360 共享WIFI。 3、开启Wireshark应用和需要抓包的手机程序、网址等（其他程序全部关闭，仅开启需要被抓包的软件）。 4、选择抓包网卡：选择360无线WIFI网卡。 5、选择开始鲨鱼鳍图标，运行一段时间停止正方形。 6、保存抓包数据,文件后缀为：pcapng 保存文件名字：w13888xxxxx游戏：XX，olt：XX，2019年8月13日 11点
软件下载

Wireshark 下载：Wireshark-win32 下载：Wireshark-win64 下载：360共享wifi
9.3、网页、网站、IP打开慢,无法访问
网页、网站、IP打开慢,无法访问
例如:xs.schoology.com
提供附件
1、ping

2、nslookup

3、tracert

4、故障页面

9.4、光猫终端卡40%
光猫终端卡40%
首先确认端口正确
1、使用DHMP系统将工单修改未处理

2、重新制作数据，网管数据loid对应ONU ID 大于63

9.5、OA设置
点击下载:OA兼容之IE8,IE9设置说明.docx 点击下载:OA.可信站点设置.reg
柯尼卡美能达 bizhub C281 点击下载bizhub_c221_c281.exe
柯尼卡美能达 bizhub 363 点击下载bizhub_423_363_283_223.exe
9.6、1
宽带测试app https://kmyd.lanzoub.com/ijQWJ072xypc https://kmyd.lanzoub.com/iHi3M072xz3g
http://183.224.28.139:18089/MOBILE/Uploads/APP/yunnan912pro1_1.0.1.apk 移动网上大学https://wangda.chinamobile.com/app/share/#/
landie https://aliosscdn.bluestacks.cn/client/BlueStacks4Setup.exe
PDA https://kmyd.lanzoub.com/iNGMw019q1kd PDA https://developer.lanzoug.com/file/?BWNRbwg5ADFVXAE5Cj9dMVtkADgAL1M1VjBWflRpUCEJYgJzCjEAPVRuBjUBCgZuUG4COgBpBDILPwYyVzxQYQUwUTUIcwAyVXABagptXWxbNQA8AGtTYlZhVmBULlAhCXkCaAplAGRUMAZiAXoGN1A5AigAbgQ2CyMGOVc6UGEFYFFlCGIAMVU0AWYKaV0+W2AAZgBsU2BWYlZhVGtQaQk8Am0KMgBgVDAGMgFmBjZQMwJjAGYENAs9Bi5XalAhBW5RIAggACdVZgElCjddOFs8ADMAaFNpVmVWaVQ5UHcJfQI8CjoAMVRkBm0BZAYxUD4CMQBmBDcLPQY0VzNQZgUrUSgIcwAyVW8BIApjXW1bNwAxAGlTaFZgVmBUPFBmCTkCcwoiACRUdQZtAWQGMVA+AjEAZgQ2CzUGOFczUGIFI1FzCDwAJFU+AWYKZl1vWy8ANwBtU2VWf1ZoVDhQfwk7AmEKYQ==
统一资管app https://kmyd.lanzoub.com/iGlcP03vr29i
app_v2.2_release_yunnanunion_2021-12-31.apk
微信图片_20220114144758.jpg
微信图片_20220114144802.jpg
微信图片_20220114145000.jpg
1876640.apk
复旦耳鸣RS.apk
https://kmyd.lanzoub.com/iQhEo00ho4zg APK下载 https://developer.lanzoug.com/file/?B2FaZAw9AjNUXQY+VmNQPFFuVW1UPFcKUDVQN1R7UjYHKVdhDyJUawZ2BTVXalE8WmUHXVNlAWdSaFNjVjlRYAc2WjUMYwJnVDQGdlZkUCJRNlVhVD5XbVBvUGVUPlJqBzZXJg8iVHAGbQVhVzNRYloyBy1TPAExUnpTZ1Y5UX8HMlpoDDcCZFQ6BmNWNlBkUTpVY1Q8V2FQNFA0VDlSYwcwVzgPZlQwBmIFa1dhUWZaNgdgUz4BNVI0UzBWPVFkBylabAwhAj1UJAYlVnFQNFF5VTlUb1doUGFQYVQwUmcHPlcxD3RUdAY5BT5XZlE2Wj0HM1M6ATdSYFNgVjNRYAc3Wj4MaQJ4VCwGdlZkUD1RfFVtVDpXY1BjUGNUPVJrBz5XMA9gVDYGdgUmV3NRJ1o9BzNTOgE3UmBTYFYyUWgHPlo/DGMCcFR3BjlWclBsUTpVaFQ4V3tQZVBkVDxSfQc/VzAPfFQyBmQFZQ== 物料app
slmgr /ipk DCPHK-NFMTC-H88MJ-PFHPY-QJ4BJ
回车确认后稍等片刻系统会弹出安装成功提示
使用此命令在目标版本上安装KMS主机
slmgr /skms kms.03k.org
按回车确认稍等片刻系统会弹出安装成功提示
最后执行自动激活命令
slmgr /ato #结束
其他常用命令如下
slmgr /upk #卸载密钥
slmgr /ckms #清除KMS主机
slmgr /dlv #显示激活信息
关于官渡分公司2022年3月20日老旧小区宏仁新村整治的割接工单 老旧小区
如未完成，紧急回退
一改二
如未完成，紧急回退
2022-03-20 09:00:00 2022-03-20 11:00:00
olt名称 官渡区076_滇池星晨_S1_OLT406_HW_MA5800-X17(100.193.38.130)
VLAN用途 VLAN用途2 宽带使用 宽带VLAN IMS语音使用 语音VLAN OTT视频使用 IPTV_VLAN ITMS使用 ITMS_VLAN
http://www.downcc.com/soft/388490.html
base.apk
9.7、win10照片添加
点击下载:win10 照片添加.reg
直接运行
9.8、crt5.1.3
SecureCRT_5.1.3.zip
9.9、华为ma5620恢复密码
Select area information : Program Area B ,Data Area B . 
Begin to expand program...
Platform System start ...
Memory Data Bus Test .................pass. Memory Address Bus Test .................pass. Press 'Ctrl+T' To Start Memory Complete Test Trace code : 0x10047200 Copy from ROM to RAM ...... OK! Uncompress from ROM to RAM ...... OK!
System Vfs init...OK
The latest reboot is caused by : others
Copyright (c) 1998 - 2011 by Huawei Technologies Co.,Ltd. All Rights Reserved.
The last update date of base BIOS A is : Jan 4 2011 09:43:09
=============================================================== BOARD INFORMATION : CPU: ARM Integrator - ARM1176JF (ARM). Processor running at 533Mhz 256M bytes DDRAM, 64M bytes flash memory installed on board Baudrate of serial channel is 9600bps Board's LAN!IP address is 10.11.104.2 Board's LAN Subnet mask is 255.255.255.0 Board's LAN MAC address is 78:1D:BA:6D:42:94
System is booting from base BIOS...
Base BIOS version is 200 
Press key to stop auto-boot 3
Main menu:
0 Boot from flash 1 Load files 9 Reboot system
Please enter a choice : 1
SubMenu: Load files
0 Back to main menu 1 Download program file to flash 2 Download Data file to!flash 3 Download basebios file to flash 4 Download cpld file 5 Download packet file d Download program file to ddram 6 Download updatetool file to flash 7 Download equipment file to flash
Please enter a choice!: 2
Please select load mode[default: 1 -- TFTP load mode]:
0 Xmodem load mode 1 TFTP load mode Q Quit
Please enter your choice:0
Please Select download speed:
1.9600BPS
2.19200BPS
3.38400BPS
4.57600BPS
5.
115200CPS Select baudrate[default : 1]: 1
6.
You will download file by xmodem at 9600 BPS, are you sure? (y/n) [y]y
7.
Please change baudrate to 9600 BPS and press enter key Press CTRL+C key to abort! Waiting ...CCCCCC Starting xmodem transfer. Press Ctrl+C to cancel. Transferring Hauwei_MA5620_database... 100% 29 KB 707 bytes/sec 00:00:42 0 Errors 
8.
29635 bytes download OK save file to main area.....ok! save file to spare area.....ok!
9.
SubMenu: Load files
10.
0 Back to main menu 1 ! Download program file to flash 2 Download Data file to flash 3 Download basebios file to flash 4 Download cpld file 5 Download packet file d Download program file to ddram 6 Download updatetool file to flash 7 ! Download equipment file to flash
11.
Please enter a choice : 0
12.
Main menu:
13.
0 Boot from flash 1 Load files !9 Reboot system
14.
Please enter a choice : 1
15.
SubMenu: Load files
16.
0 Back to main menu 1 ! Download program file to flash 2 Download Data file to flash 3 Download basebios file to flash 4 Download cpld file 5 Download packet file d Download program file to ddram 6 Download updatetool file to flash !7 ! Download equipment file to flash
17.
Please enter a choice : 0
18.
Main menu:
19.
0 Boot from flash 1 Load files !9 Reboot system
20.
Please enter a choice : 9
21.
Platform System start ...
22.
Memory Data Bus Test .................pass. Memory Address Bus Test .................pass. Press 'Ctrl+T' To Start Memory Complete Test Trace code : 0x11020A02 Copy from ROM to RAM ...... OK! Uncompress from ROM to RAM ...... OK!
23.
System Vfs init...OK
24.
The latest reboot is caused by : others
25.
Copysight (c) 1998 - 2011 by Huawei Technologies Co.,Ltd. All Rights Reserved.
26.
The last update date of base BIOS B is : Jan 4 2011 09:43:09
27.
=============================================================== BOARD INFORMATION : CPU:!ARM!Integrator - ARM1176JF (ARM). Processor running at 533Mhz 256M bytes DDRAM, 64M bytes flash memory installed on board Baudrate of serial channel is 9600bps Board's LAN IP address is 10.11.104.2 Board's LAN Subnet mask is 255.355.355.0 Board's LAN MAC address is 78:1D:BA:6D:42:94
28.
System is booting from base BIOS...
29.
Base BIOS version is 200 
30.
Press key to stop auto-boot 0
31.
Now system will boot from flash memory.
32.
Transferring control to the loaded program../OK!
33.
System Vfs init...OK
34.
BIOS file system init...OK! System is upgrading database.... start 
35.
System is upgrading database.... 3% 
36.
System is upgrading database.... 15% 
37.
System is upgrading database.... 30% 
38.
System is upgrading database.... 45% 
39.
System is upgrading database.... 51% 
40.
System is upgrading database.... 57% 
41.
System is upgrading database.... 59% 
42.
System is upgrading database.... 61% 
43.
System is upgrading database.... 63% 
44.
空库文件下载
45.
Hauwei_MA5620_database
46.
9.10、ARP病毒是什么
arp 病毒并不是某一种病毒的名称，而是对利用 arp 协议的漏洞进行传播的一类病毒的总称。arp 协议是 TCP/IP 协议组的一个协议，能够把网络地址翻译成物理地址（又称 MAC 地址）。通常此类攻击的手段有两种：路由欺骗和网关欺骗。是一种入侵电脑的木马病毒。对电脑用户私密信息的威胁很大。
故障原因及现象
原因
主要原因是在局域网中有人使用了 ARP 欺骗的木马程序，比如一些盗号的软件，游戏木马等。
现象
当局域网内有某台电脑运行了此类 ARP 欺骗的木马的时候，其他用户原来直接通过路由器上网转由通过病毒主机上网，切换的时候用户会断一次线。
切换到病毒主机上网后，如果用户已经登陆了传奇服务器，那么病毒主机就会经常伪造断线的假像，那么用户就得重新登录传奇服务器，这样病毒主机就可以盗号了。
由于 ARP 欺骗的木马发作的时候会发出大量的数据包导致局域网通讯拥塞，用户会感觉上网速度越来越慢。当木马程序停止运行时，用户会恢复从路由器上网，切换中用户会再断一次线。
该机一开机上网就不断发 Arp 欺骗报文，即以假冒的网卡物理地址向同一子网的其它机器发送 Arp 报文，甚至假冒该子网网关物理地址蒙骗其它机器，使网内其它机器改经该病毒主机上网，这个由真网关向假网关切换的过程中其它机器会断一次网。倘若该病毒机器突然关机或离线，则其它机器又要重新搜索真网关，于是又会断一次网。所以会造成某一子网只要有一台或一台以上这样的病毒机器，就会使其他人上网断断续续，严重时将使整个网络瘫痪。这种病毒（木马）除了影响他人上网外，也以窃取病毒机器和同一子网内其它机器上的用户帐号和密码为目的，而且它发的是 Arp 报文，具有一定的隐秘性，如果占系统资源不是很大，又无防病毒软件监控，一般用户不易察觉。
经抽样测试，学校提供的赛门铁克防病毒软件企业版 10.0 能有效查杀已知的 Arp 欺骗病毒（木马）病毒。恶意软件由于国际上未有明确界定，暂无一款防病毒软件能提供 100%杜绝其发作的解决方案，需要借助某些辅助工具进行清理。 
过上面的分析，可以看出MAC地址为00:25:64:A8:74:AD，IP地址为X.X.200.33的这台办公机中了ARP病毒，将自己伪装成网关，欺骗网段内的其他办公机。对于ARP病毒的处理，只要定位到病毒主机，我们就可以通过ARP专杀工具进行查杀来解决这类问题。而最好的预防办法就是能够在内网主机安装杀毒软件，并且及时的更新病毒库，同时给主机打上安全补丁，防止再次出现。通过上面的分析，可以看出MAC地址为00:25:64:A8:74:AD，IP地址为X.X.200.33的这台办公机中了ARP病毒，将自己伪装成网关，欺骗网段内的其他办公机。对于ARP病毒的处理，只要定位到病毒主机，我们就可以通过ARP专杀工具进行查杀来解决这类问题。而最好的预防办法就是能够在内网主机安装杀毒软件，并且及时的更新病毒库，同时给主机打上安全补丁，防止再次出现。
9.11、网速慢故障排查
线路排查
1、电脑有线检测到光猫延迟
正常情况≤1ms，且持续稳定。 
2、电脑有线检测到路由器延迟
正常情况≤1ms，且持续稳定。 
路由排查
避免使用万能WIFI钥匙
9.12、关于手机远程控制的教程
电脑安装
下载地址 https://www.todesk.com/download.html
手机端
安卓手机 苹果手机
电脑端
9.13、LOID数据整改(一致率修改)
生成流程
数据整改-家客小区产品清查 
进去工单，导出模板

修改账号数据

导入系统

提交归档
家庭客户产品实例，查看修改后loid

9.14、新系统地址不完整修复
1、提交工单
路径:生产流程-家宽存量业务地址整改 工单标题填入账号:W138888XXXXX 直接提交
2、生成工单、录入资源
我的待办，找到刚刚提交工单，双击。 选择账号和地址 选中当前关联信息 点击修改 修改为正确的地址 
3、提交审核

4、BOSS同步
9.15、新系统修改用户数据配置
基础功能-家客资源-




9.16、关于新浪潮覆盖地址非千兆小区修复操作
非千兆小区 复制二级分光器名称 官渡区西交集团关上小区7栋1单元3楼楼梯口资源点-GJ001/GF022-二级分光器-01
光路查出来一级分光器 
复制一级分光器 
查出来PON口 复制到OLT端口 官渡区008_关上邮政-12F_OLT039_HW_MA5680T(10.192.10.2)-0-15-GPFD-PON4
修复PON口能力 能力同步 地址修复成功 
9.1、和商务操作
9.1.1、电口融合网关只能播放CCTV5
设备只能播放CCTV5的原因是因为设备未收到组播VLAN导致，此问题按照这几个步骤检测
1. 检查设备配置
如果发现配置跟上图不同，请到（管理界面—设备管理---恢复出厂设置---深度恢复出厂设置），再重新配置，按照融合网关H10e-11配置手册V2.0进行配置。
2. 检测43链接是否为下图
进去此界面（WAN协议版本切换成IPv4-----WAN链接列表），如果不对请改正或者恢复出厂重新配置；
1.
如果前面两项都已经检测完成，但是还是有问题，别的房间可以正常播放，只有此房间或者几个房间有问题，把故障设备换到能正常播放的房间，如果还是出问题说明此设备有问题；如果无问题说明跟房间网络有关系
2.
3.如果前面两项检测完成，同时整个酒店都无法正常播放，请联系上层网络及厂家协助处理；
9.1.2、酒店短号业务配置
酒店短号业务配置
1. 数据收集
云PBX厂家开通的短号（酒店房间号）、注册密码、注册服务器地址及端口、代理服务器地址及端口
2. 融合网关接入要求
语音必须接入IMS专网（接在ONU下面透传45VLAN），状态里面3_VOIP_R_VID_45链接会获取到100开头的IP地址，如果未获取请到协调ONU厂家开通
3. 配置
备注：注册服务器地址及端口、代理服务器地址及端口填写云PBX厂商给的；号码、用户名、认证名全部填写短号，认证密码填短号注册密码 
4. 检测状态
配置完成之后，检测语音口状态，注册成功说明业务正常，如失败联系云PBX厂家处理
9.1.3、画面卡在下发零配置界面
1. 电视测检测
1.1 DHCP设置 遥控器进入设置（10086）----网络设置----有线网络设置----DHCP（如果不是，请选择DHCP）
1.2 激活 确认是否已扫码激活机顶盒，如果没有，请先激活再安装
2. 网络测检测（只试用H10e设备）
2.1 透传VLAN 确定FTTB设备是否透传VLAN，如果没有让对应厂家是否透传VLAN
2.2 删除43链接 接在光猫下面的设备确定43链接是否删除，如果没有请到网络里面先删除链接
3. 厂家联系方式
问题还未解决，请联系厂家人员
关乐 18377104654
许吉昌 15887752583
9.2、常用工具
9.2.1、ping
ping
使用方法	说明	举例
直接ping	ping 域名/IP	
ping-t	不间断地ping	
9.2.2、tracert路由追踪
tracert路由追踪
10、案例分享
10.1、关于2022年2月17日海伦国际机顶盒卡顿的处理案例
[TOC]
案例说明
用户2022年1月，反应机顶盒播放卡断，直播慢，换台卡。已经上门三次，更换机顶盒和光猫后，仍未解决，用户升级督办投诉。
现场处理
我方于2022年16日上门为用户处理，用户使用路由器公网接入机顶盒。 现场使用公网和专网直连机顶盒测试，用户播放机顶盒画面均卡顿，且黑屏。
机顶盒获取参数如下:
进入光猫查看，光猫界面192.168.1.1 异常卡顿，且会自动弹出路由器界面。 进入路由器界面，发现路由器网关设置为192.168.1.1 
故障定位
因为机顶盒、路由器均在统一局域网，机顶盒网关为192.168.1.1，因此播放时错误向路由器发起业务请求，导致卡顿，播放异常。
处理结果
更改冲突路由器IP为192.168.10.1 
经验分享
1、业务测试时，务必切断光猫所有无线、网线接入，确保干扰。 2、上门装机时候，应该养成习惯，及时变更路由器网关IP，避免同光猫冲突。 3、询问用户所有接入设备，划分好组网。
故障组网图
# 光猫192.168.1.1
## 1号路由器192.168.3.1
### 机顶盒
### 客厅WIFI
## 2号路由器192.168.1.1
### 1卧室1WIFI
### 2卧室WIFI
处理后组网图
# 光猫192.168.1.1
## 1号路由器192.168.3.1
### 机顶盒
### 客厅WIFI
## 2号路由器192.168.2.1
### 1卧室1WIFI
### 2卧室WIFI
10.2、关于2022年4月13日百富琪.6楼公司用户网络慢处理案例
案例说明:
用户为百富琪6楼公司使用，反应网速慢掉线。
处理情况:
前期铁通处理情况:
反馈是公司使用，现场使用10台电脑，因为用户终端过多，导致网速慢，无法解决。
分公司处理情况:
现场终端:无wifi光猫+tp-link千兆双频WIFI6路由器 现场光衰: 现场测速: 现场ping测: WIFI 5G 
WIFI 2.5G 
处理结果:
1、关闭光猫IPV6 2、关闭路由器IPV6下发 3、和用户解释2.5WIFI和5Gwifi区别，演示测速结果，告知用户WIFI尽量使用5G频段，如后续还存在问题则，则免费提供网线，有线接入。
