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