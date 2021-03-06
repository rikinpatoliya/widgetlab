[![](https://jitpack.io/v/uDevel/widgetlab.svg)](https://jitpack.io/#uDevel/widgetlab)

# Typing indicator or wait progress animation.

<img src="https://media.giphy.com/media/CSIyqIAxVFzhK/giphy.gif" width="30%" /> <img src="https://media.giphy.com/media/kPZRmEfmctbck/giphy.gif" width="30%" /> <img src="https://media.giphy.com/media/CSwfaFSSBvL6U/giphy.gif" width="30%" />


## Video of Sample app:

[![Youtube video of Sample app](http://img.youtube.com/vi/tNltD2vnbsw/0.jpg)](http://www.youtube.com/watch?v=tNltD2vnbsw "Sample app")

## How to use:
Just put it in your xml layout.  It can't get any easier than that.
```xml
 <com.udevel.widgetlab.TypingIndicatorView
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"/>
```
This gives you the default.  There are many optional [configurations](https://github.com/uDevel/widgetlab/wiki/Configurations) available.  This is recommeneded if you want to have unique animation; there are examples that you can modify from.


## Gradle:
Add to your project level build.gradle's allprojects
```xml
allprojects {
  repositories {
    ...
    maven { url 'https://jitpack.io' }
  }
}
```

Next add to your module level (app) build.gradle's dependencies block like this
```xml
dependencies {
          compile 'com.github.uDevel:widgetlab:0.9.1'
}
```

## Todos:
- Optimizing gc.
- More animation type.
