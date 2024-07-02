## 1. 创建应用

执行以下命令：

```bash
mvn archetype:generate \
    -DgroupId=com.yisen.demo.web \
    -DartifactId=demo-web \
    -Dversion=1.0.0-SNAPSHOT \
    -Dpackage=com.yisen.demo \
    
    -DarchetypeArtifactId=yisen-archetype-web-template \
    -DarchetypeGroupId=com.yisen \
    -DarchetypeVersion=1.0
```

命令执行成功的话，会看到如下的应用代码结构：