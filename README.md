# tGoogleSearchAnalytics

This Talend component is dedicated to get search analytics information from Google Webmasters API.

## Install instructions

### Install all requirments:

* Talend Open Studio 7.x
* Java Development Kit (JDK).
* Maven.

### Run:


$ git clone https://github.com/jrosell/tGoogleSearchAnalytics

$ cd tGoogleSearchAnalytics

$ chmod u+x mvnw

$ ./mvnw clean install
```
...
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time:  9.109 s
[INFO] Finished at: 2020-09-01T17:12:43+02:00
[INFO] ------------------------------------------------------------------------
```

$ java -jar target/thediar-talendcomp-googlesearchanalytics-0.0.1-SNAPSHOT.car studio-deploy /path/to/my/talend


For example:

$ java -jar target/thediar-talendcomp-googlesearchanalytics-0.0.1-SNAPSHOT.car studio-deploy /home/jordi/Projects/talend/TOS_DI-Win32-20200219_1130-V7.3.1
```
[studio-deploy, /home/jordi/Projects/talend/TOS_DI-Win32-20200219_1130-V7.3.1]
/home/jordi/Projects/talend/TOS_DI-Win32-20200219_1130-V7.3.1/configuration/.m2/repository/org/codehaus/mojo/animal-sniffer-annotations/1.14/animal-sniffer-annotations-1.14.jar already exists, skipping
/home/jordi/Projects/talend/TOS_DI-Win32-20200219_1130-V7.3.1/configuration/.m2/repository/org/mortbay/jetty/servlet-api/2.5-20081211/servlet-api-2.5-20081211.jar already exists, skipping
/home/jordi/Projects/talend/TOS_DI-Win32-20200219_1130-V7.3.1/configuration/.m2/repository/org/mortbay/jetty/jetty-util/6.1.26/jetty-util-6.1.26.jar already exists, skipping
/home/jordi/Projects/talend/TOS_DI-Win32-20200219_1130-V7.3.1/configuration/.m2/repository/com/google/code/findbugs/jsr305/3.0.2/jsr305-3.0.2.jar already exists, skipping
/home/jordi/Projects/talend/TOS_DI-Win32-20200219_1130-V7.3.1/configuration/.m2/repository/org/mortbay/jetty/jetty/6.1.26/jetty-6.1.26.jar already exists, skipping
/home/jordi/Projects/talend/TOS_DI-Win32-20200219_1130-V7.3.1/configuration/.m2/repository/commons-logging/commons-logging/1.2/commons-logging-1.2.jar already exists, skipping
/home/jordi/Projects/talend/TOS_DI-Win32-20200219_1130-V7.3.1/configuration/.m2/repository/com/google/errorprone/error_prone_annotations/2.1.3/error_prone_annotations-2.1.3.jar already exists, skipping
```

### Restart Talend Open Studio:

Close and open your Talend Open Studio and check on your Palette for tGoogleSearchAnalyticsInput component:

![Installed](installed.png)