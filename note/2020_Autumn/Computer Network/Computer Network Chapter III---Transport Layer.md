# Computer Network Chapter III---Transport Layer

## General and Service by Transport Layer

报文段segment从发送应用程序进程接收到的报文转换成传输层分组，该分组成为运输层的报文段

实现：应用报文划分成较小的块，并未每块加上一个运输层首部生成运输层报文段

运输层协议：TCP UDP

### 运输层&&网络层

网络层：提供了主机之间的逻辑通信

传输层：不同主机进程间的逻辑通信

传输层协议工作在端系统中，在应用层和网络层之间提供通信

传输层协议工作在网络层之上，提供的服务受制于底层网络协议的服务模型，比如带宽和时延保证

但是，底层网络协议同意不能在网络层提供相应的服务，运输层服务也能提供某些服务，底层网络协议不可靠，运输协议也能提供可靠的数据传输服务，另外的例子是加密

### Internet运输层概述

#### IP网际协议

服务模型：尽力而为交付服务，但不确保，称为不可靠服务

UDP,TCP基本责任