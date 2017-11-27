c3p0连接池

文章:
MySQL---数据库从入门走向大神系列(十四)-ComboPooledDataSource(C3P0连接池配置)   http://blog.csdn.net/qq_26525215/article/details/52212260

样例代码:code/c3p0

关于mchange-commons-java-0.2.10.jar包:
c3p0数据库连接池的辅助包，没有这个包系统启动的时候会报classnotfoundexception，这是c3p0-0.9.2版本后分离出来的包，0.9.1的时候还是一个包就搞定的