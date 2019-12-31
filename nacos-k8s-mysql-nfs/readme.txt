背景：
现在的Mysql  on k8s还不是很成熟。对于研发能力普通的中小型企业为了稳定，一般还会选对外置Mysql集群的。
所以特地对做了修改，供大家参考， 支持mysql单IP， 双IP。

顺便说一次： 在java程序中接数据库单IP即可。Java不需要知数据库的拓扑。用数据库代理层即可。比如mysql Router, ProxySql之类.