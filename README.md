# hdp-9-kafka-manager

### hdp-6-jupyter-configuration

> Configuration
- 4 VMs on google compute Engine (3 VM for Hadoop Cluster and 1 VM for data backup and micro services)
- OS: CentOS 7
- RAM: 15 Go
- CPU: 4
- Boot disk: 200Go
- Attached disk: 2000G

> Cluster model

![MetaStore remote database](https://github.com/gamboabdoulraoufou/hdp-1-host-config/blob/master/img/archi_v2.png)


> 1- Install python and all dependencies
```sh
$ git clone https://github.com/yahoo/kafka-manager.git
$ cd kafka-manager/

$ ./sbt clean dist

cd target/universal/
unzip kafka-manager-1.3.3.4.zip
cd kafka-manager-1.3.3.4/

ZK_HOSTS=localhost:2181 ./bin/kafka-manager

  ```
  
 
