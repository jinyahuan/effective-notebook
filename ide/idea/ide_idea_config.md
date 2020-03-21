<!--
* Licensed under MIT (https://github.com/jinyahuan/effective-notebook/blob/master/LICENSE)
* @author Yahuan Jin
* @since 1.0.0
-->

# IDE - IntelliJ IDEA - Configuration
* 注意：所有的相关配置操作都基于 [IntelliJ IDEA 社区版](https://github.com/JetBrains/intellij-community)原版（英文版），若是旗舰版或者汉化版可能会有点差异
* base on: ideaIC-2019.3.3


## Configure Development

### 设置换行符
> * File -> Settings... -> Editor -> Code Style
> * 在```General```栏中找到```Line separator```，默认是跟随系统，我这里选择```Unix and macOS (\n)```
> * ```Apply``` 或者 ```OK```


## Configure UI

### 配置主题的字体
主题的字体包括：菜单栏、状态栏等等窗口的字体。
默认的主题字体是自动匹配的。
> * File -> Settings... -> Appearance & Behavior -> Appearance
> * 勾选上```Use custom font```后才能进行修改，然后根据喜好选择字体，根据实际情况修改字体大小
> * ```Apply``` 或者 ```OK```

### 配置代码窗口的字体
> * File -> Settings... -> Editor -> Font
> * 根据喜好选择字体，根据实际情况修改字体大小，行间距等等
> * ```Apply``` 或者 ```OK```

### 开启键盘+鼠标快捷控制字体大小
> * File -> Settings... -> Editor -> General
> * 在```Mouse```栏中勾选```Change font size (Zoom) with Ctrl + Mouse Wheel```
> * ```Apply``` 或者 ```OK```


## Configure Others

### 取消自动更新
> * File -> Settings... -> Appearance & Behavior -> System Settings -> Updates
> * 取消勾选的```Automatically check updates for [xxx]```
> * ```Apply``` 或者 ```OK```

### 取消启动时自动打开最后一次启动的项目
> * File -> Settings... -> Appearance & Behavior -> System Settings
> * 取消勾选的```Reopen last project on startup```
> * ```Apply``` 或者 ```OK```