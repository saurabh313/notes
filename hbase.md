## install hbase 
 - download hbase.jar and edit hbase-site.xml
 ```
$ cat `pwd`/`ls hbase-1.2.6/conf/hbase-site.xml`
/usr/local/hbase-1.2.6/conf/hbase-site.xml
<configuration>
<property>
        <name>hbase.rootdir</name>
        <value>file:///Users/sjain292/hbase</value>
</property>
<property>
        <name>hbase.zookeeper.property.dataDir</name>
        <value>/Users/sjain292/zookeeper</value>
</property>
</configuration>
 ```
