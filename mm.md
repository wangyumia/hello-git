# 文档整理
1.github是什么？
   Github是IT技术人员的社交网站，基于网络的Git或版本控制的存储库和网络脱管服务
   
2.git是什么？
   版本控制系统 SVN也是版本控制系统
   
3.学习github的5个理由
  1）有很多很厉害的技术人员，称大牛，比如百度、阿里等等
  2）可以接触到最新和最前沿的IT技术，我们可以接触到这些 软件的初始、中间以及最终状态，可以第一时间了解到软件 产品的发展动向，同时能够清楚地了解到时下最火热最具有 发展力的技术。
  3）我们可以学到开发语言、项目流程、设计思想、编码规范 等等，同时可以记录我们技术的发展，像社交网站中的一个 时间轴，我们可以随时去看自己的学习历程以及积累，有时 还会发现自己的不足之处，进而改正进步。
  4）github是一个开源的，所有项目的代码文档对我们都是开 放的。在上面我们可以找到一些项目参与其中，增加自己的 项目实战经验，为以后找工作和做项目做铺垫。
  5）在github上有一些教程，我们可以进行学习，优质的学习 资源非常丰富。
  
4.github的优势是什么(基于HTML5做的)
  1)只支持git；
  2)完整协议支持；https 
  3)在线文件编辑  
  4)社交网络元素；
  5)特色工作模式；
  6)私有仓库托管；
  7）Ruby on Rails(架构)
  
5.通过github年度报告让你记忆最深刻的信息有哪些
  https://octoverse.github.com/网址
  1）最受欢迎的语言是JAVAScript;第二是JAVA
  2）在全球创建Github社区
  3）中国是新用户使用最多的国家	
  
6.github上有可以个人账号 还可以有（组织 ）账号

7.github上面的两个组成要素是什么
仓库/项目 人/组织 

8.github上两个重要页面
个人主页  数字仪表板

9.主页菜单都包含什么?
Overview  Repositories  Stars   Follwing  Follers  

10.仓库的心跳线代表什么?
Pulse是体现该仓库软件开发活跃度的功能

11.star的作用是？
star 的作用是收藏，目的是方便以后查找。

12.fork的作用是？
fork 的作用是参与，目的是你增加新的内容，然后 Pull Request，把你的修改和主仓库原来的内容合并。

13.watch的作用是？
watch 的作用是关注，目的是等作者更新的时候，你可以收到通知。

14.搜索结果分别有哪些类别?
Repositories  Code   Commits   Issues  Wikis Users

15.你在github上挖到什么宝（挖宝  就是搜索什么东西）
大牛和项目
<Node.js 包教不包会>-by alsotang 

阮一峰   jstraining 仓库  RuanYiFeng
老齐的   StartLearn

16.个人主页上的“+”下拉菜单可创建的四种类别分别有？分别的意 思？
    new gist 创建新的代码
    new organization  创建新的组织
    new repository 创建新的仓库
    import respository 导入仓库
    
17.如何能将仓库中的html文件直接解析成页面？
    settings设置->github pages->sourse->master master->save 
    
18.如何删除仓库
    settings->delete
    
19.Bash是什么操作系统的命令
     linux
     
20.Pwd是什么命令
    print working directory  打印当前工作目录
    
21.Cd是什么命令
    change directory  改变目录
    
22.Echo是什么命令
     打印 
     
23.配置用户名的命令
   #git config --global user.name ""
   
24.配置邮箱的命令
   git config --global user.email ""
   
25.命令行换行方式
   \
   
26.命令行终结方式
   ctrl+c
   
27.使用命令行比GUI方式有何优势
   1)比GUI的效率高
   2)github提供的功能有限 
   3)github只能局限于创建文件、编辑几个文件，无法创建文件夹
   4)在github上不能对多个文件进行同时编辑
   
28.提交到本地仓库时为什么有暂存区
 
   必须要经过暂存区，workspace中可能会有好多编辑，可以将所有编辑同时提交到index中 ，而从index提交到repository时，可以将灵活的将编辑内容进行提交
回撤时变动的影响是不同的，范围是不一样的在进行commit提交时，可以控制提交的颗粒度

29.新建代码仓库的命令
    git init
    
30.git clone [url] 这个命令的作用是
   下载一个项目和它的整个代码历史
   
31.添加指定文件到暂存区的命令
   git add [file1] [file2]
   
32.删除工作区文件，并且将这次删除放入暂存区的命令
   git rm [file1] [file2]
   
