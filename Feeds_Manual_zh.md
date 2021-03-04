# Feeds使用手册

**版本号：v1.2.0**

<details>
<summary> 目录 </summary>

&emsp;[1. 简介](#des)

<details>

[<summary>2. 如何安装Feeds？</summary>](#howtoinstallfeeds)

&emsp;[2.1 App Store](#appstore)

&emsp;[2.2 Google Play](#googleplay)

<details>

[<summary>2.3 elastOS Capsule Market</summary>](#elastoscapsulemarket)

&emsp;&emsp;[2.3.1 下载安装 elastOS](#installelastos)

&emsp;&emsp;[2.3.2 安装Feeds dapp](#installfeedsdapp)

</details>
</details>
<details>

[<summary>3. 如何关注Feed？</summary>](#howtofollowfeed)

&emsp;[3.1 关注已公开的Feed](#followpublicfeed)

&emsp;[3.2 通过Feed 二维码来关注](#followfeedwithqrcode)

</details>
<details>

[<summary>4. 如何发布微说？</summary>](#howtopost)

<details>

[<summary>4.1 启动服务</summary>](#startservice)

&emsp;&emsp;[4.1.1 Mac](#mac)

&emsp;&emsp;[4.1.2 Ubuntu(amd64 debian/ubuntu)](#ubuntuamd64)

&emsp;&emsp;[4.1.3 Ubuntu(arm debian/ubuntu)](#ubuntuarm)

&emsp;&emsp;[4.1.4 Feeds Docker 镜像](#docker)

</details>

&emsp;[4.2 绑定Feeds出版号](#bindpublisheraccount)

&emsp;[4.3 创建Feed](#createfeed)

&emsp;[4.4 发布微说](#post)

</details>
<details>

[<summary>5. 其他功能介绍</summary>](#elsefeature)

&emsp;[5.1 查看用户的信息](#checkuserinfo)

&emsp;[5.2 查看Feed的信息](#checkfeedinfo)

&emsp;[5.3 公开Feed](#publicfeed)

&emsp;[5.4 修改出版号信息](#updatepublisheraccount)

&emsp;[5.5 修改Feed信息](#updatefeedinfo)

</details>

&emsp;[6. 常见问题解答](#faq)

</details>

## <span id = "des">1. 简介</span>

Feeds是一个基于elastOS的dapp生态项目，elastOS一直主张的一个理念是“You own you data”，Feeds刚好是这个理念的完美贯彻者。

Feeds是一个社交网络平台，致力于服务公众对话，允许用户将自己的最新动态和想法发布出去。用户可以自己部署服务器，将自己的数据掌握在自己的手中。

## <span id = "howtoinstallfeeds">2. 如何安装Feeds?</span>

目前Feeds支持三种形式安装：

* App Store （app）

* Google Play （apk）

* elastOS Capsule Market （dapp）

### <span id = "appstore">2.1 App Store</span>

iOS用户：可以在App Store中以及扫描下面的二维码在iOS平台安装。

   <figure>
   <img src="https://trinity-website-1256757303.cos.ap-shanghai.myqcloud.com/feeds-manual/image/common/ios.png" width="120" height="150">
   </figure>

### <span id = "googleplay">2.2 Google Play</span>

安卓用户：可以在Google Play中以及扫描下面的二维码在安卓平台安装。

   <figure>
   <img src="https://trinity-website-1256757303.cos.ap-shanghai.myqcloud.com/feeds-manual/image/common/ios.png" width="120" height="150">
   </figure>

### <span id = "elastoscapsulemarket">2.3 elastOS Capsule Market</span>

#### <span id = "installelastos">2.3.1 下载安装 elastOS</span>

elastOS已安装，则请忽略这个步骤；否则继续。

elastOS可在Google Play商店中以及扫描下面的二维码来下载安装

   <figure>
   <img src="https://trinity-website-1256757303.cos.ap-shanghai.myqcloud.com/feeds-manual/image/common/elastOS-android.png" width="120" height="150">
   </figure>

#### <span id = "installfeedsdapp">2.3.2 安装Feeds dapp</span>

打开elastOS，进入主页后点击“Capsule Marketplace”图标，进入后找到“Feeds”点击“INSTALL”安装。

   <figure>
   <img src="https://trinity-website-1256757303.cos.ap-shanghai.myqcloud.com/feeds-manual/image/zh/elastOS-home.jpg" width=180 height=350>
   <img src="https://trinity-website-1256757303.cos.ap-shanghai.myqcloud.com/feeds-manual/image/zh/elastOS-market.jpg" width=180 height=350>
   </figure>

安装完毕后在 “最近浏览” 下点击右侧菜单里的“收藏”来收藏Feeds。Feeds会出现在elastOS的主界面，方便后续使用。

   <figure>
   <img src="https://trinity-website-1256757303.cos.ap-shanghai.myqcloud.com/feeds-manual/image/zh/elastOS-fav.jpg" width=180 height=350>
   <img src="https://trinity-website-1256757303.cos.ap-shanghai.myqcloud.com/feeds-manual/image/zh/elastOS-home2.jpg" width=180 height=350>
   </figure>

## <span id = "howtofollowfeed">3. 如何关注Feed？</span>

如果用户只是想关注他人的Feed，查看他人发布的微说（即Post），就不需要部署服务和绑定Feeds出版号。

Feeds中，用户可以通过两种方式关注Feed：

* 关注已公开的Feed
* 通过Feed二维码来关注

打开Feeds应用，用elastos的DID身份登录进入主页（图略；该DID身份需要上链，如果不清楚如何上链，请从“常见问题解答”中寻找答案）。

点击界面右下方的搜索图标，进入“探索Feeds”页面：

图示：

### <span id = "followpublicfeed">3.1 关注已公开的Feed</span>

在“探索Feeds”界面，选择一个Feed，点击进入该Feed的详情页：
   图示：

点击“关注”按钮，等弹出提示：“关注 *** 成功”，则该Feed添加成功，Feed下的状态显示为“正在关注”。

### <span id = "followfeedwithqrcode">3.2 通过Feed 二维码来关注</span>

在“探索Feeds”界面，点击搜索框右侧的扫描图标可以扫描其他设备上的Feed二维码来关注对应的Feed。 或者点击搜索框右侧的图片图标，可以通过扫描本地保存的Feed二维码来关注对应的Feed。

成功关注Feed后，可以在“我的时间线”下查看到已关注的Feed发布的微说。用户可以点赞微说，也可以对此微说添加微评。

   <figure>
   <img src="https://trinity-website-1256757303.cos.ap-shanghai.myqcloud.com/feeds-manual/image/zh/feedsadd-7.jpg" width=180 height=350>
   <img src="https://trinity-website-1256757303.cos.ap-shanghai.myqcloud.com/feeds-manual/image/zh/feedsadd-8.jpg" width=180 height=350>
   </figure>

备注：
   用户可以到“我的档案”->"关注"下查看已关注的Feed。

## <span id = "howtopost">4. 如何发布微说？</span>

如果要发布微说，首先需要启动服务生成Feeds出版号。用户绑定Feeds出版号后，才能创建Feed；有了Feed才能发布微说。

目前一个用户账号仅能绑定一个Feeds出版号，一个Feeds出版号可以创建多个Feed。

### <span id = "startservice">4.1 启动服务</span>

Feeds服务目前支持 Mac 和 Linux 发行版 debian。请根据自己使用的设备选择合适的版本。

下面以编辑时的最新版本为例。

#### <span id = "mac">4.1.1 Mac</span>

1. 下载服务安装包

   在PC的浏览器上打开链接下载：

   [Feeds.Service.app.macos.tar.gz](https://github.com/elastos-trinity/feeds-service/releases/download/release-v1.5.1/Feeds.Service.app.macos.zip)

   [查找最新版本](https://github.com/elastos-trinity/feeds-service/releases/)

2. 启动安装Feeds服务

* 下载后，解压打开是Feeds Service.app，如下所示：

   <figure>
   <img src="https://trinity-website-1256757303.cos.ap-shanghai.myqcloud.com/feeds-manual/image/common/feedsService.png" width=140 height=170>
   </figure>

* 点击“Feeds Service”应用图标会启动安装，弹出一个运行窗口，如下所示，同时会弹出一个请求链接的页面，点击“允许”即可。（如果无法打开，请到“常见问题解答”中找解决办法）

   <figure>
   <img src="https://trinity-website-1256757303.cos.ap-shanghai.myqcloud.com/feeds-manual/image/common/mac-0.png" width=260 height=180>
   <img src="https://trinity-website-1256757303.cos.ap-shanghai.myqcloud.com/feeds-manual/image/zh/mac-1.png" width=260 height=150>
   </figure>

* 将上述窗口中的URL链接“[http://localhost:10080/](http://localhost:10080/)”拷贝到浏览器上打开，会显示一个二维码（该二维码等待Feeds dapp 扫描来绑定该服务）。

#### <span id = "ubuntuamd64">4.1.2 Ubuntu(amd64 debian/ubuntu)</span>

1. 下载服务安装包

   在浏览器上打开链接：

   [feedsd_1.5.1_amd64_ubuntu_2004.deb](https://github.com/elastos-trinity/feeds-service/releases/download/release-v1.5.1/feedsd_1.5.1_amd64_ubuntu_2004.deb)

   [查找最新版本](https://github.com/elastos-trinity/feeds-service/releases/)

2. 启动安装Feeds服务

   选中x86_64 debian/ubuntu对应的安装包进行下载且打开：

   <figure>
   <img src="https://trinity-website-1256757303.cos.ap-shanghai.myqcloud.com/feeds-manual/image/common/Ubuntu-1.jpg" width=260 height=180>
   </figure>

   下载完成后，自动进入“Ubuntu Software”中 对应的安装包界面：

   <figure>
   <img src="https://trinity-website-1256757303.cos.ap-shanghai.myqcloud.com/feeds-manual/image/common/Ubuntu-2.jpg" width=260 height=180>
   </figure>

   点击“Install”进行安装，根据提示输入计算机的密码：

   <figure>
   <img src="https://trinity-website-1256757303.cos.ap-shanghai.myqcloud.com/feeds-manual/image/common/Ubuntu-3.jpg" width=300 height=140>
   </figure>

   完成安装后，刚显示的安装包界面显示“Install”按钮变为“Remove”。

   <figure>
   <img src="https://trinity-website-1256757303.cos.ap-shanghai.myqcloud.com/feeds-manual/image/common/Ubuntu-4.jpg" width=260 height=180>
   </figure>

   在浏览器上打开链接：[http://localhost:10080/](http://localhost:10080/)，会显示一个二维码（该二维码等待Feeds dapp扫描来绑定该服务）。

#### <span id = "ubuntuarm">4.1.3 Ubuntu(arm debian/ubuntu)</span>

1. 下载服务安装包

   打开链接下载：

   [feedsd_1.5.1_armhf_raspbian.deb](https://github.com/elastos-trinity/feeds-service/releases/download/release-v1.5.1/feedsd_1.5.1_armhf_raspbian.deb)

   [查找最新版本](https://github.com/elastos-trinity/feeds-service/releases/)

2. 启动安装Feeds服务

   与4.1.2(x86_64 debian/ubuntu)类似，不再赘述。

#### <span id = "docker">4.1.4 Feeds Docker 镜像</span>

1. 下载Docker

   可自行搜索下载。下载完成后，请继续下一步骤。

2. 启动安装Feeds服务

   启动终端，在终端输入命令来下载Feeds服务的Docker 镜像并启动服务：

       docker run -d --restart=always -p 10080:10080 trinitytech/feeds

备注：
   服务的更新和升级也可以参考文档：[安装说明](https://github.com/elastos-trinity/feeds-service/blob/master/INSTALL.md)

### <span id = "bindpublisheraccount">4.2 绑定Feeds出版号</span>

1. 点击下方tab页的 “+” 号按钮进入绑定Feeds出版号流程（或通过点击 菜单->“出版号” 进入绑定Feeds出版号流程）；

   <figure>
   <img src="https://trinity-website-1256757303.cos.ap-shanghai.myqcloud.com/feeds-manual/image/zh/feedsbind-1.jpg" width=180 height=350>
   <img src="https://trinity-website-1256757303.cos.ap-shanghai.myqcloud.com/feeds-manual/image/zh/feedsbind-2.jpg" width=180 height=350>  需要改图
   </figure>

2. 点击页面中部的扫描图标，扫描刚搭建的浏览器页面“[http://localhost:10080/](http://localhost:10080/)”的二维码，结果如下：

   <figure>
   <img src="https://trinity-website-1256757303.cos.ap-shanghai.myqcloud.com/feeds-manual/image/zh/feedsbind-3.jpg" width=180 height=350>
   <img src="https://trinity-website-1256757303.cos.ap-shanghai.myqcloud.com/feeds-manual/image/zh/feedsbind-4.jpg" width=180 height=350>
   </figure>

3. 确认无误后，点击“确认一致，继续”按钮，进入下一个界面：

   <figure>
   <img src="https://trinity-website-1256757303.cos.ap-shanghai.myqcloud.com/feeds-manual/image/zh/feedsbind-5.jpg" width=180 height=350>
   </figure>

4. 点击“创建新DID身份”按钮来生成服务的DID：

   <figure>
   <img src="https://trinity-website-1256757303.cos.ap-shanghai.myqcloud.com/feeds-manual/image/zh/feedsbind-6.jpg" width=180 height=350>
   </figure>

5. 点击“提交DID侧链发布”按钮，选择将服务的DID上链。（可以选择使用Wallet或者Assist来做上链操作）。

   <figure>
   <img src="https://trinity-website-1256757303.cos.ap-shanghai.myqcloud.com/feeds-manual/image/zh/feedsbind-7.jpg" width=180 height=350>
   </figure>

6. 此处以钱包为例来说明。

   <figure>
   <img src="https://trinity-website-1256757303.cos.ap-shanghai.myqcloud.com/feeds-manual/image/zh/feedsbind-8.jpg" width=180 height=350>
   <img src="https://trinity-website-1256757303.cos.ap-shanghai.myqcloud.com/feeds-manual/image/zh/feedsbind-9.jpg" width=180 height=350>
   </figure>

7. 交易发起后，界面跳转至Feeds应用里，接着需要给Feeds出版号颁发凭证。

   <figure>
   <img src="https://trinity-website-1256757303.cos.ap-shanghai.myqcloud.com/feeds-manual/image/zh/feedsbind-10.jpg" width=180 height=350>
   </figure>

8. 点击“颁发新凭证”按钮，在弹框里输入Feeds出版号的名称、描述、ELA钱包地址，点击“确认”，在跳转的请求签名凭证界面上点击“接受”，则凭证颁发成功。

   <figure>
   <img src="https://trinity-website-1256757303.cos.ap-shanghai.myqcloud.com/feeds-manual/image/zh/feedsbind-11.jpg" width=180 height=350>
   <img src="https://trinity-website-1256757303.cos.ap-shanghai.myqcloud.com/feeds-manual/image/zh/feedsbind-12.jpg" width=180 height=350>
   </figure>

9. 凭证颁发成功后，则绑定过程即完成。用户可以在菜单->"出版号"界面看到该Feeds出版号的相关信息。

   <figure>
   <img src="https://trinity-website-1256757303.cos.ap-shanghai.myqcloud.com/feeds-manual/image/zh/feedsbind-13.jpg" width=180 height=350>
   <img src="https://trinity-website-1256757303.cos.ap-shanghai.myqcloud.com/feeds-manual/image/zh/feedsbind-14.jpg" width=180 height=350> 换图
    </figure>

### <span id = "createfeed">4.3 创建Feed</span>

1. 用户可以通过点击tab页上的“+”号图标进入“创建Feed”界面；也可以通过“我的档案”界面下“我的Feeds”下的“创建Feed”来进入。

   <figure>
   <img src="https://trinity-website-1256757303.cos.ap-shanghai.myqcloud.com/feeds-manual/image/zh/feedscreate-1.jpg" width=180 height=350>
   </figure>

2. 打开创建界面后，分别编辑Feed的名称、描述、以及头像，然后点击“创建Feed”,确认信息后即可成功创建。

   <figure>
   <img src="https://trinity-website-1256757303.cos.ap-shanghai.myqcloud.com/feeds-manual/image/zh/feedscreate-2.jpg" width=180 height=350>
   <img src="https://trinity-website-1256757303.cos.ap-shanghai.myqcloud.com/feeds-manual/image/zh/feedscreate-3.jpg" width=180 height=350>
   </figure>

3. 创建完成后，可以在“我的Feeds”页下面看到新创建的Feed。用户可以创建多个Feed，用来分别发布不同种类的微说。再次创建Feed时，可以通过点击“创建新的Feed”来创建。

   <figure>
   <img src="https://trinity-website-1256757303.cos.ap-shanghai.myqcloud.com/feeds-manual/image/zh/feedscreate-4.jpg" width=180 height=350>
   </figure>

### <span id = "post">4.4 发布微说</span>

用户创建Feed成功后，即可开始发布微说。

1. 点击tab页上的“+”号图标，跳转到创建Post页面。 默认选中的是用户创建的第一个Feed来发布，用户可以在创建Post界面更换Feed。

   <figure>
   <img src="https://trinity-website-1256757303.cos.ap-shanghai.myqcloud.com/feeds-manual/image/zh/post-1.jpg" width=180 height=350>
   <img src="https://trinity-website-1256757303.cos.ap-shanghai.myqcloud.com/feeds-manual/image/zh/post-2.jpg" width=180 height=350>
   </figure>

2. 目前创建的Post的类型已支持文字、图片（即将支持九宫格），视频等。信息编辑完毕后点击“发布”即可完成发布。

   <figure>
   <img src="https://trinity-website-1256757303.cos.ap-shanghai.myqcloud.com/feeds-manual/image/zh/post-3.jpg" width=180 height=350>
   </figure>

   可以在“我的时间线”页面看到新发布的Feeds，关注该Feeds的用户均可查看到。

## <span id = "elsefeature">5. 其他功能介绍</span>

### <span id = "checkuserinfo">5.1 查看用户的信息</span>

可查看当前DID账号的个人信息，目前不支持在此修改。

通过点击当前DID账号的用户头像可打开详情页查看：

* 菜单->头像
* 我的档案->头像

### <span id = "checkfeedinfo">5.2 查看Feed的信息</span>

点击Feed头像进入该Feed的已发布信息列表页，点击页面上方的Feed头像进入Feed详情页。

### <span id = "publicfeed">5.3 公开Feed</span>

该功能支持出版号的绑定者来操作。

您在创建Feed之后，如果想让更多用户关注自己的Feed，了解自己发布的Post信息，那么可以选择将自己的Feed公开。公开的Feed会显示在“探索Feeds”页，其他用户关注成功后，即可查看您发布的Post信息。

点击 菜单->“出版号详情”，打开出版号详情页，页面下方会显示您自己创建的Feed，选中Feed，点击后面的按钮来切换状态使其公开。

图

### <span id = "updatepublisheraccount">5.4 修改出版号信息</span>

该功能支持出版号的绑定者来操作。

可修改出版号名称、描述以及该出版号的ELA地址。

点击 菜单->“出版号详情”，打开出版号详情页；点击右上角的修改图标，进入“编辑出版号”界面，编辑完毕后，点击“保存”，需跳转到elastOS重新颁发证书。证书颁发完毕，则修改结束。

图

### <span id = "updatefeedinfo">5.5 修改Feed信息</span>

该功能支持Feed的创建者来操作。

可修改Feed名称、描述以及头像。

点击Feed头像打开Feed的已发布信息页，再点击该页面的Feed头像进入Feed详情页，点击右上角的修改图标，进入“编辑Feed信息”页，编辑完毕后，点击“保存”，则修改结束。

图

## <span id = "faq">6. 常见问题解答</span>

**Q1：绑定出版号时颁发凭证失败，如何处理？**

**答：**

颁发凭证失败有两种可能。

第一种：用户授权登录的DID没有上链；第二种：DID链的服务出现问题，暂时不可用。

如果是第一种，请将DID上链；如果是第二种，请反馈给DID链的工作人员处理。

**Q2：用户的DID如何上链？**

**答：**

* 打开elastOS内置的dapp -> “Identity”；
* 点击界面中当前选项下的“发布”图标；
* 在发布界面上将要发布的信息选中；
* 点击“确认”，在弹出的确认对话框上再次点击“发布”；
* 从Wallet和Assist中选择一个来发起交易；待交易确认后，DID即上链。

备注：上链交易仅消耗微量的交易费，在DID链的钱包上保留少量的ELA即可。

**Q3：如何确定自己的DID是否上链？**

**答：**

打开elastOS内置的dapp -> “Identity”，如果看到“身份已发布”的说明，则DID已上链。

或者提供您的DID给工作人员，工作人员可以帮忙查询。

**Q4：如何将Feed分享给其他人？**

**答：**

* 进入Feeds主页；
* 点击要分享的Feed头像，打开Feed的已发布信息页；
* 点击该页面的Feed头像进入Feed详情页；
* 界面下方会显示该Feed的二维码；
* 可将该二维码截图分享给他人。（未来会完善分享方式）

**Q5：卸载了elastOS、删除了Feeds dapp，或者删掉了绑定的Feeds出版号，如何恢复？**

**答：**

再次走绑定流程即可，此时服务不会生成新的DID，也不需要再颁发凭证。

**Q6：Feeds Service 应用在Mac上启动时报错：**

   <figure>
   <img src="https://trinity-website-1256757303.cos.ap-shanghai.myqcloud.com/feeds-manual/image/zh/q6-1.png" width=280 height=140>
   </figure>

**如何解决该问题？**

**答：**

依次点击进入：系统偏好设置..->安全性与隐私->通用，如下图所示：

   <figure>
   <img src="https://trinity-website-1256757303.cos.ap-shanghai.myqcloud.com/feeds-manual/image/zh/q6-2.png" width=200 height=200>
   </figure>

点击“仍要打开”，然后在弹出的确认打开界面继续点击“打开”，则会打开Feeds Service，然后在弹出的请求链接上点击“允许”即可。

   <figure>
   <img src="https://trinity-website-1256757303.cos.ap-shanghai.myqcloud.com/feeds-manual/image/zh/q6-3.png" width=280 height=140>
   <img src="https://trinity-website-1256757303.cos.ap-shanghai.myqcloud.com/feeds-manual/image/zh/q6-4.png" width=280 height=140>
   </figure>

**Q7：Feeds Service服务的数据文件在哪里？**

**答：**

该服务是运行在本地的，数据库文件默认是存储在home下的“.feedsd/”。

   <figure>
   <img src="https://trinity-website-1256757303.cos.ap-shanghai.myqcloud.com/feeds-manual/image/common/q7.png" width=300 height=15>
   </figure>

删除该数据库文件，则该服务所创建的Feed以及发送的微说全部丢失。请谨慎处理。

**Q8：打赏无法顺利进行？**

**答：**

请及时更新elastOS版本。

**Q9：绑定Feeds出版号报错：“解析DID文档错误”？**

**答：**

可能原因：

1. DID链服务暂不可用，请联系工作人员；

2. 如果是在elastOS中运行的Feeds dapp，请检查开发模式是否已打开。确认打开的情况下，请查看 “elastOS->设置->开发者选项” 中连接的节点是否正确。