# Kafka platform with Health+ configurations

Kafka platform with a Kafka cluster of 3 brokers. The brokers are configured with Health+ configurations.

## Start locally

To start the services locally, you need to get the API access key/secrets for Health+. Follow these steps to start locally.

* Confluent Cloud signup: To start the platform locally with Health+ you would need to signup with Confluent Health+ through https://confluent.cloud/health-plus/signup.
* Generate Health+ access key/secrets: Sign in to the Confluent Cloud account, choose Health+ and generate Health+ access key and secrets. 
* Configure docker envs: update the file [env file](./.env) with the Health+ credentials you generated.

Now, you should be able to start locally using `docker-compose up -d`.

## View the dashboard

Within few minutes the metadata should be uploaded into Confluent Cloud and can be accessed through https://confluent.cloud/health-plus/clusters.


