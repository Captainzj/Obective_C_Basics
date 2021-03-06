### 一、学前须知

#### 1. 课程内容

- 应用
- 游戏

#### 2. 一款app立足的两大要素

- 美观的UI界面
- 实用的功能

#### 3. 课程顺序

- UI：基础\高级控件等
- 功能：数据\动画\事件\网络等
- 游戏：cocos2d-x，cocos2d（这里要说明cocos2d只能使用在iPhone上，而cocos2d-x可以跨平台 ）

### 二、 开发的准备

- Objective-C
- Xcode
- 真机调试设备(可选)
- 调试\发布证书(可选)

### 三、关于开发者证书

如果你有好的想法，你又想将这个软件做出来并发布到网络上，那么你可以有一个开发者账号，需求就在这里，这个需要钱的，你必须考虑清楚

需求的问题在于你自己

### 四、IOS系统架构

 ios系统架构分为四个部分：

- 核心系统层（Core OS）:它包括内存管理，文件系统，电源管理
- 媒体层（Medio）：它包括声音，视频，图形绘制，动画特性
- 核心服务层（Core Service）：它包括网络，数据库，定位
- 可触摸层（Cocoa Touch）：它包括界面和各种框架

### 五、Cocoa Touch重要的框架

Cocoa Touch中最重要的一个框架就是UIKit,它是涉及到可视化组件(控件、视图)的重要框架

### 六、IOS中自带的各种框架

IOS中自带很多种框架，我们这里不想提，用到了我们就去研究它

| 框架名称                | 功能                                    |
| ------------------- | ------------------------------------- |
| Foundation          | 提供OC的基础类(例NSObject)、基本数据类型等           |
| UIKit               | 创建和管理应用程序的用户界面                        |
| QuartzCore          | 提供动画特效以及通过硬件进行渲染的能力                   |
| CoreGraphics        | 提供2D绘制的基于C的API                        |
| SystemConfiguration | 检测当前网络是否可用和硬件设备状态                     |
| AVFoundation        | 提供音频录制和回放的底层API，同时负责管理音频硬件            |
| CFNetwork           | 访问和配置网络，像HTTP、FTP和Bonjour Services    |
| CoreFoundation      | 提供抽象的常用数据类型，如Unicode strings、XML、URL等 |
| CoreLocation        | 使用GPS和WIFI获取位置信息                      |

| 框架名称          | 功能                         |
| ------------- | -------------------------- |
| GameKit       | 为游戏提供网络功能：点对点互联和游戏中的语音交流   |
| AddressBook   | 提供访问用户联系人信息的功能             |
| AddressBookUI | 提供一个用户界面，显示存储在地址簿中的联系人信息   |
| AudioToolBox  | 提供音频录制和回放的底层API，同时负责管理音频硬件 |
| AudioUnit     | 提供一个接口，让应用程序可以对音频进行处理      |
| MapKit        | 为应用程序提供一个内嵌地图的接口           |
| MediaPlayer   | 提供播放视频和音频的功能               |
| MessageUI     | 提供视图控制接口用以处理E-mail和短信      |
| OpenGLES      | 提供动画特效以及通过硬件进行渲染的能力        |
| StoreKit      | 为应用程序提供在程序运行中消费的支持         |

### 七、IOS系统和Adroid系统对比

- Adroid系统基于Linux内核设计的,在Linux内核上运行了一个Java虚拟机，虚拟机再运行软件，所以运行效率不好，很占内存，现在也有基于C++开发的Adroid
- IOS系统基于UNIX的，直接与底层硬件通信。系统底层、应用框架、应用软件都是采用C\C++\Objective-C写的，有很高的运行效率