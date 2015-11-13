#Yeoman - 标准化实践（[完整版gitbook](http://nupthale.github.io/yeomanshare/advice/README.html)）

## yeoman的使用场景

&emsp;&emsp;假设，程序员小明接到一个项目：火车票订票系统，前几天思考的问题如下：
1. 项目目录结构该如何规划？
2. 使用什么类库来支撑系统开发？
3. 生产环境如何搭建（比如很多前端的生产环境是基于php，也有基于NodeJs）
4. 编译环境如何搭建（编译环境其实应该归到生产环境中，但前端很多人使用coffeescript/less/sass等，所以需要编译环境）
5. 单元测试环境如何搭建？
6. 调试环境如何搭建（本地代理远程assets等）
7. 开发完毕后打包部署如何处理？

用yeoman！只要1行命令！

##介绍
&emsp;&emsp;一套用于提高前端工程师效率的规范工作流工具，目的是帮我们更快的构建和开发应用；

&emsp;&emsp;它的使用体现在整个项目创建，开发过程，build发布）中，包含（yo，bower和grunt）三个核心工具；

* yo：项目工程依赖目录和文件生成工具，项目生产环境和编译环境生成工具
* grunt：前端集成开发工具
* bower：Web开发的包管理器，概念上类似npm，npm专注于nodeJs模块，而bower专注于CSS、JavaScript、图像等前端相关内容的管理

## Refs:
1. [yeoman - 搭建自己的脚手架](http://segmentfault.com/a/1190000002629851)
2. [使用Yeoman定制前端开发项目构建工具](http://i.wanz.im/2013/12/20/developing-front-end-scaffolding-tools-with-yeoman/)
3. [yeoman官网](http://yeoman.io/)
4. [前端项目可以更简单—Yeoman入门指南](http://smm.zoomquiet.io/data/20130910155147/index.html)
5. [Yeoman：构建漂亮Web应用的工具和框架](http://www.infoq.com/cn/news/2012/09/yeoman)
6. [编写自己的yeoman generator](http://blog.csdn.net/u010373419/article/details/37936467)

