# RedEnvelope
##抢红包助手
##运行效果图

<img src="/image/Screenshot_2015-12-02-11-19-02.png" width="280px"/> <img src="/image/Screenshot_2015-12-02-11-19-10.png" width="280px"/><img src="/image/Screenshot_2015-12-02-11-19-19.png" width="280px"/>

##1.功能
辅助抢红包，目前支持微信和QQ抢红包，以后在添加其他方式。

##2.使用
按照应用提示与使用帮助进行设置操作。

##3.技术实现
1.使用AccessibilityService对程序进行模拟自动点击。

2.使用AccessibilityService监听应用UI变化。

3.其他见源码，有详细注解。

##4.问题
1.自动抢红包模式下无法进行聊天。

2.最好是Android 4.4以上，否则会有问题。

##5.其他
1.项目中加入了有米广告，可以无视。

##6.参考

1.AccessibilityService： <http://developer.android.com/intl/zh-cn/reference/android/accessibilityservice/AccessibilityService.html>

2.实现详解：<http://blog.csdn.net/jiangwei0910410003/article/details/48895153>
