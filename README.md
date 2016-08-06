[![Download](https://api.bintray.com/packages/opprime/maven/edittextfield/images/download.svg)](https://bintray.com/opprime/maven/edittextfield/_latestVersion)

## EditTextField 介绍：
- **删除按钮仿苹果IOS的TextField，可通过设置属性clearButtonMode来设置按钮显示方式**


***


## EditTextField使用方法：

### 1. Android Studio用户可在Gradle中添加：
```groovy
compile 'com.optimus:editTextField:0.2.0'
```

### 2. 然后在布局文件的根下，添加:
```groovy
xmlns:app="http://schemas.android.com/apk/res-auto"
```

### 3. EditFieldField属性介绍:
- *```app:clearButtonMode```，设置清除按钮的显示方式，其值如下:*
    - *never：不显示清空按钮 (默认)*
    - *always：始终显示清空按钮*
    - *whileEditing：输入框内容不为空且有获得焦点*
    - *unlessEditing：输入框内容不为空且没有获得焦点*
- *```app:clearButtonDrawable```，可自定义设置清除按钮的图片。不设置此属性值时，使用默认图片。*



### 效果展示：
<img src="demoScreenShot.gif" alt="输入内容前" title="输入内容前" width="270" height="486" />
