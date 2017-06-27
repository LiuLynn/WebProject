#<center>  Web应用测试 </center>

### <center>14130130317 </center>##
### <center>曹潇 </center>##


###<center> 目  录</center>
#### <center>产品简介	-----------------------------------------------------1.1 
#### <center> 范围	-----------------------------------------------------------1.2
#### <center>测试方法及标准	--------------------------------------------1.3 
#### <center>功能测试	------------------------------------------------1.3.1.1 
#### <center>功能	----------------------------------------------------1.3.1.1.1 
####<center>数据项测试	-------------------------------------------1.3.1.1.2 
####<center>业务测试	------------------------------------------------1.3.1.2 
####<center>压力测试	------------------------------------------------1.3.1.3 
####<center>压力测试说明	----------------------------------------1.3.1.3.1 
####<center>压力测试工具	----------------------------------------1.3.1.3.2 
####<center>压力测试方法及标准	-------------------------------1.3.1.3.3 
####<center>验收测试	------------------------------------------------1.3.1.4 
####<center> 验收测试说明	---------------------------------------1.3.1.4.1
####<center>测试重点及顺序	--------------------------------------------1.4 
####<center> 预测风险	---------------------------------------------------1.4.1
####<center> 测试重点	---------------------------------------------------1.4.2
####<center> 功能测试	-------------------------------------------------1.4.2.1
####<center> 业务测试	----------------------------------------------------1.4.3
####<center> 测试用例及执行	---------------------------------------------1.5
####<center> 文档介绍	------------------------------------------------------1.6
####<center>文档目的	----------------------------------------------------1.6.1 
####<center> 文档范围	----------------------------------------------------1.6.2
####<center> 读者对象	----------------------------------------------------1.6.3
####<center> 功能测试用例	------------------------------------------------1.7
####<center> 被测试对象的介绍	----------------------------------------1.7.1
####<center> 测试范围与目的-------------------------------------------	1.7.2
####<center> 测试环境与测试辅助工具的描述	----------------------1.7.3
####<center> 测试环境	--------------------------------------------------1.7.3.1
####<center> 测试驱动程序设计	-----------------------------------------1.7.4
####<center> 功能测试用例	-----------------------------------------------1.7.5
####<center> 性能测试用例	-------------------------------------------------1.8
####<center> 被测试对象的介绍	-----------------------------------------1.8.1
####<center> 测试范围与目的--------------------------------------------	1.8.2
####<center> 测试环境与测试辅助工具的描述	-----------------------1.8.3
####<center> 测试环境	-------------------------------------------------------1.8.3.1
####<center> 测试辅助工具	---------------------------------------------1.8.3.2
####<center>测试驱动程序的设计	---------------------------------------1.8.4 
####<center>性能测试用例	------------------------------------------------1.8.5 
####<center>链接测试	---------------------------------------------------------1.9
####<center>被测试对象的介绍	-------------------------------------------1.9.1 
####<center>链接测试内容	-------------------------------------------------1.9.2 
####<center>导航测试用例	--------------------------------------------------1.10 
####<center>被测试对象的介绍	------------------------------------------1.10.1 
####<center>测试范围与目的	---------------------------------------------1.10.2 
####<center>测试环境与测试辅助工具的描述	------------------------1.10.3 
####<center>测试环境	----------------------------------------------------1.10.3.1 
####<center> 测试辅助工具	----------------------------------------------1.10.3.2
####<center> 测试驱动程序的设计	----------------------------------------1.10.4
####<center> 导航测试用例	-------------------------------------------------1.10.5
####<center> 兼容性测试用例	-------------------------------------------------1.11
####<center>被测试对象的介绍	--------------------------------------------1.11.1 
####<center> 测试范围与目的	-----------------------------------------------1.11.2
####<center> 测试环境与测试辅助工具的描述	--------------------------1.11.3
####<center> 硬件设备	------------------------------------------------------1.11.3.1
####<center> 软件环境	------------------------------------------------------1.11.3.2
####<center> 测试辅助工具	------------------------------------------------1.11.3.3
####<center> 测试驱动程序的设计	------------------------------------------1.11.4
####<center> 兼容性测试用例	------------------------------------------------1.11.5
####<center> 安全性测试用例	---------------------------------------------------1.12
####<center> 被测试对象的介绍	----------------------------------------------1.12.1
####<center> 测试范围与目的	-------------------------------------------------1.12.2
####<center> 测试环境与测试辅助工具的描述	----------------------------1.12.3
####<center> 测试环境	--------------------------------------------------------1.12.3.1
####<center>测试辅助工具	--------------------------------------------------1.12.3.2 
####<center>测试驱动程序的设计	--------------------------------------------1.12.4 
####<center> 安全性测试用例	--------------------------------------------------1.12.5

