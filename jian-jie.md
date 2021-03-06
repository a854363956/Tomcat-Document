## Introduction\(概括\)

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

* 当前文档-大多数文件将列出潜在难题。一定要充分阅读相关的文件，因为它会节省你大量的时间和精力。没有什么能比上网搜索更快的获取帮助！
* [Tomcat FAQ](http://wiki.apache.org/tomcat/FAQ)
* [Tomcat WIKI](http://wiki.apache.org/tomcat/)
* Tomcat FAQ at jGuru
* Tomcat 邮件列表档案众多网站归档Tomcat邮件列表。由于链接的变化随着时间的推移，点击这里将搜索谷歌。
* Tomcat-user邮件列表，你可以订阅这里。如果你没有得到回复，然后有一个很好的机会，你的问题可能是列表中的档案或一个常见问题回答。虽然一般关于Web应用程序开发的问题有时会被询问和回答，但请将您的问题集中在Tomcat的具体问题上。
* Tomcat-dev邮件列表，你可以订阅这里。此列表保留用于讨论Tomcat本身的开发。关于tomcat配置的问题，和问题你遇到在开发和运行的应用程序，通常会更合适的tomcat-user清单代替。

而且，如果你觉得应该在文档，通过各种手段让我们知道的tomcat-dev列表。

---

### Comments\(评论\) {#comments_section}

```
注意：

本评论部分收集您关于改进Apache Tomcat文档的建议。
如果您有困难，需要帮助，请阅读帮助页面，并在Tomcat用户邮件列表上询问您的问题。不要在这里问这样的问题。这不是问答部分。
这里解释了Apache评论系统。评论可能会被删除，我们的主持人，如果他们要么实施或认为无效/关闭主题.
```

---



