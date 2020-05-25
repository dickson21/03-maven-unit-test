Subject : Maven junit test
Created : 20200520
Author : dickson.cheng
Status : OK

Run:
$ git clone https://github.com/mkyong/maven-examples.git
$ cd maven-unit-test
$ mvn test
$ mvn -Dtest=TestMessageBuilder test
$ mvn -Dtest=TestMessageBuilder#testHelloWorld test

Ref:
maven-examples
https://github.com/mkyong/maven-examples/tree/master/maven-unit-test


/**********/
/* Output */
/**********/
C:\myprogram\java\maven\03-maven-unit-test>mvn test
[INFO] Scanning for projects...
[INFO]
[INFO] ----------------< com.mkyong.examples:maven-unit-test >-----------------
[INFO] Building maven-unit-test 1.0-SNAPSHOT
[INFO] --------------------------------[ jar ]---------------------------------
[INFO]
[INFO] --- maven-resources-plugin:2.6:resources (default-resources) @ maven-unit-test ---
[INFO] Using 'UTF-8' encoding to copy filtered resources.
[INFO] skip non existing resourceDirectory C:\myprogram\java\maven\03-maven-unit-test\src\main\resources
[INFO]
[INFO] --- maven-compiler-plugin:3.1:compile (default-compile) @ maven-unit-test ---
[INFO] Changes detected - recompiling the module!
[INFO] Compiling 2 source files to C:\myprogram\java\maven\03-maven-unit-test\target\classes
[INFO]
[INFO] --- maven-resources-plugin:2.6:testResources (default-testResources) @ maven-unit-test ---
[INFO] Using 'UTF-8' encoding to copy filtered resources.
[INFO] skip non existing resourceDirectory C:\myprogram\java\maven\03-maven-unit-test\src\test\resources
[INFO]
[INFO] --- maven-compiler-plugin:3.1:testCompile (default-testCompile) @ maven-unit-test ---
[INFO] Changes detected - recompiling the module!
[INFO] Compiling 2 source files to C:\myprogram\java\maven\03-maven-unit-test\target\test-classes
[INFO]
[INFO] --- maven-surefire-plugin:2.22.0:test (default-test) @ maven-unit-test ---
Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire-junit-platform/2.22.0/surefire-junit-platform-2.22.0.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire-junit-platform/2.22.0/surefire-junit-platform-2.22.0.pom (7.0 kB at 4.9 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire-providers/2.22.0/surefire-providers-2.22.0.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire-providers/2.22.0/surefire-providers-2.22.0.pom (2.5 kB at 6.2 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/junit/platform/junit-platform-launcher/1.2.0/junit-platform-launcher-1.2.0.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/junit/platform/junit-platform-launcher/1.2.0/junit-platform-launcher-1.2.0.pom (2.2 kB at 3.8 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/junit/platform/junit-platform-engine/1.2.0/junit-platform-engine-1.2.0.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/junit/platform/junit-platform-engine/1.2.0/junit-platform-engine-1.2.0.pom (2.4 kB at 5.2 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/junit/platform/junit-platform-commons/1.2.0/junit-platform-commons-1.2.0.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/junit/platform/junit-platform-commons/1.2.0/junit-platform-commons-1.2.0.pom (2.0 kB at 3.6 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/opentest4j/opentest4j/1.1.0/opentest4j-1.1.0.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/opentest4j/opentest4j/1.1.0/opentest4j-1.1.0.pom (1.7 kB at 2.5 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/junit/platform/junit-platform-launcher/1.2.0/junit-platform-launcher-1.2.0.jar
Downloading from central: https://repo.maven.apache.org/maven2/org/opentest4j/opentest4j/1.1.0/opentest4j-1.1.0.jar
Downloading from central: https://repo.maven.apache.org/maven2/org/junit/platform/junit-platform-engine/1.2.0/junit-platform-engine-1.2.0.jar
Downloading from central: https://repo.maven.apache.org/maven2/org/junit/platform/junit-platform-commons/1.2.0/junit-platform-commons-1.2.0.jar
Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire-junit-platform/2.22.0/surefire-junit-platform-2.22.0.jar
Downloaded from central: https://repo.maven.apache.org/maven2/org/opentest4j/opentest4j/1.1.0/opentest4j-1.1.0.jar (6.8 kB at 7.7 kB/s)
Downloaded from central: https://repo.maven.apache.org/maven2/org/junit/platform/junit-platform-launcher/1.2.0/junit-platform-launcher-1.2.0.jar (80 kB at 88 kB/s)
Downloaded from central: https://repo.maven.apache.org/maven2/org/junit/platform/junit-platform-engine/1.2.0/junit-platform-engine-1.2.0.jar (90 kB at 74 kB/s)
Downloaded from central: https://repo.maven.apache.org/maven2/org/junit/platform/junit-platform-commons/1.2.0/junit-platform-commons-1.2.0.jar (78 kB at 51 kB/s)
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire-junit-platform/2.22.0/surefire-junit-platform-2.22.0.jar (66 kB at 38 kB/s)
[INFO]
[INFO] -------------------------------------------------------
[INFO]  T E S T S
[INFO] -------------------------------------------------------
[INFO] Running com.mkyong.examples.TestMagicBuilder
[INFO] Tests run: 1, Failures: 0, Errors: 0, Skipped: 0, Time elapsed: 0.005 s - in com.mkyong.examples.TestMagicBuilder
[INFO] Running com.mkyong.examples.TestMessageBuilder
[INFO] Tests run: 2, Failures: 0, Errors: 0, Skipped: 0, Time elapsed: 0 s - in com.mkyong.examples.TestMessageBuilder
[INFO]
[INFO] Results:
[INFO]
[INFO] Tests run: 3, Failures: 0, Errors: 0, Skipped: 0
[INFO]
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time:  9.433 s
[INFO] Finished at: 2020-05-21T17:06:03+08:00
[INFO] ------------------------------------------------------------------------


C:\myprogram\java\maven\03-maven-unit-test>mvn -Dtest=TestMessageBuilder test
[INFO] Scanning for projects...
[INFO]
[INFO] ----------------< com.mkyong.examples:maven-unit-test >-----------------
[INFO] Building maven-unit-test 1.0-SNAPSHOT
[INFO] --------------------------------[ jar ]---------------------------------
[INFO]
[INFO] --- maven-resources-plugin:2.6:resources (default-resources) @ maven-unit-test ---
[INFO] Using 'UTF-8' encoding to copy filtered resources.
[INFO] skip non existing resourceDirectory C:\myprogram\java\maven\03-maven-unit-test\src\main\resources
[INFO]
[INFO] --- maven-compiler-plugin:3.1:compile (default-compile) @ maven-unit-test ---
[INFO] Nothing to compile - all classes are up to date
[INFO]
[INFO] --- maven-resources-plugin:2.6:testResources (default-testResources) @ maven-unit-test ---
[INFO] Using 'UTF-8' encoding to copy filtered resources.
[INFO] skip non existing resourceDirectory C:\myprogram\java\maven\03-maven-unit-test\src\test\resources
[INFO]
[INFO] --- maven-compiler-plugin:3.1:testCompile (default-testCompile) @ maven-unit-test ---
[INFO] Nothing to compile - all classes are up to date
[INFO]
[INFO] --- maven-surefire-plugin:2.22.0:test (default-test) @ maven-unit-test ---
[INFO]
[INFO] -------------------------------------------------------
[INFO]  T E S T S
[INFO] -------------------------------------------------------
[INFO] Running com.mkyong.examples.TestMessageBuilder
[INFO] Tests run: 2, Failures: 0, Errors: 0, Skipped: 0, Time elapsed: 0.01 s - in com.mkyong.examples.TestMessageBuilder
[INFO]
[INFO] Results:
[INFO]
[INFO] Tests run: 2, Failures: 0, Errors: 0, Skipped: 0
[INFO]
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time:  2.614 s
[INFO] Finished at: 2020-05-21T17:07:15+08:00
[INFO] ------------------------------------------------------------------------


C:\myprogram\java\maven\03-maven-unit-test>mvn -Dtest=TestMessageBuilder#testHelloWorld test
[INFO] Scanning for projects...
[INFO]
[INFO] ----------------< com.mkyong.examples:maven-unit-test >-----------------
[INFO] Building maven-unit-test 1.0-SNAPSHOT
[INFO] --------------------------------[ jar ]---------------------------------
[INFO]
[INFO] --- maven-resources-plugin:2.6:resources (default-resources) @ maven-unit-test ---
[INFO] Using 'UTF-8' encoding to copy filtered resources.
[INFO] skip non existing resourceDirectory C:\myprogram\java\maven\03-maven-unit-test\src\main\resources
[INFO]
[INFO] --- maven-compiler-plugin:3.1:compile (default-compile) @ maven-unit-test ---
[INFO] Nothing to compile - all classes are up to date
[INFO]
[INFO] --- maven-resources-plugin:2.6:testResources (default-testResources) @ maven-unit-test ---
[INFO] Using 'UTF-8' encoding to copy filtered resources.
[INFO] skip non existing resourceDirectory C:\myprogram\java\maven\03-maven-unit-test\src\test\resources
[INFO]
[INFO] --- maven-compiler-plugin:3.1:testCompile (default-testCompile) @ maven-unit-test ---
[INFO] Nothing to compile - all classes are up to date
[INFO]
[INFO] --- maven-surefire-plugin:2.22.0:test (default-test) @ maven-unit-test ---
[INFO]
[INFO] -------------------------------------------------------
[INFO]  T E S T S
[INFO] -------------------------------------------------------
[INFO] Running com.mkyong.examples.TestMessageBuilder
[INFO] Tests run: 1, Failures: 0, Errors: 0, Skipped: 0, Time elapsed: 0.005 s - in com.mkyong.examples.TestMessageBuilder
[INFO]
[INFO] Results:
[INFO]
[INFO] Tests run: 1, Failures: 0, Errors: 0, Skipped: 0
[INFO]
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time:  2.560 s
[INFO] Finished at: 2020-05-21T17:08:03+08:00
[INFO] ------------------------------------------------------------------------
