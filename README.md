Just run:
```
mvn compile exec:java -Dexec.mainClass="org.test.Test"
```

Here is my output:
```
 andrej$ mvn compile exec:java -Dexec.mainClass="org.test.Test"
[INFO] Scanning for projects...
[INFO] 
[INFO] --------------------------< org.example:test >--------------------------
[INFO] Building test 1.0-SNAPSHOT
[INFO] --------------------------------[ jar ]---------------------------------
[INFO] 
[INFO] --- maven-resources-plugin:2.6:resources (default-resources) @ test ---
[WARNING] Using platform encoding (UTF-8 actually) to copy filtered resources, i.e. build is platform dependent!
[INFO] Copying 0 resource
[INFO] 
[INFO] --- maven-compiler-plugin:3.1:compile (default-compile) @ test ---
[INFO] Changes detected - recompiling the module!
[WARNING] File encoding has not been set, using platform encoding UTF-8, i.e. build is platform dependent!
[INFO] Compiling 1 source file to /Users/andrej/projects/my/test/test/target/classes
[INFO] 
[INFO] --- exec-maven-plugin:3.0.0:java (default-cli) @ test ---
Import works: interface org.graphstream.graph.Graph[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time:  1.659 s
[INFO] Finished at: 2022-05-03T16:12:19+02:00
[INFO] ------------------------------------------------------------------------
```