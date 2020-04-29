This server uses tshock and is aimed for terraria 1.3.5.3

Execute container with next command: 

````
docker run -d -p 7777:7777 -v /terraria:/terraria -v /tshock/ServerPlugins:/tshock/ServerPlugins --name terraria -e TERRARIA_WORLD_SIZE=3 -e TERRARIA_WORLD_NAME="myservername" -e TERRARIA_SERVER_PASS="password" waterknight/terraria
````