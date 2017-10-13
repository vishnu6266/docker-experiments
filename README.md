

### Docker commands

   //in one of the manager nodes run 
   docker swarm init --force-new-cluster  
  
  //generate token to generate token for manager
  
   
  //remove all unused containers
  docker rm `docker ps --no-trunc -aq`
  
  
  //to recover a docker swarm node
  
  //file system 
  cp -prf /var/lib/docker/swarm /var/lib/docker/swarm.bkp
  cd /var/lib/docker/swarm
  rm -rf *
  
