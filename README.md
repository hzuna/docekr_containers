# docekr_containers

## (java version "1.8.0_261") with (tomcat)/platform: Centos:7

### 使用: 
#### 1.docker pull hzunadocker/java-env:latest
#### 2.docker run -p 6666:8080 -it hzunadocker/java-env /bin/bash
#### 3.cd /usr/local/apache-tomcat-9.0.41/bin
#### 4. ./startup.sh

### 验证: 
#### 打开浏览器访问主机ip:6666
#### java -version

----------------------------------------------------------------------------------------------------------

## Apache2 + Mysql + PHP7.4 + PHPMyadmin/platform: Ubuntu
### 使用:
#### 1.docker pull hzunadocker/webservice:latest
#### 2.docker run -p 8080:80 -it hzunadocker/webservice /bin/bash
#### 2.service mysql start
#### 3.service apache2 start

### 验证:
#### 打开浏览器访问主机ip:8080

### 说明:
#### web目录在 /var/www/html
