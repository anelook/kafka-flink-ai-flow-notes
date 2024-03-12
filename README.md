# kafka-flink-ai-flow-notes

## Get the JAR 

```git clone https://github.com/Aiven-Labs/flink-ai-job```
```nvm clean package```

## Create services:
- Aiven for Apache Kafka
- Aiven for Apache Flink --> Upload and deploy custom JARs - enable

## Add topics to Apache Kafka
- reviews-in
- positive-review
- negative-review

## Create integration between Kafka and Flink
- Console -> Create pipeline -> Data Service Integrations -> select Kafka service -> click on Integrate
- Console -> Application ->  new application -> jar

## Get integration_id
https://aiven.io/docs/products/flink/howto/manage-credentials-jars
install cli
conda env list
conda create --name aiven
conda activate aiven
conda install pip
pip install aiven-client

login 
Create a token
avn user login you@example.com --token

avn service integration-list service-name


## Get OpenAI key

## Deployment

myKafkaSource=INTEGRATION_ID
openAIKey=


