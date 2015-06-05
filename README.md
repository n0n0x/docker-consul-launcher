# [Docker-consul](https://github.com/progrium/docker-consul) launcher with extensive parameter support

## How to run:

The following will output a docker command:

	$ docker run n0n0x/docker-consul-launcher -a 127.0.0.1 -j 192.168.1.11 -e 1
 
You can wrap the command to launch consul in a subshell:

	$ $(docker run n0n0x/docker-consul-launcher -a 127.0.0.1 -j 192.168.1.11 -e 1)


## Help:

	$ docker run n0n0x/docker-consul-launcher -h 
