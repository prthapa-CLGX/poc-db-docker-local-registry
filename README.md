# poc-db-docker-local-registry
POC-Assembly line

Pre-requisites: 
	1) Install docker

	2) Create a docker network bridge:

		docker network create --driver bridge poc-network
        
	3) Start Postgres in docker container

	4) Create docker-registry-volume directory in local-registry

	5) Start local Registry in docker container

