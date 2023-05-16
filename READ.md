creating the kafka topics and set up
https://medium.com/@sangeethaprabhagaran/creating-a-kafka-topic-in-windows-e51b15e5ccd4

pushing mysql data into kafka
https://medium.com/@sangeethaprabhagaran/pushing-mysql-data-into-kafka-6ab8ab5bf755

kafka producer step--- 
KafkaProducer(bootstrap_servers=['localhost:9092'],
              api_version=(0,11,5),
              value_serializer=lambda x: dumps(x).encode('utf-8'))