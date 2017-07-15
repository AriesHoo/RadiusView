RadiusView
--------------------------
一、简介：

一个用于需要圆角矩形框背景的TextView或Layout的情况,减少直接使用时引入的shape资源文件，包括RadiusTextView，RadiusEditText,RadiusLinearLayout，RadiusRelativeLayout,RadiusLinearLayout
该库为[FlycoRoundView](https://github.com/H07000223/FlycoRoundView)扩展,主要增加不可点击状态属性并修改部分属性命名方式，使用方式参照layout_main.

1.1 Gradle集成**

```
allprojects {
    repositories {
        ...
        maven { url "https://jitpack.io" }
    }
}
```

```
dependencies {
     compile 'com.github.AriesHoo:RadiusView:1.0.3'
}
```

二、截图预览

4.4

![](https://github.com/AriesHoo/RadiusView/blob/master/screenshot/00.png)

5.0

![](https://github.com/AriesHoo/RadiusView/blob/master/screenshot/01.png)

三、鸣谢 
1、[FlycoRoundView](https://github.com/H07000223/FlycoRoundView)
