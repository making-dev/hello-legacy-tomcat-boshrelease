```
wget https://download.run.pivotal.io/openjdk-jdk/trusty/x86_64/openjdk-1.8.0_111.tar.gz
wget http://ftp.kddilabs.jp/infosystems/apache/tomcat/tomcat-8/v8.0.38/bin/apache-tomcat-8.0.38.tar.gz
wget https://github.com/making/hello-legacy-tomcat/releases/download/1.0/hello-legacy-tomcat-1.0.war
bosh add blob openjdk-1.8.0_111.tar.gz java
bosh add blob apache-tomcat-8.0.38.tar.gz tomcat
bosh add blob hello-legacy-tomcat-1.0.war hello-legacy-tomcat
```
