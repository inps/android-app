## 1. 需要配置android代理
## 2. 配置build.gradle, 手动下载gradle6.1.1

buildscript {
    repositories {
        google()
        maven {
            url 'http://maven.aliyun.com/nexus/content/groups/public/'
        }

        jcenter()