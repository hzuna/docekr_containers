# docekr_containers

### (java version "1.8.0_261") with (tomcat)/platform: Centos:7

#### 使用: 
> 1.docker pull hzunadocker/java-env:latest</br>
> 2.docker run -p 6666:8080 -it hzunadocker/java-env /bin/bash</br>
> 3.cd /usr/local/apache-tomcat-9.0.41/bin</br>
> 4. ./startup.sh</br>

#### 验证: 
> 打开浏览器访问主机ip:6666</br>
> java -version</br>

---

### Nginx + MariaDB + PHP7.4 /platform: Alpine
#### 使用:
>1.docker pull hzunadocker/alpine_with_webservice</br>
>2.docker run -p 8080:80 -it hzunadocker/alpine_with_webservice /bin/sh</br>
>2.rc-service mysql start</br>
>3./usr/sbin/nginx</br>

#### 验证:
>打开浏览器访问主机ip:8080
