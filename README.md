# voltdb_tpcc

# 1 Set up the environment

sudo apt -y install ant build-essential ant-optional python cmake valgrind ntp ccache git python-httplib2 python-setuptools python-dev apt-show-versions 

(Notice, since we need JDK8, but the default version is already openjdk-11-* in Ubuntu20)

sudo apt remove --autoremove openjdk-11-* 

sudo apt install openjdk-8-jdk 

![image](https://user-images.githubusercontent.com/55301130/189866171-f444180f-c6b6-4fa6-8f1a-ff7f40635d6d.png)

# 2 Build the VoltDB (https://github.com/VoltDB/voltdb/wiki/Building-VoltDB)

git clone https://github.com/VoltDB/voltdb.git

cd voltdb

ant

(If build up successfully) cd bin; ./voltdb --version

![image](https://user-images.githubusercontent.com/55301130/189867067-6ec2c34a-c3f4-4f93-9c55-5dd152d04502.png)

(add ~/voltdb/bin into ${PATH})


