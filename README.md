# [首页查询更多项目](https://github.com/GraduationProject-springboot) 包安装运行


# 0654springboot留守儿童爱心网站--论文

![picture](https://raw.githubusercontent.com/GraduationProject-springboot/.github/main/img/wx.png)

### 点击播放视频 ▼
[![Watch the video](https://i.sstatic.net/Vp2cE.png)](https://www.bilibili.com/video/BV14HerezEwW?p=11)


﻿
**毕业设计**

留守儿童爱心网站



学生姓名 

![](/md/blog.001.png)学    号 

![](/md/blog.002.png)指导教师 

![](/md/blog.003.png)所在学校 

![](/md/blog.004.png)专业名称 

![](/md/blog.005.png)班    级 





摘要

随着留守儿童爱心管理的不断发展，留守儿童爱心网站在现实生活中的使用和普及，留守儿童爱心管理成为近年内出现的一个热门话题，并且能够成为大众广为认可和接受的行为和选择。设计留守儿童爱心网站的目的就是借助计算机让复杂的管理操作变简单，变高效。

留守儿童爱心网站采用了B/S结构，JAVA作为开发语言，数据库采用了B/S结构，Mysql数据库进行开发。该系统包括前台操作，后台由管理员和用户两个部分，一方面，为用户提供首页、宣传新闻、志愿活动、爱心捐赠、个人中心、后台管理等功能；另一方面，为管理员提供首页、个人中心、用户管理、宣传新闻管理、志愿活动管理、爱心捐赠管理、旧物捐赠管理、活动报名管理、系统管理等功能。

**【关键词】**留守儿童爱心；JAVA；B/S结构















#########


Abstract

With the continuous development of love management for left-behind children, the use and popularity of love websites for left-behind children in real life, love management for left-behind children has become a hot topic in recent years, and can become a widely recognized and accepted behavior and choice. The purpose of designing the left-behind children love website is to make the complex management operation simple and efficient with the help of computers.

Left-behind children love website adopts B/S structure, JAVA as development language, B/S structure for database and Mysql database for development. The system includes the front desk operation, the background by the administrator and the user two parts, on the one hand, to provide users with home page, publicity news, volunteer activities, love donation, personal center, background management and other functions; On the other hand, it provides administrators with home page, personal center, user management, publicity and news management, volunteer activity management, love donation management, old things donation management, activity registration management, system management and other functions.

【 Key words 】 Left-behind children love; JAVA; B/S structure





#########

#########



目录

[1引言	1](#_Toc100700191)

[1.1选题的背景	1](#_Toc100700192)

[1.2选题的目的与意义	1](#_Toc100700193)

[1.3研究的主要内容	2](#_Toc100700194)

[2 开发环境和相关技术	3](#_Toc100700195)

[2.1系统的开发环境	3](#_Toc100700196)

[2.2相关技术简介	3](#_Toc100700197)

[2.2.1 B/S结构简介	3](#_Toc100700198)

[2.2.2 Mysql数据库技术	3](#_Toc100700199)

[2.2.3 JAVA语言简介	4](#_Toc100700200)

[2.2.4 SpringBoot框架	4](#_Toc100700201)

[3系统的可行性研究及需求分析	5](#_Toc100700202)

[3.1可行性研究	5](#_Toc100700203)

[3.1.1技术可行性分析	5](#_Toc100700204)

[3.1.2经济可行性分析	5](#_Toc100700205)

[3.1.3运行可行性分析	5](#_Toc100700206)

[3.2 系统现状分析	5](#_Toc100700207)

[3.3功能需求	6](#_Toc100700208)

[3.4系统设计规则与运行环境	6](#_Toc100700209)

[4系统的总体设计及相关技术准备	8](#_Toc100700210)

[4.1总体设计	8](#_Toc100700211)

[4.1.1设计的原则及目标	8](#_Toc100700212)

[4.1.2系统的主要的功能结构	8](#_Toc100700213)

[4.2系统设计	9](#_Toc100700214)

[4.2.1数据表E-R图	9](#_Toc100700215)

[4.2.2 数据库的主要表结构	10](#_Toc100700216)

[5系统的详细设计与实现	16](#_Toc100700217)

[5.1系统功能模块	16](#_Toc100700218)

[5.2管理员功能模块	19](#_Toc100700219)

[5.3用户功能模块	24](#_Toc100700220)

[6系统测试与维护	26](#_Toc100700221)

[6.1测试内容	26](#_Toc100700222)

[6.1.1管理员登录测试	26](#_Toc100700223)

[6.1.2信息测试	26](#_Toc100700224)

[6.1.3项目测试	27](#_Toc100700225)

[6.1.4修改密码测试	27](#_Toc100700226)

[6.1.5其他功能测试	28](#_Toc100700227)

[6.2系统维护	28](#_Toc100700228)

[7 结束语	29](#_Toc100700229)

[参考文献	30](#_Toc100700230)

[致谢	31](#_Toc100700231)


# **1引言**
## 1.1选题的背景
现代社会，由于经济不断发展，旧物捐赠的数量也在不断的增加，人们对留守儿童爱心信息的需求也越来越高。

以往的留守儿童爱心的管理，一般都是纸质文件来管理留守儿童爱心信息，传统的管理方式已经无法满足现代人们的需求；使用留守儿童爱心网站, 首先可以大幅提高留守儿童爱心信息检索，只需输入留守儿童爱心相关信息就能在数秒内反馈想要的结果；其次可存储大量的留守儿童爱心信息，同时留守儿童爱心信息安全性有更高的保障；这些优点大大提高运营效率并节省运营成本。因此，开发留守儿童爱心网站对留守儿童爱心信息进行有效的管理是很必要的，不仅提高了留守儿童爱心管理效率，增加了用户信息安全性，方便及时反馈信息给管理员，增加了与管理员之间的互动交流，更能提高用户的体验强度。

本系统为了数据库结构的灵活性所以打算采用MySQL来设计数据库，而java技术，B/S架构则保证了较高的平台适应性。本文主要介绍了本系统的开发背景，所要完成的功能和开发的过程，主要说明了系统设计的重点、设计思想。
## 1.2选题的目的与意义
本课题的选题目的就是通过各个功能模块的优化组合达到不同的管理细节，最大程度的实现管理的自动化与信息化，使留守儿童爱心信息管理更加清晰，透明，易于操作，便于管理，并且能够自动的检查人工操作的环节，降低留守儿童爱心网站的出错率。留守儿童爱心网站里最大特点就是信息管理，由于留守儿童爱心的信息量比较大，管理的功能种类多且复杂，比如：首页、个人中心、用户管理、宣传新闻管理、志愿活动管理、爱心捐赠管理、旧物捐赠管理、活动报名管理、系统管理等等。在过去传统的留守儿童爱心信息管理中，上述的各种管理工作处理起来是相当的繁琐和复杂。在处理信息的过程中还会出现信息的重复传递或者信息的漏传，因此留守儿童爱心管理有必要引入计算机来管理信息，从而提高管理的效率，提高服务质量。

本系统是为了顺应了时代的变更、留守儿童爱心行业的迅猛发展而设计的，利用互联网的交互性和实时性，为用户提供便利、快捷、舒适的服务，提高服务质量，让用户随时了解系统动态，从而提高维修体验，而管理者也可以轻松管理。该系统具有以下优点：

1. 本系统实时地为用户提供留守儿童爱心信息。用户可以随时登录系统查看信息，每一个信息都真实可靠。
1. 本系统的页面设计简洁明了，用户操作简单方便。
1. 本系统解决了传统留守儿童爱心因为资金费用的问题，节约了在电子商务上投入的资金。同时也为已经建立了电子商务网站的留守儿童爱心，提供了更大的业务空间。
1. 本系统易于更新、成本低廉、可以与用户进行双向的信息交流，可以满足不断更新变化的市场需求，吸引更多的用户。
## 1.3研究的主要内容
本系统主要是设计出留守儿童爱心网站，基于B/S构架，后台数据库采用了Mysql，可以使数据的查询和存储变得更加有效，可以确保留守儿童爱心管理的工作能够正常、高效的进行，从而提高工作的效率。总体的研究内容如下：

1. 系统的界面简洁、明了，方便用户操作。系统大量的使用控件，大大的缩短了代码的长度。系统的大部分的功能能够通过控件来实现，用户可以非常方便的完成各类操作。
1. 系统分前台和后台，可以同时达到管理员和用户的不同需求。系统使用权限包括：管理员和用户两个用户角色。主要功能包括首页、个人中心、用户管理、宣传新闻管理、志愿活动管理、爱心捐赠管理、旧物捐赠管理、活动报名管理、系统管理等。
















# **2 开发环境和相关技术**
## 2.1系统的开发环境
浏览器：IE 8.1（推荐6.0以上）

开发使用语言：JAVA

JDK版本：JDK\_8

数据库管理系统软件：Mysql

运行平台：Windows 7

运行环境：Tomcat8.0
## 2.2相关技术简介
留守儿童爱心网站基于B/S的结构、主要采用JAVA语言开发，使得整个系统变得易于操作、界面简洁、使用安全。测试服务器为Tomcat8.0，结合Mysql数据库开发完成。
### 2.2.1 B/S结构简介
随着系统软件的不断改进和升级，B/S结构产品更为方便的特征体现地十分明显。对于一个中等偏大的来说，如果系统管理员每天要在很多台电脑之间来回查看，不断奔走，那么效率和工作量就会变得很低，但是如果使用了B/S结构，那么管理员只要对服务器进行管理就够了。

B/S结构最大的优点它不需要安装任何的系统，它所有的客户端就只是浏览器，所以只要有一台电脑并且可以上网就可以解决所有问题，客户端可以完全地不用管理员维护。无论使用系统的使用者是什么样的规模，也不管分支有多么的庞大，都不会对维护和升级的工作量造成影响，所有的维护和升级只需要操作服务器。随着B/S结构的不断发展，使用的人也不断增加，从而带动了AJAX技术的发展，和B/S结构一样，它也能在客户端上处理程序，这便缓解了服务器的负担，提高了交互性，而且实现了局部实时刷新。
### 2.2.2 Mysql数据库技术
Mysql是一个全面的，运用集成的商业智能工具提供级的数据管理。Mysql是一个小型的关系型数据库管理系统，它具有成本低、体积小、运行速度快，并且源码是开放的一系列的优点，所以很多中小型网站会选择Mysql作为开发使用的数据库来降低开发成本。

Mysql是现有的运行速度最高效的数据库系统，通过SQL语句可以迅速的查出运行结果，它支持多种操作系统，为JAVA、C等多种编程语言提供API。

Mysql数据库提供了以下好处：

1. 充分利用数据。Mysql可以为业务线、分析应用程序提供安全、可靠的数据库，还能让用户使用报表、分析和数据挖掘等相关的嵌入功能从数据中得到其他有用的信息。
1. 提高生产效率，降低开发成本。SQL的查询算法被优化，查询的速度大大的提高，Mysql可以提供关键的、及时的信息满足各种特定的需求，可以存储超过50000000条记录，不限制同时访问数据库的用户人数。
### 2.2.3 JAVA语言简介
JavaScript是一种网络脚本语言，广泛运用于web应用开发，可以用来添加网页的格式动态效果，该语言不用进行预编译就直接运行，可以直接嵌入HTML语言中，写成js语言，便于结构的分离，支持多种浏览器可以在多平台下运行。它具有三个不同的体系，分别为J2SE、J2EE、J2ME。Java 语言比较容易理解，而且也容易学习和上手，其语法与C语言和C++语言很相似，它可以自动的处理废料，而且不会受到内存的影响。

Java 程序被编译后形成的class 文件，这样就能够实现在多系统中正常运行。Java语言支持多个线程同吋执行，Java程序所需要的类能够动态的或者通过网络被载入到运行环境。Java开发工具支持JavaJDK7\8,开发集成环境IDE为Eclipse。
### 2.2.4 SpringBoot框架
SpringBoot是一个全新开源的轻量级框架。基于Spring4.0设计，其不仅继承了Spring框架原来有的优秀特性，而且还通过简化配置文件来进一步简化了Spring应用的整个搭建以及开发过程。另外在原本的Spring中由于随着项目的扩大导入的jar包数量越来越大，随之出现了jar包版本之间的兼容性问题，而此时SpringBoot通过集成大量的框架使得依赖包的版本冲突，以及引用的不稳定性问题得到了很好的解决。

SpringBoot可以看做是Spring的加强版本，但实质上都是Spring的相关技术，有了这些优秀的开源框架，程序员在开发过程中将事半功倍。







# **3系统的可行性研究及需求分析**
## 3.1可行性研究
### 3.1.1技术可行性分析
经过大学四年的学习，已经掌握了JAVA、Mysql数据库等方面的编程技巧和方法，对于这些技术该有的软硬件配置也是齐全的，能够满足开发的需要。

本留守儿童爱心网站采用的是Mysql作为数据库，可以绝对地保证用户数据的安全；可以与Mysql数据库进行无缝连接。

所以，留守儿童爱心网站在技术上是可以实施的。
### 3.1.2经济可行性分析
本留守儿童爱心网站是作为毕业设计自己开发的，所以产生的费用微乎其微，系统建成之后可能会为今后的留守儿童爱心管理提供便利，并且系统完成之后产生的维护费用也不大。综合计算，所有的开支都不大，所以留守儿童爱心网站在经济上是不存在问题的。
### 3.1.3运行可行性分析
运行可行性是指评价和估计新的系统（即留守儿童爱心网站）给已经存在的系统带来的影响和产生的后果，如工作环境等，还要分析在指定时间内能否按期完成指定的系统开发任务等。

当前，信息化技术已经相当完善，工具之间的整合非常方便。通过框架编程的学习，对框架的使用规则已经掌握，各个功能模块之间的编写、测试和维护，使用Tomcat服务器可以实现系统的B/S结构，所以在运行上是可行的。

综上所述，本留守儿童爱心网站的开发在技术上、经济上和运行上都是完全可行的。
## 3.2 系统现状分析
系统使用用户的数量直接决定了用户信息管理者的工作量，毫无疑问，管理者的工作量较大较繁琐。通过总结出系统当前对用户管理的工作状态得以下分析：

统筹规划，如果系统在信息化管理中不够全面，缺少综合性、系统性、整体性，那不可避免的需要投入大量人力物力来规划整理信息。引入信息化管理方式无疑可以达到节省信息管理成本的目的不仅减少资源浪费还可以使留守儿童爱心信息变得井井有条，成为市场竞争中的一大优势。

要循序渐进，做事不能心急，一步一个脚印，都不可能一步到位，就算信息管理系统也一样，要让系统发挥最大效率还是应该多调研，多听取用户和管理者的意见，并进行必要的统筹规划，有组织有目的地设计系统功能，团结各个部门发挥主观能动性。

(3)信息安全措施不到位

隐私权神圣不可侵犯，这是中华人民共和国宪法赋予我们的权利，人和人都不能侵犯我们的正当权益，而网络用户信息管理存在极大安全隐患，信息泄露的案列不在少数，加强信息安全措施是完善网络信息管理过程中不可避免的一环。

` `(4)资源不能充分共享

资源共享是网络的一大特点，没有共享就没有社交，网络也就失去了他应有的魅力，如果能够实现用户信息共享，无疑对于用户的发展存在不可或缺的帮助。

(5)现有系统可扩展性不高。

如今科学技术发展飞速，随着而来的就是技术更新，那势必会给软件更新带来挑战，因此，系统必须具备良好的开放性和可扩充性，为了不落后于时代，这是必备特色之一。

基于上述分析，留守儿童爱心管理系统应该切合实际，做到确实有效，集体表现为：一是系统能够整理并集合归类用户信息，防止用户信息混乱，难以整理；二是系统要安全稳定，不能泄露用户信息，造成隐私泄露，不仅伤害用户利益更是对经营者名誉的损毁；三是系统要具有良好的开放性，不仅要方便定期的维护维修，更要方便及时增加新功能，保证先进的时代契合性。经过详细的讨论论证，确定系统的总体要求。
## 3.3功能需求
需求分析是指详细的分析要解决的问题，弄清楚要解决的问题的要求，最终达到一个什么样的结果。需求分析的最终任务就是对即将要开发的系统的功能、性能等方面进行定义。

留守儿童爱心网站是一个管理信息系统，为了宣传的需要，为了给用户提供方便快捷的服务，从而设计了留守儿童爱心网站。管理员可以通过这个系统把留守儿童爱心信息发布出去，可以方便用户快速地了解最新动态，用户也可以从中获得多样化的优质服务，促进了和用户之间的沟通。

留守儿童爱心网站的主要包括了管理员和用户两个角色。

a)用户进入系统可以实现首页、个人中心、旧物捐赠管理、活动报名管理等；

b)管理员的主要功能包括首页、个人中心、用户管理、宣传新闻管理、志愿活动管理、爱心捐赠管理、旧物捐赠管理、活动报名管理、系统管理等；
## 3.4系统设计规则与运行环境
软件系统的优劣很大程度上是由系统设计的完善与否决定的。世间万物都必须遵循生老病死的法则，这是大自然的规则不能违反，软件设计也一样需要遵循系统设计规则。因此，在设计过程中必须遵循系统设计规则。

规则如下：

简单性：为了扩大系统使用者的受众面，系统设计应该本着操作越简单约好的原则，这样不仅能提高系统的使用率更能够扩大系统使用面。。

针对性：一个系统针对性越强，所能提供的功能必然越完善，用户体验肯定更好，所以应该明确指定系统针对性。

实用性：实用永远是检验一个系统是否成功的唯一标准，使用的语言再高端，使用的结构再新颖但不能满足用户的要求那就是失败。

运行环境：

本系统是利用B/S结构来开发的，数据库在服务器上进行部署 Mysql即可，其他包括My Eclipse等常规开发程序。






















# **4系统的总体设计及相关技术准备**
## 4.1总体设计
### 4.1.1设计的原则及目标
留守儿童爱心管理的工作量随着信息的不断发展和人们的自动化办公意识的不断增强变得越来越复杂，原有的系统已经满足不了相关工作人员的使用需求。为了解决这一问题，并且方便信息行业实施留守儿童爱心管理的工作，提高工作的效率，有必要利用现有留守儿童爱心行业的资源，开发出更好、更方便的留守儿童爱心网站。

本留守儿童爱心网站是把IT技术用到留守儿童爱心信息的管理中，它具有标准留守儿童爱心网站所具备的现实生活中完整的留守儿童爱心管理过程，完全的实现了虚拟现实。它可以收集和保存用户的信息，真正的实现了节约资源、提高使用效率、处理业务的同时实现了留守儿童爱心网站的功能。

本系统采取的原则有：

a）开发采用的是B/S模式。B/S模式的优点是处理前台与后台时层次分明，并且符合现在大部分用户习惯的网页搜索的方法。

b）运用面向对象的开发与设计思想。只有对系统的整体充分了解才能使用面向对象的技术，通过面向对象的技术可以保证系统的框架，从而使系统更加稳定，提高运行的效率。

c）采用结构化的设计方法。将系统分成各个功能模块，正确的处理模块之间和模块内部的联系以及与数据库的联系，定义各模块之间的内部结构，通过对不同模块的设计和模块与模块之间关系的设计来实现整个系统的功能。

d）系统的界面简单清晰。系统的界面设计简单，方便用户快速的操作使用。
### 4.1.2系统的主要的功能结构
留守儿童爱心网站的主要功能的结构如图4-1所示。

![](/md/blog.006.png)

图4-1网站功能结构图
## 4.2系统设计
### 4.2.1数据表E-R图
E-R图为实体-关系图，本系统的E-R图展现了各个实体之间的关系，在本数据库中，各个实体之间的关系均为多对多的关系，如下图：

志愿活动属性图如图4-2所示。

![](/md/blog.007.png)

图4-2志愿活动实体属性图

爱心捐赠实体属性图如图4-3所示。

![](/md/blog.008.png)

图4-3爱心捐赠实体属性图
### 4.2.2 数据库的主要表结构
表4-1：爱心捐赠

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|juanzengbiaoti|varchar|200|捐赠标题|||
|juanzengneirong|longtext|4294967295|捐赠内容|||
|fabushijian|datetime||发布时间|||
|jigoumingcheng|varchar|200|机构名称|||
|juanzengdidian|varchar|200|捐赠地点|||
|fengmiantupian|varchar|200|封面图片|||
|weixinzhanghao|varchar|200|微信账号|||
|weixinyonghuming|varchar|200|微信用户名|||

表4-2：志愿活动

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|huodongbianhao|varchar|200|活动编号|||
|huodongmingcheng|varchar|200|活动名称|||
|fuwuneirong|longtext|4294967295|服务内容|||
|huodongdidian|varchar|200|活动地点|||
|kaishishijian|date||开始时间|||
|jieshushijian|date||结束时间|||
|huodongtupian|varchar|200|活动图片|||
|lianxifangshi|varchar|200|联系方式|||

表4-3：用户

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|yonghuzhanghao|varchar|200|用户账号|||
|mima|varchar|200|密码|||
|yonghuxingming|varchar|200|用户姓名|||
|xingbie|varchar|200|性别|||
|nianling|varchar|200|年龄|||
|touxiang|varchar|200|头像|||
|yonghushouji|varchar|200|用户手机|||

表4-4：宣传新闻

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|xinwenbiaoti|varchar|200|新闻标题|||
|xinwenneirong|longtext|4294967295|新闻内容|||
|fengmiantupian|varchar|200|封面图片|||
|fabushijian|datetime||发布时间|||
|faburen|varchar|200|发布人|||

表4-5：用户表

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|username|varchar|100|用户名|||
|password|varchar|100|密码|||
|role|varchar|100|角色||管理员|
|addtime|timestamp||新增时间||CURRENT\_TIMESTAMP|

表4-6：token表

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|userid|bigint||用户id|||
|username|varchar|100|用户名|||
|tablename|varchar|100|表名|||
|role|varchar|100|角色|||
|token|varchar|200|密码|||
|addtime|timestamp||新增时间||CURRENT\_TIMESTAMP|
|expiratedtime|timestamp||过期时间||CURRENT\_TIMESTAMP|

表4-7：旧物捐赠

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|juanzengbianhao|varchar|200|捐赠编号|||
|juanzengbiaoti|varchar|200|捐赠标题|||
|juanzengdidian|varchar|200|捐赠地点|||
|wuliudanhao|varchar|200|物流单号|||
|juanzengwupin|varchar|200|捐赠物品|||
|juanzengshijian|datetime||捐赠时间|||
|yonghuzhanghao|varchar|200|用户账号|||
|yonghuxingming|varchar|200|用户姓名|||
|yonghushouji|varchar|200|用户手机|||

表4-8：活动报名

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|baomingbianhao|varchar|200|报名编号|||
|huodongbianhao|varchar|200|活动编号|||
|huodongmingcheng|varchar|200|活动名称|||
|huodongdidian|varchar|200|活动地点|||
|kaishishijian|varchar|200|开始时间|||
|jieshushijian|varchar|200|结束时间|||
|yonghuzhanghao|varchar|200|用户账号|||
|yonghuxingming|varchar|200|用户姓名|||
|yonghushouji|varchar|200|用户手机|||
|baomingshijian|datetime||报名时间|||
|beizhu|varchar|200|备注|||
|sfsh|varchar|200|是否审核||否|
|shhf|longtext|4294967295|审核回复|||

表4-9：宣传新闻评论表

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|refid|bigint||关联表id|||
|userid|bigint||用户id|||
|nickname|varchar|200|用户名|||
|content|longtext|4294967295|评论内容|||
|reply|longtext|4294967295|回复内容|||

表4-10：配置文件

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|name|varchar|100|配置参数名称|||
|value|varchar|100|配置参数值|||









# **5系统的详细设计与实现**
## 5.1系统功能模块
系统首页的主要功能展示了首页、宣传新闻、志愿活动、爱心捐赠、个人中心、后台管理等信息，进行相应操作。运行结果如图5-1所示。

![](/md/blog.009.jpeg)

图5-1 系统首页界面图

宣传新闻，在宣传新闻页面中可以查看新闻标题、发布时间、发布人等内容进行评论或提交等操作，如图5-2所示。

![](/md/blog.010.png)

图5-2宣传新闻界面图

志愿活动，在志愿活动页面可以查看活动名称、活动编号、活动地点、开始时间、结束时间、联系方式等内容进行活动报名等操作；如图5-3所示。

![](/md/blog.011.png)

图5-3志愿活动界面图

爱心捐赠，在爱心捐赠页面中可以查看捐赠标题、发布时间、机构名称、 捐赠地点、微信账号、微信用户名等内容进行捐赠内容等操作，如图5-4所示。

![](/md/blog.012.png)

图5-4爱心捐赠界面图

个人中心，在个人中心页面中通过填写用户账号、密码、用户姓名、性别、年龄、图片、用户手机等内容进行更新信息等操作，如图5-5所示。

![](/md/blog.013.png)

图5-5个人中心界面图

用户注册，在用户注册页面中通过填写用户账号、密码、确认密码、用户姓名、年龄、用户手机等内容进行注册等操作如图5-6所示。

![](/md/blog.013.png)

图5-6用户注册界面图
## 5.2管理员功能模块
管理员进入系统前在登录页面根据要求填写用户名和密码，选择角色等信息，点击登录进行登录操作，如图5-7所示。

![](/md/blog.014.png)

图5-7管理员登录界面图

管理员登录系统后，可以对首页、个人中心、用户管理、宣传新闻管理、志愿活动管理、爱心捐赠管理、旧物捐赠管理、活动报名管理、系统管理等功能进行相应的操作管理，如图5-8所示。

![](/md/blog.015.png)

图5-8管理员功能界面图

用户管理，在用户管理页面可以对索引、用户账号、用户姓名、性别、年龄、头像、用户手机等内容进行详情、修改或删除等操作，如图5-9所示。

![](/md/blog.016.png)

图5-9用户管理界面图

宣传新闻管理，在宣传新闻管理页面可以对索引、新闻标题、封面图片、发布时间、发布人等内容进行详情、查看评论、修改或删除等操作，如图5-10所示。

![](/md/blog.017.png)

图5-10宣传新闻管理界面图

志愿活动管理，在志愿活动管理页面可以对索引、活动编号、活动名称、活动地点、开始时间、结束时间、活动图片、联系方式等内容进行详情、修改或删除等操作，如图5-11所示。

![](/md/blog.018.png)

图5-11志愿活动管理界面图

爱心捐赠管理，在爱心捐赠管理页面可以对索引、捐赠标题、发布时间、机构名称、捐赠地点、封面图片、微信账号、微信用户名等内容进行详情、修改或删除等操作；如图5-12所示。

![](/md/blog.019.png)

图5-12爱心捐赠管理界面图

旧物捐赠管理，在旧物捐赠管理页面可以对索引、捐赠编号、捐赠标题、捐赠地点、物流单号、捐赠物品、捐赠时间、用户账号、用户姓名、用户手机等内容进行详情、修改或删除等操作，如图5-13所示。

![](/md/blog.020.png)

图5-13旧物捐赠管理界面图

活动报名管理，在活动报名管理页面中可以对索引、报名编号、活动编号、活动名称、 活动地点、开始时间、结束时间、用户账号、用户姓名、用户手机、报名时间、备注、审核回复、审核状态、审核等内容进行详情、修改或删除等操作如图5-14所示。

![](/md/blog.021.png)

图5-14活动报名管理界面图

系统管理，在轮播图管理页面中可以对索引、名称、值等内容进行详情或删除等操作，如图5-15所示。

![](/md/blog.022.png)

图5-15系统管理界面图
## 5.3用户功能模块
用户进入系统可以查看首页、个人中心、旧物捐赠管理、活动报名管理等内容，进行详细的操作，如图5-16所示。

![](/md/blog.023.png)

图5-16用户功能界面图

旧物捐赠管理，在旧物捐赠管理页面中可以对索引、捐赠编号、捐赠标题、捐赠地点、物流单号、捐赠物品、捐赠时间、用户账号、用户姓名、用户手机等内容进行详情或删除等操作如图5-17所示。

![](/md/blog.024.png)

图5-17旧物捐赠管理界面图

活动报名管理，在活动报名管理页面中可以对索引、报名编号、活动编号、活动名称、活动地点、开始时间、结束时间、用户账号、用户姓名、用户手机、报名时间、备注、审核回复、审核状态等内容进行详情或删除等操作如图5-18所示。

![](/md/blog.025.png)

图5-18活动报名管理界面图
#########


# **6系统测试与维护**
系统测试是指测试整个系统已经完成的功能模块是否能够达到满足所有的需求的行为。系统测试是保证系统质量和可靠的关键，对设计过程中的系统分析与实现的审查。它是用来检验系统是否达到了需求分析的要求，并且能够找出不满足或者存在问题的地方。
## 6.1测试内容
### 6.1.1管理员登录测试
测试系统的登录模块，可以通过设置不同的用户名和密码，在一定程度上还可以测试是否成功连接数据库，使用管理员账号和密码，测试结果如下表6-1所示。

表6-1 管理员测试用例

|编号|账号|密码|预期结果|实际结果|
| :-: | :-: | :-: | :-: | :-: |
|1|abo|abo|成功登录|成功登录|
|2|abo|123|显示密码输入错误提示信息|显示密码输入错误提示信息|
|3|ado|abo|显示用户名输入错误提示信息|显示用户名输入错误提示信息|
### 6.1.2信息测试
`	`主要测试蛋糕的添加、修改和删除。测试结果如表6-2所示。

表6-2蛋糕信息测试用例

|编号|测试内容|输入说明|输出说明|
| :-: | :-: | :-: | :-: |
|1|添加蛋糕信息|进入网站后台管理中心，点击系统管理中的蛋糕——发布新增，输入蛋糕信息|<p>按“提交数据”按钮后，</p><p>1、 若输入数据正确，则显示操作成功，表示添加成功；</p><p>2、若输入字段错误，则系统跳出提示，确认后重新添加。</p>|
|2|修改蛋糕信息|进入网站后台管理中心，点击系统管理中的蛋糕管理中的修改按钮，输入要修改的蛋糕信息|<p>按“提交数据”按钮后，</p><p>1、若输入数据正确，则显示操作成功，表示修改成功；</p><p>2、若输入字段错误，则系统跳出提示，确认后重新修改。</p>|
|3|删除蛋糕信息|进入网站后台管理中心，点击系统管理中的蛋糕管理，勾选框选择删除的蛋糕|<p>按“删除”链接后，</p><p>直接删除。</p>|
### 6.1.3项目测试
项目信息主要测试添加项目、修改和删除项目。测试结果如表6-3所示。

表6-3信息测试用例

|编号|测试内容|输入说明|输出说明|
| :-: | :-: | :-: | :-: |
|1|添加项目信息|进入网站后台管理中心，点击项目管理——添加项目，输入相关信息|<p>按“提交数据”按钮后，</p><p>1、若输入数据正确，则显示操作成功，表示添加成功；</p><p>2、若输入字段错误，则系统跳出提示，确认后重新添加。</p>|
|2|修改项目信息|进入网站后台管理中心，点击项目管理，点击修改链接，输入要修改的信息|<p>按“提交数据”按钮后，</p><p>1、若输入数据正确，则显示操作成功，表示修改成功；</p><p>2、若输入字段错误，则系统跳出提示，确认后重新修改。</p>|
|3|删除项目信息|进入网站后台管理中心，点击项目管理，点击删除链接|<p>按“删除”链接后，</p><p>直接删除。</p>|
### 6.1.4修改密码测试
修改密码时，按照正常的修改的流程，测试能否实现密码的修改。具体的操作步骤是用管理员的账号和密码正常登录之后，进入系统管理，选择修改登录密码，登录密码要在6-16位，测试结果如表6-4所示。

表6-4 修改密码测试用例

|编号|输入|期望的输出/相应|实际情况|
| :-: | :-: | :-: | :-: |
|1|新密码长度在6到16位之间|密码修改成功|密码修改成功|
|2|新密码长度是16位|密码修改成功|密码修改成功|
|3|新密码长度是6位|密码修改成功|密码修改成功|
|4|不输入旧密码|显示未输入旧密码提示信息|显示未输入旧密码提示信息|
|5|输入错误的旧密码|显示旧密码输入错误提示信息|显示旧密码输入错误提示信息|
|6|新密码输入为空|显示未输入新密码提示信息|显示未输入新密码提示信息|
|7|新密码长度为17位|显示密码长度在6到16之间提示信息|显示密码长度在6到16之间提示信息|
|8|新密码长度为5位|显示密码长度在6到16之间提示信息|显示密码长度在6到16之间提示信息|
### 6.1.5其他功能测试
测试其他各类的功能模块的数据信息的添加，修改和删除等功能，各个模块按照各自的特征需求，使用不同的测试用例对各个功能模块进行完整的功能测试。测试的结果如表6-5所示。

表6-5 系统功能情况测试表

|待测试的功能模块名称|测试结果|备注|
| :-: | :-: | :-: |
|系统管理|通过|操作简单|
|用户管理|通过|操作简单|
|类型管理|通过|操作简单|
|留守儿童爱心信息管理|通过|操作简单|
|订单信息管理|通过|操作简单|
|跟踪服务管理|通过|操作简单|
## 6.2系统维护
对于一个系统来说，完成设计只是一部分，最重要的还是后期的维护。系统维护的好坏决定了系统的生命力。在最初设计留守儿童爱心网站时，就已经考虑了系统维护的问题，所以在设计的过程中，就采用了非常严谨的编写代码的风格，考虑了窗体和控件在实际生活中的应用，操作数据库时也保证了数据的一致性、可靠性和完整性。







# **7 结束语**
本文介绍了留守儿童爱心网站的开发全过程，从选题背景与意义，到开发环境与相关技术简介，到系统的可行性和需求分析，到系统的总体设计，再到系统的详细设计，最后到系统的测试与维护。

通过对系统的设计、代码的编写和系统的测试，系统实现的功能达到了预期的要求。系统各个功能操作简单，方便用户使用。

然而，由于自身水平有限加上时间关系，系统中还是存在许多不足，系统功能上还有要改进的地方，比如说如何让用户能够与管理员实现在线即时交互、如何让用户查看志愿活动、爱心捐赠等等，这些问题的存在可能会给用户带来不便。希望在日后的学习和工作中，能够将这个系统修改得更加完善。











**参考文献**

[1] 柏亚军.JSP编程基础及应用实例集锦.人民邮电出版社，2016

[2] 武延军 黄飞跃.精通JSP编程技术.人民邮电出版社，2017

[3] 薛东.我国电子商务的现状与问题探析.内江科技，2018

[4] 于海霞.电子商务网站的设计与实现.科技资讯，2019

[5] Karl Moss.Java Servlet开发人员指南.清华大学出版社，2016

[6] 陈海山.深入Java Servlet网络编程.清华大学出版社，2018

[7] 蔡剑 景楠.Java Web应用开发.清华大学出版社，2018

[8] 王国辉 牛强.JSP信息系统开发实例精选.机械工业出版社，2017

[9] 赵森.中文SQL Server 2005程序设计教程.冶金工业出版社，2016

[10] liuguoyan. Design and implementation of family financial management. [J/OL]]. Shandong: shandong university. 2018.

[11] zhongliwei.Web version traffic movie violation inquiry system.[J/OL] modern technology manufacturing and equipment.

[12]Dai ma. Web application of SSH2 composite framework based on J2EE architecture. [D] soochow university. 2017.10.01.












**致谢**

时光荏苒，毕业设计论文终于成稿了，这意味着这段求学之旅即将划上圆满的句号，在这条道路上有过梦想，有过失望，有过无奈……此时此刻，感激之情油然而生，需要表达出来，感谢一直以来关心和帮助过我的老师、同学和朋友。

在这次的毕业设计中，首先要衷心地感谢我的指导老师。我的指导老师帮助我解决了很多疑难和困惑，每当我遇到问题时，他都能很有耐心给我讲解，为我解答，还能找出我自己发现不了的问题，并且给我意见和建议，使我能按时完成本次的毕业设计。其次，还要感谢我的同学和朋友，不仅在精神上给我支持和鼓励，而且在设计过程中遇到困难时，也能在知识和技术方面给我帮助。

这次的毕业设计中，不仅提高了技术和理论知识的应用，还提高了自己奋发向上的学习精神。在以后的学习和工作道路上，我依然会继续努力，争取做出更大的成果。最后，再次感谢我的老师，同学，还有在设计中给过我帮助的人。









37
![](/md/blog.026.png)











