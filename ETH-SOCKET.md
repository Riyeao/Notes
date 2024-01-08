# ETH-SOCKET

线程：defaultTaskHandle：lwip初始化，以太网管理初始化，（APP层初始化中的）对收发对象进行配置初始化，for循环中不断判断管理员是否在线，在线则进行发送，否则等待两个周期（考虑单独开个线程，不用默认线程？）

​			EtherRecvTaskHandle：空

