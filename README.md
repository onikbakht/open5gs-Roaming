containers specification edited according to the Roaming architecture, docker compose edited also to get all needed containers run
----------------------------------------------------------------
***useful commands:
*command for docker compose file to get all needed containers to run :
- docker-compose --env-file C:\Users\omiid\docker-open5gs\.env up -d
(edit the path accoding to your own pc directories ofcource !)
(-d switsch lets the containers to run in background so that you can still use your command line)
*command to see the running containers:
- docker-compose ps
*command ti bring down the containers which ran up with docker compose:
- docker-compose down
*command to read some general logs : 
- docker-compose logs
  
