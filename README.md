

## 1. 创建应用
```bash
mvn clean install
```

## 2. 创建应用

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