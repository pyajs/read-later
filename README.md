# read-later
平时收集的一些开发资料，包含了前端、后端、运维、设计各方面的文章，供大家茶余饭后阅读，希望有所帮助~

## 前端开发

1. 几个多步骤guide的示例和下载，如果项目中有提供“下一步”“下一步”这样的form的需求，可以参考下：
	* <http://azmind.com/2015/05/31/multi-step-registration-form-bootstrap-css3-jquery/>
	* <http://azmind.com/2016/05/30/bootstrap-wizard/>
	* <http://www.panopta.com/2013/02/06/bootstrap-application-wizard-2/>
2. Bootstrap Tour 为页面添加操作步骤提示功能，如果需要为用户提供交互式的站点使用指导，可参考这个工具：<http://bootstraptour.com/>
3. 与上一条的效果类似，这里提供了10种交互式指导的工具：<https://ourcodeworld.com/articles/read/328/top-10-best-tour-website-guide-javascript-and-jquery-plugins>
4. 两个Bootstrap代码段的收集演示站点，如果使用bootstrap开发时有问题，可以到这里搜索参考下别人写的代码：
	* <http://bootsnipp.com/> 
	* <http://www.bootply.com/>
5. jQuery QueryBuilder, 用于图形化地生成查询语句和规则，可以帮助用户把条件和AND/OR这类逻辑关系拼接起来:<http://querybuilder.js.org/demo.html>
6. 可动态变化的favicon，在favicon上做文章，完成提示的效果:<http://lab.ejci.net/favico.js/>
7. 几个提供免费壁纸和免费视频的网站，提供的图片和视频都很赏心悦目，这些网站同时也提供了API，在设计每天自动变化的登录页背景时可以使用：
	* <https://unsplash.com/>
	* <https://pixabay.com/>	
8. 几篇前端设计的文章，讲了表单设计的最佳实践，表单设计过程中有很多细节可能我们一直都没有注意过，在设计实用的表单时可用于参考：
	* <https://www.ventureharbour.com/form-design-best-practices/>
	* <http://www.ui.cn/detail/168477.html>
	* <http://www.techug.com/post/design-better-forms.html>
9. 项目中需要画关系图时可以选择以下的几个库：
	* 效果和果冻一样的库，我们在项目中用得较多：<http://visjs.org/network_examples.html>
	* 另一个库：<http://js.cytoscape.org/>
10. Ant Design的github项目上的一个issue，大家纷纷提供了自己利用antd写的界面，不乏精彩之作，如果要使用AntD来做项目，可以提前参考下：<https://github.com/ant-design/ant-design/issues/477>
11. 两个用于生成web版虚拟桌面的项目，可用于演示和教学类项目：
	* <https://www.os-js.org/>
	* <https://nagyervin.eu/njdesktop>
12. Ant Design的设计模式和规范，讲了很多实用的界面设计细节，其实应该是值得PM在做设计的时候先看看的，但是我们没有PM相关的部分，就先放到这里了：<https://ant.design/docs/spec/introduce-cn>
13. Material Dashboard，近期github上比较火的前端项目，一个Material Design风格的admin界面，有vue、react版本，比之前看到的很多bootstrap改版都要漂亮很多:<https://github.com/creativetimofficial/material-dashboard> (免费版演示功能较少，升级到pro版需要59刀)
14. httpbin，用来完成http请求测试的工具，如果没有后端的配合，可以使用该项目进行一些测试：<https://httpbin.org>


## 后端开发

1. Life is short, you need Python。提供下awesome python的网站吧，希望大家都能找到合适的库，快速完成自己的工作：
  * 英文版：<http://awesome-python.com/> 
  * 中文版：<https://github.com/jobbole/awesome-python-cn>
