# C 语言资源大全中文版

我想很多程序员应该记得 GitHub 上有一个 Awesome - XXX 系列的资源整理。[awesome-c](https://notabug.org/koz.ross/awesome-c) 是 koz.ross 发起维护的 C 语言资源列表，内容包括了：构建系统、编译器、数据库、加密、初中高的教程/指南、书籍、库等等。

Awesome 系列虽然挺全，但基本只对收录的资源做了极为简要的介绍，如果有更详细的中文介绍，对相应开发者的帮助会更大。这也是我们发起这个开源项目的初衷。

* * *

### 我们要做什么？

- 基于 awesome-c 列表，我们将对其中的各个资源项进行编译整理。此外还将从其他来源补充好资源。
- 整理后的内容，将收录在[伯乐在线资源频道](http://hao.jobbole.com/)。可参考已整理的内容：
  - 《[libPhenom：Facebook开源的高性能C语言并发编程框架](http://hao.jobbole.com/libphenom/)》

* * *

### 如何参与本项目？

从下面的目录来看，本项目的工作量小不了，所以非常期待能有更多程序员一起来参与。

不过加入前，有几个小要求：

* 英文还不错，能读懂英文并用自己的话复述；
* 在用 C 语言；

如有兴趣，请加 QQ：50872495。加 Q 时请注明「C语言大全」。// 这不是 QQ 群。

* * *

### 本项目的参与者

- 维护者：
- 贡献者：[Yonah潇](http://www.jobbole.com/members/Yonah/)、[骷髅](http://www.jobbole.com/members/lighter_cd/)

注：名单不分排名，不定期补充更新

* * *

## 目录
*   [构建系统](#build-systems)
*   [编译器](#compilers)
*   [加密](#crypto)
*   [数据库](#database)
*   [文档生成](#documentation-generation)
*   [编辑器](#editors)
*   [环境](#environments)
*   [框架](#frameworks)
*   [游戏编程](#game-programming)
    *   [引擎](#engines)
    *   [资源](#resources)
*   [通用编程](#generic-programming)
*   [图形](#graphics)
*   [GUI](#gui)
*   [JSON](#json)
*   [学习、参考和指南](#learning-reference-and-tutorials)
    *   [在线资源](#online)
        *   [参考](#reference)
        *   [初级](#beginner)
        *   [中级](#intermediate)
        *   [高级](#advanced)
        *   [自学资源](#self-study-courses)
    *   [实体书](#physical)
        *   [参考](#reference-1)
        *   [初级](#beginner-1)
        *   [中级](#intermediate-1)
        *   [高级](#advanced-1)
*   [多媒体](#multimedia)
*   [网络编程](#networking-and-internet)
    *   [Web 框架](#web-frameworks)
*   [数值计算](#numerical)
*   [并行编程](#parallel-programming)
*   [正则表达式](#regex)
*   [序列化](#serialization)
*   [源码集锦](#source-code-collections)
*   [标准库](#standard-libraries)
*   [字符串处理](#string-manipulation)
*   [测试工具](#testing)
*   [文本编辑器扩展](#text-editor-extensions)
    *   [Emacs](#emacs)
    *   [Vim](#vim)
*   [工具](#tools)
*   [其他工具](#utilities)
*   [XML](#xml)
*   [其他资源](#resources-2)
    *   [有影响力的书](#influential-books)
    *   [知名网站/博客](#websites-blogs)
    *   [微信公众号](#weibo-weixin)

<h2 id="build-systems">构建系统</h2>

下面是一些 C 项目的自动化构建和测试工具。

*   [aimake](http://nethack4.org/projects/aimake/) - 一个被设计来避免复杂配置的构建工具。[GNU GPL3](http://www.gnu.org/licenses/gpl.html) 或更高版本。
*   [Autoconf](https://www.gnu.org/software/autoconf/) - 一个可扩展的 M4 宏指令包，提供命令行脚本来自动配置软件源码包，是 Autotools 的一部分。[GNU GPL3](http://www.gnu.org/licenses/gpl.html) 或更高版本。
*   [Automake](https://www.gnu.org/software/automake/automake.html) - 一个自动生成符合 GNU 代码标准的 Makefile.in 文件的工具。需要与 Autoconf 配合使用，它也是 Autotools 的一部分。[GNU GPL3](http://www.gnu.org/licenses/gpl.html) 或更高版本。
*   [Jam](http://www.perforce.com/resources/documentation/jam) - 一个构建系统，它被设计的比make更加易用。隐式地理解 C 的构建规则。[Jam License](https://en.wikipedia.org/wiki/Perforce_Jam#License)。
*   [Libtool](https://gnu.org/software/libtool/) - 一个通用库支持脚本，是 Autotools 的一部分。[GNU GPL3](http://www.gnu.org/licenses/gpl.html) 或更高版本。
*   [Meson](http://mesonbuild.com/) - 一个非常快，用户友好的构建系统，基于 Ninja。[Apache2.0](http://directory.fsf.org/wiki/License:Apache2.0).

<h2 id="compilers">编译器</h2>

*   [Clang](http://clang.llvm.org/) - 一个基于 LLVM 的 C 的编译器，支持 C11 标准。[NCSA](http://directory.fsf.org/wiki/License:IllinoisNCSA).
*   [CompCert](https://github.com/AbsInt/CompCert) - 一个经过充分验证的 C 编译器。支持几乎所有的 C89 标准。[GNU GPL2.1](http://www.gnu.org/licenses/gpl.html) 或更高版本。
*   [GCC](https://gcc.gnu.org/) - 在它的编译器集合中提供了 C 编译器。支持 C11 和 OpenMP 的标准。[GNU GPL3](http://www.gnu.org/licenses/gpl.html) 或更高版本。
*   [PCC](http://pcc.ludd.ltu.se/) - 一个值得尊敬的 C 编译器，支持 C99 标准。[Various licenses](http://pcc.ludd.ltu.se/licenses/)，完全免费。
*   [TCC](http://bellard.org/tcc/) - 一个迷你，速度快的 C 编译器，支持 C99（除了复杂的类型）。 [GNU LGPL2.1](http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html)

<h2 id="crypto">加密</h2>

*   [GnuTLS](http://www.gnutls.org/) - 一个安全通信库，实现了 SSL，TLS 和 DTLS。[GNU GPL2.1](http://www.gnu.org/licenses/gpl.html) 或更高版本。
*   [libgcrypt](https://www.gnu.org/software/libgcrypt/) - 一个通用的密码库，支持多种加密方法。 [GNU LGPL2.1](http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html) （代码），[GNU GPL2.1](http://www.gnu.org/licenses/gpl.html) 或更高版本（说明书和工具）。
*   [OpenSSL](https://www.openssl.org/) - 一个 SSL 和 TLS 协议的实现，还包括一个加密库。[Dual Licensed under the OpenSSL License and the SSLeay License](https://www.openssl.org/source/license.html)。
*   [libsodium](https://github.com/jedisct1/libsodium) - 一个现代，易用的加密库。[Expat](http://directory.fsf.org/wiki/License:Expat)。
*   [libtomcrypt](https://github.com/libtom/libtomcrypt) - 一个相当全面，模块化和可移植的工具集。公开领域。
*   [mbed TLS](https://tls.mbed.org/) - 一个 C 实现的加密库。[Apache2.0](http://directory.fsf.org/wiki/License:Apache2.0)。

<h2 id="database">数据库</h2>

下面列出了基于 C API 的数据库和数据存储

*   [BerkeleyDB](http://www.oracle.com/us/products/database/berkeley-db/overview/index.html) - 一个高性能的嵌入式键值对数据库。[GNU AGPLv3](https://gnu.org/licenses/agpl.html)。
*   [Hiredis](https://github.com/redis/hiredis) - 一个极简的 Redis 客户端。[3-clause BSD](http://directory.fsf.org/wiki/License:BSD_3Clause)。
*   [LMDB](http://symas.com/mdb/) - 一个极快，极简的嵌入式键值对数据存储系统。[newOpenLDAP](http://directory.fsf.org/wiki/License:OpenLDAPv2.7)。
*   [MariaDB](https://mariadb.com/) - 一个强壮，可扩展和可靠的 SQL 服务器，设计来作为 MySQL 的替代品。[3-clause BSD](http://directory.fsf.org/wiki/License:BSD_3Clause)。
*   [mongo-c-driver](https://github.com/mongodb/mongo-c-driver) - 一个高性能的 MongoDB 客户端。[Apache2.0](http://directory.fsf.org/wiki/License:Apache2.0).
*   [PostgreSQL](http://www.postgresql.org/) - 一个强大的对象关系数据库系统。[PostgreSQL licence](http://opensource.org/licenses/postgresql)。
*   [recutils](https://www.gnu.org/software/recutils/) - 一个工具和 C 库的集合，用于访问可编辑，纯文本的名为 recfiles 的数据库文件。[GNU GPL3](http://www.gnu.org/licenses/gpl.html) 或更高版本。
*   [Redis](http://redis.io/) - 一个先进的键值对存储系统。[3-clause BSD](http://directory.fsf.org/wiki/License:BSD_3Clause)。
*   [sophia](https://github.com/pmwkaa/sophia) - 一个现代，可嵌入的键值对数据库。[FreeBSD](http://directory.fsf.org/wiki?title=License:FreeBSD "License:FreeBSD")。
*   [SQLite](http://www.sqlite.org/) - 一个自包含，无服务器，零配置，支持事务的 SQL 数据库引擎，包括 C 接口。公开领域。
*   [UnQLite](http://unqlite.org/) - 一个自包含，无服务器，零配置，支持事务的 NoSQL 数据库引擎，包括 C 接口。[FreeBSD](http://directory.fsf.org/wiki?title=License:FreeBSD "License:FreeBSD")。

<h2 id="documentation-generation">文档生成</h2>

*   [Cxref](http://www.gedanken.org.uk/software/cxref/) - 生成 C 程序的文档，支持 LaTeX，HTML， RTF 或者 SGML 的格式。[GNU GPL2.1](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html)
*   [DocOnce](https://hplgit.github.io/doconce/doc/web/index.html) - 一种朴素的标签标记语言，可以用来生成多种格式的文档。[3-clause BSD](http://directory.fsf.org/wiki/License:BSD_3Clause).
*   [Doxygen](http://www.stack.nl/~dimitri/doxygen/index.html) - 一个事实上的标准工具，用于从注释的代码中生成 C 文档。能够生成多种格式的文档。[GNU GPL2.1](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html)。
*   [GTK-Doc](http://www.gtk.org/gtk-doc/) - 一个从注释的代码中生成 C 文档的工具，支持 Autotools [GNU GPL2.1](http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html)（代码）, [GNU FDL1.1](https://www.gnu.org/licenses/old-licenses/fdl-1.1.html)。

<h2 id="editors">编辑器</h2>

这些是特别精致，IDE 类型的编辑器。如果你想要一个程序员的文本编辑器，看别的地方。此外，不管你选择哪一款编辑器，它都支持 C。

*   [Anjuta DevStudio](http://anjuta.org/) - GNOME IDE。 [GNU GPL2.1](http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html)。
*   [Code::Blocks](http://www.codeblocks.org/) - 一个可扩展，可配置的 IDE，支持 C。[GNU GPL3](http://www.gnu.org/licenses/gpl.html)。
*   [CodeLite](http://www.codelite.org/) - 一个跨平台的 IDE。 [GNU GPL2.1](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html)。
*   [Eclipse](http://www.eclipse.org/ide/) - 一个用 Java 写成的 IDE。 [EPL](http://directory.fsf.org/wiki/License:EPLv1.0)。
*   [Geany](http://www.geany.org/) - 一个很小很快的 IDE。 [GNU GPL2.1](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html)及更高版本。
*   [KDevelop](https://www.kdevelop.org/) - KDE IDE. [GNU GPL2.1](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html)。

<h2 id="environments">环境</h2>

下面列出了被设计来引领 Windows 进入支持 C 的 21 世纪的技术。

*   [Cygwin](https://cygwin.com/) - 被设计用于在 Windows 下模拟 POSIX 兼容环境。[Various licenses, all free](https://cygwin.com/licensing.html)。
*   [MinGW-w64](http://mingw-w64.yaxm.org/doku.php/start) - 一个 Windows 下极简的 C 开发环境，支持 64 位。[Various licenses, all free](http://mingw.org/license)。

<h2 id="frameworks">框架</h2>

这一节包括提供数据结构的大型库和你所期待“现代”的标准库。

*   [APR](http://apr.apache.org/) - Apache Portable Runtime；另一个跨平台的实用函数库。[Apache2.0](http://directory.fsf.org/wiki/License:Apache2.0)。
*   [C Algorithms](https://github.com/fragglet/c-algorithms) - 一个常用算法和数据结构的集合。
*   [CPL](http://www.eso.org/sci/software/cpl/) - The Common Pipeline Library；一系列详尽，高效和强壮的软件工具包。[GNU GPL2.1](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html)。
*   [EFL](https://www.enlightenment.org/p.php?p=about/efl) - 一个大型实用数据结构和函数的的集合。多种许可证，完全免费。
*   [GLib](https://wiki.gnome.org/Projects/GLib) - 一个便携，高效和强大的实用函数和数据结构库。[GNU LGPL2.1](http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html)。
*   [GIO](https://developer.gnome.org/gio/) - 一个现代和易用的 VFS API。[GNU LGPL2.1]。
*   [GObject](https://developer.gnome.org/gobject/stable/) - 一个 C 的面向对象系统和对象模型。[GNU LGPL2.1](http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html)。
*   [libnih](https://github.com/keybuk/libnih) - 一个轻量级的 C 函数和数据结构库。[GNU GPL2.1](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html)。
*   [libU](http://www.koanlogic.com/libu/) - 一个提供基本实用函数的迷你库，包括内存分配，字符串处理和日志功能。
*   [PBL](http://www.mission-base.com/peter/source/) - 一个包括实用函数，特色数据结构等的大型库。[GNU LGPL2.1](http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html)及更高版本（库），[GNU GPL2.1](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html)及更高版本（测试代码）。
*   [qlibc](https://github.com/wolkykim/qlibc) - 一个简单且强大的 C 库，当我们想要小且轻的库时，可作为 Glib 的替代品。[qLib license](https://github.com/wolkykim/qlibc/blob/master/LICENSE) (类似于 [FreeBSD](http://directory.fsf.org/wiki?title=License:FreeBSD "License:FreeBSD")).
*   [stb](https://github.com/nothings/stb) - 一系列单文件 C 库。公共领域。
*   [libcstl](http://hao.jobbole.com/libcstl/)：标准C语言通用数据结构和常用算法库。[官网](http://libcstl.org/)

<h2 id="game-programming">游戏编程</h2>

<h3 id="engines">引擎</h3>

这些作为 C 游戏编程代码的例子。

*   [Corange](http://hao.jobbole.com/corange/)：一个纯 C 的游戏引擎。[官网](https://github.com/orangeduck/Corange)
*   [FreeBSD](http://directory.fsf.org/wiki?title=License:FreeBSD "License:FreeBSD")。
*   [Darkplaces](https://icculus.org/twilight/darkplaces/) - 一个 Quake2 引擎的修改版本。[GNU GPL2.1](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html)。
*   [ioquake3](https://github.com/ioquake/ioq3) - Quake3 引擎，终于免费啦。[GNU GPL2.1](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html)。
*   [Orx](https://bitbucket.org/orx/orx) - 一个便携，轻量级，插件化，数据驱动，面向 2D 的游戏引擎。[zlib](http://directory.fsf.org/wiki/License:Zlib)。
*   [Quake2](https://github.com/id-Software/Quake-2) - Quake2 引擎。[GNU GPL2.1](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html)。
*   [Spearmint](https://github.com/zturtleman/spearmint) - 一个为 FPS 游戏设计的引擎。[GNU GPL3](http://www.gnu.org/licenses/gpl.html)及更高版本。

<h3 id="resources">资源</h3>

这些是筛选过的，对游戏编程有用的库。

*   [Allegro](http://liballeg.org) - 一个跨平台，视频游戏开发和多媒体库。[zlib](http://directory.fsf.org/wiki/License:Zlib)。
*   [Chipmunk2D](https://github.com/slembcke/Chipmunk2D) - 一个快且轻量级的 2D 游戏物理库。[Expat](http://directory.fsf.org/wiki/License:Expat)。
*   [CSFML](http://www.sfml-dev.org/download/csfml/) - 一个用 C 封装的 [SFML](http://www.sfml-dev.org/index.php)。[zlib](http://directory.fsf.org/wiki/License:Zlib)。
*   [FreeGLUT](https://github.com/dcnieho/FreeGLUT) - 一个替代性的 OpenGL 实用工具包。允许用 OpenGL 上下文创建和管理窗口。[X11](http://directory.fsf.org/wiki/License:X11)。
*   [GLFW](http://www.glfw.org/) - 一个使用 OpenGL 上下文创建窗口的多平台库。[zlib](http://directory.fsf.org/wiki/License:Zlib)。
*   [libao](https://github.com/timonwong/libao) - 一个有多种输出的跨平台音频库。[GNU GPL2.1](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html)及更高版本。
*   [RetroArch](https://github.com/libretro/RetroArch) - [libretro](http://www.libretro.com/) 的参考前端。[GNU GPL3](http://www.gnu.org/licenses/gpl.html)。
*   [SDL](https://www.libsdl.org/) - 一个跨平台库，通过 OpenGL 提供音频，键盘，鼠标，操纵杆和图形硬件的底层访问。[zlib](http://directory.fsf.org/wiki/License:Zlib)。
*   [SDL2](https://www.libsdl.org/)- 一个跨平台库，通过 OpenGL 提供音频，键盘，鼠标，操纵杆和图形硬件的底层访问。这是最新版本。[zlib](http://directory.fsf.org/wiki/License:Zlib)。

<h2 id="generic-programming">通用编程</h2>

*   [klib](https://github.com/attractivechaos/klib) - 小且轻量级的常用算法和数据结构实现。[Expat](http://directory.fsf.org/wiki/License:Expat)。

<h2 id="graphics">图形</h2>

*   [Cairo](http://cairographics.org/) - 一个 2D 图像库。[GNU LGPL2.1](http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html) 或者 [MPLv1.1](https://directory.fsf.org/wiki/License:MPLv1.1)。
*   [Cogl](https://github.com/rib/cogl-web/wiki) - 一个 GPU 图像和实用 API。[Expat](http://directory.fsf.org/wiki/License:Expat)（依赖使用 [3-clause BSD](http://directory.fsf.org/wiki/License:BSD_3Clause) 许可，库使用 [LGPLv2.1](http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html) 许可）。
*   [Clutter](https://blogs.gnome.org/clutter/get-it/) - 一个基于 OpenGL 的 UI 库。[GNU LGPL2.1](http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html)。
*   [heman](https://github.com/prideout/heman) - 一个迷你图像实用工具库，处理高度图，法线图，距离场等。[Expat](http://directory.fsf.org/wiki/License:Expat)。
*   [libcaca](https://github.com/cacalabs/libcaca) - 一个基于终端接口的 ASCII 渲染器。[WTFPLv2](http://www.wtfpl.net/txt/copying/)。
*   [libimagequant](http://pngquant.org/lib/) - 小且轻量级的库，用于高质量的从 RGBA 图像到 8 位像素图的转换。[FreeBSD](http://directory.fsf.org/wiki?title=License:FreeBSD "License:FreeBSD")。
*   [libjpeg-turbo](http://libjpeg-turbo.virtualgl.org/) - 一个更快的读写 JPEG 文件库。[Various licences](http://www.libjpeg-turbo.org/About/License)。
*   [libpng](https://http://www.libpng.org/) - 官方 PNG 参考库。[libpng license](http://www.libpng.org/pub/png/src/libpng-LICENSE.txt)。
*   [libxmi](https://gnu.org/software/libxmi/) - 一个光栅化 2D 位图的函数库。[GNU GPL3](http://www.gnu.org/licenses/gpl.html) 或更高版本。
*   [mozjpeg](https://github.com/mozilla/mozjpeg) - 一个提升 JPEG 图像质量的编码器。[3-clause BSD](http://directory.fsf.org/wiki/License:BSD_3Clause)。
*   [OpenGL](https://www.opengl.org/) - 一个高性能图像的工业标准，提供了原生 C语言 绑定。[Various licenses](http://www.sgi.com/tech/opengl/?/license.html)。

<h2 id="gui">GUI</h2>

这些具体来说就是[控件工具包](http://en.wikipedia.org/wiki/Widget_toolkit)

*   [GTK+](http://www.gtk.org/) - 一个跨平台的控件工具包。[GNU LGPL2.1](http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html)。
*   [IUP](http://webserver2.tecgraf.puc-rio.br/iup/) - 另一个跨平台的控件工具包。[Expat](http://directory.fsf.org/wiki/License:Expat)。
*   [Tk](http://www.tcl.tk/) - 一个基本控件工具包，Tcl/Tk 的一部分。[Tcl/Tk License](http://www.tcl.tk/software/tcltk/license.html)。
*   [XForms Toolkit](http://xforms-toolkit.org/) - 一个为 XWindow 设计的控件工具包。[GNU LGPL2.1](http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html)。

<h2 id="json">JSON</h2>

*   [Jansson](http://www.digip.org/jansson/) - 一个编码，解码和处理 JSON 的 C 库。[Expat](http://directory.fsf.org/wiki/License:Expat)。
*   [jsmn](http://zserge.com/jsmn.html) - 一个极简的 JSON 解析器。[Expat](http://directory.fsf.org/wiki/License:Expat)。
*   [json-c](https://github.com/json-c/json-c/wiki) - 一个处理 JSON 的库。[Expat](http://directory.fsf.org/wiki/License:Expat)。
*   [WJElement](https://github.com/netmail-open/wjelement/) - 高级 JSON 处理库，支持 JSON Schema。任意版本的 LGPL。
*   [YAJL](https://lloyd.github.io/yajl/) - 一个很快的 JSON 流解析 C 库。[ISC](http://directory.fsf.org/wiki/License:ISC)。

<h2 id="learning-reference-and-tutorials">学习、参考和指南</h2>

下面列出了学习 C 编程的资源，或者跟 C 编程相关的有用的东西。

### 在线

#### 参考

*   [SEI CERT C 编码标准](https://www.securecoding.cert.org/confluence/display/c/SEI+CERT+C+Coding+Standard)
*   [C FAQ - comp.lang.c 常见问题](http://c-faq.com/)
*   [GNU/Linux 下 C/POSIX 标准库实现的比较](http://www.etalabs.net/compare_libcs.html)
*   [C11 标准草案](http://www.open-std.org/JTC1/SC22/WG14/)
*   [GNU C 参考手册](https://www.gnu.org/software/gnu-c-manual/)
*   [Robert Pike 的 C 笔记](http://kamalatta.ddnss.de/otherdocs/pikestyle.html)

#### 初级

*   [指针教程](http://home.netcom.com/~tjensen/ptr/pointers.htm)
*   [C 语言指针 5 分钟教程](http://blog.jobbole.com/25409/)
*   [C 语言内存地址基础](http://blog.jobbole.com/44845/)
*   [C 语言函数指针基础](http://blog.jobbole.com/44639/)
*   [C 语言指针和数组基础](http://blog.jobbole.com/44863/)
*   [构建 C 项目](http://nethack4.org/blog/building-c.html)
*   [C 编程百科全书](https://en.wikibooks.org/wiki/C_Programming)
*   [“有趣”的 C 介绍](https://gist.github.com/eatonphil/21b3d6569f24ad164365)
*   [用 GDB 学习 C](https://www.recurse.com/blog/5-learning-c-with-gdb)
*   [POSIX 线程编程指南](https://computing.llnl.gov/tutorials/pthreads/) (有点过时，但大部分还是有效和有用的)
*   [GNU C 编程指南](http://www.crasseux.com/books/ctut.pdf) (在线 PDF)
*   [C 语言中的模板](http://blog.pkh.me/p/20-templating-in-c.html)


#### 中级

*   [8 个你应该知道的 GDB 技巧](https://blogs.oracle.com/ksplice/entry/8_gdb_tricks_you_should)
*   [10 个 C99 技巧](http://blog.noctua-software.com/c-tricks.html)
*   [深入并发：尝试互斥锁和原子操作](http://jvns.ca/blog/2014/12/14/fun-with-threads/)
*   [OpenMP 介绍](https://www.youtube.com/playlist?list=PLLX-Q6B8xqZ8n8bwjGdzBJ25X2utwnoEG) (视频)
*   [OpenMP 指南](https://computing.llnl.gov/tutorials/openMP/) (针对 OpenMP3 标准)
*   [memcpy 与 memmove 的比较](http://www.tedunangst.com/flak/post/memcpy-vs-memmove)
*   [MPI 指南](https://computing.llnl.gov/tutorials/mpi/)
*   [C 语言中一些未知特性或者技巧](http://proprogramming.org/some-unknown-features-or-tricks-in-c-language/)
*   [失落的 C 语言结构体封装艺术](http://blog.jobbole.com/57822/)
*   [C 程序员需要了解的内存知识](http://marek.vavrusa.com/c/memory/2015/02/20/memory/)
*   [每个 C 程序员需要知道的未定义行为知识](http://blog.llvm.org/2011/05/what-every-c-programmer-should-know.html)

#### 高级

*   [C 中的高级元编程](http://250bpm.com/blog:56)
*   [一个快速教程：如何实现和调试 malloc，free，calloc，和 realloc](http://danluu.com/malloc-tutorial/)
*   [位操作技巧](https://graphics.stanford.edu/~seander/bithacks.html)
*   [我不懂 C](http://kukuruku.co/hub/programming/i-do-not-know-c)
*   [在 C 语言中实现智能指针](http://snaipe.me/c/c-smart-pointers/)
*   [C 中的内联函数](http://www.greenend.org.uk/rjk/tech/inline.html)
*   [C 中的自定义控制结构元编程](http://www.chiark.greenend.org.uk/~sgtatham/mp/)
*   [用 C 的宏解决临时内存问题](http://www.samnip.ps/thought/macro-storage-for-inverse-comma)
*   [C 语言中一些不为人知的角落](https://docs.google.com/presentation/d/1h49gY3TSiayLMXYmRMaAEMl05FaJ-Z6jDOWOz3EsqqQ/edit?pli=1#slide=id.gaf50702c_0153)
*   [编写高效的 C 和 C 代码优化](http://www.codeproject.com/Articles/6154/Writing-Efficient-C-and-C-Code-Optimization)

#### 自学教程

*   [C 语言认证协会预备课程](http://www.cppinstitute.org/?page_id=1487)

### 实体书

#### 参考资料

*   [C: A Reference Manual 5E](http://careferencemanual.com/) - C99 完全参考手册
*   [C Pocket Reference](http://shop.oreilly.com/product/9780596004361.do) - C99 简明参考手册
*   [The C Programming Language 2E](https://en.wikipedia.org/wiki/The_C_Programming_Language) - 第一本 C 语言书籍，由 C 的创造者编写。

#### 初级

*   [C Primer Plus 6E](http://www.pearsonhighered.com/educator/product/C-Primer-Plus-6E/9780321928429.page) - 一个全面的 C11 编程指南。
*   [C Programming: A Modern Approach](http://knking.com/books/c2/index.html) - 一本极好的学习 C 基础的书。
*   [Head First C](http://shop.oreilly.com/product/0636920015482.do) - 一本“深入浅出”风格的学习 C 的书籍。

#### 中级

*   [21st Century C](http://shop.oreilly.com/product/0636920033677.do) - 一本非常好的 C 语言书籍，可作为第二选择。
*   [Understanding and Using C Pointers](http://shop.oreilly.com/product/0636920028000.do) - 一本深入讨论 C 指针的书。
*   [ZeroMQ](http://shop.oreilly.com/product/0636920026136.do) - 一本介绍如何用 C 使用 ZeroMQ 的书。

#### 高级

*   [Expert C Programming: Deep C Secrets](http://dl.acm.org/citation.cfm?id=179241) - 一本从有趣，深度和娱乐的视角分析 C 内部结构的书籍。

<h2 id="multimedia">多媒体</h2>

*   [FFMPEG](https://www.ffmpeg.org/) - 一个完整，跨平台的录音，转换和流化视频以及音频的解决方案。[GNU LGPL2.1](http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html) 或更高版本，部分是 [GNU GPL2.1](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html) 或更高版本。
*   [GStreamer](http://gstreamer.freedesktop.org/) - 一个声音和可视化媒体的框架。[GNU LGPL2.1](http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html)。
*   [lodepng](http://lodev.org/lodepng/) - 一个简单的 PNG 图像解码器和编码器，不需要其他依赖。[3-clause BSD](http://directory.fsf.org/wiki/License:BSD_3Clause).

<h2 id="networking-and-internet">网络编程</h2>

*   [asnlc](http://lionet.info/asn1c/compiler.html) - 一个把 ASN.1 规范转换为 C 代码的编译器。[FreeBSD](http://directory.fsf.org/wiki?title=License:FreeBSD "License:FreeBSD")。
*   [czmq](https://github.com/zeromq/czmq) - 一个 ZeroMQ 的高级绑定。
*   [GNU adns](https://gnu.org/software/adns/) - 一个高级，易用，异步的 DNS 客户端和实用工具。[GNU GPL3](http://www.gnu.org/licenses/gpl.html) 及更高版本。
*   [GNU SASL](https://gnu.org/software/gsasl/) - 一个简单身份认证和安全层和一些常见 SASL 机制的实现。[GNU GPL3](http://www.gnu.org/licenses/gpl.html) 及更高版本。
*   [GnuTLS](http://www.gnutls.org/) - 一个安全通信库，实现了 SSL，TLS 和 DTLS。[GNU LGPL2.1](http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html) 及更高版本。
*   [gumbo-parser](https://github.com/google/gumbo-parser) - 一个 C99 标准的 HTML5 解析库。[Apache2.0](http://directory.fsf.org/wiki/License:Apache2.0)。
*   [http-parser](https://github.com/joyent/http-parser) - 一个 HTTP 请求回应解析器。[Expat](http://directory.fsf.org/wiki/License:Expat)。
*   [ldns](http://www.nlnetlabs.nl/projects/ldns/index.html) - 一个简化 DNS 编程的库。[3-clause BSD](http://directory.fsf.org/wiki/License:BSD_3Clause)。
*   [libcurl](http://curl.haxx.se/libcurl/) - 一个客户端的 URL 转换库，支持多种格式。[curl license](http://curl.haxx.se/docs/copyright.html)。
*   [LibEtPan](https://github.com/dinhviethoa/libetpan) - 一个邮件库，支持 IMAP，SMTP，POP 和 NNTP 网络协议。[3-clause BSD](http://directory.fsf.org/wiki/License:BSD_3Clause)。
*   [libev](http://software.schmorp.de/pkg/libev.html) - 一个事件驱动库。[FreeBSD](http://directory.fsf.org/wiki?title=License:FreeBSD "License:FreeBSD").
*   [libevent](http://libevent.org/) - 一个在网络服务器中事件驱动库的可替代品。[3-clause BSD](http://directory.fsf.org/wiki/License:BSD_3Clause)。
*   [libgss](https://gnu.org/software/gss/) - 通用安全服务。[GNU GPL3](http://www.gnu.org/licenses/gpl.html) 或更高版本。
*   [libhttpd](http://www.hughes.com.au/products/libhttpd/) - 一个给应用或嵌入式设备添加基本 Web 服务器功能的库。[GNU GPL2](http://www.gnu.org/licenses/gpl.html)。
*   [libidn](https://gnu.org/software/libidn/) - Stringprep，Punycode 和 IDNA 规范的实现。[GNU GPL3](http://www.gnu.org/licenses/gpl.html) 或更高版本。
*   [libmicrohttpd](https://gnu.org/software/libmicrohttpd/) - 一个迷你库，可作为其他应用的一部分，让运行 HTTP 服务器变得简单。[GNU LGPL2.1](http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html) 或更高版本。
*   [libsoup](https://wiki.gnome.org/action/show/Projects/libsoup?action=show&redirect=LibSoup) - 一个 GNOME HTTP 客户端/服务器库，使用了 GObject。[GNU LGPL2.1](http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html)。
*   [lwan](https://github.com/lpereira/lwan) - 一个实验性，可扩展，高性能的 HTTP 服务器。 [GNU GPL2.1](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html)。
*   [mongoose](https://github.com/cesanta/mongoose) - 基于 C 的嵌入式 Web 服务器。[GNU GPL2.1](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html)。
*   [nanomsg](https://github.com/nanomsg/nanomsg) - 一个基于 C 的 ZeroMQ 实现。[Expat](http://directory.fsf.org/wiki/License:Expat)。
*   [onion](https://github.com/davidmoreno/onion) - 易于使用的 HTTP 服务器库。[Apache2.0](http://directory.fsf.org/wiki/License:Apache2.0)。
*   [OpenSSL](https://www.openssl.org/) - 一个 SSL 和 TLS 协议的实现，还包括一个加密库。[Dual Licensed under the OpenSSL License and the SSLeay License](https://www.openssl.org/source/license.html)。
*   [oSip](https://gnu.org/software/osip/) - 一个基于 C 的 SIO 实现，没有额外的依赖。[GNU LGPLv2.1](http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html) 或更高版本。
*   [s2n](https://github.com/awslabs/s2n) - 一个 C99 标准的 TLS/SSL 协议的实现，简单，快并且以安全优先。[Apache2.0](http://directory.fsf.org/wiki/License:Apache2.0)。
*   [socket99](https://github.com/silentbicycle/socket99) - BSD 套接字 API 的 C99 封装。[ISC](http://directory.fsf.org/wiki/License:ISC)。
*   [Tox](https://github.com/irungentoo/toxcore) - 一个通信平台，被设计为 Skype 杀手。[GNU GPL3](http://www.gnu.org/licenses/gpl.html)。
*   [twitc](https://github.com/sinemetu1/twitc) - 一个与 Twitter OAuth API 交互的迷你 C 库。[Expat](http://directory.fsf.org/wiki/License:Expat)。

<h3 id="web-frameworks">Web框架</h3>

*   [balde](https://github.com/balde/balde) - 一个基于 GLib 的 C 微框架。 [GNU LGPLv2.1](http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html)。

<h2 id="#numerical">数值计算</h2>

*   [apophenia](https://github.com/b-k/apophenia) - 一个用于统计和科学计算的库。[GNU GPL2.1](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html)。
*   [ATLAS](http://math-atlas.sourceforge.net/) - 自动调谐线性代数软件。 [3-clause BSD](http://directory.fsf.org/wiki/License:BSD_3Clause)。
*   [BLAS](http://www.netlib.org/blas/) - Basic Linear Algebra Subprograms；提供向量和矩阵操作的一系列操作。[BLAS license](http://www.netlib.org/blas/#_licensing)。
*   [Cuba](http://www.feynarts.de/cuba/) - 一个计算多维的数值积分的库。 [GNU LGPLv3](http://www.gnu.org/licenses/lgpl.html)。
*   [FFTW](http://www.fftw.org/) - The Fastest Fourier Transform in the West；一个高度优化的快速傅立叶变换例程。[GNU GPL2.1](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html) 或更高版本。
*   [FLINT](http://flintlib.org/) - Fast Library for Number Theory;一个支持算数，多项式，幂级数和矩阵等。[GNU GPL2.1](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html) 或更高版本。
*   [GLPK](https://gnu.org/software/glpk/) - GNU Linear Programming Kit；一个求解大规模线性规划，混合整数规划和其他相关问题。[GNU GPL3](http://www.gnu.org/licenses/gpl.html) 或更高版本。
*   [GMP](https://gmplib.org/) - GNU Multple Precision Arithmetic Library；一个支持任意精度计算的库。双重许可 [GNU GPL2.1](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html) 和 [GNU LGPLv3](http://www.gnu.org/licenses/lgpl.html)。
*   [GNU MPC](http://www.multiprecision.org/index.php?prog=mpc&page=home) - 一个支持复杂数字计算的库。[GNU LGPL3](http://www.gnu.org/licenses/lgpl.html) 或更高版本。
*   [GNU MPFR](http://mpfr.loria.fr/index.html) - 一个支持任意精度的浮点数计算库。[GNU LGPL3](http://www.gnu.org/licenses/lgpl.html) 或更高版本（大多数最近版本），[GNU LGPL2.1](http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html) 或更高版本（2.4.x 之前）。
*   [GNU MPRIA](https://gnu.org/software/mpria/) - 一个支持多精度合理区间运算的可扩展数学库。[GNU GPL3](http://www.gnu.org/licenses/gpl.html) 或更高版本。
*   [GSL](http://www.gnu.org/software/gsl/) - The GNU Scientific Library；一个精确的数值计算库。[GNU GPL3](http://www.gnu.org/licenses/gpl.html)。
*   [KISS FFT](http://sourceforge.net/projects/kissfft/) - 一个非常快的傅里叶变换库。[3-clause BSD](http://directory.fsf.org/wiki/License:BSD_3Clause)。
*   [LAPACKE](http://www.netlib.org/lapack/lapacke.html) - 一个 [LAPACK](http://www.netlib.org/lapack/) 的 C 接口。[3-clause BSD](http://directory.fsf.org/wiki/License:BSD_3Clause)。
*   [PARI/GP](http://pari.math.u-bordeaux.fr/) - 一个数论的计算机代数系统，包括 C 编译器。[GNU GPL2.1](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html) 或更高版本。
*   [PETSc](http://www.mcs.anl.gov/petsc/) - 一系列数据结构和例程，用于计算由偏微分方程建模的应用程序的可扩展并行解。[FreeBSD](http://directory.fsf.org/wiki?title=License:FreeBSD "License:FreeBSD")。
*   [SLEPc](http://slepc.upv.es/) - 一个在并行计算机中的解决大型，稀疏特征值问题的软件库。[GNU LGPL3](http://www.gnu.org/licenses/lgpl.html)
*   [Yeppp!](http://www.yeppp.info/) - 非常快，SIMD 优化的数学库。 [3-clause BSD](http://directory.fsf.org/wiki/License:BSD_3Clause)。

<h2 id="parallel-programming">并行编程</h2>

*   [cchan](http://repo.hu/projects/cchan/) - 一个线程间通信通道构建的小型库。公共领域。
*   [ck](https://github.com/concurrencykit/ck) - 并发原语，安全内存回收机制和非阻塞数据结构。[FreeBSD](http://directory.fsf.org/wiki?title=License:FreeBSD "License:FreeBSD")。
*   [mill](http://libmill.org/) - 用 C 写成的 Go 风格并发。[X11](https://directory.fsf.org/wiki/License:X11)
*   [MPICH](http://www.mpich.org/) - MPI 的另一种实现。[MPICH licence](http://git.mpich.org/mpich.git/blob_plain/6aab201f58d71fc97f2c044d250389ba86ac1e3c:/COPYRIGHT)。
*   [OpenMP](http://openmp.org/wp/about-openmp/) - 一组 C 编译指令，使其易于并行化代码。标准（许可不适用）。
*   [OpenMPI](https://github.com/open-mpi/ompi) - 一个消息传输接口实现。[3-clause BSD](http://directory.fsf.org/wiki/License:BSD_3Clause)。
*   [PETSc](http://www.mcs.anl.gov/petsc/) - 一系列数据结构和例程，用于计算由偏微分方程建模的应用程序的可扩展并行解。[FreeBSD](http://directory.fsf.org/wiki?title=License:FreeBSD "License:FreeBSD")。
*   [pth](https://gnu.org/software/pth/) - 一个非抢占式优先级调度多线程执行的可扩展实现。[GNU GPL3](http://www.gnu.org/licenses/gpl.html) 或者更高版本。
*   [pthreads](http://en.wikipedia.org/wiki/POSIX_Threads) - POSIX 线程库。标准（没有适用的许可）。
*   [SLEPc](http://slepc.upv.es/) - 一个在并行计算机中的解决大型，稀疏特征值问题的软件库。[GNU LGPL3](http://www.gnu.org/licenses/lgpl.html)。
*   [TinyCThread](https://tinycthread.github.io/) - 一个可扩展，小型的 C11 标准线程 API 实现。[zlib](http://directory.fsf.org/wiki/License:Zlib)。

<h2 id="regex">正则表达式</h2>

> 有些人遇到问题时就会想：“啊，我知道了，我可以使用正则表达式”。于是现在他们有了两个问题。- Jamie Zawinski。

*   [PCRE](http://www.pcre.org/) - 与 Perl 5 正则表达式完全相同的实现。[3-clause BSD](http://directory.fsf.org/wiki/License:BSD_3Clause)。
*   [SLRE](https://github.com/cesanta/slre) - Super Light Regular Expression library;一个 Perl 正则表达式语法子集的迷你实现。[GNU GPL2.1](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html)。
*   [TRE](https://github.com/laurikari/tre/) - 一个与 POSIX 一致，充满特色的正则表达式库。[FreeBSD](http://directory.fsf.org/wiki?title=License:FreeBSD "License:FreeBSD")。
*   PS：关于正则表达式，deerchao 有篇文章不错 《[正则表达式 30 分钟入门教程](http://blog.jobbole.com/96708/)》

<h2 id="serialization">序列化</h2>

*   [c-capnproto](https://github.com/jmckaskill/c-capnproto) - 一个 Cap'n Proto 序列化协议的实现。 [Expat](http://directory.fsf.org/wiki/License:Expat)。
*   [cmp](https://github.com/camgunz/cmp) - 一个 [MessagePack](http://msgpack.org/) 序列化协议的实现。 [Expat](http://directory.fsf.org/wiki/License:Expat)。
*   [libavro](http://avro.apache.org/docs/current/api/c/index.html#_introduction_to_avro_c) - 一个 Avro 数据序列化系统的 C 实现。[Apache2.0](http://directory.fsf.org/wiki/License:Apache2.0)。
*   [mpack](https://github.com/ludocode/mpack) - 另一个 [MessagePack](http://msgpack.org/) 序列化协议的实现。[Expat](http://directory.fsf.org/wiki/License:Expat)。
*   [protobuf-c](https://github.com/protobuf-c/protobuf-c) - 一个 Google Protocol Buffer 的 C 实现。[FreeBSD](http://directory.fsf.org/wiki?title=License:FreeBSD "License:FreeBSD")。
*   [xdr](http://en.wikipedia.org/wiki/External_Data_Representation) - External Data Representation；数据序列化标准。标准（没有可用许可）。

<h2 id="source-code-collections">源码集锦</h2>

下面包含了一些小型源码集合。如果你想要大型且成熟的，看《框架》那一节。

*   [CCAN](http://ccodearchive.net/) - 模仿 Perl 的 CPAN，这是一个大的实用 C 代码集合。完整的列表在 [这里](http://ccodearchive.net/list.html)。多种许可（所有都是免费软件）。
*   [clib](https://github.com/clibs/clib) - 一个 C 软件包管理器，配备了一堆自己的库。 [Expat](http://directory.fsf.org/wiki/License:Expat)。
*   [gnulib](https://www.gnu.org/software/gnulib/) - 通用 GNU 代码的集合。多种许可证，全部免费。
*   [libdjb](http://www.fefe.de/djb/) - 做各种事情的库的集合。（显然）公共领域。

<h2 id="standard-libraries">标准库</h2>

下面包括了标准 C 库。

*   [Bionic](https://github.com/android/platform_bionic) - 谷歌为 Android 开发的 C 标准库。[3-clause BSD](http://directory.fsf.org/wiki/License:BSD_3Clause)。
*   [dietlibc](http://www.fefe.de/dietlibc/) - 标准 C 库，可能是最小的二进制文件。[GNU GPL2.1](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html)。
*   [glibc](http://www.gnu.org/software/libc/) - GNU C 库。一个 C 标准库的实现。 [GNU LGPL2.1](http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html)。
*   [musl](http://www.musl-libc.org/) - 标准 C 库，兼容 POSIX 2008 和 C11，为静态链接设计。[Expat](http://directory.fsf.org/wiki/License:Expat)。

<h2 id="string-manipulation">字符串处理</h2>

*   [bstrlib](http://bstring.sourceforge.net/) - 更好的字符串处理库。双重许可，[3-clause BSD](http://directory.fsf.org/wiki/License:BSD_3Clause) 或 [GNU GPL2.1](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html)。
*   [ICU](http://site.icu-project.org/) - International Components for Unicode；提供 Unicode 支持的库。 [ICU license](http://source.icu-project.org/repos/icu/icu/trunk/license.html)。
*   [libunistring](https://gnu.org/software/libunistring/) - 处理 Unicode 字符串的 C 库。[GNU LGPL3](http://www.gnu.org/licenses/lgpl.html)。
*   [libgiconv](https://gnu.org/software/libiconv/) - 文本转换库。[GNU LGPL2.1](http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html)（库），[GNU GPL3](http://www.gnu.org/licenses/gpl.html)（编码转换程序）。
*   [SDS](https://github.com/antirez/sds) - Simple Dynamic Strings；一个用简单方式处理 C 字符串的库，而且兼容标准 C 字符串函数。可通过 [clib](https://github.com/clibs/clib) 使用。[FreeBSD](http://directory.fsf.org/wiki?title=License:FreeBSD "License:FreeBSD")。
*   [shoco](https://github.com/Ed-von-Schleck/shoco) - 一个小型文本压缩器。[Expat](http://directory.fsf.org/wiki/License:Expat)。
*   [smaz](https://github.com/Ed-von-Schleck/shoco) - 一个高效的字符串压缩库。[3-clause BSD](http://directory.fsf.org/wiki/License:BSD_3Clause).

<h2 id="testing">测试工具</h2>

*   [CHEAT](https://github.com/Tuplanolla/cheat) - 一个非常简单的单元测试框架。[FreeBSD](http://directory.fsf.org/wiki?title=License:FreeBSD "License:FreeBSD")。
*   [Check](http://check.sourceforge.net/) - 一个 C 的单元测试框架。[GNU LGPL2.1](http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html)。
*   [CMock](https://github.com/ThrowTheSwitch/CMock) - 一个 C 的 mock/stub 生成器。
*   [cmocka](http://cmocka.org/) - 一个支持 mock 对象的单元测试框架。[Apache2.0](http://directory.fsf.org/wiki/License:Apache2.0)。
*   [Criterion](https://github.com/Snaipe/Criterion) - 一个 KISS 风格，非侵入式的 C 测试框架。 [Expat](http://directory.fsf.org/wiki/License:Expat)
*   [CUnit](http://cunit.sourceforge.net/) - 另一个 C 的单元测试框架。[GNU LGPL2.0](http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html)。
*   [minunit](https://github.com/siu/minunit) - 极小的 C 单元测试框架。[Expat](http://directory.fsf.org/wiki/License:Expat)。
*   [Unity](https://github.com/ThrowTheSwitch/Unity) - 一个简单的 C 单元测试框架。 [Expat](http://directory.fsf.org/wiki/License:Expat)。

<h2 id="text-editor-extensions">文本编辑器扩展</h2>

在几乎任何像样的文本编辑器支持 C 之际，有一些扩展，让编辑器更加令人愉快。下面是根据编辑器分目录的。

### Emacs

*   [CEDET](http://cedet.sourceforge.net/) - Collection of Emacs Development Environment Tools；给 Emacs 提供一种类似 IDE 的特点，是内建的。[GNU GPL3](http://www.gnu.org/licenses/gpl.html) 或更高版本。
*   [Flycheck](https://github.com/flycheck/flycheck) - 现代语法检查。对于 C，它可以使用 GCC 或者 Clang 作为后端。[GNU GPL3](http://www.gnu.org/licenses/gpl.html) 或更高版本。
*   [Yasnippet](https://github.com/capitaomorte/yasnippet) - 一个模板系统，支持 C 的通用代码片段。[GNU GPL3](http://www.gnu.org/licenses/gpl.html) 或更高版本。

### Vim

*   [Syntastic](https://github.com/scrooloose/syntastic) - 语法检查和语言分析。[Do What The Fuck You Want To license](https://github.com/scrooloose/syntastic/blob/master/LICENCE)。
*   [YouCompleteMe](http://valloric.github.io/YouCompleteMe/) - 一个 Vim 的代码补全引擎。[GNU GPL3](http://www.gnu.org/licenses/gpl.html)。

<h2 id="tools">工具</h2>

下面是实用的程序列表，包括了帮助你编写和调试 C 代码的库或者编译器，不包括编辑器。

*   [adlint](https://yanoh.github.io/adlint/) - 一个静态分析器。支持完全的 C89 标准和部分 C99 标准。[GNU GPL3](http://www.gnu.org/licenses/gpl.html) 或更高版本。
*   [Artistic Style](http://astyle.sourceforge.net/) - 一个支持 C 的小而快的自动化代码格式化工具。[GNU LGPL3](http://www.gnu.org/licenses/lgpl.html)。
*   [address-sanitizer](https://github.com/google/sanitizers) - 一个很快的内存错误探测器。[Apache2.0](http://directory.fsf.org/wiki/License:Apache2.0)。
*   [biicode](https://biicode.github.io/biicode/) - 一个现代的 C 依赖管理器。[Expat](http://directory.fsf.org/wiki/License:Expat)。
*   [c](https://github.com/ryanmjacobs/c) - 在命令行中编译和执行 C 脚本，也支持 shebang。 [Expat](http://directory.fsf.org/wiki/License:Expat)。
*   [c99sh](https://github.com/RhysU/c99sh) - 用 hash-bang 运行 C 文件。[FreeBSD](http://directory.fsf.org/wiki?title=License:FreeBSD "License:FreeBSD")。
*   [CBMC](http://www.cprover.org/cbmc/) - C Bounded Model Checker；一个检查数组边界，指针安全和用户自定义断言的工具。[Original BSD](https://directory.fsf.org/wiki/License:BSD_4Clause)。
*   [cdecl](https://github.com/mpv-player/mpv) - 一个在线服务，能够把 C 的声明翻译成英文，反向也可以。公共领域。
*   [cinclude2dot](http://www.flourish.org/cinclude2dot/) - 在 C 项目中使用 Graphviz 的图像包含依赖。任意的 GNU GPL 版本（根据文件中的要求）
*   [Complexity](https://www.gnu.org/software/complexity/) - 一个测量 C 代码复杂性的工具。[GNU GPL3](http://www.gnu.org/licenses/gpl.html) 或更高版本。
*   [DDD](https://www.gnu.org/software/ddd/ddd.html) - 各种命令行调试器的图形前端。[GNU GPL3](http://www.gnu.org/licenses/gpl.html) 或更高版本。
*   [fab](http://fabutil.org/) - 让每次构建都最优的构建系统。[GNU GPL3](http://www.gnu.org/licenses/gpl.html)。
*   [GDB](http://www.gnu.org/software/gdb/) - The GNU Project debugger；一个 C 调试器。[GNU GPL3](http://www.gnu.org/licenses/gpl.html) 或更高版本。
*   [Glade](https://glade.gnome.org/) - 一个让 TK+ GUIs 开发更快的 RAD 工具。[GNU GPL2.1](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html)。
*   [GMSL](http://gmsl.sourceforge.net/) - GNU Make Standard Library；一个 GNU Make 额外功能的集合。[3-clause BSD](http://directory.fsf.org/wiki/License:BSD_3Clause)。
*   [GNU Global](https://www.gnu.org/software/global/) - 一个 C 的源码标签工具。[GNU GPL3](http://www.gnu.org/licenses/gpl.html)。
*   [gprof](http://www.gnu.org/software/binutils/) - 一个性能分析工具。GNU binutils 的一部分。[GNU GPL3](http://www.gnu.org/licenses/gpl.html) 或更高版本。
*   [Highlight](http://www.andre-simon.de/index.php) - 把源码转化为高亮的格式化文本。[GNU GPL3](http://www.gnu.org/licenses/gpl.html)。
*   [include-what-you-use](https://github.com/include-what-you-use/include-what-you-use) - 帮助程序员发现不必要的包含和提供解决他们的建议。基于 LLVM/Clang（只能与它一起工作）。[NCSA](http://directory.fsf.org/wiki/License:IllinoisNCSA)。
*   [indent](https://www.gnu.org/software/indent/) - 自动格式化 C 代码，让它更容易阅读。也能把一种风格的代码转化为另一种。[GNU GPL3](http://www.gnu.org/licenses/gpl.html) 或更高版本。
*   [Make](https://www.gnu.org/software/make/) - 一个控制程序的可执行和其他非代码文件的生成的工具。[GNU GPL3](http://www.gnu.org/licenses/gpl.html) 或更高版本（链接到 GNU 的实现)。
*   [qo](https://github.com/andlabs/qo) - 无需分开的配置文件的构建系统。[Expat](http://directory.fsf.org/wiki/License:Expat)。
*   [rr](http://rr-project.org/) - 记录非确定执行来允许可确定调试的调试器。[FreeBSD](http://directory.fsf.org/wiki?title=License:FreeBSD "License:FreeBSD")。
*   [tup](http://gittup.org/tup/index.html) - 一个很快，基于文件，跨平台的构建系统。[GNU GPL2.1](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html)。
*   [unifdef](http://dotat.at/prog/unifdef/) - 移除 #ifdef 和 #if 指令包含的文本，不会改变文件的其他部分。[3-clause BSD](http://directory.fsf.org/wiki/License:BSD_3Clause) 和 [FreeBSD](http://directory.fsf.org/wiki?title=License:FreeBSD "License:FreeBSD")。
*   [Valgrind](http://www.valgrind.org/) - 各种动态分析工具，包括一个内存泄漏检测工具。[GNU GPL2.1](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html)。

<h2 id="utilities">其他工具</h2>

下面是包罗万象的目录，主要是那些不适合放在其他目录的东西。

*   [ApeTagLibs](https://github.com/jeremyevans/ape_tag_libs/tree/master/c) - APEv2 标签的 C 库。[Expat](http://directory.fsf.org/wiki/License:Expat)。
*   [bfd](http://sourceware.org/binutils/docs/bfd/) - 处理二进制对象文件的库。GNU binutils 的一部分。[GNU GPL3](http://www.gnu.org/licenses/gpl.html) 或更高版本。
*   [ccv](https://github.com/liuliu/ccv) - C-based/Cached/Core Computer Vision library；现代计算机视觉。 [3-clause BSD](http://directory.fsf.org/wiki/License:BSD_3Clause)。
*   [cf4ocl](https://fakenmc.github.io/cf4ocl/) - The C Framework for OpenCL；一个跨平台面向对象框架，用于开发和用基准问题测试 [OpenCL](https://www.khronos.org/opencl/) 项目。[GNU LGPL3](http://www.gnu.org/licenses/lgpl.html)（库）, [GNU GPL3](http://www.gnu.org/licenses/gpl.html)（其他代码）。
*   [CommonMark](https://github.com/jgm/CommonMark) - CommonMark 规范的 C 实现。[Variety of licenses, all free](https://github.com/jgm/CommonMark/blob/master/LICENSE)。
*   [CException](https://github.com/ThrowTheSwitch/CException) - 异常的 C 实现。[Expat](http://directory.fsf.org/wiki/License:Expat)。
*   [docopt.c](https://github.com/docopt/docopt.c) - 命令行选项解析器的 C 实现。[Expat](http://directory.fsf.org/wiki/License:Expat)。
*   [dyncall](http://www.dyncall.org/) - 另一个外部函数接口库。[Expat](http://directory.fsf.org/wiki/License:Expat)。
*   [FANN](http://leenissen.dk/fann/wp/) - Fast Artifical Neural Network library；一个神经网络的实现。[GNU GPL2.1](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html)。
*   [Firm](http://pp.ipd.kit.edu/firm/Index) - 一个 C 库，提供了基于图像中间表示，优化和适合编译器的汇编代码生成。配备了 C 的前端例子，使用相同的许可。[GNU LGPLv2.1](http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html)。
*   [gjrand](http://sourceforge.net/projects/gjrand/) - 随机数字生成的例程库。[GNU GPL2.1](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html) 或者 [GNU GPLv3](http://www.gnu.org/licenses/gpl.html)（用户的选择）。
*   [GNU FreeIPMI](https://gnu.org/software/freeipmi/index.html) - 一个带内和带外的 IPMI 实现。[GNU GPL3](http://www.gnu.org/licenses/gpl.html)。
*   [GNU gperf](https://www.gnu.org/software/gperf/) - 一个完美的哈希函数生成器，提供一系列的字符串。输出 C 代码。[GNU GPL3](http://www.gnu.org/licenses/gpl.html) 或更高版本。
*   [GNU Libffcall](https://gnu.org/software/libffcall/) - 一个构建外部函数接口库的集合。[GNU GPL3](http://www.gnu.org/licenses/gpl.html) 或更高版本。
*   [gperftools](https://github.com/gperftools/gperftools) - 一系列测量和提高性能的实用工具集合。[3-clause BSD](http://directory.fsf.org/wiki/License:BSD_3Clause)。
*   [hammer](https://github.com/abiggerhammer/hammer) - 二进制格式的解析器组合。[GNU GPL2.1](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html).
*   [Hans Boehm GC](http://www.hboehm.info/gc/) - C 的垃圾收集器？如果我用了不要介意。多种许可证，完全免费。
*   [huffandpuff](https://github.com/adamierymenko/huffandpuff) - 一个极小的哈夫曼编码器和解码器。公共领域。
*   [iniparser](https://github.com/ndevilla/iniparser) - 一个 .ini 文件的解析器。[Expat](http://directory.fsf.org/wiki/License:Expat)。
*   [jemalloc](http://www.canonware.com/jemalloc/) - 一个 malloc 实现，着重于段错误的避免和可扩展并发支持。[FreeBSD](http://directory.fsf.org/wiki?title=License:FreeBSD "License:FreeBSD")。
*   [jwHash](https://github.com/watmough/jwHash) - 一个很快的哈希表实现。[Apache2.0](http://directory.fsf.org/wiki/License:Apache2.0)。
*   [kdtree](https://github.com/jtsiomb/kdtree) - KD-trees 的简单库。[3-clause BSD](http://directory.fsf.org/wiki/License:BSD_3Clause)。
*   [Kitsune](http://kitsune-dsu.com/) - 高效，通用的框架，用于软件的动态升级。 [GNU LGPL3](http://www.gnu.org/licenses/lgpl.html) 或更高版本。
*   [libavl](http://adtinfo.org/libavl.html/index.html) - 一个包括各种自平衡二叉树的库。[GNU GPL3](http://www.gnu.org/licenses/gpl.html) 或更高版本。
*   [libbson](https://github.com/mongodb/libbson) - BSON 实用库。[Apache2.0](http://directory.fsf.org/wiki/License:Apache2.0)。
*   [libCello](http://libcello.org/) - 引入高级语言给 C 的库。
*   [libcox](http://libcox.net/) - 一个运行跨平台系统调用和跨系统标准工具的库。[FreeBSD](http://directory.fsf.org/wiki?title=License:FreeBSD "License:FreeBSD")。
*   [libffi](https://github.com/atgreen/libffi) - 轻量级的外部函数接口库。[Expat](http://directory.fsf.org/wiki/License:Expat)。
*   [libgit2](https://libgit2.github.com/) - Git 的纯 C 实现。[GNU GPL2 only, with a linking exception](https://github.com/libgit2/libgit2/blob/master/COPYING)。
*   [libimobiledevice](https://github.com/libimobiledevice/libimobiledevice) - 一个跨平台协议库，用于与 iThings 通信。[GNU LGPLv2.1](http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html) 或更高版本（库），[GNU GPL2.1](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html) 或更高版本（工具）。
*   [libmpv](https://github.com/mpv-player/mpv) - 音乐播放库。编译的时候加入 `./waf configure --disable-cplayer --enable-libmpv-shared` 来避免生成音乐播放器。[GNU GPL2.1](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html) 或更高版本。
*   [libnfc](https://github.com/nfc-tools/libnfc) - 一个平台独立的 NFC 库。[GNU LGPL3](http://www.gnu.org/licenses/lgpl.html)。
*   [libPhenom](http://facebook.github.io/libphenom/index.html) - 事件框架，用于构建高扩展和高性能系统。[Apache2.0](http://directory.fsf.org/wiki/License:Apache2.0)。
*   [libsoundio](https://github.com/andrewrk/libsoundio) - 跨平台，实时音频输入输出的库，有很多种后端。[Expat](http://directory.fsf.org/wiki/License:Expat)。
*   [libucl](https://github.com/vstakhov/libucl) - 通用配置库解析器。[FreeBSD](http://directory.fsf.org/wiki?title=License:FreeBSD "License:FreeBSD")。
*   [libudp](https://notabug.org/koz.ross/libudp) - 一个统一设计模式的 C 实现。[GNU GPL3](http://www.gnu.org/licenses/gpl.html) 或更高版本。
*   [libuv](https://github.com/libuv/libuv) - 跨平台异步 I/O。[Expat](http://directory.fsf.org/wiki/License:Expat)。
*   [libYAML](http://www.pyyaml.org/wiki/LibYAML) - 一个 YAML 1.1 解析器和发射器。 [Expat](http://directory.fsf.org/wiki/License:Expat)。
*   [lzo](http://www.oberhumer.com/opensource/lzo/) - 一个很快的数据压缩库。[GNU GPL2.1](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html)。
*   [mpc](https://github.com/orangeduck/mpc) - 解析器组合库。[FreeBSD](http://directory.fsf.org/wiki?title=License:FreeBSD "License:FreeBSD")
*   [ncurses](https://gnu.org/software/ncurses/) - 彩色的终端 UI 库。[GNU GPL3](http://www.gnu.org/licenses/gpl.html) 或更高版本。
*   [nope.c](https://github.com/riolet/nope.c) - 一个基于 C 语言，超级轻量级的软件平台，用于可扩展服务端和网络应用的开发（想想 C 程序员的 nodejs）。
*   [pbc](https://github.com/cloudwu/pbc) - 一个协议缓冲库。[Expat](http://directory.fsf.org/wiki/License:Expat)。
*   [rabbitmq-c](https://github.com/alanxz/rabbitmq-c) - [RabbitMQ](http://www.rabbitmq.com/) 的客户端库。[Expat](http://directory.fsf.org/wiki/License:Expat)。
*   [Ragel](http://www.colm.net/open-source/ragel/) - 为编译C的状态机的DSL。[GNU GPL2.1](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html)。
*   [uthash](http://troydhanson.github.io/uthash/) - 哈希表实现，允许已经存在的数据结构很容易地存在哈希表里面。[1-clause BSD](http://troydhanson.github.io/uthash/license.html)。
*   [Viola](https://github.com/eatonphil/Viola) - libCello 的简化版本。[Expat](http://directory.fsf.org/wiki/License:Expat)。
*   [zlib](https://github.com/madler/zlib) - 一个相当漂亮却精致不张扬的压缩库。[3-clause BSD](http://directory.fsf.org/wiki/License:BSD_3Clause)。

<h2 id="xml">XML</h2>

> “XML 是垃圾。真的，没有任何借口。XML 对人类不友好的，甚至对于电脑来说也是一场灾难。根本就没有这个可怕的垃圾存在的理由” -Linus Torvalds

*   [Expat](http://www.libexpat.org/) - 面向流的 XML 解析器。[Expat](http://directory.fsf.org/wiki/License:Expat)。
*   [libxml2](http://xmlsoft.org/) - 一个符合标准，轻量级的 XML 解析器。[Expat](http://directory.fsf.org/wiki/License:Expat)。
*   [mini-xml](http://www.msweet.org/projects.php?Z3) - 小型 XML 读写库。没有 C 标准库的依赖。[GNU LGPL2.1 with static linking exception](http://svn.msweet.org/mxml/trunk/COPYING)。
*   

<h2 id="resources-2">其他资源</h2>

<h3 id="influential-books">有影响力的书</h3>
*具有广泛影响且值得阅读的 C 语言经典书籍。*

* 待补充

<h3 id="websites-blogs">知名网站/博客</h3>
*值得关注的 C 语言技术站点和博客。*

<h4>中文</h4>

* 待补充

<h4>英文</h4>

* 待补充

<h3 id="weibo-weixin">微信公众号</h3>
* CPP开发者：专注分享 C/C++ 开发相关的技术文章和工具资源。
<br><img src="http://ww1.sinaimg.cn/small/63918611gw1epb2c4w55aj2046046t8t.jpg" width=150 height=150>
