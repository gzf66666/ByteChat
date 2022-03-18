# ByteChat
基于muduo网络库在Nginx tcp负载均衡环境中的集群聊天服务器和客户端源码

编译方式:
方法一————手动编译
1.cd build
2.rm -rf *
3.cmake ..
4.make
方法二————使用自动编译脚本一键编译
./autobuild.sh

文件夹介绍：
bin/ 可执行文件夹 存放服务器和客户端的可执行文件
build/ 编译链接过程中所需要的所有构造文件
include/ 项目所有头文件
src/ 项目所有源文件
test/ 测试文件
thirdparty/ 第三方文件

运行程序前需要运行Nginx，并配置数据库
