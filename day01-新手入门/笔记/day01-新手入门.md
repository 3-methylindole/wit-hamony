# day01 - 新手入门

# 今日目标

- [ ] 了解鸿蒙
  - [ ] 开源的OpenHarmony
  - [ ] 商业版本的OpenHarmony
  - [ ] 硬件互助和资源共享
  - [ ] 一次开发，多端部署
- [ ] 开发工具的安装和使用
  - [ ] window环境
  - [ ] mac环境
- [ ] HelloWorld
  - [ ] 工程目录结构
  - [ ] 模块目录
  - [ ] 相关配置文件



# 一、了解鸿蒙

![img](assets/QQ_1735095264225.png)

## 1.鸿蒙的由来

鸿蒙是由华为自主研发的==国产操作系统==

华为鸿蒙系统（HUWEI Harmony OS），是华为公司2019年8月9号于东莞举行的华为开发者大会(HDC.2019)上正式发布的操作系统。

一款全新的面向全场景的分布式操作系统。创造了一个超级虚拟终端互联世界，将人、设备、场景有机的联系在一起，将消费者在全场景中接触多种终端，实现急速发现、急速连接、硬件互助、资源共享，用合适的设别提供场景体验。



## 2.HarmonyOS 和 OpenHarmony

### 2.1 OpenHarmony 开源的

OpenHarmony  是由开放原子开源基金（OpenAtom  Foundation）孵化及运营的开源项目。

开放原子开源基金会由：华为、阿里、腾讯、百度、新浪、招生银行、360等十家互联网企业共同发起组件的。

目标：面向全场景的分布式操作系统。创造了一个超级虚拟终端互联世界，将人、设备、场景有机的联系在一起，将消费者在全场景中接触多种终端，实现急速发现、急速连接、硬件互助、资源共享，用合适的设别提供场景体验。



如果你对HarmonyOS 底层的技术感兴趣，想了解更多的HarmonyOS 并对它做出共享，那么你选择OpenHarmony，如果要做二次开发，那么可以不必了解OpenHarmony 

### 2.2 商业版的HarmonyOS

HarmonyOS 作为新一代的只能终端操作系统，为不同的设备的智能化、互联和些哦她那个提供了一个统一的语言

HarmonyOS是华为基于OpenHarmony、AOSP等开源项目开发的面向多种全场景设备的商用版本，所以HarmonyOS中包含了OpenHarmony



## 3.鸿蒙学习路线

![](assets/1学习路径.png)

### 北向开发

- 安装ide（DevEcoStudio）
- 学习TypeScript
- 学习ArkTS语言
- 学习ArkUI
- 学习Ability框架
- 项目案例



## 4.鸿蒙特性

### 特性一：硬件互助，资源共享

多种设备之间能够实现硬件互助、资源共享、依赖的关键技术包括、分布式软总线、分布式设备虚拟化、分布式数据管理、分布式任务调度

#### 4.1 分布式软总线

分布式软总线：是手机、平板、只能穿戴设备、智慧屏、车机等分布式设备的通信基座，为设备之间的互联互通提供了统一的分布式通信能力。



应用场景：只能家居、多屏互动课堂

![](assets/2分布式软总线.png)

#### 4.2 分布式设备虚拟化

分布式设别虚拟化平台可以实现不同设备的资源融合、设备管理、数据处理多种设备能共同形成一个超级虚拟终端。

游戏场景：在智慧屏玩游戏，可以将手机虚拟化为遥控器、借助手机的重力传感器、加速传感器、触控能力，为玩家提供更便捷更流畅的游戏体验

![](assets/3分布式设备虚拟化.png)



#### 4.3 分布式数据管理

分布式数据管理是基于分布式软总线的能力，实现应用程序数据和用户数据的分布式管理，用户数据不再于单一物理设别绑定，业务逻辑于数据存储分离、跨设备的数据处理如同本地数据处理一样方便快捷。

