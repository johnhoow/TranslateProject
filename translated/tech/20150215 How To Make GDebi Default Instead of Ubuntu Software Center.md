如何使 GDebi 代替 Ubuntu Software Center 作为默认的 deb 包安装器
================================================================================
![](http://itsfoss.itsfoss.netdna-cdn.com/wp-content/uploads/2015/02/Make_GDebi_Default.jpeg)

假如你使用 Ubuntu 或像 Elementary OS Freya 一样的基于 Ubuntu 的 Linux 发行版本，也许你使用 Ubuntu 软件中心 来安装 `.deb` 可执行文件。对于查找和安装应用， Ubuntu 软件中心 是一个很好的应用，但它会消耗很多资源且运行速度缓慢。这就是为什么我更偏爱使用 [App Grid，一个 Ubuntu 软件中心 的轻量替代品][1] 的原因。

现在，假如你只是尝试安装一个 `.deb` 文件， 我不会向你推荐 Ubuntu 软件中心 或 App Grid ，我的建议为 GDebi，一个安装 Debian 可执行文件的专用程序。它极其轻量，且专注于安装 `.deb` 文件。关于 GDebi 最有用的功能是它也可以为你展示出将要安装的程序的依赖。

在这篇文章中，我们将见证 ** 如何安装 GDebi 和使用它代替 Ubuntu 软件中心 作为默认的安装器**。

### 在 Ubuntu 和其他 Linux 发行版本中安装 GDebi ###

打开终端并使用下面的命令:

    sudo apt-get install gdebi

### 使得 GDebi 成为默认的 `.deb`包安装器  ###

一旦你安装了 GDebi，就该是看看如何使它成为安装 `.deb` 文件的默认应用的时刻了。请读者注意在这篇教程中 我使用的是 Elementary OS Freya ，但下面的步骤对于所有基于 Ubuntu 的发行版本都是适用的。

首先下载一个 `.deb`文件。例如你已经下载了一个 Google Chrome 的 `.deb`包。进入下载目录并右击该 `.deb`文件。在这里，接着选择 **属性**选项。

![](http://itsfoss.itsfoss.netdna-cdn.com/wp-content/uploads/2015/02/GDebi_default.jpeg)

在属性中，你应该可以看到 **打开方式** 选项。点击它并选择为 GDebi。

![](http://itsfoss.itsfoss.netdna-cdn.com/wp-content/uploads/2015/02/GDebi_default_Ubuntu.jpeg)

这样下次你双击一个 `.deb` 文件，便会自动打开 GDebi 来安装这个`.deb` 文件。使用这样轻量的应用的确是一个[加速 Ubuntu][2] 或其他 Linux 系统的好方法。

你有什么意见呢？对于安装应用，你仍然偏爱于 Ubuntu 软件中心 还是 GDebi 呢？抑或,假如你是一个守旧派，也许你更喜欢 [新立得软件包管理器(Synaptic Package Manager)][3]？ 哪一个是你的最爱呢？

--------------------------------------------------------------------------------

via: http://itsfoss.com/gdebi-default-ubuntu-software-center/

作者：[Abhishek][a]
译者：[FSSlc](https://github.com/FSSlc)
校对：[校对者ID](https://github.com/校对者ID)

本文由 [LCTT](https://github.com/LCTT/TranslateProject) 原创翻译，[Linux中国](http://linux.cn/) 荣誉推出

[a]:http://itsfoss.com/author/abhishek/
[1]:http://itsfoss.com/app-grid-lighter-alternative-ubuntu-software-center/
[2]:http://itsfoss.com/speed-up-ubuntu-1310/
[3]:http://www.nongnu.org/synaptic/