2. 几个python kafka客户端性能评测对比的文档，可以参考下选型和性能测试应该怎么来做：<http://activisiongamescience.github.io/2016/06/15/Kafka-Client-Benchmarking/>
3. valentina studio，一个多数据库管理工具，免费版也已经很好用了，对pgadmin不满的话可以尝试下:<https://www.valentina-db.com/en/valentina-studio-overview>
4. 我们常用的一些词可能会发音错误，因此有人整理了这么一份列表：<https://github.com/shimohq/chinese-programmer-wrong-pronunciation>
5. MODELING WORKFLOWS IN REST APIS 提供了三种将工作流使用restful风格来表示的方法讨论：<http://www.kennethlange.com/posts/Modeling-Workflows-in-REST-APIs.html>
6. github的api文档，对restful API使用有一些很细节的规定和描述，可作为API设计和使用的参考，但到了V4版后github开始用graphql了~：<https://developer.github.com/v3/>
7. python3 cookbook，从python2转到python3，总会感觉自己没把python3的新特性用到位，可以参考下这本书，掌握python3最新特性带来的快感：<http://python3-cookbook.readthedocs.io/zh_CN/latest/index.html>
8. 一篇讲network.taget的文章，可以试着读完这篇文章，然后确定自己的service配置文件该怎么写才好：<https://www.freedesktop.org/wiki/Software/systemd/NetworkTarget/>
9. 一个SQL注入的演示网站，用于教育类项目的搭建，同时也提示大家：代码写成这样就注定会被黑啊：<http://sqlidemo.altervista.org/>
10. 一篇博文《不要用 JWT 来做 Web 应用的会话管理》，对jwt的使用场景做了一些讨论，说得比较在理，如果你执着要在项目中用jwt替代其他的认证token方式，可以先看下这篇文章：<http://t.cn/R1gbld7>
11. 系统设计入门，github上的热门项目，十全大补项目，可用于快速了解一些系统的设计方法和现在流行的系统元素，有中文版：<https://github.com/donnemartin/system-design-primer>
12. termtosvg，一款可以录制终端命令行操作的工具，录制完成后生成一个svg动画，可直接嵌入到网页中，有动画演示命令的执行过程，比只截个图要好得多，推荐写教程时使用：<https://github.com/nbedos/termtosvg>
13. Django Admin Cookbook，提供了一些定制django admin界面的实用方法：<https://books.agiliq.com/projects/django-admin-cookbook/en/latest/index.html>
14. 使用uwsgi实现异步任务，介绍了在django项目中如何简单地利用uwsgi实现异步队列：<https://knktc.com/2018/07/24/uwsgi-spooler-as-async-queue/>
15. 在开发多用户多权限的系统时免不了要进行账号的切换，使用SessionBox这个chrome的插件可以很容易地解决多用户的session问题，让不同的标签可以使用不同的session，直接命名和分组，非常好用：<https://sessionbox.io/>
16. 在github上发布项目，记得要参考这两篇：
   * 如何维护ChangeLog: <https://keepachangelog.com/zh-CN/1.0.0/> 
   * 语义化版本控制规范: <https://semver.org/lang/zh-CN/> 
17. octotree，一个github上看代码的神器插件，可以在github和gitlab页面中显示代码树，方便直接在页面中查看代码：<https://github.com/ovity/octotree>
18. 一些在线正则表达式匹配检测的网站，有助于平时编写正则时使用：
   * pyregex，界面风格不错，提供了一些cheatsheet: <http://www.pyregex.com/>
   * pythex，界面较为简洁: <https://pythex.org/>
19. tldr, 一款非常实用的命令行工具，如果觉得看man page有点吃力，可以使用这款工具，仅列出常用的命令：<https://github.com/tldr-pages/tldr>



## 运维
1. monitorix工具，用于监控系统性能，并通过rrdtool绘制成图形，最终通过web界面进行展示，可直接通过yum安装： <http://www.monitorix.org/>
2. 常看开源项目的人都熟悉awesome列表，这里的这个列表提供了一份系统管理员常用的管理工具的列表，可能会有帮助：<https://github.com/n1trux/awesome-sysadmin>
3. 系统管理员面试问题集，提供了从初级到高级的各种linux系统管理问题，平时看一下拓展下linux的能力也是不错的：<https://github.com/trimstray/test-your-sysadmin-skills>


## 安全
1. 移动安全wiki，集合了大量的移动安全工具介绍和链接：<https://mobilesecuritywiki.com/>