协同办公场景：将手机上的文档投屏到智慧屏，在智慧屏上执行翻页、缩放、涂鸦等操作，文档的最新的状态可以在手机上同步显示。

![](assets/4分布式数据管理.png)



#### 4.4 分布式任务调度

分布式任务调度基于分布式软总线、分布式数据管理、分布式Profile等技术特性，构建统一的分布式服务管理（发现、同步、注册、调用）机制，支持对跨设备的应用进行远程启动，远程调用、远程连接以及迁移等操作。



导航场景：如果用户驾车出行，上车前，在手机上规划好路径，上车后，导航自动迁移到机车和车载系音像。下车后导航自动迁移到手机上。

![](assets/5分布式任务调度.png)



#### 4.5 分布式连接能力

分布式连接能力提供了只能终端底层和应用层的连接能力。通过USB接口共享终端部分硬件资源和软件能力

![](assets/6分布式连接能力.png)



### 特性二：一次开发多端部署

HarmonyOS提供了用户程序框架、Ability框架以及UI框架，支持应用开发过程中多终端业务逻辑和界面逻辑进行复用

![](assets/7一次开发，多端部署.png)

### 特性三：统一OS，弹性部署

通过组件化和小型化等涉及方法，支持多种终端设备按需弹性部署。



# 二、DevEcoStudio

> 方舟编译器



## 1.下载

`下载地址：https://developer.huawei.com/consumer/cn/deveco-studio/`

`实际下载地址：https://developer.huawei.com/consumer/cn/download/`



![img](assets/QQ_1735098151308.png)

## 2.安装

![img](assets/QQ_1735098257859.png)

![img](assets/QQ_1735098301185.png)

![img](assets/QQ_1735098319586.png)

![img](assets/QQ_1735098332401.png)

![img](assets/QQ_1735098430679.png)

![img](assets/QQ_1735098512392.png)



> 安装成功后，桌面有个图标

![img](assets/QQ_1735098523793.png)

## 3.认识DevEco Studio界面

![img](assets/QQ_1735107515133.png)

> 进入到IDE后，我们可以看到界面如下。
>
> 界面大致可以分为4个部分：
>
> - 代码编辑区
> - 预览区
> - 工程目录区
> - 通知区

![img](assets/QQ_1735107862447.png)



## 4.新建工程

> 创建一个新的项目

![img](assets/QQ_1735108090213.png)

![img](assets/QQ_1735108182135.png)

![img](assets/QQ_1735108374254.png)

> 等待，最后可以看到

![img](assets/QQ_1735108509525.png)



## 5.预览区设置

![img](assets/QQ_1735108766743.png)

![img](assets/QQ_1735108954433.png)



## 6.模拟器

![img](assets/QQ_1735109091108.png)

![img](assets/QQ_1735109145097.png)

![img](assets/QQ_1735109197634.png)

![img](assets/QQ_1735109249045.png)

![img](assets/QQ_1735109276017.png)

![img](assets/QQ_1735109306220.png)

![img](assets/QQ_1735109370400.png)

## 7.项目在模拟器中运行

![img](assets/QQ_1735109437993.png)

![img](assets/QQ_1735109607304.png)



## 8.修改图标和应用名

![img](assets/QQ_1735109919633.png)

### 8.1 修改图标

![img](assets/QQ_1735110225513.png)

> 修改完成后，重新在模拟器中运行

![img](assets/QQ_1735110273391.png)



### 8.2 修改应用名称

![img](assets/QQ_1735111407042.png)

## 9.工程目录

### 9.1 项目目录结构

![img](assets/QQ_1735111506693.png)

> 目录结构说明：
>
> - AppScope 中存放应用全局所需要的资源文件
>   - element : 主要存放的公共的字符串、布局文件等资源
>   - media : 存放全局公共的多媒体资源文件
> - <font style="color:red;">**entry** </font>是应用的主要模块，存放HarmonyOS应用的代码、资源等等。
> - oh_modules 是工程的依赖包，存放工程的源文件
> - build-profile.json5 是工程级配置信息，包括签名、产品配置等
> - hvigorfile.ts 是工程级编译构建任务脚本，hvigor是基于任务管理机制实现的一款全新的自动化构建工具，主要提供任务注册编排，工程模型管理、配置管理等核心功能
> - oh-package.json5 是工程级依赖配置文件，用于记录引入包的配置信息





