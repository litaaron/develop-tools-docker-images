# Docker 搭建代码质量检测中文平台 SonarQube

## 国际化
重新构建 sonar Dockerfile
将 sonar-l10n-zh-plugin-1.16.jar ADD /opt/sonarqube/extensions/plugins/ 目录下

/opt/sonarqube/extensions/plugins/ 为 sonar 插件目录


## 编译启动
```shell
docker-compose build
docker-compose up -d
```

## findbugs 地址
https://github.com/spotbugs/sonar-findbugs/

## p3c 地址
https://gitee.com/jasonlong10/sonar-p3c-pmd-plugin

## web api
http://172.23.50.100:9000/web_api
