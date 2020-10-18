# tiny_docker

C++

# 1.建cpp文件

root@youyou-virtual-machine:/home/youyou/hello# vim hello.cpp
     
# 2.编写dockerfile

root@youyou-virtual-machine:/home/youyou/hello# vim hell-dockerfile 

# 3.创建镜像
root@youyou-virtual-machine:/home/youyou/hello# docker build -f ./hell-dockerfile  -t my-hello-docker:v1.0 .

# 4.运行镜像

root@youyou-virtual-machine:/home/youyou/hello# docker run my-hello-docker:v1.0

# 5.运行结果

