##智能车任务分配项目
---
使用netty5做服务端，智能车作为客户端，服务端负责与每个智能车通信，为每个智能车分配任务。
### 编程日志
---

2.16 分配任务给每个客户端

2.17 大量更新

    1 设计实现服务器与智能车的通信协议；
    2 完善服务器的指令读取功能；
    3 服务器实现接收智能车位置，接收控制台输入的任务信息；
    4 服务器实现根据任务和智能车位置，为每台智能车分配任务；
    5 服务器实现将任务发送给对应的智能车；
    3 实现智能车上传位置信息与读取任务分配结果功能。
