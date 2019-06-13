# GitHub极简教程

（**说明**本文只涉及GitHub For Windows，暂无Mac端，如果你使用的是Macbook，可根据内容自行更改）

## 准备

1. 下载[GitHub For Windows](https://desktop.github.com/)，安装这里不赘述（由于某些原因，GitHub的客户端下载比较缓慢且极易失败，所以我准备了安装包，可自行安装）。
2. [注册GitHub账号](https://github.com/)
3. 推荐安装VScode和Typora（同样准备了安装包，可自行安装）

## 登录

1. 登陆GitHub For Windows。

   ![1560386608560](https://github.com/AlbertZorichHawking/Tutorial/blob/master/Img/1560386608560.png)

## 创建代码库

### 认识界面



![1560386759914](https://github.com/AlbertZorichHawking/Tutorial/blob/master/Img/1560386759914.png)



GitHub For Windows的界面非常清爽（只是是**纯英文**界面），里面有三个选项Clone，Create，Add。

简单介绍介绍这三个功能。

### Clone

就是将在浏览器上已经创建好的项目导入到本地，换句话说就是下载到本地。（开放课题项目的GitHub地址如下https://github.com/AlbertZorichHawking/Game-Theory，可以复制直接下载）

![1560386945325](https://github.com/AlbertZorichHawking/Tutorial/blob/master/Img/1560386945325.png)

### Add

如果本地有工程，就可以使用Add添加（当然了，我们现在是没有的）

![1560386871738](https://github.com/AlbertZorichHawking/Tutorial/blob/master/Img/1560386871738.png)

### Create

创建代码库， Name填写你的项目名称，Description写这个项目的简单描述，Local path写你将要保存在本地路径，建议勾选Initialize选项，这样会自动生成一个Markdown主文件，可以填写项目的详细介绍。

![1560387374031](https://github.com/AlbertZorichHawking/Tutorial/blob/master/Img/1560387374031.png)



我在这里填写First，来创建第一个repository。

![1560387604459](https://github.com/AlbertZorichHawking/Tutorial/blob/master/Img/1560387604459.png)



## 修改第一个代码库中内容

我们来找到刚刚创建的代码库在本地的位置。就是刚刚在local path的地址路径，当然如果你忘了，请右键点击First。

![1560387736740](https://github.com/AlbertZorichHawking/Tutorial/blob/master/Img/1560387736740.png)

选择Open in Explorer。这样就可以转到刚刚的路径下。 新建一个文本文档。用VScode打开。 如下

![1560388045464](https://github.com/AlbertZorichHawking/Tutorial/blob/master/Img/1560388045464.png)

填写完内容后保存并关闭，此时的GitHub就会变成这个样子(Changs)：

![1560388121346](https://github.com/AlbertZorichHawking/Tutorial/blob/master/Img/1560388121346.png)

你会发现此时github会出现刚刚编辑的内容。

1. 这个是测试文本
2. 你好

并且前面会有**蓝色标识**，这个蓝色标识会提示你将要上传的文本。比如我第一次只想上传 **这个是测试文本**并不想把**你好**上传。 这时我们点击一下**你好**的前面的**蓝色标识**。



![1560388214216](https://github.com/AlbertZorichHawking/Tutorial/blob/master/Img/1560388214216.png)



**你好**前面的蓝色标识没有了。 

填写好**Summer**和**Description**，Summer就是这次改动的总结，我们也可以理解为标题*（必填）*，而Description可以理解为详细概况*（选填）*

------

这里只选择第一个修改对象，也就是**这个是测试文本**就行修改。summer填写为*第一次修改*，Description填写为: *上传了这个是测试文本* ，之后点击**Commit to master**。

![1560388384015](https://github.com/AlbertZorichHawking/Tutorial/blob/master/Img/1560388384015.png)



切换到**History**目录下



![1560388439326](https://github.com/AlbertZorichHawking/Tutorial/blob/master/Img/1560388439326.png)



我们会发现它改变了。 这次我们把**你好**进行添加。

![1560388494873](https://github.com/AlbertZorichHawking/Tutorial/blob/master/Img/1560388494873.png)



在**History**目录下发生了这样的改变。会在**History**目录下形成一天时间线，来指出每一次的修改标题和内容，同时会把修改的内容用**绿色标识**标出。打开本地的文本，删除刚刚添加的第一行**这个是测试文本**。

![1560388590555](https://github.com/AlbertZorichHawking/Tutorial/blob/master/Img/1560388590555.png)

此时会发现GitHub发生了变化。 有必要**说明**如果使用自带的txt编辑器编辑会出现**乱码**,这个是编码问题,如果不修改编码,只是在客户端上显示乱码,但是上传后不会出现乱码,为了保险起见,建议还是把文本编码修改为 utf-8 ，或者使用VScode编辑.

![1560388764834](https://github.com/AlbertZorichHawking/Tutorial/blob/master/Img/1560388764834.png)



此时的**红色标识**标识删除。写好Summer和Description并点击Commit to master。 这样就删除了第一行。同时在**History**目录下又多了一条时间轴。

## 上传与同步

### 上传

此时，当你打开github网页，就会发现此时你的修改的内容并没有出现在这里。这是因为你没有进行同步，仅仅是在本地就行了修改。此时我们仅仅需要点击右边的**publish**



![1560389073174](https://github.com/AlbertZorichHawking/Tutorial/blob/master/Img/1560389073174.png)



此时你就会本地内容已经上传到网页上。点击View on GitHub即可查看，这里的浏览器推荐使用Chrome，window自带的浏览器可能会打不开

![1560389208764](https://github.com/AlbertZorichHawking/Tutorial/blob/master/Img/1560389208764.png)



![1560389269077](https://github.com/AlbertZorichHawking/Tutorial/blob/master/Img/1560389269077.png)



### 同步

当你的代码库上传后就会发现，点击**Fetch origin**即可同步代码库

## 关于Markdown文档

Markdown是一种轻量级的标记语言，十分高效，支持插入图片，图表，代码，公式等等，建议在以后的文档中优先使用Markdown（推荐的Typora是个人认为windows端最好的Markdown编辑器）。

## 说明

这是GitHub上最简单的上传内容，由于大家暂时没有GitHub账号和客户端，暂时没有更新如何向一个项目贡献代码（其他内容也可以）的内容，相关内容会有后续更新。
