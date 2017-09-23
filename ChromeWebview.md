# 运行环境要求
- Android 应用中启用 WebView 调试
- Android 版本 4.4 +
# 调试步骤
1. 使用 USB 数据线将手机与电脑相连

2. 手机进入开发者模式，勾选 USB 调试，并允许调试
![](http://upload-images.jianshu.io/upload_images/5018455-ae5d7db19b635d68.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
3. 电脑打开 Chrome 浏览器，在地址栏输入：chrome://inspect/#devices 并勾选 Discover USB devices 选项
![](http://upload-images.jianshu.io/upload_images/5018455-04f75d89c6821c74.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
4. 手机允许远程调试，并访问调试页面
![](http://upload-images.jianshu.io/upload_images/5018455-f9ca7fdbcbf2f3a1.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
5. 电脑点击 inspect 按钮
![](http://upload-images.jianshu.io/upload_images/5018455-1268b2232f261fb3.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
注意：使用 Chrome Inspect 查看页面时，Chrome 需要从 https://chrome-devtools-frontend.appspot.com 加载资源，如果你得到的调试界面是一片空白，那你可能需要科学上网。
6. 进入调试页面
![](http://upload-images.jianshu.io/upload_images/5018455-33e8c3a9f91d5d39.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

到此就OK了。