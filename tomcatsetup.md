### Introduction\(概述\) {#Introduction}

有几种方法可以在不同的平台上运行Tomcat。这其中的主要文件是一个文件名为[running.txt](http://tomcat.apache.org/tomcat-8.5-doc/RUNNING.txt)。我们鼓励您参考该文件，如果下面的信息不能回答你的一些问题。

---

### Windows {#Windows}

在Windows上安装Tomcat是非常容易的,可以使用Windows安装程序。它的接口和功能类似于其他基于向导的安装程序，只有少数项目对其支持。

* **Installation as a service\(安装window服务\) -**无论选择什么设置，Tomcat都将被安装为Windows服务。使用“组件”页上的复选框将服务设置为“自动”启动，以便在Windows启动时自动启动Tomcat。为了获得最佳的安全性，该服务应作为一个单独的用户运行，具有较低的权限（请参见Windows Services管理工具及其文档）。
* **Java location **-安装程序将使用运行服务提供一个默认的JRE。安装程序使用注册表来确定一个java 7或更高版本的JRE的基础路径，包括JRE安装的JDK的一部分。在64位操作系统时，安装程序会首先寻找64位JRE,如果64位JRE不存在那么在寻找一个32位的JRE。这不是强制使用的安装程序检测到默认的JRE。安装任何java 7或更高版本的JRE（32位或64位）都可用于。
* **Tray icon **- 当Tomcat作为服务运行时，Tomcat运行时不会出现任何托盘图标。请注意，当选择在安装结束时运行Tomcat，托盘图标将被使用，即使Tomcat被安装为一个服务。
* _**有关如何管理Tomcat作为Windows服务的信息，请参阅Windows服务指南。**_

```
安装程序将创建快捷方式，允许启动和配置Tomcat。需要注意的是Tomcat管理Web应用程序只能在Tomcat运行时使用。
```

---

## Unix daemon

可以将Tomcat作为守护进程运行使用来自Commons Daemon项目的jsvc工具。对于jsvc源形式包括Tomcat二进制文件，需要编译。构建jsvc需要C的ANSI编译器（如GCC），GNU autoconf，和JDK。

在运行脚本之前，该JAVA\_HOME环境变量应该设置为JDK的基础路径。另外，当调用_./configure_，JDK的路径可以指定使用，           `--with-java`，如。`./configure --with-java=/usr/java`

