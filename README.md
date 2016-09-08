# Lab-0

> `重要` **机房守则** 
>
> **1. 食物请勿带入机房。**
>
> **2. 遇到机器故障，请联系机房管理员或者助教。**
>
> 请加入此QQ群 进群后改名为 姓名+学号尾号
>![image](https://cloud.githubusercontent.com/assets/6169077/18339078/f9eac3e8-75cf-11e6-8afe-63288628784d.png)
>
>
> 本次 Lab 目标
>
> 1. 了解开发基础知识
> 2. 熟悉编程相关软件
> 3. 编写一个简单的 Java 程序
> 

##目录

[1. 创建一个自己的文件夹](#1)  
[2. 学习使用软件学院FTP](#2)  
[3. 注册github账号](#3)  
[4. 下载安装JAVA1.8并配置环境变量](#4)  
[5. JAVA编辑器介绍](#5)  
[6. 写一个JAVA小程序](#6)  



<h2 id='1'>第一步 创建一个自己的文件夹</h2>
请在机房电脑的D盘下创建一个以自己学号为名的文件夹。 例如：16302010001  
`注意`  **保存在机房C盘的文件重启后会丢失，因此所有内容务必保存在D盘。** 

<h2 id='2'>第二步 学习使用软件学院 FTP 站点</h2>
FTP 站点类似于云盘，我们可以对 FTP 站点进行文件的上传、下载操作。软件学院的 FTP 上有往届所有专业课程的课程资料，我们主要使用 FTP 提交每次 lab 和期中期末两次 Project。

###进入FTP
打开我的电脑，在地址栏输入 ftp://10.132.141.33  

![1x](https://cloud.githubusercontent.com/assets/6169077/18310556/a7004386-7531-11e6-99c0-4918f8976bfe.png)

在弹出的对话框里输入账号密码 —— 用户名：`ss`  密码：`ss`  

![2x](https://cloud.githubusercontent.com/assets/6169077/18310598/e8c0b68e-7531-11e6-99ee-553068fe883b.png)

进入 `class/16/程序设计（陈荣华）`，课程相关的文件会放置在此文件夹下，每次 lab 和 project 做好后需要您上传到 work_upload 文件夹下对应的目录中。  
`注意` **提交作业时请按  `学号_姓名`  的格式修改文件名称， 例如  `16302010001_XXX`**

`注意`  **作业上传后无法删除或者修改，若需要更改请换个名字再上传一份 例如 `16302010001_XXX修改版`** 

需要从FTP获取文件时，复制此文件，粘贴到你的电脑上等待下载完成即可。  
向FTP某文件夹上传文件时，请复制本地你要上传的文件，粘贴在对应文件夹下等待上传即可。  

`注意` **该 FTP 站点非校园网无法访问（例如南区宿舍、张江校区宿舍、校外网络、4G网络）。**

<h2 id='3'>第三步 注册 github 账号</h2>

### GitHub是什么

一言以蔽之，Github 是用于保存和分享代码的平台。

`扩展阅读` 当我们在编写程序时，我们往往和其他人一起协作，共同完成一个软件的开发。对于大型软件来说，团队中成员之间的协作及代码的版本管理变得尤为重要。GitHub就是这样一个提供了版本控制的代码托管网站。也就是说，你可以将一个项目的代码储存在GitHub的一个仓库中，并允许别人与你共同开发这个项目。除此之外，它也提供了一些方便社会化软件开发的功能，包括允许用户追踪其他用户、组织、软件库的动态，对软件代码的改动和bug提出评论等。GitHub也提供了图表功能，用于显示开发者们怎样在代码库上工作以及软件的开发活跃程度。截止到2015年，GitHub已经有超过九百万注册用户和2110万代码库。事实上已经成为了世界上最大的代码存放网站和开源社区。

### 我们使用GitHub做什么

目前，我们使用GitHub来：

- 发布课程作业
- 开展交流讨论  

**课程的 Github 地址**：https://github.com/java-b

- 每个布置的Lab（上机作业）和Project都会拥有一个单独的项目仓库。以这个Lab为例，它的主页为：https://github.com/java-b/Lab-0
- 在课程的 [讨论区](https://github.com/java-b/Forum) 中，你可以找到一些课程的推荐阅读，也可以提问、交流。助教看到问题之后将会第一时间回复。
`注意` **课程成绩中的平时分与讨论活跃度相关。**   

### 如何使用GitHub

注册GitHub账号：

1. 访问 https://github.com 
2. 输入你的用户名、邮箱及密码
3. 点击 `Sign up for GitHub` 注册
 
![3x](https://cloud.githubusercontent.com/assets/6169077/18310821/4f033542-7533-11e6-8bda-c2e8b4ac11c0.png)

前往课程主页：https://github.com/java-b

熟悉[如何在讨论区中发布新的帖子？](https://github.com/java-a/syllabus/issues/1)及[如何回复一个帖子？](https://github.com/java-a/syllabus/issues/2)。

<h2 id='4'>第四步 下载安装 JDK 1.8 并配置环境变量</h2>
请在 FTP 的 Materials 文件夹或者 Java 官网下载 [JDK 1.8](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html) 安装包并安装。  
配置环境变量请参考此链接：http://jingyan.baidu.com/article/f96699bb8b38e0894e3c1bef.html

<h2 id='5'>第五步 Java 编辑器介绍</h2>
###轻量编辑器
与 Windows 自带的记事本相比，这类编辑器由于提供了代码高亮、自动补全等功能，更适合写代码。目前，我们将使用这类编辑器进行简单的开发。

- [Atom](https://atom.io/) `推荐使用` 免费，Github 出品，功能大而全，扩展性强。
- [VS code](https://code.visualstudio.com/) `推荐使用` 免费，微软出品，扩展性逊于前一个编辑器，但是性能不俗。
- [Editplus](https://www.editplus.com/) 

###IDE（集成开发环境）  
如果说轻量级编辑器是轻便的“手枪”，那么集成开发环境就是强大的“火炮”。它为代码编写提供了极为完善的环境，我们将在以后的学习中用到。

- [Intellij IDEA](https://www.jetbrains.com/idea/) `推荐使用` 功能丰富，将是大家未来编写程序的主力。
- [Eclipse](https://www.eclipse.org/) 

<h2 id='6'>第六步 写一个 Java 小程序</h2>
首先，请在自己的文件夹下新建一个文本文件（txt格式），打开。  
粘贴上以下内容：  
```
  public class HelloWorld {  
      //输出一行字符串“Hello World!”  
      public static void main(String[] args) {  
        System.out.println("Hello World!");  
      }  
  }
```
保存并将文件名修改为HelloWorld.java  
![image](https://cloud.githubusercontent.com/assets/6169077/18313123/af429130-753f-11e6-8ded-e23f5e8b3104.png)  
请点击是  
这样我们就写好了一个在控制台中打印“Hello World!”的小程序。  
下面我们来编译、运行这个程序：  

###编译
首先通过 **命令提示符** 进入当前代码目录，方法有如下两种：

- 在代码所在的文件夹下，同时做到 `键盘按住 shift 键` 和 `鼠标点击右键`，选择 `在此处打开命令窗口`。  
- 打开命令提示符，按图示操作：
![image](https://cloud.githubusercontent.com/assets/6169077/18314312/23e68622-7545-11e6-9f9a-004a45841405.png)  

接着，输入命令 `javac Helloworld.java` 。如果编译成功，会产生一个名为HelloWorld.class的文件，如图。
![image](https://cloud.githubusercontent.com/assets/6169077/18314449/b490fa04-7545-11e6-8b18-582e0fcf8e4e.png)  

编译结束，不要关闭命令行。

###运行
在命令行中继续输入 `java Helloworld`
输入此命令后如正确运行，会产生如下结果：  
![image](https://cloud.githubusercontent.com/assets/6169077/18314616/61817b94-7546-11e6-8201-57683c5e2433.png)  

`注意` **课后请在自己的电脑上安装[JDK 1.8](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html)和代码编辑器。**
