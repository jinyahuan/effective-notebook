<!--
* Licensed under MIT (https://github.com/jinyahuan/effective-notebook/blob/master/LICENSE)
* @author Yahuan Jin
* @since 1.0.0
-->

# IDE - IntelliJ IDEA - Configuration - Java Develop

#### 自动导包和自动优化imports
> * File -> Settings... -> Editor -> General -> Auto Import
> * 在```Java```框中勾选下面这两个
>     * Add unambiguous imports on the fly     这个的意思是：快速 import 唯一类（如果是多个同名类当然还是要手动选择的）
>     * Optimize imports on the fly (for current project)      这个的意思是：快速优化 import，比如排序、合并等等
> * ```Apply``` 或者 ```OK```

#### 实现序列化接口的类自动生成序列号 (serialVersionUID)
> * File -> Settings... -> Editor -> Inspections -> Java -> Serialization issues
> * 找到```Serializable class without 'serialVersionUID'```并勾选勾起来
> * 找到```Serializable non-'static' inner class without 'serialVersionUID''```并勾选勾起来
> * ```Apply``` 或者 ```OK```
> * 操作时，使用```Alt + Enter```快捷键就能看到```Add 'serialVersionUID' field```的警告了

#### 开启鼠标停留显示注释提示
> * File -> Settings... -> Editor -> General
> * Other 模块 找到 `Show quick documentation on mouse move`，打上勾
> * 设置 Tooltip delay （延迟时间），默认的也可以
> * ```Apply``` 或者 ```OK```

#### 配置代码风格（格式化）
> * 统一入口为: File | Settings | Editor | Code Style | Java
> * 具体配置见下面的相关配置
> * 配置完后: ```Apply``` 或者 ```OK```

##### else 放到新的一行（也就是大括号后不跟上 else 了）
> * 找到 ```Wrapping and Braces```
> * 找到 ```'if()' statement```
> * 勾选上 ```'else' on new line```

##### 简单的方法 方法与大括号在同一行
> * 找到 ```Wrapping and Braces```
> * 找到 ```Keep when reformatting```
> * 勾选上 ```Simple methods in one line```

##### JavaDoc 单行注释时不格式化成标准模式
> * 找到 ```JavaDoc```
> * 找到 ```Other```
> * 勾选上 ```Do not wrap one line comments```

--------

#### 设置全局（默认）的项目配置
> * 总入口: 起始页 -> Configure -> Structure for New Projects -> Project
> * 配置完后: ```Apply``` 或者 ```OK```

##### 设置全局（默认）的 JDK
> * 找到 ```Project SDK```，然后自己选择/创建

--------

#### 设置 Console 输出的行数上限
注意: 不是设定具体的行数，而是通过修改```buffer size```来延迟删除旧行
> * File | Settings | Editor | General | Console
> * 勾选```Override console cycle buffer size (1024 KB)```
> * 然后填上自己需要值
> * ```Apply``` 或者 ```OK```

--------
