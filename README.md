# aliyun-kafka-logstash-docker

> 使用阿里云的ONS自带的kafka模式，使用logstash来生产或者消费kafka消息的时候，配置需要注意，用ONS模式进行鉴权，详细配置参考：`logstash.conf`，需要注意的是需要将`ons-sasl-client-0.1.jar`包拷贝到logstash的kafka-input-plugin目录下面去，不然用ONS模式进行鉴权的时候会找不到该包

## 参考文档：
https://github.com/dongeforever/KafkaOnsDemo

https://www.elastic.co/guide/en/logstash/current/plugins-inputs-kafka.html

