# BipedRobot
Biped robot 两足机器人


## Design
1. 操作系统应该使用Centos或Ubuntu。
2. 身体各部分模块化设计，接口标准化。


## Other
1. 使用Centos和Ubuntu的目的是：
   - 接入其丰富的软硬件支持。支持日常使用的软硬件，而不是为机器人专门设计开发的操作系统、软硬件。
   - 降低开发门槛。去除传统嵌入式开发对于硬件的要求。降低软件开发的门槛，应该可以支持所有主流的标准C、C++、Java、C#、Python、Matlab等语言，而不是嵌入式需要的C或C++语言，各个芯片的C还有些不一样。这样可以增大开发者的群体。
2. 各个部分可以单独开发。接口标准化的目的是，不限制编程语言的使用。身体部分可以只有一条腿。单腿一般是跳跃行走，双腿一般是正常不行。