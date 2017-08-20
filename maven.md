- to generate maven project 
```
$ mvn archetype:generate -DgroupId=com.acme.shop -DartifactId=ShopCoreApi
$ ls -l
total 0
drwxr-xr-x  4 sjain292  staff  136 Aug 20 17:27 ShopCoreApi

```
- to build the package 
```
$ mvn package 
$ ls -lrt
total 8
drwxr-xr-x  4 sjain292  staff  136 Aug 20 17:27 src
-rw-r--r--  1 sjain292  staff  757 Aug 20 17:27 pom.xml
drwxr-xr-x  8 sjain292  staff  272 Aug 20 17:30 target
```
- to generate test results  
```
$ mvn surefire-report:report
$  ls target/site/surefire-report.html
target/site/surefire-report.html
```

- to show test coverage 
```
$ mvn cobertura:cobertura
$ ls target/site/cobertura/index.html
target/site/cobertura/index.html
```
- to generate static code analysis
  - use [findbugs](https://mvnrepository.com/artifact/org.codehaus.mojo/findbugs-maven-plugin)
