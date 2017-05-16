### Introduction\(概述\) {#Introduction}

有几种方法可以在不同的平台上运行Tomcat。这其中的主要文件是一个文件名为[running.txt](http://tomcat.apache.org/tomcat-8.5-doc/RUNNING.txt)。我们鼓励您参考该文件，如果下面的信息不能回答你的一些问题。

---

### Windows {#Windows}

在Windows上安装Tomcat是非常容易的,可以使用Windows安装程序。它的接口和功能类似于其他基于向导的安装程序，只有少数项目对其支持。

* **Installation as a service\(安装window服务\) -**无论选择什么设置，Tomcat都将被安装为Windows服务。使用“组件”页上的复选框将服务设置为“自动”启动，以便在Windows启动时自动启动Tomcat。为了获得最佳的安全性，该服务应作为一个单独的用户运行，具有较低的权限（请参见Windows Services管理工具及其文档）。



