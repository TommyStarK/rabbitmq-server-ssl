# rabbitmq-server-ssl
RabbitMQ server running in a docker container with ssl enabled

# Usage

```
# Edit 'pkiGenerator.sh' to setup your dns on the rabbitmq server
$ ./pkiGenerator.sh
$ dock-compose up --build --detach
```