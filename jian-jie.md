## 概括

对于管理员和Web开发人员来说，在开始之前，您应该熟悉一些重要的信息。 本文档简要介绍了Tomcat容器的一些概念和术语。 同样，当你需要帮助时，去哪里。

---

## Terminology\(术语\)

在阅读这些文件的过程中，您将会遇到许多条款; 一些具体到Tomcat，以及其他由Servlet和JSP规范定义的。

* Context  web程序的上下文
* Term2 - This is it. \(PS:水平有限无法理解\)
* Term3 - This is it! \(PS:水平有限无法理解\)

---

## Directories and Files\(目录和文件\)

在整个文档中，您会注意到有许多对$CATALINA\_HOME的引用。  这表示您的Tomcat安装的根目录。 当我们说“这个信息可以在你的$CATALINA\_HOME/README.txt文件中找到”时，我们的意思是查看Tomcat安装根目录下的README.txt文件。 可选地，可以为每个实例定义$CATALINA\_BASE，为多个实例配置Tomcat。 如果未配置多个实例，则$CATALINA\_BASE与$CATALINA\_HOME相同。

这些是一些关键的tomcat目录：

* /bin - 启动，关机和其他脚本。 \* .sh文件对于Unix系统  \* .bat文件对于Windows系统 。 由于Win32命令行缺乏某些功能，因此这里还有一些附加文件。
* /conf - 配置文件和相关的DTD。 这里最重要的文件是server.xml。 它是容器的主要配置文件。
* /logs - 默认情况下日志文件存放在这个目录
* /webapps - 默认情况下这个地方存放你的web程序

---

### Configuring Tomcat \(配置Tomcat\) {#Configuring_Tomcat}

本节将了解容器配置过程中所使用的基本信息。

配置文件中的所有信息都是在启动时读取的，这意味着对文件的任何更改都必须重新启动容器。

---

## Where to Go for Help\(如何获取帮助\)

虽然我们尽了最大努力确保这些文件写得清楚易懂，但我们可能遗漏了一些东西。以下是各种网站和邮件列表，以防你被卡住。

请记住，一些问题和解决方案各不相同的主要版本的Tomcat。当您在网络上搜索时，将有一些与Tomcat 8无关的文档，但仅限于早期版本。

* 当前文档-大多数文件将列出潜在难题。一定要充分阅读相关的文件，因为它会节省你大量的时间和精力。没有什么比上网搜索能更快的获取帮助！
* 


