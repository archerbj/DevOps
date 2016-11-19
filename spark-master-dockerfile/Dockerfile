#version:0.0.1
#版本号

#指明基础镜像
FROM archerbj/spark-base:latest

#作者信息
MAINTAINER Archer “277525065@qq.com"

#开放端口 8080
EXPOSE 8080

#设置自启动EntryPoint
ENTRYPOINT ["/bin/bash","-c","/home/eti/spark-2.0.0-bin-hadoop2.7/sbin/start-master.sh && tail -f /dev/null"]

#设置自启动命令
#CMD ["-D"]
