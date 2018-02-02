#  21点游戏双人对战(javaweb形式)
## 功能说明
 * 本项目实现了一个双人在线对战的web21点游戏，进入页面后需要创建房间或者加入房间，等待房间存在两个人准备即可，等待双方准备完毕即可开始游戏，游戏采</br>
 用轮庄模式，并实时显示服务器在线人数。
## 详细
 * 核心
    > 用javaweb写聊天室，可能大多人会困惑于怎么用广播让其他人看到消息，然而http协议是短链接进行访问模式，无法像tcp协议一样建立长链接，当然大多人想到用ajax定时访问服务器获得信息的方式，可这种方式在链接过多的时候效率比较低。</br>
    > WebSocket协议是基于TCP的一种新的网络协议。它实现了浏览器与服务器`全双工(full-duplex)`通信——允许服务器主动发送信息给客户端。
 * 具体功能模块的实现在[博客](http://blog.csdn.net/qq_35442958/article/details/79188998 "CSDN博客")中有说明
 * 技术栈：spring+springMVC+websocket+maven+bootstrp
## 运行
 * 可以把target下的Chatrum.war放在tomcat下运行，然后访问[http://127.0.0.1:8080/Chatrum/rum/chat.html](http://127.0.0.1:8080/Chatrum/rum/chat.html)就可以
 * 也可以IDE导入项目，更新maven依赖，然后用maven命令tomcat7:run运行，然后访问[http://127.0.0.1:8080/rum/chat.html](http://127.0.0.1:8080/rum/chat.html)就可以
 * 也可以访问[http://120.78.164.110:8080/Blackjack/blackjack/blackJack.html](http://120.78.164.110:8080/Blackjack/blackjack/blackJack.html)查看
 ## 预览
   ![BlackJack](http://img.blog.csdn.net/20180128203624896?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvcXFfMzU0NDI5NTg=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast "初始化界面")  
  
