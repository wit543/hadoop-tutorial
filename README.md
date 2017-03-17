# hadoop-tutorial

## Compile java files.

setup

```Bash
export JAVA_HOME=/usr/java/default # change to your java path ex-oracle: /usr/lib/jvm/java-8-oracle
export PATH=$JAVA_HOME/bin:$PATH
export HADOOP_CLASSPATH=$JAVA_HOME/lib/tools.jar
```
compile
```bash
hadoop com.sun.tools.javac.Main MyJavaFile.java # change this to your java file
```

create a jar file
``` bash
jar cf MyJARFile.jar MyJavaFile*.class # change the name of the jar file and name of the class
```
