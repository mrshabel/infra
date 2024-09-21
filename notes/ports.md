# PORT MAPPINGS

Applications and their respective internal and external ports are shown in the table below. The common nextwork shared across all instances of the application allows us to use the service names as the host of the application, `service-name:port`.

| Application          | Internal Port | External Port |
| -------------------- | ------------- | ------------- |
| Nginx                | 80            | 8000          |
| RabbitMQ             | 5672          | 5672          |
| RabbitMQ Management  | 15672         | 15672         |
| Auth Service         | 8000          | 8005          |
| Auth DB              | 27017         |               |
| Auth DB Management   | 8002          | 8006          |
| Notification Service | 8000          | 8007          |
