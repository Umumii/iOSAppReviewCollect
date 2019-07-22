## iOSAppReviewCollect
Record problems encountered during the racking process.

----
##### Guideline 2.1 - Performance - App Completeness

Your app or its metadata does not appear to include final content. Specifically, your app contained placeholder contents in 公告 in 首页.

Before you submit your app to the App Store, all of its content and metadata must be final. Your app must not include placeholder or incomplete information. For example, an app with “lorem ipsum” text in the app description field will be rejected. Likewise, an app with placeholder screenshots, such as “screenshot coming soon,” will be rejected. Instead, you should only submit an app with complete information and content throughout.

翻译：
您的应用或其元数据似乎不包含最终内容。 具体来说，您的应用程序在首页的公告中包含占位符内容。

在将应用程序提交到App Store之前，其所有内容和元数据都必须是最终的。 您的应用不得包含占位符或不完整信息。 例如，应用说明字段中包含“lorem ipsum”文字的应用将被拒绝。 同样，具有占位符屏幕截图的应用程序（例如“即将推出的屏幕截图”）将被拒绝。 相反，您应该只提交一个包含完整信息和内容的应用程序。

```
原因：
测试账号看到的内容为人为随意添加信息，不具有真实有效性。
解决方法：
修改测试账号所看信息，保证信息真实有效。
```

----
##### Guideline 2.2 - Performance - Beta Testing


Your app contains references to test, trial, demo, beta, pre-release or other incomplete content.

Specifically, the screenshots contained 测试.

翻译：
您的应用包含对测试，试用，演示，测试版，预发布或其他不完整内容的引用。
具体来说，截图包含测试。

```
解决方法：
预览截图、测试账号中去除演示、测试、demo等相关字样。
```
----

##### Guideline 2.3.3 - Performance - Accurate Metadata


We noticed that your screenshots do not sufficiently reflect your app in use.

Specifically, your 12.9-inch iPad Pro (3rd Generation) screenshots do not display the app in the correct device frame.

翻译：
我们注意到您的屏幕截图无法充分反映您正在使用的应用。
具体来说，您的12.9英寸iPad Pro（第3代）屏幕截图不会在正确的设备框架中显示应用程序。

```
解决方法：
预览中增加iPad Pro（第3代）快照，并且使快照中所用手机模型与真实模型保持一致。
```
---
##### Guideline 2.1 - Information Needed


We have started your app's review, but we were unable to successfully access all or part of your app. 

In order for us to continue the review, you will still need to provide a functional demo account that gives us access to all parts of your app so that we may fully review its content, features, and functionality. If all or part of your app is restricted, you will still need to provide a whitelisted demo account that gives us access to your app. Note that providing a demo video showing your app in use is not enough for us to continue the review.

Specifically, please kindly provide a Chinese mobile phone number and its SMS verification code since we have no Chinese mobile phone number and could not call you at the time of review.

翻译：
我们已开始对您的应用进行审核，但我们无法成功访问您的全部或部分应用。

为了让我们继续审核，您仍然需要提供一个功能模拟帐户，让我们可以访问您应用的所有部分，以便我们可以全面审核其内容，功能和功能。 如果您的全部或部分应用受到限制，您仍需要提供一个白名单模拟帐户，以便我们访问您的应用。 请注意，提供显示您正在使用的应用的演示视频不足以让我们继续进行审核。

具体来说，请提供中国手机号码及其短信验证码，因为我们没有中文手机号码，在审核时无法给您打电话。

```
原因：
项目中增加了短信验证功能，导致审核时无法及时获取到短信验证码。
解决方法：
增加账号白名单，让审核人员可以直接使用应用。
```