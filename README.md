# checkservices-salt-prometheus
checkservices-salt-prometheus is a small script to check services of saltminions, and report the output to prometheus.

### Installation

Pull this script:

```sh
$ git clone https://github.com/sjors101/checkservices-salt-prometheus.git
```

Install Python modules with PIP:
```sh
$ pip install prometheus_client
$ pip install subprocess
```

### Running as daemon

```sh
$ cd /opt/checkservices-salt-prometheus
$ python checkservices-salt-prometheus &
```
