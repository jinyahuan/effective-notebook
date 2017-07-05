<!--
* Licensed under MIT (https://github.com/jinyahuan/effective-notebook/blob/master/LICENSE)
* @author JinYahuan
* @since 1.0.0
-->

### 快捷键

#### 查看快捷键设置
1. 打开 Eclipse。
2. 菜单栏中依次点击 Windows -> Preferences -> General -> Keys。
	* 然后就可以查看所有的快捷键了。
	* 检索。可以在 “type filter text”框中输入对应的快捷键或备注快速查询该快捷键。如： 输入 Content Assist 或 Alt+/。

#### 常用快捷键
Up 指代 键盘上的 Up(↑) 键   
Down 指代 键盘上的 Up(↓) 键   
Left 指代 键盘上的 Up(←) 键   
Right 指代 键盘上的 Right(→) 键   

| 快捷键                    | Description                    | 描述                    |
| :---                     | :---                           | :---                   |
||||
| Alt+Shift+Up             || 选择光标所在的块（从单词、语句块、方法块等等，范围越来越大） |
| Alt+Shift+Right          || 同上 |
| Alt+Shift+Left           || 同上 |
| Alt+Shift+Down           || 与 Ctrl+Alt+Up/Right/Left 操作相反 |
| Alt+Up                   || 将光标所在行的内容移动到上面一行 |
| Alt+Down                 || 将光标所在行的内容移动到下面一行 |
| Alt+Right                || 回到上一次编辑的地方 |
| Alt+left                 || 回到下一次编辑的地方 |
| Alt+Enter                || 显示当前文件的 Properties |
| Alt+Shift+O              || 自动 import 包（若有重名的类需自己选择） |
| Alt+Shift+J              || 快速生成 Javadoc 注释 |
||||
| Ctrl+1                   || 快速修复代码错误（通常会有多种解决方式，需要自行选择最佳解决方式） |
| Ctrl+F11                 || 运行（可能有 Run on server 和 Jva Application【如果有 main 方法】 两种） |
| Ctrl+Alt+H               || 查看所选内容（对象和方法）调用情况 |
| Ctrl+Alt+Up              || 将光标所在行的内容复制到上面一行 |
| Ctrl+Alt+Down            || 将光标所在行的内容复制到下面一行 |
| Ctrl+D                   || 删除光标所在行 |
| Ctrl+Z                   || 撤销 |
| Ctrl+Y                   || 与 Ctrl+Z 操作相反|
| Ctrl+I                   || 更正所选行的缩进（只缩进行首） |
| Ctrl+H                   || 打开搜索特定内容的搜索框（功能很强大） |
| Ctrl+T                   | Show the quick hierarchy of the selected element | 所选内容的层级结构（超类到本类及其同级类） |
| Ctrl+Shift+F             || Format 选中的内容 |
| Ctrl+Shift+G             || 查找当前所选内容的所有引用（即查找与所选内容相同的地方） |
| Ctrl+Shift+R             || 打开搜索特定文件名的搜索框 |
||||
| Shift+Enter              || 在光标所在行下面一行插入空白行|
| Ctrl+Shift+Enter         || 在光标所在行上面一行插入空白行|
||||
| Table                    || 增加缩进 |
| Shift+Table              || 与 Table 操作相反 |



### 常规设置

#### workspace 设置
1. 打开 Eclipse。
2. 菜单栏中依次点击 Windows -> Preferences -> General -> Workspace。
	* 在右侧中找到 Text file encoding 类别框，使用 UTF-8 为默认的文件编码。
		* 勾选 Other，然后选择 UTF-8，如果没有找到该内容，则自己输入。
	*  在右侧中找到 New text file line delimiter 类别框，使用 Unix 的换行分割符。
		* 勾选 Other，然后选择 Unix，如果没有找到该内容，则自己输入。

#### 字体设置
1. 打开 Eclipse。
2. 菜单栏中依次点击 Windows -> Preferences -> General -> Appearance -> Colors and Fonts。
	* 设置字体、字型及大小
		* 展开 Basic。
		* 选择 Text Font 后，点击 Edit(或直接双击 Text font)。
		* 设置字体
			* 默认为 Consolas，如果需要替换，在下方的列表框自行选择。
		* 设置字型
			* 默认为 常规，如果需要替换，在下方的列表框自行选择。
		* 设置大小
			* 建议设置为 12 或 小四（太小看着难受，太大放不了多少代码）。

#### console 打印的最大字符数设置
1. 打开 Eclipse。
2. 菜单栏中依次点击 Windows -> Preferences -> Run/Debug -> Console。
	* 设置为无限制模
		* 去除 Limit console output 前的“勾”。
	* 设置为指定字符数
		* 勾选 Limit console output
		* 在 Console buffer size (characters) 中输入指定的值（默认为80000）。


### 格式设置

#### 设置 .xml 文件格式化
1. 打开 Eclipse
2. 菜单栏中依次点击 Windows -> Preferences -> XML -> XML Files -> Editor
	* 然后在右侧中找到 Formating 类别框
		1. 设置行宽（超过后换行）
			* 设置 Line width，以110个字符为例，那么输入110。
		2. 设置缩进
			* 使用4个空格（默认配置）：勾选 Indent using tabs（注意：使用此模式后，Indentation size 的值会自动失效）。
			* 自定义：
				* 先勾选 Indent using spaces。
				* 然后设置 Indentation size，以2个空格为例，那么输入2。

#### Java Code Style 设置
1. 打开 Eclipse
2. 菜单栏中依次点击 Windows -> Preferences -> Java -> Code Style
	* 设置 Formatter（代码格式化）
		* 点击 Formatter
		* 可以在默认的规则中选择一套，也可以 Import 本地外部规则库（自定义的或第三方的）
			* Import 本地外部规则库，点击 Import，然后找到文件，点击 打开 即可导入（注意：如果导入多个外部库时，修改一个库的同时可能会修改另外的库的规则，所以尽量只使用一套，想要替换的化先 Export 该规则库）。
			* 新建一个新的规则库（基于已存在的规则库）：暂略。
	* 设置 Code Templates（代码模版）
		* 点击 Code Templates
		* 具体设置暂略。

### 优化设置

#### 优化内容提示（注意：配置不好的可能会有点卡）
1. 打开 Eclipse
2. 菜单栏中依次点击 Windows -> Preferences -> Java -> Editor -> Content Assist
3. 然后在右侧中找到 Auto Activation 类别框
	1. 启用自动提示
		* 勾选 Enable auto activation。
	2. 设置延迟时间
		* 设置 Auto activation delay(ms) ，以300ms 为例，那么输入300。
	3. 设置提示的触发器（符合该内容中的某一项就会触发内容提示）
		* 设置 Auto activation triggers for Java，以26个大小写英文字母、点、括号为例，那么输入".ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz()"（双引号内的内容）。
