# spark_installation
Directions on Setting up a Master and Slaves for Spark

## Master Node

1.  `sudo pacman -Syyu jre8-openjdk`
2.  `sudo pacman -Syyu scala`
3.  `# wget http://www.us.apache.org/dist/spark/spark-1.4.1/spark-1.4.1.tgz`
4.  `# tar zxvf spark-1.4.1.tgz`
5.  `# cd spark-1.4.1`
6.  `# build/mvn -Pyarn -Phadoop-2.4 -Dhadoop.version=2.4.0 -DskipTests clean package`
7.  `sudo pacman -Syyu maven`
8.  make sure multilib is enabled
8.  `pacaur -Syyu unixodbc java-runtime libxtst`
9.  

## Slave Node