#<center> 西电网上商城系统测试 #

##1.1 产品简介

#####西电商城是一个B2C平台,类似京东商城.用户可以在商城进行浏览商品,搜索商品、下单等操作.商家可以在后台系统编辑商品，处理订单等。

##1.2 范围

#### 本测试计划包括：

- 前台用户登录
- 首页商品展示
- 用户资料修改
- 用户浏览商品
- 多种商品分类形式
- 便捷的商品检索功能
- 用户中心功能
- 购物车功能
- 在线订单生成
- 相关商品
- 订单管理功能

##1.3 测试方法及标准

###1.3.1.1 功能测试

#### 1.3.1.1.1 功能

- 分页能不能使用
- 跳转页面能否跳转到预期的页面
- 		 鼠标点击用户名是否能跳到页面
-		 查看用户名是否重名
-		 输入的用户名和密码中下划线是否可以用
-		 IE中的地址栏能不能输入不用登录就可以到下张页面 
-		 能不能输入中文保存到数据库
- 数据库密码是否正确
- 是否能运行起来
- 运行起来的程序是否能关闭
-	     在取数据时候看里面有面有值会不会打印出来空（null）
-		 一个用户不能登录两次
-		 点击修改是否能修改
-		 点击删除是否能删除

#### 1.3.1.1.2 数据项测试

- 字母数字数据项是否能够正确回显，并输入到系统中？
- 图形模式的数据项（如滑动条、按钮）是否正常工作？
- 是否能够识别非法数据？
- 数据输入消息是否可理解？

###1.3.1.2  业务测试

功能测试完成后进行业务测试，业务测试关注的要点是业务流程，及数据流从系统中的一个模块流到另一个模块的过程中的正确性。

###1.3.1.3 压力测试

####1.3.1.3.1 压力测试说明

本次压力测试根据实际情况包含性能测试，重点模拟客户进行多用户测试。压力测试有一条8：2原则。及百分之八十的业务量在百分之二十的时间内输入。例如:正常每天有100条新数据，测试时在两小时内输入80条数据。

####1.3.1.3.2 压力测试工具

####Jmeter

####1.3.1.3.3 压力测试方法及标准


压力测试的方法及标准参考压力测试计划

###1.3.1.4 验收测试

####1.3.1.4.1 验收测试说明

测试组对经过内部单元测试、集成测试和系统测试后的系统所进行的测试，测试用例采用业务流程测试用例。

##1.4 测试重点及顺序

### 1.4.1 预测风险

本次测试过程中，可能出现的风险如下：

- 模块功能的实现情况
- 系统整体功能的实现情况
- 代码的编写质量
- 人员经验以及对软件的熟悉度
- 开发人员、测试人员关于项目约定的执行情况

### 1.4.2 测试重点

#### 1.4.2.1 功能测试

这里仅为测试重点的描述，具体测试方法以及内容请参见测试用例。

##### 4.2.1.1 商品添加

- 在后台界面添加商品名称，价格
- 使用不同的名称添加商品

##### 4.2.1.2 销售界面

- 销售界面中与顾客有关的地方是否已经关联
- 增、删、改功能是否已经实现
- 各列表中显示是否正确

##### 4.2.1.3 产品和价格

