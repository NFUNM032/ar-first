# Unity3d安装操作

### 安装目的

通过安装Unity3D的基本操作，掌握Unity3d/3Dmax软件配置，JAVA/Andriod项目开发，以及基于Andiold Apk的发布

### 准备阶段（安装软件）

- 链接：https://pan.baidu.com/s/1oeOJ6IyuOPIMhopIIkZp6A 
提取码：ipqs
1. 首先安装Unity3d开发平台
   - UnitySetup64-5.6.2f1
   - UnityStandardAssetsSetup-5.6.2f1
   - UnitySetup-Android-Support-for-Editor-5.6.2f1
2. 再安装JAVA开发平台
   - jdk-8u144-windows-i586_8.0.1440.1 (安装JAVA开发包)
   - android-sdk_r24.4.1-windows

### 具体步骤
**1. 将UnitySetup64-5.6.2f1、UnityStandardAssetsSetup-5.6.2f1、UnityStandardAssetsSetup-5.6.2f1分别安装好**
  在安装好后对个人信息内容进行设置，然后便可进入首页

![unity3d开发平台首页](https://upload-images.jianshu.io/upload_images/9456717-0be55483f581d470.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


**2. 将jdk-8u144-windows-i586_8.0.1440.1进行安装（安装中可依据自己所储存的地址进行修改）**
   **注意：jdk所处的文件路径一定都要是英文的，不能出现中文字符，否则将无法进行安装**

 ![安装Java开发包](https://upload-images.jianshu.io/upload_images/9456717-8ed44cfd837bd690.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

![Java安装成功](https://upload-images.jianshu.io/upload_images/9456717-8c6e145c23b48ca1.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

**3. 配置环境变量**
   - (1) 找到电脑中的环境变量面板
   
![环境变量面板](https://upload-images.jianshu.io/upload_images/9456717-d42b775571c16bf9.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

   - (2) 新建变量名"Java_home"，变量值G:\AR\first\Jdk（即jdk的安装路径）
   
![新建变量名](https://upload-images.jianshu.io/upload_images/9456717-c1eae9c35802b8d1.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

   - (3) 编辑变量名"Path"，在原变量值的最后面加上 "%JAVA_HOME%\bin"

![编辑变量名“PATH”](https://upload-images.jianshu.io/upload_images/9456717-83d5fad0a6e4c262.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

   - (4) 验证是否成功安装Java
   
打开cmd 使用“Java -version”命令查看是否安装成功
![成功安装界面](https://upload-images.jianshu.io/upload_images/9456717-93e928568f7f3c2a.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

**4. 安装sdk（Andriod开发包）**
  软件：android-sdk_r24.4.1-windows

![Andriod开发包](https://upload-images.jianshu.io/upload_images/9456717-431d855f6f615c3c.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

**5. 配置unity开发环境**
   - (1) 打开unity，新建一个项目，打开Edit中的Preferences选项
   - (2) 找到External Tools中，点击SDK、JDK中的点击Browse,并选择SDK（对应安卓开发平台的路径）与JDK（对应Java的路径）
   
![更改配置环境](https://upload-images.jianshu.io/upload_images/9456717-a9b33d8aaa8bc93d.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


**6. 完成之后，打开已有场景**

![打开已有场景](https://upload-images.jianshu.io/upload_images/9456717-527645d0e97f48c0.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

**7. 在“file”下找到 “build setting ”选项进行配置（切换平台为安卓Android平台）**
   点击Player settings修改Other Settings中的 package name，命名方式可自由修改，***但是命名的格式必须为"xxx.xxx.xx"***,修改完成后，点击Build。
   
![image.png](https://upload-images.jianshu.io/upload_images/9456717-3c0a8f4bfdab3037.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

**8. 点击Build后，添加文件名，保存路径，APK安装包成功创建**

![射弹安装包](https://upload-images.jianshu.io/upload_images/9456717-fa22e87e2dc3191d.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

**9. 打包完成后，可直接安装至手机进行下载，或者使用”夜神模拟器“在电脑进行成品查看**

![成品](https://upload-images.jianshu.io/upload_images/9456717-5f2e8da05b8dcb85.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)











