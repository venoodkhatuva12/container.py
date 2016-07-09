# container.py
To monitor docker containers memory, cpu, network and status

pre-requisite...

dnspython3>=1.12.0
docker-py>=1.0.0

How to use it...

container.py [-h] container {cpu,ip,memory,network,status} ...

positional arguments:
  container             Container name

optional arguments:
  -h, --help            show this help message and exit

Counters:
  Available counters

  {cpu,ip,memory,network,status}
  cpu                 Display CPU usage
  ip                  Display IP Address
  memory              Display memory usage
  network             Display network usage
  status              Display the container status


