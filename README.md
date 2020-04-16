# multiparty-meeting-win
可私有云、局域网部署的轻量级视频会议系统，这个是windows平台编译版本

客户端基于chrome内核的浏览器运行，支持多人视频会议、屏幕共享、文件共享、文字交互等功能

演示地址：https://meeting.linksoon.net:440/

基于multiparty-meeting编译

原项目地址：https://github.com/havfo/multiparty-meeting

windows编译版下载：http://www.linksoon.net/solution/Details.html?ID=141

执行方式：

1、首先开启redis服务

在redis目录执行 redis-server redis.windows.conf

2、开启服务端

在server目录执行 npm start

3、运行app目录下的客户端
