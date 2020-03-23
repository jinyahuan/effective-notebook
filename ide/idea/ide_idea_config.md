<!--
* Licensed under MIT (https://github.com/jinyahuan/effective-notebook/blob/master/LICENSE)
* @author Yahuan Jin
* @since 1.0.0
-->

# IDE - IntelliJ IDEA - Configuration
* 注意：所有的相关配置操作都基于 [IntelliJ IDEA 社区版](https://github.com/JetBrains/intellij-community)原版（英文版），若是旗舰版或者汉化版可能会有点差异
* base on: ideaIC-2019.3.3

* TIPS: 不一定要按照操作顺序，一步步进到需要操作的地方，进入到```Settings...```之后就可以直接搜索关键字了


## Configure Development
* [Java Develop Configuration](./ide_idea_config_java.md)

### 设置换行符
> * File -> Settings... -> Editor -> Code Style
> * 在```General```栏中找到```Line separator```，默认是跟随系统，我这里选择```Unix and macOS (\n)```
> * ```Apply``` 或者 ```OK```

### 设置文件编码

#### 设置当前项目的文件编码
> * File -> Settings... -> Editor -> File Encoding
> * Global Encoding: 选择 UTF-8
> * Project Encoding: 选择 UTF-8
> * Properties Files (*.properties)
>   * Default encoding for properties files: 选择 ISO 8859-1
>   * transparent native-to-ascii conversion: 勾上  （这个主要是方便查看配置文件的内容，以本地化编码显示）
> * ```Apply``` 或者 ```OK```

#### 设置全局项目的文件编码
> * File -> Other Settings -> Settings for New Projects... -> Editor -> File Encoding
> * （除了进入的姿势不一样）之后的操作与[设置当前项目的文件编码][config_current_project_file_encoding_uri]一样

#### 过滤项目窗口指定的文件夹/文件
> * File -> Settings.. -> Editor -> File Types
> * 在下方的```Ignore files and folders```中补充自己需要过滤的文件夹或文件
>     * 例如：```.idea;.classpath;.project;.settings;*.iml;.gitignore;```
> * ```Apply``` 或者 ```OK```

#### 设置代码文件模板

##### 设置代码文件的文件头注释
> * File -> Settings... -> Editor -> File and Code Templates
> * 点击 Includes
> * 点击 File Header
> * 然后在右侧的输入框中输入自己的模板
>     * 例如：
>       ```
>       /**
>        * @author Yahuan Jin
>        * @since 1.0
>        */
>       ````
> * ```Apply``` 或者 ```OK```

##### 设置文件的 copyright
> * File -> Settings... -> Editor -> Copyright -> Copyright Profiles
> * 按情况新建/复制/导入一份，以新建为例
> * 点击```+```，然后输入名字，点击```OK```
> * ```name```框可以修改模板的名字
> * 在```Copyright text (may contain Velocity templates):```框中输入版权信息
>     * 例如：
>       ```Copyright (c) 2020 Yahuan Jin. All rights reserved.```
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


[config_current_project_file_encoding_uri]: ./ide_idea_config.md#设置当前项目的文件编码
