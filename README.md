# LocalChatRoom

项目描述：聊天系统基于C/S编程模型，集服务器和客户端为一体，实现多用户并发模式下的聊天功能，包括登录、查看好友列表、私聊、公聊、消息记录、退出等操作。
开发环境：Windows、MFC、VS2013
主要职责：
	使用MFC框架设计图形界面， socket进行TCP网络通信，WSAAsyncSelect模型实现并发交互；
	实现服务器端socket的地址绑定、监听、数据接收和解析，及客户端的连接和数据发送；
	自定义协议，区分好友、私聊、公聊等功能。