33.改名文件，并且将这个改名文件放入暂存区的命令
   git mv [file-origin] [file-rename]
   
34.提交暂存区到仓库的命令
   git commit -m [message]
   
35.直接从工作区提交到仓库的命令
   git commit  -a -m [message] #前提是该文件已经有仓库中的历史版本
   
36.显示变更信息的命令
   git status
   
37.查看历史信息的命令
   git log
   
38.Commit的意义是
   代码提交到仓库
   
39.Pull的意义是
   将远程仓库的提交拉下到本地
   
40.Push的意义是
   将本地的提交推送到远程仓库

2017/5/8  

41.MarkDown是什么？
   Markdown是一种可以使用普通文本编辑器编写的标记语言，通过简单的标记语法，它可以使普通文本内容具有一定的格式。
   是一个在web上使用的文本到HTML的转换工具，可以通过简单易读，易写的文本格式生成结构化的HTML文档，易读易写是它最大的特点
   目前  github,Stackoverflow，有道云，思维导读等网站均支持这种格式
   
42.MarkDown的特点？
    兼容HTNL
    在线观看
    平台支持
    排版样式简单
    
   1)专注文字内容而不是排版样式。
   2)轻松的导出 HTML、PDF 和本身的 .md 文件。
   3)纯文本内容，兼容所有的文本编辑器与字处理软件。
   4)可读，直观。适合所有人的写作语言
   
43.MarkDown的用途？
   IT人士：写日志，技术文稿，记录代码片段，撰写文档
   1）写博客
   2）用于编写说明文档，并且以“README.MD”的文件名保存在软件的目录下面。
   每个仓库都有README.md文档
   
44.MarkDown的编辑工具有哪些？
   Mac OS:MOU
   Windows:MarkdownPad  Mark Pad,HBuilder
   Linux:ReText
   Web:Github,markable.in,有道云笔记
   1）dillinger
   2）MaHua 
   3）简书
   4）FarBox 
   5）Cmd Markdown
   6）小书匠编辑器 
   7）Sublime Text 2
   8）Atom 
   9）MarkdownPad
   10）Typed
   11）Ulysses 
   12）iA Writer 
   13）Byword 
   14）MacDown
   15）Typora
   16）Miu
   17）MdCharm 
   
HBuilder  左边编辑，右边看效果；
          文本编辑工具
          文件夹为红色  master  意思是与Github仓库相连接  点击->team
markable.in  https://markable.in   密码：weiwei0405   
             # 为一级标题  最多有6级标题
             export 导出文档  
             文本直接写入 分段的话：在两行中间添加一个空行
             列表：
              有序列表：1.加空格  加字  1. 哇哈哈  该前面的数字不影响有序列表的顺序
              1. 哇哈哈
              5. 哇哈哈
              3. 哇哈哈
              效果是：1. 哇哈哈
              2. 哇哈哈
              3. 哇哈哈
              * 可乐
              * 雪碧
              * 芬达
              *可以被替换成其他符号
              > 你好呀 往里走一层
              超链接  [百度](http://www.baidu.com)   
             ![这是logo](http://www.edu2act.cn/static/img/logo.png)
             插入一张图片  
             点击Tab键if(true) {} else{}显示代码段
             use the 'print()' function  在print() 上加``  ``是1左边那个键~
             
45.MarkDown的区块元素和区段元素分别包含哪些？


区块元素：
          
          1）段落和段行   一个 Markdown 段落是由一个或多个连续的文本行组成，它的前后要有一个以上的空行。
          2）标题 
          3）区块引用   在段落的第一行最前面加>
          区块引用可以嵌套（例如：引用内的引用），只要根据层次加上不同数量的 > ：
          区块内也可以套用其他的 Markdown 语法，包括加粗、列表、代码区块等：
          4)列表   Markdown 支持有序列表和无序列表。
          无序列表使用星号、加号或是减号作为列表标记，效果一样：
          有序列表则使用数字接着一个英文句点：
          5）代码区块  要在 Markdown 中建立代码区块很简单，只要简单地缩进 4 个空格或是 1 个制表符就可以，
          6）分隔线 可以在一行中用三个以上的星号、减号、底线来建立一个分隔线，行内不能有其他东西。你也可以在星号或是减号中间插入空格
区段元素：1）1.链接
方块括号后面紧接着圆括号并插入网址链接即可
         2）强调

Markdown 使用星号（*）和底线（_）作为标记强调字词的符号
         3）行内标记

行内标记用反引号把它包起来' '
         4）插入图片
         5）其他
