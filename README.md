# zookeeper-initd-image
可以初始化数据的zookeeper docker image；实现类似mysql image可以初始化写入数据的功能。  
When a container is started for the first time, a new database with the specified name will be created and initialized with the provided configuration variables. Furthermore, it will execute files with extensions .sh, .sql and .sql.gz that are found in /docker-entrypoint-initdb.d. Files will be executed in alphabetical order...  
https://hub.docker.com/_/mysql
