# java-lab

工作无关的个人兴趣代码实验场。按主题拆成独立模块，每个模块挂上想摸的技术栈，边读源码边验证想法。

| 模块 | 想验证什么 | 主要依赖 |
| --- | --- | --- |
| `api-lab` | RPC 协议与序列化 | protobuf / gRPC / Hessian |
| `net-lab` | 网络编程、HTTP/2 与 HTTP/3 | spring-boot-web / Netty / gRPC-netty |
| `raft-lab` | 共识算法的不同实现 | raft-java / dledger / Ratis |
| `misc-lab` | JVM 字节码、MySQL 协议 | ASM / classfile 教程 / mysql-protocol |

模块目前基本是骨架，验证过的部分才会有完整实现。
