## Scripts for bootstraping a CoreOS machine into a useful state
- enable the daemon's remote API
- generate a TLS certificate and client/server keys for secure remote communication
- install unit files (e.g., containers that run at startup)
  
### Wishlist
- CLI 
- switch DOCKER_HOST based on a list of DOCKER_HOSTs, like /.ssh/config
- create dockerd host
  - locally (in vm), or remotely (on DO via triton? later aws) 
- rename to tug 
- install TLS cert/keys (not just generation)
- join forces with docker-compose.yml, launch on existing/new hosts in 2 commands 
  - build seed stacks 
    - goal: beefy, performant and ready-for-reddit application clusters (db, static assets, cache, middle layer) that can be cloned and launched in one command 
    - simple web crawling stack
      - finish datahog? !

## Discover docker-machine and despair
