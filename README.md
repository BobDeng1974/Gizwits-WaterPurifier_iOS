机智云智能净水器
=============

	此公版开源App已不再维护，机智云推出了物联开源框架，并提供了其他开源案例供参考。机智云公版开源App项目地址：

	机智云物联开源框架iOS项目 https://github.com/gizwits/GizOpenSource_AppKit_iOS
	机智云智能灯2代iOS项目 https://github.com/gizwits/Gizwits-SmartBuld_iOS
	机智云Gokit的iOS项目 https://github.com/gizwits/gokit-ios
	机智云Gokit的APICloud项目 https://github.com/gizwits/gokit_demo_in_apicloud

	我们在机智云社区、QQ群提供技术支持，意见反馈渠道。机智云社区网址：http://club.gizwits.com/forum.php

	QQ群：
	G1机智云物联网云服务 104975951
	G2机智云物联网云服务 491509598
	G3机智云物联网云服务 287087942

	意见反馈：http://form.mikecrm.com/s1ZJxj

Gizwits Water Purifier iOS Demo App

	▪这是一款使用XPGWifiSDK的开源代码示例APP，可以帮助开发者快速入手，使用XPGWifiSDK开发连接机智云的物联APP。
	▪该APP针对的是智能家电中的净水器类产品。

使用说明

    使用机智云开源APP之前，需要先在机智云开发平台创建您自己的产品和应用。
    开源App需要使用您申请的AppId、AppSecret以及您自己的产品ProductKey才能正常运行。
    具体申请流程请参见：http://docs.gizwits.com/hc/。
    上述信息申请好之后，在代码中请找到"your_app_id"、"your_app_secret"、"your_product_key"字符串做相应的替换。

功能介绍

    Gizwits Water Purifier 主要展示如何使用XPGWifiSDK，开发智能净水器。项目中用到了大部分主要SDK接口，供使用XPGWifiSDK的开发者参
    考。主要功能如下：

	1.净水器电源的开关
	2.净水器净水模式和冲洗模式的切换
	3.净水器滤芯寿命重置
	4.净水器滤芯寿命获取
	5.净水器异常报警

	▪如果开发者希望开发的设备与以上功能类似，可参考或直接使用该APP进行修改进行快速开发自己的智能家电App。

	▪以下功能是机智云开源App的几个通用功能，除UI有些许差异外，流程和代码都几乎一致：

	1.机智云账户系统的注册、登陆、修改密码、注销等功能
	2.机智云设备管理系统的AirLink配置入网、SoftAP配置入网，设备与账号绑定、解绑定，修改设备别名等功能
	3.机智云设备的登陆，控制指令发送，状态接收，设备连接断开等功能

	▪另外，因为该项目并没有相对应的实体硬件设备供开发者使用，因此还提供了扫描虚拟设备功能，通过扫描机智云实验室内相对应的虚拟设备，可进行设备的绑定和控制等功能。同时可免费申请gokit进行设备的配置入网和绑定等流程。

项目依赖和安装

	下载代码后可直接编译运行。如果需要更新 XPGWifiSDK，请自行替换官方网站的最新版本。

硬件依赖

    Gizwits Light 项目调试，需要有调试设备的支持，您可以使用虚拟设备或者实体设备搭建调试环境。

	▪	虚拟设备
        机智云官网提供GoKit虚拟设备的支持，链接地址：
        http://site.gizwits.com/zh-cn/developer/product/6814/virtualdevice

	▪	实体设备
        GoKit开发板。您可以在机智云官方网站上免费预约申请（限量10000台），申请地址：
        http://gizwits.com/zh-cn/gokit
        
    GoKit开发板提供MCU开源代码供智能硬件设计者参考，请去此处下载：https://github.com/gizwits/gokit-mcu

问题反馈

	您可以给机智云的技术支持人员发送邮件，反馈您在使用过程中遇到的任何问题。
	邮箱：club@gizwits.com
