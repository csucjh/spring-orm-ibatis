其实是因为spring4.0开始不在支持ibatis，所以将最后一个支持版本的spring-orm中的ibatis包拉出来单独形成一个包

这种方式老项目改造成本小，还有一种改造就是直接升级到mybatis但是需要对sql改造，成本太大


使用方式：
1、先使用mvn clean install安装包到本地仓库，或者上传到本地nexus私服

2、添加依赖
<dependency>
    <groupId>org.springframework</groupId>
    <artifactId>spring-orm-ibatis</artifactId>
    <version>4.3.14.RELEASE</version>
</dependency>
