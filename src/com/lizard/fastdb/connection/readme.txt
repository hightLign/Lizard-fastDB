这就是使用接口，具体类实现最好的例子。
假如有其他的连接池要增加，则只要实现ConnectionProvider接口即可，在datasource.xml中只要配置这个实现类即可，会通过反射来实现的。