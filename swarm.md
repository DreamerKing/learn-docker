docker swarm init
docker swarm join-token manager
docker swarm join --token SWMTKN-1-3rnpb3vpojuxl8o7cbncgdkvpi3e90mxzay0do6xbn3p16hawd-31j3sh4cvm3p30kxly56v3v17 192.168.65.3:2377
docker swarm leave --force