# mybatis_reverse_engineering
通过mybatis生成单表相关的pojo和mapping文件

# 步骤
将项目打包，放到该目录下：microservice-mybatis-1.0-SNAPSHOT.jar

1.在config下的generatorConfig.xml文件中配置好自己的mysql数据库地址和账号密码以及要生成的表
2.打开dos窗口进入到当前jar文件所在的目录(可以直接按着shift右击直接在当前文件下打开dos窗口)
3.执行命令：java -jar microservice-mybatis-1.0-SNAPSHOT.jar
4.在config文件夹下会生成单表相关的pojo文件和mapping映射文件
