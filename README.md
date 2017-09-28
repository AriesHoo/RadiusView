# RadiusView
--------------------------
## 简介：

一个用于需要圆角矩形框背景的TextView或Layout的情况,减少直接使用时引入的shape资源文件，包括RadiusTextView，RadiusEditText,RadiusLinearLayout，RadiusRelativeLayout,RadiusFrameLayout,RadiusCheckBox，RadiusRadioButton,主要有圆角控制、默认背景(边框线)、按下背景(边框线)、不可点击背景(边框线)、选择selected背景(边框线)、选中checked背景(边框线);全圆角、四角单独设置圆角功能，使用方式参照layout_main.

<font color=#00ffff size=24>说明1.1.0以后版本UIWidget维护，不再做版本更新</font>

更全常见UI库参看 [UIWidget](https://github.com/AriesHoo/UIWidget)

[[Sample PC Download]](https://github.com/AriesHoo/RadiusView/blob/master/apk/sample.apk)

[[Sample Mobile Download]](http://fir.im/r84v)

![](https://github.com/AriesHoo/UIWidget/blob/master/apk/qr.png)

**Gradle集成**

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

## 录屏预览

![](https://github.com/AriesHoo/RadiusView/blob/master/screenshot/00.gif)

## 鸣谢

[FlycoRoundView](https://github.com/H07000223/FlycoRoundView)

