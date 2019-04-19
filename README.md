# rabbitmq-server-ssl
RabbitMQ server running in a docker container with ssl enabled

## Usage

```
# Edit 'pkiGenerator.sh' to setup your dns on the rabbitmq server
$ ./pkiGenerator.sh
$ dock-compose up --build --detach
```

## UI management

- http://127.0.0.1:15672

**credentials:** `guest/guest`