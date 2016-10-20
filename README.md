# Elicopter [![Slack Status](https://elicopter-slackin.herokuapp.com/badge.svg)](https://elicopter-slackin.herokuapp.com/)

Glue between all Elicopter components.

## Getting Started

### Clone Repositories

Clone `core` repository:
```
git clone https://github.com/elicopter/core.git
```

Clone `ground_station` repository:
```
git clone https://github.com/elicopter/ground_station.git
```

Clone `parts` repository (coming soon):
```
git clone https://github.com/elicopter/parts.git
```

### Run RabbitMQ

RabbitMQ handles communication between `core` and `ground_station`.

Run with Docker:
```
docker run --name elicopter-rabbitmq -d -p 15672:15672 -p 5672:5672 rabbitmq:3-management
```

### Configure RabbitMQ

Add `core` user:
```
docker exec -ti elicopter-rabbitmq rabbitmqctl add_user core core
docker exec -ti elicopter-rabbitmq rabbitmqctl set_permissions -p / core ".*" ".*" ".*"
```

Add `ground_station` user:
```
docker exec -ti elicopter-rabbitmq rabbitmqctl add_user ground_station ground_station
docker exec -ti elicopter-rabbitmq rabbitmqctl set_permissions -p / ground_station ".*" ".*" ".*"
```

### Run

* To run `core`, check the project documentation [here](https://github.com/elicopter/core).
* To run `ground_station`, check the project documentation [here](https://github.com/elicopter/ground_station).

## Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.

## Authors

* **Loic Vigneron** - [Spin42](https://github.com/spin42)
* **Marc Lainez** - [Spin42](https://github.com/spin42)
* **Thibault Poncelet** - [Spin42](https://github.com/spin42)
* **Who's next? :)**

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

