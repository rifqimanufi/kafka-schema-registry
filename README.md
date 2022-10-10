# kafka-schema-registry

This is a repository for Session 8 of Data Engineer Fellowship in IYKRA. In this session, I was tasked to make an avro producer and consumer using bitcoin_price_Training dataset.

Pre-requisite:

Python 3.7 or later.
confluent_kafka. You can get that by using command pip install confluent_kafka.
avro. You can get that by using command pip install avro-python3.
requests. You can get that by using command pip install requests.

How to run:

Open your working file directory and navigate it in your terminal to use command docker-compose up to run file docker-compose.yml.
You can edit your key and value schema based on your choice in file bitcoin_price_key.avsc and bitcoin_price_value.avsc.
Run python file avro_producer.py with command python avro_producer.py.
Run python file avro_consumer.py with command python avro_consumer.py.
Simply kill every terminal if you're done running and use docker-compose down to delete all container.
