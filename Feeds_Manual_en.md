# Feeds Manual

**Version：v1.2.0**

<details open = “open”>
<summary> Directory </summary>

&emsp;[1. Introduction](#des)

<details>

[<summary>2. How to Install Feeds</summary>](#howtoinstallfeeds)

&emsp;[2.1 App Store](#appstore)

&emsp;[2.2 Google Play](#googleplay)

<details>

[<summary>2.3 elastOS Capsule Market</summary>](#elastoscapsulemarket)

&emsp;&emsp;[2.3.1 Download and Install elastOS](#installelastos)

&emsp;&emsp;[2.3.2 Download and install Feeds in elastOS](#installfeedsdapp)

</details>
</details>
<details>

[<summary>3. How to Follow a Feed？</summary>](#howtofollowfeed)

&emsp;[3.1 Follow public Feeds](#followpublicfeed)

&emsp;[3.2 Follow Feed with QR code](#followfeedwithqrcode)

&emsp;[3.3 Follow Feed with Feed url](#followfeedwithfeedurl)

</details>
<details>

[<summary>4. How to publish a Post？</summary>](#howtopost)

<details>

[<summary>4.1 Start Feeds Service</summary>](#startservice)

&emsp;&emsp;[4.1.1 Mac](#mac)

&emsp;&emsp;[4.1.2 Ubuntu(amd64 debian/ubuntu)](#ubuntuamd64)

&emsp;&emsp;[4.1.3 Ubuntu(arm debian/ubuntu)](#ubuntuarm)

&emsp;&emsp;[4.1.4 Feeds Docker Image](#docker)

</details>

&emsp;[4.2 Bind Feeds Publisher Account](#bindpublisheraccount)

&emsp;[4.3 Create a Feed](#createfeed)

&emsp;[4.4 Create a Post](#post)

</details>
<details>

[<summary>5. Other features</summary>](#otherfeature)

&emsp;[5.1 Check user details](#checkuserinfo)

&emsp;[5.2 Check Feed details](#checkfeedinfo)

&emsp;[5.3 Make Feed public](#publicfeed)

&emsp;[5.4 Update Publisher Account](#updatepublisheraccount)

&emsp;[5.5 Update Feed Details](#updatefeedinfo)

</details>

&emsp;[6. FAQ](#faq)

</details>

## <span id = "des">1. Introduction</span>

Feeds is a project based on elastOS. Since its inception, elastOS has championed the tagline "Own your data" and Feeds exemplifies this principled vision.

Feeds is a decentralized social networking platform dedicated to serving public discussion and enabling users to post their lives and ideas. Users can deploy servers independently with Feeds Service on the device and fully control their data.

## <span id = "howtoinstallfeeds">2. How to Install Feeds</span>

Currently Feeds supports three forms of installation:

* App Store

* Google Play

* elastOS Capsule Market

### <span id = "appstore">2.1 App Store</span>

iOS users: Feeds is available on the App Store, and at QR code below.

   <figure>
   <img src="https://trinity-website-1256757303.cos.ap-shanghai.myqcloud.com/feeds-manual2/image/common/ios.png" width="120" height="150">
   </figure>

### <span id = "googleplay">2.2 Google Play</span>

Android users: Feeds is available on the Google Play Store, and at QR code below.

   <figure>
   <img src="https://trinity-website-1256757303.cos.ap-shanghai.myqcloud.com/feeds-manual2/image/common/android.png" width="120" height="150">
   </figure>

### <span id = "elastoscapsulemarket">2.3 elastOS Capsule Market</span>

#### <span id = "installelastos">2.3.1 Download and Install elastOS</span>

elastOS is already installed, please ignore this step; otherwise continue.

elastOS is available on the Google Play Store, and at QR code below.

   <figure>
   <img src="https://trinity-website-1256757303.cos.ap-shanghai.myqcloud.com/feeds-manual2/image/common/elastOS-android.png" width="120" height="150">
   </figure>

#### <span id = "installfeedsdapp">2.3.2 Download and install Feeds in elastOS</span>

  * Open elastOS and land on the homepage, click the icon of "Capsule Marketplace" and open it. Find the "Feeds" and install it.

      <figure>
      <img src="https://trinity-website-1256757303.cos.ap-shanghai.myqcloud.com/feeds-manual2/image/en/elastOS-home.jpg" width=180 height=350>
      <img src="https://trinity-website-1256757303.cos.ap-shanghai.myqcloud.com/feeds-manual2/image/en/elastOS-market.jpg" width=180 height=350>
      </figure>

  * Under "Recent Capsules", click "Favorites" in the right hand menu to make Feeds to appear on the main interface of elastOS for subsequent use.

      <figure>
      <img src="https://trinity-website-1256757303.cos.ap-shanghai.myqcloud.com/feeds-manual2/image/en/elastOS-fav.jpg" width=180 height=350>
      <img src="https://trinity-website-1256757303.cos.ap-shanghai.myqcloud.com/feeds-manual2/image/en/elastOS-home2.jpg" width=180 height=350>
      </figure>

## <span id = "howtofollowfeed">3. How to Follow a Feed？</span>

For users that just follow other feeds and read their posts, it is not necessary to deploy services and bind Feeds publisher account.

Users have two ways to follow the feed In Feeds:

* Follow public Feeds
* Follow Feed with QR code
* Follow Feed with Feed url

Open the Feeds application, use the elastOS DID login function to enter the homepage (the DID identity must be published on-chain. If you do not know how to publish it, please find the answer in the "FAQ" section).

   <figure>
   <img src="https://trinity-website-1256757303.cos.ap-shanghai.myqcloud.com/feeds-manual2/image/en/feedssign.jpg" width=180 height=350>
   <img src="https://trinity-website-1256757303.cos.ap-shanghai.myqcloud.com/feeds-manual2/image/en/feedshome.jpg" width=180 height=350>
   </figure>

Click the search icon in the bottom right corner to enter the "Explore Feeds" page:

   <figure>
   <img src="https://trinity-website-1256757303.cos.ap-shanghai.myqcloud.com/feeds-manual2/image/en/explorefeeds.jpg" width=180 height=350>
   </figure>

### <span id = "followpublicfeed">3.1 Follow public Feeds</span>

Select a Feed on the "Explore Feeds" page, click the "Follow" button in the feed column, or click the feed to enter the Feed detail page:

   <figure>
   <img src="https://trinity-website-1256757303.cos.ap-shanghai.myqcloud.com/feeds-manual2/image/en/feeddetail.jpg" width=180 height=350>
   </figure>

Click the "Follow" button and wait for a pop-up prompt: "Followed ***（Feed name） Successfully", the feed is followed successfully.

After you have followed the feed successfully, you can go to "My Profile" -> "Following" to view the feeds you have followed.

   <figure>
   <img src="https://trinity-website-1256757303.cos.ap-shanghai.myqcloud.com/feeds-manual2/image/en/feedsprofilefollowing.jpg" width=180 height=350>
   </figure>

You can view the posts of the feed you have followed under "My Timeline". You can like post, or leave a comment to the post.

   <figure>
   <img src="https://trinity-website-1256757303.cos.ap-shanghai.myqcloud.com/feeds-manual2/image/en/feedstimeline.jpg" width=180 height=350>
   </figure>

### <span id = "followfeedwithqrcode">3.2 Follow Feed with QR code</span>

On the "Explore Feeds" page, click the scan icon on the right side of the search box to call the scanner to scan the feed QR code on other devices to follow the corresponding feed.

### <span id = "followfeedwithfeedurl">3.3 Follow Feed with Feed url</span>

Open the "Explore Feeds" interface, paste a feed url into the search box, click Search to find the feed. It will automatically follow the feed after finding this feed.

## <span id = "howtopost">4. How to publish a Post？</span>

For a user to publish a Post, he or she must start the service to generate the Feeds publisher account. Feed can be created only after binding the Feeds publisher account, and only with the Feed can the Post be published.

At present, a user account can only be bound to one Feeds publisher account, and multiple feeds can be created to one Feeds publisher account.

### <span id = "startservice">4.1 Start Feeds Service</span>

Currently supports Mac and Linux debian distributions. Please select the appropriate version according to the device you are using.

Take the latest version at the time of editing as an example:

#### <span id = "mac">4.1.1 Mac</span>

1. Download service installation package

   Open the link to download on a PC browser:

    [Feeds.Service.app.macos.tar.gz](https://github.com/elastos-trinity/feeds-service/releases/download/release-v1.1.0/Feeds.Service.app.macos.tar.gz)

    [Find the latest version](https://github.com/elastos-trinity/feeds-service/releases/)

2. Start the installation of Feeds Service

* After downloading, unzip and open the Feeds Service.app, as shown below:

   <figure>
   <img src="https://trinity-website-1256757303.cos.ap-shanghai.myqcloud.com/feeds-manual2/image/common/feedsService.png" width=140 height=170>
   </figure>

* Clicking on the "Feeds Service" application icon will start the installation, and a running window will pop up, as shown below. Then, a page requesting a link will pop up at the same time. Click "Allow". If you are unable to open it, please refer to "FAQ" for troubleshooting.

   <figure>
   <img src="https://trinity-website-1256757303.cos.ap-shanghai.myqcloud.com/feeds-manual2/image/common/mac-0.png" width=260 height=180>
   <img src="https://trinity-website-1256757303.cos.ap-shanghai.myqcloud.com/feeds-manual2/image/en/mac-1.png" width=260 height=150>
   </figure>

* Copy the URL link "[http://localhost:10080/](http://localhost:10080/ )" in the above window, paste in the browser, and open it. A QR code will be displayed, which will be scanned by the Feeds application to bind the service.

#### <span id = "ubuntuamd64">4.1.2 Ubuntu(amd64 debian/ubuntu)</span>

1. Download service installation package

   Open the link to download on a PC browser:

   [feedsd_1.1.0_amd64_ubuntu_2004.deb](https://github.com/elastos-trinity/feeds-service/releases/download/release-v1.1.0/feedsd_1.1.0_amd64_ubuntu_2004.deb)

   [Find the latest version](https://github.com/elastos-trinity/feeds-service/releases/)

2. Start the installation ofFeeds Service

   Select the installation package corresponding to x86_64 debian/ubuntu to download and open:

   <figure>
   <img src="https://trinity-website-1256757303.cos.ap-shanghai.myqcloud.com/feeds-manual2/image/common/Ubuntu-1.jpg" width=260 height=180>
   </figure>

   After the download is complete, automatically enter the corresponding installation package interface in "Ubuntu Software":

   <figure>
   <img src="https://trinity-website-1256757303.cos.ap-shanghai.myqcloud.com/feeds-manual2/image/common/Ubuntu-2.jpg" width=260 height=180>
   </figure>

   Click "Install", and enter the computer password as prompted:

   <figure>
   <img src="https://trinity-website-1256757303.cos.ap-shanghai.myqcloud.com/feeds-manual2/image/common/Ubuntu-3.jpg" width=300 height=140>
   </figure>

   After the installation is complete, the installation package interface displayed above shows that the "Install" button changes to "Remove".

   <figure>
   <img src="https://trinity-website-1256757303.cos.ap-shanghai.myqcloud.com/feeds-manual2/image/common/Ubuntu-4.jpg" width=260 height=180>
   </figure>

   Open the link on the browser:[http://localhost:10080/](http://localhost:10080/), and a QR code will be displayed, which is waiting for the Feeds Capsule to scan in order to bind the service.

#### <span id = "ubuntuarm">4.1.3 Ubuntu(arm debian/ubuntu)</span>

1. Download service installation package

   Open the link to download:

   [feedsd_1.1.0_armhf_raspbian.deb](https://github.com/elastos-trinity/feeds-service/releases/download/release-v1.1.0/feedsd_1.1.0_armhf_raspbian.deb)

   [Find the latest version](https://github.com/elastos-trinity/feeds-service/releases/)

2. Start the installation of Feeds Service

   This process is similar to 4.1.2 (x86_64 debian/ubuntu) and will not be repeated here.

#### <span id = "docker">4.1.4 Feeds Docker Image</span>

1. Download Docker

   You can search and download by yourself. After the download is complete, proceed to the next step.

2. Start the installation of Feeds Service

   Start the terminal, enter the command in the terminal to download the Docker image of the Feeds service and start the service:

       docker run -d --restart=always -p 10080:10080 trinitytech/feeds

### <span id = "bindpublisheraccount">4.2 Bind Feeds Publisher Account</span>

1. On the homepage，click the "+" button on the tab page below to initiate the process of binding the Feeds publisher account. The binding process can also be initiated by using the "Publisher Account" option on menu page;

   <figure>
   <img src="https://trinity-website-1256757303.cos.ap-shanghai.myqcloud.com/feeds-manual2/image/en/feedshome.jpg" width=180 height=350>
   <img src="https://trinity-website-1256757303.cos.ap-shanghai.myqcloud.com/feeds-manual2/image/en/feedsmenu.jpg" width=180 height=350>
   </figure>

2. Click the scan icon in the middle of the page and scan the QR code of the browser page "[http://localhost:10080/](http://localhost:10080/)". The results are as follows:

   <figure>
   <img src="https://trinity-website-1256757303.cos.ap-shanghai.myqcloud.com/feeds-manual2/image/en/feeds-bind1.jpg" width=180 height=350>
   <img src="https://trinity-website-1256757303.cos.ap-shanghai.myqcloud.com/feeds-manual2/image/en/feeds-bind2.jpg" width=180 height=350>
   </figure>

3. After confirming that it is correct, click the "Confirm" button to enter the next interface:

   <figure>
   <img src="https://trinity-website-1256757303.cos.ap-shanghai.myqcloud.com/feeds-manual2/image/en/feeds-bind3.jpg" width=180 height=350>
   </figure>

4. Click the "Proceed to create a new DID" button to generate the Service DID:

   <figure>
   <img src="https://trinity-website-1256757303.cos.ap-shanghai.myqcloud.com/feeds-manual2/image/en/feeds-bind4.jpg" width=180 height=350>
   </figure>

5. Click the "Publish on DID Sidechain" button to publish the DID of the Service on-chain. Users can choose to use Wallet or Assist to complete publication.

   <figure>
   <img src="https://trinity-website-1256757303.cos.ap-shanghai.myqcloud.com/feeds-manual2/image/en/feeds-bind4-1.jpg" width=180 height=350>
   </figure>

6. For an example, see the wallet screenshots below. As shown in the figure below, click "Confirm" and enter the master password to complete the operation of publishing DID on the chain.

   <figure>
   <img src="https://trinity-website-1256757303.cos.ap-shanghai.myqcloud.com/feeds-manual2/image/en/feeds-bind4-2.jpg" width=180 height=350>
   </figure>

7. After the transaction is initiated, the interface transitions to the FeedsCapsule, at which point a credential must be issued to the Feeds publisher account.

   <figure>
   <img src="https://trinity-website-1256757303.cos.ap-shanghai.myqcloud.com/feeds-manual2/image/en/feeds-bind5.jpg" width=180 height=350>
   </figure>

8. Click the "Issue credentials" button, enter the name,description,and ELA Address of the Feeds publisher account in the pop-up box, click "Confirm", and click "Accept" on the redirected request, sign the Credential interface, and then the credential will be issued successfully.

   <figure>
   <img src="https://trinity-website-1256757303.cos.ap-shanghai.myqcloud.com/feeds-manual2/image/en/feeds-bind5-1.jpg" width=180 height=350>
   <img src="https://trinity-website-1256757303.cos.ap-shanghai.myqcloud.com/feeds-manual2/image/en/feeds-bind5-2.jpg" width=180 height=350>
   </figure>

9.  After the credential is issued successfully, the binding process is complete. Users can check the service information with the "Publisher Account" section of the menu.

   <figure>
   <img src="https://trinity-website-1256757303.cos.ap-shanghai.myqcloud.com/feeds-manual2/image/en/feeds-bind6.jpg" width=180 height=350>
   <img src="https://trinity-website-1256757303.cos.ap-shanghai.myqcloud.com/feeds-manual2/image/en/feeds-bind6-1.jpg" width=180 height=350>
   </figure>

### <span id = "createfeed">4.3 Create a Feed</span>

1. Users can enter the Create Feeds interface by clicking the "+" icon on the tab page, or through the "Create Feeds" (or "Create New Feed") in "My Feeds", under the My Profile interface.

   <figure>
   <img src="https://trinity-website-1256757303.cos.ap-shanghai.myqcloud.com/feeds-manual2/image/en/feeds-create1.jpg" width=180 height=350>
   </figure>

2. After opening the creation interface, edit the name, description, and avatar of the Feeds, and then click "Create Feed" and confirm the information to create a new unique Feeds.

   <figure>
   <img src="https://trinity-website-1256757303.cos.ap-shanghai.myqcloud.com/feeds-manual2/image/en/feeds-create2.jpg" width=180 height=350>
   <img src="https://trinity-website-1256757303.cos.ap-shanghai.myqcloud.com/feeds-manual2/image/en/feeds-create3.jpg" width=180 height=350>
   </figure>

3. After creation is complete, users can see the newly created Feeds under the My Feeds page. Users may create up to 5 Feeds to publish different types of Posts. When users want to create Feeds in the future, they can do so by clicking "Create New Feed".

   <figure>
   <img src="https://trinity-website-1256757303.cos.ap-shanghai.myqcloud.com/feeds-manual2/image/en/feeds-create4.jpg" width=180 height=350>
   </figure>

### <span id = "post">4.4 Create a Post</span>

After the user has successfully created Feeds(s),aPost can be created.

1. Enter the Feeds homepage, click the "+" icon on the tab page to jump to "New Post" page. By default, the first Feed created by the user is selected for publishing. In this interface, click the "V" icon behind the feed name, and the feed list menu will pop up, where the user can select the feed to publish the post.

   <figure>
   <img src="https://trinity-website-1256757303.cos.ap-shanghai.myqcloud.com/feeds-manual2/image/en/feeds-post1.jpg" width=180 height=350>
   <img src="https://trinity-website-1256757303.cos.ap-shanghai.myqcloud.com/feeds-manual2/image/en/feeds-post2.jpg" width=180 height=350>
   </figure>

2. The type of Post created so far supports text, pictures (coming soon to support Jiugongge), video, etc. After editing, click "Post" to complete publication.

   <figure>
   <img src="https://trinity-website-1256757303.cos.ap-shanghai.myqcloud.com/feeds-manual2/image/en/feeds-post3.jpg" width=180 height=350>
   </figure>

   Users can see the newly released Feeds on the My Feeds Timeline page, and users who follow particular Feeds can view them.

   <figure>
   <img src="https://trinity-website-1256757303.cos.ap-shanghai.myqcloud.com/feeds-manual2/image/en/feeds-post4.jpg" width=180 height=350>
   </figure>

## <span id = "otherfeature">5. Other features</span>

### <span id = "checkuserinfo">5.1 Check user details</span>

You can view the personal information of the current DID account, currently it is not supported to modify it here.

Click on the user avatar of the current DID account to open the details page to view:

* Menu -> avatar
* My profile -> avatar

### <span id = "checkfeedinfo">5.2 Check Feed details</span>

Click the feed avatar to enter the published post list page of the feed, and click the feed avatar at the top of the page to enter the feed details page.

### <span id = "publicfeed">5.3 Make Feed public</span>

Supports users who bind the publisher account to modify.

After you create your feed, if you want more users to follow your feed and read the Posts you publish, you can make your feed public. The public feed will be displayed on the "Explore Feeds" page. After other users have successfully followed your feed, they can view your posts.

Click Menu -> "Publisher Account" to open the "Publisher Account details" page, the bottom of the page will display the feeds created by yourself. Select the feed and click the button behind to switch the status to make it public.

   <figure>
   <img src="https://trinity-website-1256757303.cos.ap-shanghai.myqcloud.com/feeds-manual2/image/en/feeds-public1.jpg" width=180 height=350>
   <img src="https://trinity-website-1256757303.cos.ap-shanghai.myqcloud.com/feeds-manual2/image/en/feeds-public2.jpg" width=180 height=350>
   </figure>

### <span id = "updatepublisheraccount">5.4 Update Publisher Account</span>

Support users who bind the publisher account to modify.

The name， description and the ELA address of the publisher account can be modified.

Click Menu -> "Publisher Account" to open the "Publisher Account Details" page; click the edit icon in the upper right corner to enter the "Edit Account" interface. After editing, click "Save" to jump to elastOS to reissue the certificate. After the certificate is issued, the modification ends.

   <figure>
   <img src="https://trinity-website-1256757303.cos.ap-shanghai.myqcloud.com/feeds-manual2/image/en/feeds-updateaccount.jpg" width=180 height=350>
   </figure>

### <span id = "updatefeedinfo">5.5 Update Feed Details</span>

Support the creator of the feed to modify.

You can modify the feed name, description, and avatar.

Click the feed avatar to open the published post list page of the feed, then click the feed avatar on the page to enter the feed details page, click the edit icon in the upper right corner to enter the "Edit Feed Info" page. After editing, click "Save" to complete the modification.

   <figure>
   <img src="https://trinity-website-1256757303.cos.ap-shanghai.myqcloud.com/feeds-manual2/image/en/feeds-updatefeed1.jpg" width=180 height=350>
   <img src="https://trinity-website-1256757303.cos.ap-shanghai.myqcloud.com/feeds-manual2/image/en/feeds-updatefeed2.jpg" width=180 height=350>
   </figure>

## <span id = "faq">6. FAQ</span>

**Q1：What should I do if the credential issuance process fails?**

**Answer:**

There are two types of issues which may produce a failure to issue credentials.

In the first type, the DID authorized by the user at login is not published on-chain. In the second type, the DID on-chain service is experiencing a technical problem and is temporarily unavailable.

For the first type, please publish the DID on- chain; for the second type, please report the malfunction to Elastos community moderators.

**Q2：How do you publish the user's DID on-chain?**

**Answer:**

Please adhere to the following steps:

* Open elastOS' built-in "Identity" Capsule
* Click the "Publish" icon under the current option in the interface
* Select the information to be published on the "Publish" interface
* Click "Confirm", and click "Publish" again on the pop-up confirmation dialog box
* Choose one of Wallet and Assist to initiate the transaction on the DID side chain. After the transaction is confirmed, the DID will be published on the side chain.

**Tip:**

The transactions only consume a small amount of gas (transaction fees), but keep a small amount of ELA on your DID Sidechain Wallet to avoid further complications.

**Q3：How do I determine whether my DID has been published on-chain?**

**Answer:**

Open elastOS' built-in "Identity" Capsule, if you see the description "Identity Published", the DID has been published.

Or provide the DID in question to Elastos community moderators, and they will be able to inform you.

**Q4：How do I share a Feed with others?**

**Answer:**

* Enter the Feeds homepage
* Click on the avatar of the feed you want to share to open the published post list page of the feed
* Click on the feed avatar on this page to enter the feed details page
* The QR code of the feed will be displayed at the bottom of the interface
* You can share QR code screenshots with others. (In the future, there will be significant improvements to the Feed sharing processes.)

**Q5：I uninstalled elastOS, deleted the Feeds Capsule, or deleted the bound Feeds Publisher Account. How do I recover it?**

**Answer:**

The best method is to go through the binding process once again. This time, the service will not generate a new DID, and there is no need to issue credentials again.

**Q6：The Feeds Service Capsule reports an error when launching on Mac:**

   <figure>
   <img src="https://trinity-website-1256757303.cos.ap-shanghai.myqcloud.com/feeds-manual2/image/en/q6-1.png" width=280 height=140>
   </figure>

**How do I solve this problem?**

**Answer:**

Click to enter: System Preferences...->Security & Privacy->General, as shown in the figure below:

   <figure>
   <img src="https://trinity-website-1256757303.cos.ap-shanghai.myqcloud.com/feeds-manual2/image/en/q6-2.png" width=200 height=200>
   </figure>

Click "Open Anyway", and then continue to click "Open" in the pop-up confirmation interface to open the Feeds Service. Finally, click "Allow" on the pop-up request link.

   <figure>
   <img src="https://trinity-website-1256757303.cos.ap-shanghai.myqcloud.com/feeds-manual2/image/en/q6-3.png" width=280 height=140>
   <img src="https://trinity-website-1256757303.cos.ap-shanghai.myqcloud.com/feeds-manual2/image/en/q6-4.png" width=280 height=140>
   </figure>

**Q7：Where are the data files for Feeds Service?**

**Answer:**

The service is running locally, and the database file is stored in ".feedsd/" under home by default.

   <figure>
   <img src="https://trinity-website-1256757303.cos.ap-shanghai.myqcloud.com/feeds-manual2/image/common/q7.png" width=300 height=15>
   </figure>

If the database file is deleted, the Feeds created by the service - as well as the posts sent by the service - are all lost. Please handle with caution.

**Q8：Why did my ELA transfer to a Feeds address fail?**

**Answer:**

Please update your elastOS Application promptly.

**Q9：Why do I keep getting the following error when I try to bind a Feed Publisher Account: "resolve diddocument error"?**

**Answer:**

There are two possible reasons:

1. The DID Sidechain service is temporarily unavailable. In this case, please contact Elastos’ community moderators;

2. If it is the Feeds dapp running in elastOS, please check whether the “elastOS->Settings->Development Mode” is turned on. Please check whether the connected node is correct in “elastOS->Settings->Developer Options”.