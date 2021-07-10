# simple_im
 简单即时通讯

 使用方法：
 1. 启动服务
    nodemon socket.js 
 2. 连接到服务
    telnet ip port 
    即telnet localhost 9000
 3. 发送数据 
    在terminal 输入数据即可
    
问题
1. 如果telnet没有命令怎么办？
    * mac brew安装
    * window 自带telnet服务，在控制面板/程序/启用或关闭windows功能中开启
2. telnet只能单字符发送怎么办？
    使用ctrl+] 开启命令模式
    使用send xxx 发送整个字符串