- 搜索到的结果是否正确
- 按类别和视图查询是否正确


#####4.2.1.4 联系活动管理
- 浏览窗口是否正确
- 编辑功能是否实现
- 是否根据指定条件搜索
#####4.2.1.5 选择商品的修改
- 选择界面是否可用
- 搜索界面显示是否正确

###1.4.3 业务测试
这里只是描述了业务测试的大概情况，这里的业务测试包含模块之间的关系。


#####4.2.2.1 销售
- 购买时关联到购物车
- 与商品库关联
#####4.2.2.2 订单	
- 订单中可以查看所买商品信息
- 与商品库关联
- 自动生成订单


## 1.5 测试用例及执行

## 1.6文档介绍

###1.6.1 文档目的
本文档的目的在于为执行测试提供用例，指导测试的实施，查找分析缺陷，评估测试质量。
###1.6.2 文档范围
本文档包括了功能测试用例、性能测试用例、导航测试用例、兼容性测试用例、安全性测试用例、链接测试用例。
### 1.6.3 读者对象
测试组成员

##1.7 功能测试用例

###1.7.1 被测试对象的介绍
西电商城是一个B2C平台，类似京东商城。用户可以在商城进行浏览商品，搜索商品、下单等操作。商家可以在后台系统编辑商品，处理订单等。
以下主要是针对西电商城系统的各功能进行测试。
###1.7.2 测试范围与目的
测试范围是测试设计中的各个功能。
测试目的是在于明确系统功能测试的范围，并详细描述测试该系统的功能需求。

###1.7.3 测试环境与测试辅助工具的描述

#### 1.7.3.1测试环境


