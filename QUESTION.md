# 课堂问题汇总

## 一、github(1) 2017/5/4

> ### 1、github是什么？
    GitHub是全球最大的社交编程及代码托管网站
	是it技术人员的一个社交网站
	
> ### 2、git是什么？
    是一款免费、开元的分布式版本控制系统，用于敏捷高效地处理任何或大或小的项目
	git本身就是一个版本控制系统，github就是用git做的控制。
	
> ### 3、学习github的5个理由
	①有很多很厉害的技术人员，称大牛，比如百度、阿里等等。
	②可以接触到最新和最前沿的IT技术，我们可以接触到这些软件的初始、中间以及最终状态，可以第一时间了解到软件产品的发展动向，同时能够清楚地了解到时下最火热最具有发展力的技术。
	③我们可以学到开发语言、项目流程、设计思想、编码规范等等，同时可以记录我们技术的发展，像社交网站中的一个时间轴，我们可以随时去看自己的学习历程以及积累，有时还会发现自己的不足之处，进而改正进步。
	④github是一个开源的，所有项目的代码文档对我们都是开放的。在上面我们可以找到一些项目参与其中，增加自己的项目实战经验，为以后找工作和做项目做铺垫。
	⑤在github上有一些教程，我们可以进行学习，优质的学习资源非常丰富。

> ### 4、github的优势
    ①GitHub 只支持 Git 格式的版本库托管，而不像其他开源项目托管平台还对CVS、SVN、Hg 等格式的版本库进行托管。
	②GitHub 对 Git 版本库提供了完整的协议支持，支持 HTTP 智能协议、Git-daemon、SSH 协议。
    ③GitHub 提供在线编辑文件的功能，不熟悉 Git 的用户也可以直接通过浏览器修改版本库里的文件。
    ④将社交网络引入项目托管平台是 GitHub 的创举。用户可以关注项目、关注其他用户进而了解项目和开发者动态。
    ⑤项目的 Fork 和 Pull Request 构成 GitHub最独具一格的工作模式。对提交代码的逐行评注及 Pull Request构成 GitHub 特色的代码审核。
    ⑥itHub 通过私有版本库托管、面向企业的版本库托管和项目管理平台、人员招聘等付费服务获得了商业上的成功，这种成功使得 GitHub不必以页面中嵌入广告的方式维持运营，最大的受益者还是用户。
	
> ### 5、通过github年度报告让你记忆最深刻的信息有哪些
	github有超过580多万的活跃用户，33.1 万活跃组织。受欢迎程度：js是第一，java第二，Python第三。新注册成长最多的国家是中国，相比于去年同期增长97%

> ### 6、github上有可以个人账号 还可以有（ ）账号
    组织

> ### 7、github上面的两个组成要素是什么
    组织、个人和仓库

> ### 8、github上两个重要页面
    个人主页和数字仪表板

> ### 9、主页菜单都包含什么
    收藏、概述、仓库、关注，被关注

> ### 10、仓库的心跳线代表什么
    仓库更新的活跃程度

> ### 11、star的作用是？
    star 的作用是收藏，目的是方便以后查找

> ### 12、fork的作用是？
    当选择 fork，相当于你自己有了一份原项目的拷贝。参与项目，可以将代码拽到本地。

> ### 13、watch的作用是？
    更新会发送提示。

> ### 14、搜索结果分别有哪些类别
    repositories（仓库）、code（代码）、commits（提交）、siiues（）、wikis（）、users（）

> ### 15、你在github上挖到什么宝
    发现微信抢红包bug的代码

## 二、github(2) 2017/5/4

> ### 1、个人主页上的“+”下拉菜单可创建的四种类别分别有？分别的意思？
    new repository       创建一个新的仓库
    import repository    导入存储库
    new gist             新要点
    new organization     新组织


> ### 2、如何能将仓库中的html文件直接解析成页面？
    从仓库的settings的GitHub pages 直接点开页面

> ### 3、如何删除仓库
    settings里面有一个delete this repository

> ### 4、Bash是什么操作系统的命令
    linux

> ### 5、Pwd是什么命令
    显示当前文件夹

> ### 6、Cd是什么命令
    修改成什么文件夹

