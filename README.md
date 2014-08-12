[![Build Status](https://travis-ci.org/itsrunning/Webdriver_Java_TestNG_Gradle.svg?branch=master)](https://travis-ci.org/itsrunning/Webdriver_Java_TestNG_Gradle)

# Webdriver-Java-TestNG test framework

A Java/TestNG web automation framework with Webdriver.

## Get running...
Step 1: Clone this repository to your local
```
git clone https://github.com/itsrunning/Webdriver_Java_TestNG_Gradle.git
```

Step 2: Ensure Java 8 and gradle build tool are installed in your local machine
```
  JAVA_8 : http://www.oracle.com/technetwork/java/javase/overview/java8-2100321.html
  Gradle : http://www.gradle.org/downloads

```
Step 3: Provided Firefox is installed, proceed to run the TestNG test
```
  gradle test
```

## FAQ
 ```
 1. Which IDE can be used for writing test?
       - Not necessary to use Eclipse or Intellija and you can use any open source IDE.
       Eclipse : https://www.eclipse.org/downloads/
       IntelliJ IDEA : http://www.jetbrains.com/idea/download/

 2. How to resolve  Error "command not found: gradle" ?
      - Install gradle through brew or download zip file from internet and extract to your local. And add gradle full path ( .../../bin) to your PATH variable.
      - Set Java_Home to PATH Variable.
 3. How to configure TestNG?
      - No need to configure TestNG and its available with gradle.

 ```