# Zcash-miner

Check out [zcash-miner](https://hub.docker.com/r/amitkumarjaiswal/zcash-miner/) docker image on Docker Hub.

Run Zcash miner on an AWS Docker swarm cluster.

Install the required packages. (important: need `docker >= v1.12`)

`$ brew install docker awscli`
Create a config.conf then run the commands below.

`$ export AWS_ACCESS_KEY_ID=`
`$ export AWS_SECRET_ACCESS_KEY=`

Generate the swarm cluster.

`$ bash generateCluster.sh`