> ### 7、Echo是什么命令
    输出

> ### 8、配置git用户名的命令
    git config user.name 你的目标用户名;

> ### 9、配置邮箱的命令
    git config user.email 你的目标邮箱名;

> ### 10、命令行换行方式
    \n

> ### 11、命令行终结方式
    Ctrl+c+z

> ### 12、使用命令行比GUI方式有何优势
    复杂的命令使用批处理来工作，所有复杂的命令都可以用，GUI部分不能用

> ### 13、提交到本地仓库时为什么有暂存区
    从仓库撤销一些提交时，更加方便区分提交和管理

> ### 14、新建代码仓库的命令
    git init

> ### 15、git clone [url] 这个命令的作用是
    克隆一个仓库

> ### 16、添加指定文件到暂存区的命令
    git add

> ### 17、删除工作区文件，并且将这次删除放入暂存区的命令
    git rm 

> ### 18、改名文件，并且将这个改名文件放入暂存区的命令
    git mv

> ### 19、提交暂存区到仓库的命令
    git commit -m

> ### 20、直接从工作区提交到仓库的命令
    git commit -a -m

> ### 21、显示变更信息的命令
    git status

> ### 22、查看历史信息的命令
    git log

> ### 23、Commit的意义是
    提交到本地仓库

> ### 24、Pull的意义是
    取回远程仓库的变化，并与本地分支合并

> ### 25、Push的意义是
    将本地仓库中文件推到远程仓库上

## 三、MarkDown 2017/5/8

> ### 1、MarkDown是什么？
    Markdown是一种可以使用普通文本编辑器编写的标记语言，通过简单的标记语法，它可以使普通文本内容具有一定的格式。
    通常是在web端使用的文本到html的转换工具，可以通过简单、易读易写的文本格式生成结构化的html文档
    后缀名为.md，

> ### 2、MarkDown的特点？
    兼容html，在线观看、平台支持、排版样式简单
    语法简洁明了、语法简单、易读易写，能够直接阅读、而且功能比纯文本更强

> ### 3、MarkDown的用途？
    ①可用于编写说明文档，并且以README.MD文件名保存在软件的目录下面
    ②可转化为演讲PPT、word产品文档、LaTex论文等

> ### 4、MarkDown的编辑工具有哪些？
    Web(在线)：GitHub、markable.in、有道云
    Windows：Atom、MarkdownPad、Miu、Typora、Rstudio
    Linux：Atom、ReText、UberWriter、Rstudio
    OSX：Atom、Byword、Mou、Typora、MacDown、RStudio
    IOS：Mou

