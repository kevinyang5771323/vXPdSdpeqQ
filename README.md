# Python Socket 与多线程聊天室系统 python370

## 项目概述


## 技术栈

- **后端**：Python 3.x, socket, threading
- **客户端GUI**：Python 3.x, tkinter, customtkinter, PIL

## 运行环境

- Python 3.7 或更高版本

## 功能模块

### 客户端功能

- 用户连接：支持昵称设定，处理昵称冲突逻辑
- 实时聊天：发送和接收文本消息，支持群聊和私聊
- 图片消息：选择图片，通过Base64编码发送和展示

### 服务器端功能

- 在线状态：维护在线用户列表，实时更新
- 并发处理：通过多线程支持同时与多个客户端通信
- 基础容错：监测客户端异常断开，实现自动重连机制

## 系统角色

- 客户端：用户通过图形界面与服务器进行交互，发送和接收消息
- 服务器端：处理客户端连接，消息广播，维护共享状态

## 目录结构

```
/chatroom_system
|-- /client
|   |-- main.py
|   |-- gui.py
|   |-- utils.py
|-- /server
|   |-- main.py
|   |-- chatroom.py
|   |-- threading.py
|-- README.md
|-- setup.py
```

## 部署步骤

1. 确保Python环境为3.7版本以上
2. 克隆或下载项目至本地
3. 根据需要配置环境，安装必要的Python库
4. 分别在服务器端和客户端执行主程序

## 核心亮点

- 使用纯Python实现，易于学习和理解
- 实现了基础的并发处理和共享状态管理
- 支持文本和图片消息的发送与接收
- 提供完整的注释源码，便于跟随实践
- 适合作为期末项目或课程设计使用，直观展现网络编程和分布式系统基础知识的应用

## 免费源码获取

```
8000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)


## 项目截图

![](https://img14.360buyimg.com/ddimg/jfs/t1/329802/11/17074/19068/68d40d9dF1a338adb/5fe436eefaff5ee0.jpg)

![](https://img11.360buyimg.com/ddimg/jfs/t1/240851/31/30091/49765/68d40d9dF11d13f76/3b9714794f84679e.jpg)

![](https://img10.360buyimg.com/ddimg/jfs/t1/330475/9/16848/70118/68d40d9eFa59b79d2/5f7ee336ca6aa61a.jpg)
