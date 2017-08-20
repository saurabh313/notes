- to generate maven project 
```
 ✝  ~/Documents/learn/notes   master±  mvn archetype:generate -DgroupId=com.acme.shop -DartifactId=ShopCoreApi
✘ ✝  ~/Documents/learn/notes   master±  ls -l
total 0
drwxr-xr-x  4 sjain292  staff  136 Aug 20 17:27 ShopCoreApi
 ✝  ~/Documents/learn/notes   master± 
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
