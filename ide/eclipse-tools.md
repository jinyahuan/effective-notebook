<!--
* Licensed under MIT (https://github.com/jinyahuan/effective-notebook/blob/master/LICENSE)
* @author JinYahuan
* @since 1.0.0
-->

### Lombok

#### 介绍
减少开发时的代码冗余。比如说 POJO 类的 getter 和 setter方法。    
项目官网：[https://projectlombok.org/][lombok_website]    
Github 项目首页：[https://github.com/rzwitserloot/lombok][lombok_github_website]    

#### 使用

##### 在 Maven 项目中使用使用 Lombok
在 Maven pom.xml 的 dependencies 节点中加入：
模版：
```
    <dependency>
      <groupId>org.projectlombok</groupId>
      <artifactId>lombok</artifactId>
      <version>${lombok.version}</version>
      <scope>provided</scope>
    </dependency>
```
例子：
```
    <dependency>
      <groupId>org.projectlombok</groupId>
      <artifactId>lombok</artifactId>
      <version>1.16.12</version>
      <scope>provided</scope>
    </dependency>
```
##### 在 Eclipse 中使用 Lombok
1. 下载 Lombok。
    * 方式一：从本地 Maven 仓库中获取。
    * 方式二：在官网获取。
    * 方式三：在 Github 中的官方源码仓库中获取。
2. 安装 Lombok。
    * 方式一：自动配置。双击 Lombok jar包，然后指定（Specify location） Eclipse 启动器（即 eclipse.exe）的路径，然后在点击安装或更新（Install/update），最后退出安装器（Quit Installer）。
    * 方式二：手动配置。模版：`-javaagent:Lombok jar包路径`。
        * 将 Lombok jar包拷贝到与 Eclipse 启动器同级目录下，然后修改文件名为（这种做法每次升级 Lombok只需要重新拷贝一份然后修改文件名；当然也可以不改文件名，但是版本升级都需要改配置文件）：lombok.jar。
        * 修改 eclipse.ini。尽量将其加在最后一行（好像是要在什么加载之后加载的）。       
          案例：`-javaagent:lombok.jar`    

[lombok_website]:https://projectlombok.org/
[lombok_github_website]:https://github.com/rzwitserloot/lombok
