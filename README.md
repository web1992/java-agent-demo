# Java Agent

```shell
mvn clean package

# -javaagent 的路径替换成完整的路径
java -javaagent:D:/dev/github/java-agent-demo/agent/target/agent-0.0.1-SNAPSHOT.jar -jar ./app/target/app-0.0.1-SNAPSHOT.jar
```


