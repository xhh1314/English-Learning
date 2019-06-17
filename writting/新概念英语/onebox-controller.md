
### ControllerCenter

process()方法是各种pc qa方法的入口，这个方法基本可以覆盖大部分文本搜索的状态

processQaRequst() 方法主要是解析request参数，并发送请求，其中get 和 post方法解析参数方式不一样，不过最后都会把参数封装到`QaRequest`中，然后构造一个IOneboxHandler发送请求，IOneboxHandler有多个实现，这里应该实现了lu的调用

processResponse()是把收到的结果转换成json，其中有一个redirect方法值得注意

### OneboxServiceSocket
该类里实现当调用asr服务获取到query之后，进行结果查询
