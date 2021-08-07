搭建dubbo admin环境步骤：
1，mvn clean install -Dmaven.skip.test=true -DskipTests=true
2，修改WEB-INF下的dubbo.properties中的zk的ip地址
3，配置tomcat的context-path
4，访问localhost:port/context-path
5，密码为WEB-INF下的dubbo.properties中的密码