> ### 5、MarkDown的区块元素和区段元素分别包含哪些？
    区段元素：连接、强调、代码、图片
    区块元素：段落与换行、标题(#或者=、-)、区块引用(>)、列表、代码区块、分割线

## 四、UI设计 2017/5/11

> ## 一、设计基础
> ### 1、什么是设计？
    有目的地策划

> ### 2、哪些属于设计范畴：
    平面设计、软件设计(架构)、工业设计、概念设计、产品设计...

> ### 3、用户界面（UI）设计是什么？
    在任何机器的互动过程中，有一个层面，即我们说的界面，针对这个界面进行设计

> ### 4、界面设计三大原则
    ①置界面于用户的控制之下；
    ②减少用户的记忆负担；
    ③保持界面的一致性.
    
> ### 5、用户界面设计的组成部分
    结构设计(概念设计)、交互设计、视觉设计

> ### 6、结构设计的分类
    网页结构设计、系统结构设计

> ### 7、什么是交互设计
    是定义、设计人造系统的行为的设计领域，它定义了两个或多个互动的个体之间交流的内容和结构，使之互相配合，共同达成某种目的

> ### 8、用户界面（UI）设计工作流程
    需求调研、模块分析、结构设计、交互设计、视觉设计、界面级源代码、维护和测试

> ### 9、用户界面（UI）设计的发展方向
    交互设计师、视觉设计师、系统构架师、测试工程师

>## 二、UI设计常识

> ### 1、UI是哪两个单词的简称
    User Inerface 用户界面

> ### 2、什么是VI系统
    Visual Identity，企业视觉识别系统，是企业文化宣传的重要组成部分。
    (VI>UI)

> ### 3、VI设计原则包括？
    同一性、差异性、文化性、有效性

> ### 4、VI系统包含哪两部分
    ① 基本要素系统：标志、标准字、标准色、标志和标准字的组合
    ② 应用系统：企业网站、办公用具、企业外部建筑环境、企业内部建筑环境、交通工具、服装服饰、广告媒体、产品包装、公务礼品、陈列展示、印刷品

> ### 5、对于logo的合法的两种更改
    等比例缩放、颜色调为黑白色

> ### 6、色彩模式有哪两种
    ①RGB模式（色光结合）：适用于显示器、投影仪、扫描仪、数码相机...
    ②CMYK模式（颜料结合）：适用于打印机、印刷机...

> ### 7、图片格式有哪两种？
    ① 位图：使用像素的一格一格的小点来描述图像
    ② 矢量图：使用线段和曲线描述图像，所以称为矢量，同时图形也包含了色彩和位置信息

> ### 8、两种图片格式的特点是？
    位图：不可无限放大
    矢量图：可损耗无限放大

> ### 9、两种图片格式分别常用的扩展名为？
    位图：*.jpg *.gif *.png
    矢量图：*.ai *.eps *.cdr 

> ### 10、可用性设计体现在哪三个方面
    内容布局、使用人性化、美观

> ### 11、常用到的网络资源有
    图片、小图标、文字、代码、音乐、动画、其他

> ### 12、客户交流时的注意事项
    你永远比客户专业、永远要保持礼貌、要让用户知道你做了哪些工作

>## 三、UI设计流程

> ### 1、前期需求阶段，UI设计所需要考虑的四个问题
    需求分析、栏目排版、色彩搭配、风格设计

> ### 2、UI设计在需求分析阶段需要注意的问题？
    网站制作目标、网站所处行业、网站包含内容、网站使用人群

> ### 3、在栏目排版时，首页内容通常包含哪些部分？
    主题栏：包括logo、banner
    更新栏：新闻内容、信息等
    指南栏：导航条、搜索栏、网站地图等
	交流栏：网站统计、留言板等
	广告栏：广告发布

> ### 4、色彩搭配时需要注意的问题
    选择主色调、考虑行业色、主色调与其他色搭配

> ### 5、中期设计阶段需要做的工作有哪些？
    设计工具选择
    设计制作
    布局方式
    样式定义
    交流沟通

> ### 6、设计效果图时需注意的问题？
    ① 尽量多用可循环较小的背景图，少用整张大图
    ② 尽量多用填充色，少用照片
	③ 尽量多用系统字体，少用特殊字体
    ④ 大面积使用的颜色尽量不超过3个色系

> ### 7、前端页面的设计中，html、css和javascript分别的作用是？
    html：控制结构
    css:控制样式
    javasript:控制行为
    
## 五、UI设计(WEB) 2017/5/15
>## 一
> ### 1、网页设计包含哪三方面
    页面规划、页面元素、页面交互

> ### 2、页面规划包含哪三方面
    尺寸、栏目、布局

> ### 3、页面规划的尺寸为设计系统界面设计，取决于？
    用户使用的显示设备

> ### 4、自动适应占满所有宽度空间，一般用于？
    应用在后台的管理

> ### 5、栏目设计包含哪两部分
    确定栏目内容、确定栏目格式

> ### 6、栏目内容分为几部分，分别是什么？简述
    顶部：网站的脸，含有特征元素，含有能与其他网站相区别的信息
	    logo、导航栏、banner、搜索栏、注册登录入口、辅助栏目
    正文：网页的躯干，包含网页需要显示的大部分内容
	    内容搜索、内容更新、互动栏目、用户登录、快速导航、广告、其他
    底部：网页的脚，包含网页的版权、审批、声明等信息及辅助栏目
	    辅助栏目、版权信息、其他

> ### 7、页面顶部一般都包含哪三部分
    logo、导航栏、banner (通常只有这三个部分)

> ### 8、确定栏目形式的宗旨为？
    要很好的表达出来栏目的功能，体现出来栏目想展示的东西
    
> ## 二

> ### 1、浏览网页时，一般遵循（）-型的视觉路线
    F：从左到右，从上到下重要性依次减小

> ### 2、通常在做页面设计之前，会做____。
    页面原型图

> ### 3、简述页面原型图
    标注出在哪里实现什么样的功能，不用具体到页面效果图的效果
    
> ### 4、色彩基本上可以分为（）个色系
    七个

> ### 5、简述7个色系。
    红色系：多用于政府、婚庆、餐饮等网站
    橙色系：多用于家具、动漫、儿童用品等网站
    黄色系：多用于商业、金融等网站
    绿色系：多用于医疗、农业、保险等网站
    蓝色系：多用于科技、电器、信息等网站
    紫色系：多用于美容、女性等网站
    黑白色系：多与其他颜色混合使用

> ### 6、简述配色忌讳
    忌脏：背景与文字内容对比不强烈，灰暗的色彩令人沮丧
    忌纯：艳丽的村色对人的刺激太强烈，缺乏内涵
    忌跳：再好看的颜色，也不能脱离整体
    忌花：要有一种主色贯穿其中，主色并不是面积最大的颜色，而是最主要的，最 能揭示和反应主题的颜色
    忌素：颜色浅固然显得干净，但如果对比过弱，整的苍白无力了
    蓝色忌纯，绿色忌黄，红色忌艳丽

> ## 三
> ### 1、简述网页设计风格
    欧美风格：欧美国家惯用的设计风格，一类简洁明了、色彩单一；一类构图复杂，色彩浓烈
    韩国风格：韩国惯用的界面设计，色彩清爽、多用蓝、绿色、多用大图片、渐变色、人物和卡通矢量图
    中国风格：具有中国古典风格的设计，古香古色，以具有中国特色的花纹或图案来装饰
    web2.0风格：简单设计、大面积留白和更少的内容、更大和更多样的标题文字、醒目简洁的logo...
    扁平化风格：核心意义：去除冗余、厚重和繁杂的装饰效果去掉特效、极简的元素、有意义的图标、更多圆角、中性的颜色、鲜明的对比、简洁的字体、善用灰色

> ### 2、LOGO的细节要求？
    不允许：随意变色、拉伸、模糊、更改 
    允许的：等比例缩放、反白

> ### 3、图片选取的细节要求？
    不可模糊、变形、质量低下、带背景色

> ## 四

> ### 1、交互三要素？
    统一、醒目、便利

> ### 2、统一指哪些方面？
    风格、导航、操作

> ### 3、风格指哪些方面
    颜色、图标和整个设计的样式、版式有统一的风格

> ### 4、导航的统一指的是哪些方面的统一？
    设计样式，摆放位置，内容

> ### 5、醒目主要指的哪三方面？
    文字、信息、功能

> ## 五

> ### 1、便利性可从几点讨论？
    导航、搜索、文字、指示标与面包屑、 反馈信息、控件、扩展和维护、广告	

> ### 2、搜索文本框中要有
    搜索的提示

> ### 3、放在（ ）的内容一定要是最能吸引人的、最有特色的
    首页

> ### 4、指示标是？其作用？
    当前访问的那个栏目，告诉用户当前访问的栏目

> ### 5、什么是面包屑？面包屑的作用：
    除了首页外每个子页都应该有的指示性路径，指示路径

> ### 6、什么是级联菜单？
    是指有多个层级的菜单，每个级别的菜单，有与之相关联的子级菜单。

> ### 7、级联联菜单的好处？
    进行信息栏目筛选能够清晰地获取信息(JAVA、ajax)

> ## 六

> ### 1、好的网页的标准?
    这是什么网站？
    网站上有什么？
    我能在这个网站上做什么？
    为什么我还应该在这里？

> ### 2、合格的网页是什么，具有哪些特点？
    美观舒适的风格、高效的导航、符合大众习惯的布局、简洁的操作、及时的反馈、明确的标注和指示、拥有吸引人的元素、良好的可维护性和可扩展性

> ### 3、（ ）是设计时最为用心的地方，把网页很好的连接起来，用户使用起来会更加方便.
    导航栏

> ### 4、举出几个有关网页设计的网站：
    优设网、Icon搜索、站酷、黄蜂网、花瓣网