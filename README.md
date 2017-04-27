
#pay-java-parent

##整合支付模块（微信支付，支付宝）

声明： 本项目最初想法自 https://github.com/chanjarster/weixin-java-tools, 15年1月左右关注chanjarster/weixin-java-tools，并将其回调处理修改并进行使用。

开发版 https://git.oschina.net/egzosn/pay-java-parent/tree/develop

###特性



    1. 不依赖任何 mvc 框架
    2. 也不依赖 servlet，仅仅作为工具使用，可轻松嵌入到任何系统里（项目例子利用spring mvc的 @PathVariable进行，推荐使用类似的框架）
    3. 支付请求调用支持HTTP和异步、支持http代理
    4. 控制层统一异常处理
    5. LogBack日志记录
    6. 简单快速完成支付模块的开发
    7. 支持多种支付类型多支付账户扩展（目前已支持微信支付，支付宝支付，友店支付）

###本项目包含 3 个部分：

     1. pay-java-common  公共lib,支付核心与规范定义
     2. pay-java-demo  具体的支付demo
     3. pay-java-*  具体的支付实现库


###使用
这里不多说直接上代码  集群的话,友店可能会有bug。

测试链接 ： http://pay.egan.in/index.html

服务端+网页端详细使用与简单教程请看 [pay-java-demo](pay-java-demo?dir=1&filepath=pay-java-demo)

android 例子 [pay-java-android](http://git.oschina.net/egzosn/pay-java-android)


##交流
很希望更多志同道合友友一起扩展新的的支付接口。

这里感谢[ouyangxiangshao](https://github.com/ouyangxiangshao) 与[Actinian](http://git.oschina.net/Actinia517) 所提交的安卓例子或者分支

非常欢迎和感谢对本项目发起Pull Request的同学，不过本项目基于git flow开发流程，因此在发起Pull Request的时候请选择develop分支。

E-Mail：egzosn@gmail.com

QQ群：542193977

