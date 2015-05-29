![](https://raw.githubusercontent.com/KuaiFaMaster/FastAssistant_PC_DOC/master/img/logo.png)




#1 软件简介
致力于降低游戏开发之外的繁复，提高效率！
*   完全免费
*   云端测试
*   加固加压
*   多选打包

#2 环境运行要求
##2.1 硬件环境
*   奔腾4及以上cpu
*   2G及以上内存
*   2G及以上硬盘空间

##2.2 软件环境
*   32/64bit Windows 8.1操作系统（向下兼容，Windows 10 操作系统正在适配）
*   IE6.0及以上
*   如腾讯、360、金山等杀毒软件阻止进程，请点击信任并放入白名单。

#3 安装打包工具
##3.1 下载
打开[快发助手官网](http://www.haojieru.com),下载快发助手客户端
##3.2 安装
双击`kuaifatool.exe`,进行安装，请注意以下事项

*   请勿将软件安装至中文路径下

#4 注册账号
目前快发助手只接受企业用户注册，具体的注册流程请移步至[开放平台](http://open.haojieru.com/)

#5 使用软件
##5.1 使用前的准备工作
*   游戏中英文名称
*   512*512 游戏icon（.png）图片一张
*   签名文件秘钥
*   签名别名
*   在快发助手申请的支付回调地址
*   把待打包的游戏接入快发助手sdk，具体SDK，请参考http://sdkkit.youxigongchang.com/document/doc。

##5.2 登陆
![登陆](http://static.youxigongchang.com/upload/game/201504/09/ff/85/aPKaTK.png)
请输入在快发助手开放平台注册的账号及密码即可登陆

##5.3 功能预览
![预览](http://static.youxigongchang.com/upload/game/201504/09/5e/27/rj9uzL.png)

*   首页
    *   软件进入后的默认展示页，可在此添加、删除及修改游戏基础数据
*   配置管理：
    *   在配置管理页面可以轻松管理已经配置好的
*   测试管理：
    *   查看所有提交的测试请求，及获取测试结果
*   版本管理：
    *   查看通过工具打包的所有apk包
*   加固管理：
    *   查看所有提交的加固请求，及获取加固后的apk

##5.4 如何添加游戏？
点击下图`添加游戏`按钮
![添加游戏](http://static.youxigongchang.com/upload/game/201504/09/9d/e5/fHiTO0.png)
进入添加游戏界面，如下：
![添加游戏](http://static.youxigongchang.com/upload/game/201504/09/fc/fa/Cy1884.png)
请认真填写相应内容，以便后续打包工作可以正常进行

注意事项：

*   请不要在英文名框内混入特殊字符，如空格等
*   准备所要打包母包包名、母包第一个启动的Activity名称（在Androidmanfiest.xml里配置的android：name 属性）。
*   图标请务必上传`512x512`分辨率的`png图片`，后续打包工作会对此图做处理，敬请放心，不会增大安装包
*   登陆回调可留空
*   支付回调请务必核对准确，以保证支付后能成功回调到贵方服务器
*   如您不愿意上传keystore，则自行生成一个新的，待打包完成后自行对apk包签名，所以一定要上传一个keystore，以保证功能正常

添加完成后即可点击保存按钮，保存成功后会有弹窗提示，若添加失败，则会有详细信息提示您在哪一步填写有问题。

##5.5 如何修改/删除游戏参数？
当您添加完成游戏后，会在左边栏列出您所添加过的所有游戏
![修改游戏](http://static.youxigongchang.com/upload/game/201504/09/20/af/mjLSG8.png)
鼠标单击您所想要修改的游戏
![修改游戏](http://static.youxigongchang.com/upload/game/201504/09/f6/1e/Hy5KS0.png)
当修改完成后点击保存即可，`若想删除，则点击删除，删除后无法找回，请谨慎操作`。

##5.6 如何配置渠道参数
点击tab栏配置管理按钮
![配置渠道](http://static.youxigongchang.com/upload/game/201504/09/0d/c6/GG0KWP.png)
然后点击需要添加的游戏
![配置渠道](http://static.youxigongchang.com/upload/game/201504/09/b7/3c/vbnn1G.png)
若之前已经添加过，则左边栏会列出所添加过的渠道(没有添加过则为空)
![](http://static.youxigongchang.com/upload/game/201504/09/68/cb/nX584O.png)
若想要`添加渠道`则点击`添加渠道`按钮，若想要修改配置，则点击想要修改的渠道即可，将会出现如下界面：
![](http://static.youxigongchang.com/upload/game/201504/09/86/84/T0m1uD.png)
注意事项：
*   每个渠道左边栏都不同
*   左边栏内容请咨询相关渠道获取
*   支付回调地址是为了方便您为不同的渠道配置不同的回调服务器，入股没有这个业务需求，则务必留空
*   如果有角标，有时候会跟您的logo不重合，您可以通过图片右方和下方的滑块调整角标位置
*   检索框内输入关键字可以快速跳转到相应的渠道

##5.7 如何打包
在`左边栏`选中`某款游戏`后，点击`母包地址`后的`浏览按钮`，选择已经接入快发助手的母包
![](http://static.youxigongchang.com/upload/game/201504/09/92/c1/1KCKqD.png)
选择正确的母包后，会在左下角出现打包，同时在`添加渠道`按钮下方出现`测试按钮`
![](http://static.youxigongchang.com/upload/game/201504/09/28/4a/z1ifDS.png)
我们建议您在打包前对母包做一个完整的测试，只需要点击`免费测试`，并`确认测试`即可，测试完成后会有实时的消息提示框通知您。
点击`开始打包`按钮后,即可弹出打包界面
![](http://static.youxigongchang.com/upload/game/201504/09/d3/40/9C44i1.png)
注意事项：

*   打包过程中关闭界面则中断打包

![](http://static.youxigongchang.com/upload/game/201504/09/8c/b0/CebnrH.png)

*   打包完成后打包按钮会变成位置按钮，点击即可在windows管理器中查看
*   可多选或全选，打包时间略久，请耐心等待

##5.8 管理打包后的apk
点击tab栏，`版本管理`按钮
![](http://static.youxigongchang.com/upload/game/201504/09/27/67/efLGaH.png)
左边点击想要操作的游戏，右边即可出现所有的打包历史，
如果点击测试，并勾选相应的测试内容，点击开始测试，则会开始上传并自动提交一次测试任务
![](http://static.youxigongchang.com/upload/game/201504/09/62/8c/9SuHyH.png)
![](http://static.youxigongchang.com/upload/game/201504/09/1d/77/y1WTmT.png)

tips：

*   功能性测试指对游戏基础功能及操作的测试，涉及闪屏、登陆、支付、新手引导等的测试
*   兼容性测试指在多部手机上进行apk的安装及启动等的测试，可检查主流机型的适配

上传完成的任务可在测试管理中查看，并可获取结果
![](http://static.youxigongchang.com/upload/game/201504/09/21/d9/DOWXnH.png)
![](http://static.youxigongchang.com/upload/game/201504/09/07/ea/SSm5SK.png)
具体获取的文件格式取决于测试提供方，目前支持 pdf、excel、web、word这几种格式
![](http://static.youxigongchang.com/upload/game/201504/09/1c/98/rXrHGS.png)

点击加固，可对应用进行加固操作，企业级加固将保证您的应用更难被破解
![](http://static.youxigongchang.com/upload/game/201504/09/52/7e/OifHKG.png)
在加固管理中点击加固结果，即可下载加固好的应用，并自动签名
![](http://static.youxigongchang.com/upload/game/201504/09/e0/c5/ifr5a1.png)

#6 各个渠道特性
##6.1 联想
![](http://static.youxigongchang.com/upload/game/201504/09/6e/2f/O0GKSO.png)

    游戏启动Activity名称: 此参数就是在母包的Androidmenifest.xml中的启动的Activity的android:的属性名。
    
![](http://static.youxigongchang.com/upload/game/201504/09/71/d1/WDqfv5.png)

    商品列表: 此参数是因为在联想渠道后台需要配置商品对应关系。点开此参数的填写界面
    
![](http://static.youxigongchang.com/upload/game/201504/09/ae/db/i5CmH4.png)

    传入的商品id: 此id必须要传入整形。
    渠道号id: 为在联想后台配置的商品id列表
![](http://static.youxigongchang.com/upload/game/201504/09/5c/10/LizbT4.png)
![](http://static.youxigongchang.com/upload/game/201504/09/c6/cd/LKOuL8.png)


##6.2 爱游戏，egame
![](http://static.youxigongchang.com/upload/game/201504/09/7b/a5/rTufzH.png)

    要注意此参数的填写。 此参数要上传渠道给的dat文件。选择dat文件所在位置，点击确定上传即可。
    
##6.3 柴米
![](http://static.youxigongchang.com/upload/game/201504/09/14/40/erzXD0.png)

    MD5值的 ，在申请柴米参数的时候会用到。填写此值即可。
    像柴米、腾凤、天逸达渠没有用户系统。接入的是快发助手的登录系统，所以在打包之前请联系我们客服，把用户系统数据同步一下，以免出现登录不上的情况。

##6.4 平安万里通
![](http://static.youxigongchang.com/upload/game/201504/09/45/42/rLO008.png)
    
    渠道给参数有测试和正式两种。
    在打测试环境的包时，正式模式请选择debug模式。使用正式参数时选择product模式

##6.5 手盟
![](http://static.youxigongchang.com/upload/game/201504/09/c3/a6/u1eTO8.png)

    填写参数时需要填写两次参数的,填写两次即可(后续版本将修复此问题)

##6.6 腾凤
![](http://static.youxigongchang.com/upload/game/201504/09/cf/7d/DqnvP8.png)

    注意：所有填写包名参数的渠道，都要填写母包包名。不要填写申请参数时使用的包名。因为PC端打包所有渠道都有自己的后缀名。请参考附件1渠道包名后缀。
![](http://static.youxigongchang.com/upload/game/201504/09/8b/d7/bfD0m1.png)

    注意参数填写。此参数为商户参数。由渠道提供。

##6.7 树海（长沙试玩）
![](http://static.youxigongchang.com/upload/game/201504/09/7a/62/940qr9.png)

    注意参数的填写，请填写渠道给的pkcs8.txt文件里的参数。
    填写参数时不要-----BEGIN PRIVATE KEY-----和-----END PRIVATE KEY-----。并且参数要弄成一行，不要中间的换行符、空格等。以免发生报错

##6.8 飞流
![](http://static.youxigongchang.com/upload/game/201504/09/90/f2/T444G8.png)

    注意的值的填写。此参数是一个商户一个id，由飞流渠道提供。
    例如参数
    
    -----BEGIN PUBLIC KEY-----MIIBIjANBgkqhkiG9w0BAQEFAAOCAQ8AMIIBCgKCAQEAxSNenb3OHqjMhT9Z5oDGYrgnu+ALC4F9XJSLxPyjHFOXmEkCRpE76B4AfHmYRYQlLFlb1HGWPKRHheI5TUaylAiE0ZHpi2YlJWJAsnoEVfwB3O4vYGcRWpxjJwUFhwM+ptRwKowyCuebg9oFlBRgdmQ33scxoIYv+xP+KDtlRqloCzaIg6LU/RHTesxXs5+8SRapuYcQQ010VLfWD3GVKUjMyfFTk/cHAGmUi4qR40xDE/jyORmFX7NO7j7bXCpxZWQFpth0lmoOSoQSoEKzU4Nk/nYC4ugvZCmyBDyVsnnbeihZerynw4sfX+T0+sdz9if4rSqBZqZF1qjcCglKuQIDAQAB-----END PUBLIC KEY-----
    
    这个要注意 --------BEGIN 和 -----END PUBLIC KEY----- 都需要保留


##6.9 当乐
![](http://static.youxigongchang.com/upload/game/201504/09/bf/cd/Pa1OW1.png)

    1、 要注意的填写。在当乐后台申请参数时，会提供此参数。
    2、 等了要用自己的签名。就是打好的apk要重现使用签名命令重新签名。

##6.10 泡椒
![](http://static.youxigongchang.com/upload/game/201504/09/01/32/TSmjHO.png)

    注意参数的填写。这辆个字段都是有默认值。渠道没有具体要求，就不需要改动。

##6.11 7K7K
![](http://static.youxigongchang.com/upload/game/201504/09/e6/20/T08SCS.png)

    注意参数的填写。这两个参数填写一样的。
    
##6.12 点点乐
![](http://static.youxigongchang.com/upload/game/201504/09/e5/a0/WTqvb5.png)

    注意参数也要填写两次。
    
##6.13 逗你玩
![](http://static.youxigongchang.com/upload/game/201504/09/c6/82/nT8eP4.png)

    对比率是人民币对游戏的比率。

##6.14 摇滚河马
![](http://static.youxigongchang.com/upload/game/201504/09/8a/1f/zvPy9C.png)

    参数填写相同的值

##6.15 值尚
![](http://static.youxigongchang.com/upload/game/201504/09/e9/26/Ti50S4.png)

    参数，填写正确。游戏包名为游戏母包包名。

##6.16 美图盒子
![](http://static.youxigongchang.com/upload/game/201504/09/df/a9/yzj5aD.png)

    参数填一样的。注意美图也是要单独签名。打出包以后，渠道有自己的签名。使用签名命令重新签一次名即可。
    
##6.17 安峰
 ![](https://raw.githubusercontent.com/KuaiFaMaster/FastAssistant_PC_DOC/a39c216c80fafc6b096a8ba6cef94b4e6a379b5d/img/anfeng.jpg)
	
	渠道私钥填写参数时不要-----BEGIN RSA PRIVATE KEY-----和-----END RSA PRIVATE KEY-----。

 

#7 感谢您选择快发助手
    
#####客服QQ：940111913

#####客服邮箱：kefu@haojieru.com

#####商务 QQ：940111913

#####商务邮箱：sales@haojieru.com

#####地址：成都市高新区天府软件园E区E6-1座 四楼（610041）
    
    


        

