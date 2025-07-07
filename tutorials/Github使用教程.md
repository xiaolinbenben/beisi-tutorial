## Github使用教程

- 用自己的账号登录github网站https://github.com/
- ![图片3.1.png](../src/image/图片3.1.png)


2. 加入小组的项目，邀请信已经发到各位登录github的邮箱里，请去邮箱查收。

![图片3.2.png](../src/image/图片3.2.png)

![图片3.3.png](../src/image/图片3.3.png)

点击View invitation，会看到下面的页面

![图片3.4.png](../src/image/图片3.4.png)

点击Accept接受邀请

![图片3.5.png](../src/image/图片3.5.png)

看到我们项目的仓库“vlogPlus”后，就说明仓库加入成功了！此时你可以往小组仓库里上传、下载、修改里面的文件了。

3. 安装GitHub Desktop

  ![图片3.6.png](../src/image/图片3.6.png)双击运行GitHubDesktopSetup.exe

  ![图片3.7.png](../src/image/图片3.7.png)

它将会自动完成安装，

![图片3.8.png](../src/image/图片3.8.png)

看到这个页面说明安装完成
再点击![图片3.9.png](../src/image/图片3.9.png)

![图片3.10.png](../src/image/图片3.10.png)

输入你的github用户名和密码，登录

![图片3.11.png](../src/image/图片3.11.png)

输入你的名字和邮箱，continue

![图片3.12.png](../src/image/图片3.12.png)

这里不用选yes，点finish

![图片3.13.png](../src/image/图片3.13.png)

在右边可以看到我们小组的仓库

![图片3.14.png](../src/image/图片3.14.png)

选中我们小组的仓库，点击下发的Clone按钮，

![图片3.15.png](../src/image/图片3.15.png)

在local path处设置要保存在你电脑上的路径，我这里是放在D盘下的vlogPlus文件夹下，设置好了后点击Clone

![图片3.16.png](../src/image/图片3.16.png)

看到界面变成了这样，说明Clone已经完成了，在D盘下确实出现了VlogPlus文件夹

![图片3.17.png](../src/image/图片3.17.png)


4. 上传自己写好的代码
   例如我写了一个helloWorld.java，想把它上传到小组的仓库里，请先将你要上传的这个文件放到你本地计算机的仓库里，本教程的例子
    ![图片3.18.png](../src/image/图片3.18.png)

然后回到GitHub Desktop这个软件，会发现它检测到了changes，也就是你修改了你本地计算机上的仓库，添加了一个helloWorld.java这个文件

![图片3.19.png](../src/image/图片3.19.png)

在左下角填写描述信息，说一说你做了什么修改，一定要说详细，让我们其他组员能看懂，这是代码版本管理中很重要的一个步骤

![图片3.20.png](../src/image/图片3.20.png)

说明写好了之后，点击下面的commit
然后点击右上角的![图片3.21.png](../src/image/图片3.21.png)

![图片3.22.png](../src/image/图片3.22.png)

这样就成功把新文件上传到仓库上啦！

5. 修改、删除、同步本地仓库和github仓库
   修改和删除道理一样，只要对你电脑上的仓库里的内容进行了改变，打开GitHub Desktop后，它都会检测到有changes，只要commit然后再push就可以更新github仓库里的内容了。
   【重要】同步仓库：每个组员每次敲代码之前都要先进行同步，在小组最新版的代码上进行工作，这样可以减少冲突！

   ![图片3.23.png](../src/image/图片3.23.png)

点击右上角的Fetch

![图片3.24.png](../src/image/图片3.24.png)

看到这个界面，说明云端的仓库有新版本，也就是说别的组员更新了新的东西上去了。再点击

![(图片3.25.png](../src/image/图片3.25.png)，就可以把云端仓库的更新同步到本地计算机的仓库上![图片3.26.png](../src/image/图片3.26.png)
 我们可以看到，别的组员新加的或修改的东西已经同步到了我的本机仓库里了。

确认同步工作做完后，大家再开始做各自的开发任务吧！！每个人都要确保自己每次都是在最新版本上做工哦！

## 如何用GitHub协助开发
1. [启动GitHub Desktop](../src/video/启动GitHub%20Desktop.mp4)

2. [使用GitHub协作开发](../src/video/如何使用GitHub协作.mp4)

3. [Pull request](../src/video/Pull%20requests.mp4)