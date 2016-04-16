# Net-working-experiment

<h1>网络编程课程实验题目Node.js版（利用Electron实现C-S模型）</h1>

客户端截图:<img width='300' height='300' src="https://github.com/NumberZ/Net-working-experiment/blob/master/images/client.png" />
服务端截图:<img  width='300' height='300' src="https://github.com/NumberZ/Net-working-experiment/blob/master/images/server.png" />
<strong>利用Electron实现C-S模式</strong>

* 实验1:C-S通信

  实验要求：
  
  1. 设计程序，分别构建通信的两端:服务器端和客户端应用程序,套接字类型为面向连接的Socket,自己构建双方的应答模式，实现双方的数据的发送和接收（S发给C，C发给S）。
  
  2. 服务端程序能响应单个或任意多个客户端连接请求；服务端能向单个客户发送消息，支持群发消息给所有客户端；
  
  3. 通信的双方具备异常响应功能，包括对方异常退出的处理。如果客户端退出，服务器有响应；反之亦然。
  
* 实验2:C-C通信

  实验要求：
    
  1. Server支持多客户访问；
  
  2. C与S之间使用TCP连接；
  
  3. C与C之间直接通信（不是通过S传递）。
  
  4. C与C之间直接通信既可以使用TCP，也可以使用UDP。
  
