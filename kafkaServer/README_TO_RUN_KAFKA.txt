-- create zookeeper server
cd D:\NguyenNghia\kafka
.\bin\windows\zookeeper-server-start.bat .\config\zookeeper.properties

-- create a topic

.\bin\windows\kafka-topics.bat --create --topic topic-example --bootstrap-server localhost:9092