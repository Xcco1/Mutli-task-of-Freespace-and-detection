# Mutli-task-of-Freespace-and-detection

The task is still processing！~

You are welcome to contact me by WeChat:18202113716 or QQ:1377125526

首先第一次尝试该多任务，首先采取共享backbone的方式，backbone采用MobileNetV2，和我们其他工作中的backbone保持了一直。

对于检测，采用NanoDet中的GhostFPN，以及Head，

对于FreeSpace,先借鉴BiseNetV2,使用BGA layer进行特征融合，然后设计了一个轻量化分割头。

now the parameters:2.16M,GFlops:9.17 when the input size is (720,1280)

![img](https://user-images.githubusercontent.com/61531491/178978468-a630424d-f949-4523-9164-0fedf6613b37.jpg)
![img](https://user-images.githubusercontent.com/61531491/178978721-dbc36f96-5de7-4d0d-aa06-12d07c2a1108.jpg)


