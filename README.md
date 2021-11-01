本目录存放Solo模式启动的fabric网络，用于开发环境，便利于调试智能合约:
1. 不使用TLS
2. 不使用Raft集群, 而是SOLO模式
3. peer是dev模式启动

本组织复用了生产环境(xixisese/fabric-prod)的ca，采用了orgA根证书和管理员证书

启动成功后，调试智能合约的方法见[fabric调试chaincode的方法](http://liwuzhi.art/?p=444)

