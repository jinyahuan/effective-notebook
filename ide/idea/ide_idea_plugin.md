<!--
* Licensed under MIT (https://github.com/jinyahuan/effective-notebook/blob/master/LICENSE)
* @author JinYahuan
* @since 1.0.0
-->

# IntelliJ IDEA Plugins

> * 插件的安装方式，操作基于[IntelliJ IDEA 社区版](https://github.com/JetBrains/intellij-community)原版（英文版）[ideaIC-2019.3.3]，若是旗舰版或者汉化版可能会有点差异
>     * 方式1: 在线安装
>         * File -> Settings... -> Plugins -> Marketplace
>         * 然后搜索插件的关键字或者全名，找到匹配的
>         * Install，然后重启就可以用了
>         * restart
>     * 方式2: 离线安装 在 IDEA 的在线插件库网站下载到本地，然后在
>         * 去[插件官网](https://plugins.jetbrains.com/)搜索插件，下面的插件都给了对应的链接了
>         * 点击```Versions```
>         * 查看```Compatibility with```，确定该插件是兼容你的```IDEA```版本的
>         * 然后```Download```，下完之后最好把压缩包放到```IDEA```文件夹同级的目录，方便更换版本的时候重新装
>         * File -> Settings... -> Plugins -> 齿轮图标 -> Install Plugin from Disk...
>         * 找到下下来的压缩包，然后点击```OK```
>         * ```Apply``` 或者 ```OK```
>         * restart


## Lombok
### 相关网址
* [插件网址](http://plugins.jetbrains.com/plugin/6317-lombok)
* [插件源码网址](https://github.com/mplushnikov/lombok-intellij-plugin)

## FindBugs (FindBugs-IDEA)
### 介绍
* 貌似搜不到了，只能去下载离线版的进行安装
* Provides static byte code analysis to look for bugs in Java code from within IntelliJ IDEA.
### 相关网址
* [插件网址](http://plugins.jetbrains.com/plugin/3847-findbugs-idea)
* [插件源码网址](https://github.com/andrepdo/findbugs-idea)

## SpotBugs
### 介绍
* Provides static byte code analysis to look for bugs in Java code from within IntelliJ IDEA.
### 相关网址
* [插件网址](https://plugins.jetbrains.com/plugin/14014-spotbugs)
* [插件源码网址](https://github.com/spotbugs/spotbugs)

## Spring Assistant
### 介绍
* Spring Assistant - IntelliJ plugin that assists you in developing spring applications
### 相关网址
* [插件网址](https://plugins.jetbrains.com/plugin/10229-spring-assistant)
* [插件源码网址](https://github.com/1tontech/intellij-spring-assistant)

## CheckStyle (CheckStyle-IDEA)
### 相关网址
* [插件网址](http://plugins.jetbrains.com/plugin/1065-checkstyle-idea/)
* [插件源码网址](https://github.com/jshiell/checkstyle-idea)

## Alibaba Java Coding Guidelines
### 相关网址
* [插件网址](http://plugins.jetbrains.com/plugin/10046-alibaba-java-coding-guidelines/)
* [插件源码网址](https://github.com/alibaba/p3c)

## Maven Helper
### 相关网址
* [插件网址](http://plugins.jetbrains.com/plugin/7179-maven-helper/)
* [插件源码网址](https://github.com/krasa/MavenHelper)

## VisualVM Launcher
### 相关网址
* [插件网址](http://plugins.jetbrains.com/plugin/7115-visualvm-launcher/)
* [插件源码网址](https://github.com/krasa/VisualVMLauncher)

## Free MyBatis plugin
### 介绍
* MyBatis 增强工具
* 生成 mapper xml 文件
* 快速从代码跳转到 mapper 及从 mapper 返回代码
* MyBatis 自动补全及语法错误提示
### 相关网址
* [插件网址](https://plugins.jetbrains.com/plugin/8321-free-mybatis-plugin)
* [插件源码网址](https://github.com/wuzhizhan/free-idea-mybatis)

## MyBatis Log Plugin
### 介绍
* MyBatis 增强工具
* 把 MyBatis 输出的日志还原成完整的 SQL 语句
### 相关网址
* [插件网址](https://plugins.jetbrains.com/plugin/8321-free-mybatis-plugin/)
* [插件源码网址](https://github.com/kookob/mybatis-log-plugin)

## jclasslib Bytecode viewer
### 介绍
* jclasslib is a bytecode viewer for Java class files
### 使用方式
* 第一次的使用方式为：选中```Java```文件后，点击菜单栏中的```View -> Show Bytecode With jclasslib```
### 相关网址
* [插件网址](https://plugins.jetbrains.com/plugin/9248-jclasslib-bytecode-viewer)
* [插件源码网址](https://github.com/ingokegel/jclasslib)

## ASM Bytecode Outline 2017
### 介绍
* 有个 ASM Bytecode Outline 插件，这个插件是前面那个插件的 fork 过来开发的，用来兼容新版的```IDEA```
* Displays bytecode for Java classes and ASMified code which will help you in your class generation. Updated for newer IDEA versions.
### 使用方式
* 第一次的使用方式为：选中```Java```文件后，右键 -> ```Show Bytecode outline```
### 相关网址
* [插件网址](https://plugins.jetbrains.com/plugin/10254-asm-bytecode-outline-2017)
* [插件源码网址](https://github.com/thiakil/asm-bytecode-intellij) 注意分支

## Bytecode View (IDEA 不知道哪个版本开始自带的)
### 介绍
* Shows the bytecode of a compiled Java class file.
### 使用方式
* 第一次的使用方式为：选中```Java```文件后，点击菜单栏中的```View -> Show Bytecode```