![](http://i.imgur.com/TGfluya.png)

###1.7.4 测试驱动程序设计

###1.7.5 功能测试用例

![](http://i.imgur.com/NPr3enA.png)

![](http://i.imgur.com/Agd0CN6.png)

![](http://i.imgur.com/S2lyqWC.png)

![](http://i.imgur.com/r1BywqG.png)

![](http://i.imgur.com/kYr7CSb.png)

![](http://i.imgur.com/h3YBKFj.png)

![](http://i.imgur.com/1U8QXeW.png)

![](http://i.imgur.com/HLPuTW1.png)

![](http://i.imgur.com/gLdWtsN.png)

![](http://i.imgur.com/coD6fUX.png)

![](http://i.imgur.com/Q7E4P8I.png)

![](http://i.imgur.com/k4vbgnF.png)

![](http://i.imgur.com/3M4DCx4.png)

![](http://i.imgur.com/QgSPhyD.png)

##1.8 性能测试用例

###1.8.1 被测试对象的介绍

西电商城是一个B2C平台，类似京东商城。用户可以在商城进行浏览商品，搜索商品、下单等操作。商家可以在后台系统编辑商品，处理订单等。

以下主要是针对西电商城系统的各功能进行测试。

### 1.8.2 测试范围与目的

测试范围：需求性能中的各个子内容,包括页面平均响应速度、可容纳同时在线的用户数。
测试目的：在于明确系统性能测试的范围，并详细描述测试该系统的的各性能。

###1.8.3 测试环境与测试辅助工具的描述

#### 1.8.3.1 测试环境

![](http://i.imgur.com/B44BJAw.png)

#### 1.8.3.2 测试辅助工具

自动化测试工具Jmeter

### 1.8.4 测试驱动程序的设计

###1.8.5 性能测试用例

![](http://i.imgur.com/jKY9yU9.png)

![](http://i.imgur.com/QPc2qMi.png)

![](http://i.imgur.com/wTXSF8X.png)

![](http://i.imgur.com/Jy0d4hi.png)

## 1.9 链接测试

### 1.9.1 被测试对象的介绍

西电商城是一个B2C平台，类似京东商城。用户可以在商城进行浏览商品，搜索商品、下单等操作。商家可以在后台系统编辑商品，处理订单等。

以下主要是针对西电商城系统的各功能进行测试。

###1.9.2 链接测试内容 

#####4.2.1 测试所有链接是否按指示的那样确实链接到了该链接的页面                               
#####4.2.2 测试所链接的页面是否存在；                                                       
#####4.2.3 保证Web应用系统上没有孤立的页面(所谓孤立页面是指没有链接指向该页面，只有知道正确的URL地址才能访问)。

##1.10 导航测试用例

###1.10.1 被测试对象的介绍

西电商城是一个B2C平台，类似京东商城。用户可以在商城进行浏览商品，搜索商品、下单等操作。商家可以在后台系统编辑商品，处理订单等。

以下主要是针对西电商城系统的各功能进行测试。

###1.10.2 测试范围与目的

![](http://i.imgur.com/Lfcwh8p.png)

1. 导航是否直观
2. Web系统的主要部分是否可通过主页访问
3. 系统是否需要站点地图、搜索引擎或其他的导航帮助
4. Web应用系统的页面结构、导航、菜单、连接的风格是否一致 
5. Web应用系统导航帮助要尽可能地准确。Web应用系统的层次一旦决定，就要着手测试用户导航功能。

###1.10.3 测试环境与测试辅助工具的描述

####1.10.3.1 测试环境

![](http://i.imgur.com/oV1rVuV.png)

####1.10.3.2 测试辅助工具

###1.10.4 测试驱动程序的设计

###1.10.5 导航测试用例

![](http://i.imgur.com/lLpdANO.png)

![](http://i.imgur.com/F2HKZnE.png)

##1.11 兼容性测试用例 

###1.11.1 被测试对象的介绍

西电商城是一个B2C平台，类似京东商城。用户可以在商城进行浏览商品，搜索商品、下单等操作。商家可以在后台系统编辑商品，处理订单等。

以下主要是针对西电商城系统的各功能进行测试。

###1.11.2 测试范围与目的

1. 操作系统兼容性 
2. 浏览器兼容性 
3. 其它的软件兼容 
4. 硬件兼容 
5. 带宽限制/网络环境兼容性

###1.11.3 测试环境与测试辅助工具的描述

####1.11.3.1 硬件设备


![](http://i.imgur.com/tayRHIW.png)
####1.11.3.2 软件环境

服务器软件环境

操作系统：采用Windows10 Server

Web服务：

数据库：MySQL

客户端软件环境

操作系统：Windows7以上，IE5.5以上（推荐使用IE7.0）

#### 1.11.3.3 测试辅助工具

  Firefox 或者　Microsoft　IE

###1.11.4 测试驱动程序的设计

###1.11.5 兼容性测试用例

![](http://i.imgur.com/2S4Fbbz.png)

##1.12 安全性测试用例

###1.12.1 被测试对象的介绍

西电商城是一个B2C平台，类似京东商城。用户可以在商城进行浏览商品，搜索商品、下单等操作。商家可以在后台系统编辑商品，处理订单等。

以下主要是针对西电商城系统的各功能进行测试。

###1.12.2 测试范围与目的

1. 现在的Web应用系统基本采用先注册，后登陆的方式。因此，必须测试有效和无效的用户名和密码，要注意到是否大小写敏感，可以试多少次的限制等；
2. Web应用系统是否有超时的限制，用户登陆后在一定时间内（例如15分钟）没有点击任何页面，是否需要重新登陆才能正常使用；
3. 为了保证Web应用系统的安全性，需要测试相关信息是否写进了日志文件、是否可追踪；
4. 当使用了安全套接字时，还要测试加密是否正确，检查信息的完整性；
5. 服务器端的脚本常常构成安全漏洞，这些漏洞又常常被黑客利用。所以，还需测试没有经过授权，就不能在服务器端放置和编辑脚本的问题。

###1.12.3 测试环境与测试辅助工具的描述

####1.12.3.1 测试环境
![](http://i.imgur.com/8n68gHc.png)

####1.12.3.2 测试辅助工具

无

###1.12.4 测试驱动程序的设计

### 1.12.5 安全性测试用例

![](http://i.imgur.com/s9GoW2S.png)