### 9.2 模块目录结构

![img](assets/QQ_1735112039249.png)

> 以后我们只会关注entry  >  src 目录
>
> - <font style="color:red;">**main文件夹**</font>
>   - ets： 用于存放arkts代码
>   - resource ： 用于存放多媒体文件及布局文件等
>   - module.json5: 时模块的配置文件
> - mock : 可以放模拟数据
> - ohosTest ：测试相关
> - build-profile.json5 ： 是模块级配置信息，包括编译构建配置项
> - hvigorfile.ts ： 文件时模块级构建脚本
> - oh-package.json5 ： 是模块级依赖配置信息文件



![img](assets/QQ_1735112355313.png)



# 三、页面结构

> 页面的基本结构

![img](assets/QQ_1735113241553.png)

## 1.页面的创建

![img](assets/QQ_1735113319909.png)

![img](assets/QQ_1735113349296.png)







## 2.页面的基本结构(演示)

文档地址：`https://developer.huawei.com/consumer/cn/doc/harmonyos-guides-V5/application-dev-guide-V5`

> 官方网站： `https://developer.huawei.com/`

![img](assets/QQ_1735113602831.png)

> 官方文档地址：`https://developer.huawei.com/consumer/cn/develop/`

![img](assets/QQ_1735113717483.png)

### 2.1 页面的布局

> 布局官方网址：`https://developer.huawei.com/consumer/cn/doc/harmonyos-guides-V5/arkts-build-layout-V5`

#### 2.1.1 线性布局 Column

##### 概述

线性布局（LinearLayout）是开发中最常用的布局，通过线性容器[Row](https://developer.huawei.com/consumer/cn/doc/harmonyos-references-V5/ts-container-row-V5)和[Column](https://developer.huawei.com/consumer/cn/doc/harmonyos-references-V5/ts-container-column-V5)构建。线性布局是其他布局的基础，其子元素在线性方向上（水平方向和垂直方向）依次排列。线性布局的排列方向由所选容器组件决定，Column容器内子元素按照垂直方向排列，Row容器内子元素按照水平方向排列。根据不同的排列方向，开发者可选择使用Row或Column容器创建线性布局。

![img](assets/QQ_1735114482348.png)

##### 基本概念

- 主轴：线性布局容器在布局方向上的轴线，子元素默认沿主轴排列。Row容器主轴为水平方向，Column容器主轴为垂直方向。

  - ![img](assets/QQ_1735115649690.png)

- 交叉轴：垂直于主轴方向的轴线。Row容器交叉轴为垂直方向，Column容器交叉轴为水平方向。

  - ```javascript
    Column({space:0}){
          Text('我爱中国')
          Text('我爱鸿蒙')
          Text('我爱鸿蒙')
          Text('我爱鸿蒙')
          Text('我爱华为')
        }
        //交叉轴方向HorizontalAlign.Start  默认值   HorizontalAlign.Center 居中  HorizontalAlign.End靠右边
        .alignItems(HorizontalAlign.End)
        .height('100%')  //占据整个手机屏幕的高度
        .width('100%') //宽度沾满整个手机屏幕   (设置交叉轴的对齐方式，一定要设置宽度)
    ```

  - 

- 间距：布局子元素的间距。

  - ![img](assets/QQ_1735114873801.png)



完整示例代码

![img](assets/QQ_1735116079367.png)

#### 2.1.2 线性布局 Row

![img](assets/QQ_1735114491903.png)



间距

![img](assets/QQ_1735116274945.png)

主轴

![img](assets/QQ_1735116425900.png)

![img](assets/QQ_1735116397319.png)

交叉轴/侧轴

![img](assets/QQ_1735116529349.png)















