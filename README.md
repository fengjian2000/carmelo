Carmelo是基于Java的游戏服务端框架，适合于页游和手游。它的主要特点是：

利用Netty实现高效的NIO通信，同时支持TCP/HTTP协议
完善的三层架构模型，易扩展
通用、完善的session管理机制，无需从头实现
提供了完整的server/client demo，可以作为很好的开发参考
提供较多游戏开发常用的工具类（后面准备陆续加入）



Start from here
----------------------------
**Pre-requisites**: Please have Java 1.8, Maven 3.x, Eclipse and MySQL 5.6.x installed. 

Build
-----
1.  git clone https://github.com/needmorecode/carmelo.git
2.  cd carmelo
3.  mvn eclipse:eclipse
4.  Eclipse -> file -> import -> maven -> existing maven projects -> select carmelo project
5.  carmelo project in Eclipse -> right click on pom.xml -> run as -> maven install

Test
-----
1.  cd src/main/java/carmelo/examples 
2.  execute /server/my_test_user.sql in MySQL
3.  run or debug /server/ServerMain.java in Eclipse
4.  run or debug /client/TcpClientMain.java or /client/HttpClientMain.java in Eclipse
