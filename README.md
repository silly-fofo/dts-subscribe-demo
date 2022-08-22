1、下载如下的jar包到客户订阅client运行的环境

2、编写config配置文件：
brokerUrl=your broker url
topic=your dts topic
sid=your sid
userName=your user name
password=your password
initCheckpoint=start timestamp
subscribeMode=ASSIGN
isForceUseInitCheckpoint=true

3、运行如下命令：
java -jar dts_subscribe_sdk_dep_demo-1.0-SNAPSHOT-jar-with-dependencies.jar config

4、让用户查看并提供dts-new-subscribe.log日志文件
