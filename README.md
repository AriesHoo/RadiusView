# RadiusView
--------------------------
### 一、简介：

一个用于需要圆角矩形框背景的TextView或Layout的情况,减少直接使用时引入的shape资源文件，包括RadiusTextView，RadiusEditText,RadiusLinearLayout，RadiusRelativeLayout,RadiusLinearLayout
该库为[FlycoRoundView](https://github.com/H07000223/FlycoRoundView)扩展,主要增加不可点击状态属性并修改部分属性命名方式，使用方式参照layout_main.

更全常见UI库参看 [UIWidget](https://github.com/AriesHoo/UIWidget)

[[Sample PC Download]](https://github.com/AriesHoo/RadiusView/blob/master/apk/sample.apk)

[[Sample Mobile Download]](http://fir.im/r84v)

![](https://github.com/AriesHoo/UIWidget/blob/master/apk/qr.png)

**1.1 Gradle集成**

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
     //compile 'com.github.AriesHoo:RadiusView:1.1.0'
      compile 'com.github.AriesHoo:RadiusView:${LATEST_VERSION}'
}
```

### 二、录屏预览

![](https://github.com/AriesHoo/RadiusView/blob/master/screenshot/00.gif)
