# BipedRobot
Biped robot 两足机器人


## Design
1. The operating system should use Centos or Ubuntu.
2. Modular design of each body part and standardized interface.


## Other
1. The purpose of using Centos and Ubuntu is to: 
   - Access its rich software and hardware support. Support daily software and hardware, instead of operating system, software and hardware specially designed and developed for robots. 
   - Reduce the threshold for development. Remove traditional hardware requirements for embedded development. Reducing the threshold of software development should support all mainstream standard C, C ++, Java, C #, Python, Matlab and other languages, instead of the C or C ++ language required for embedded, and the C of each chip is somewhat different. This can increase the developer community.
2. Each part can be developed separately. The purpose of interface standardization is not to limit the use of programming languages. The body part can have only one leg. One leg is generally a jumping walk, and legs are usually normal.