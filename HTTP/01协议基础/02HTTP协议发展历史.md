## HTTP/0.9

* 只有一个命令GET
* 没有Header等描述数据的信息
* 服务器发送完毕就关闭TCP连接

## HTTP/1.0

* 增加很多命令
* 增加status code 和 header
* 多字符集支持、多部分发送、权限、缓存等

## HTTP/1.1

* 持久连接 keep-alive
* pipeline 同一个tcp连接里发送多个请求
* 增加host和其他一些命令

## HTTP2

* 所有数据以二进制传输
* 同一个连接里发送多个请求不需按顺序来 并行，提升传输效率
* 头信息压缩以及**推送**等提高效率的功能
