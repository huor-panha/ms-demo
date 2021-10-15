- Front haproxy
1. # apt update
2. # apt install haproxy
3. Copy haproxy.cfg to /etc/haproxy and modify your backend server
4. # /etc/init.d/haproxy restart

- Swarm manager 
1. apt update & install docker (both nodes)
2. # docker swarm init
3. # cd ms-deployment
4. # ./start.sh

- Docker Node
1. Run join cluster from console output from manager




1. Clone project & build (optional)

2. Deploy to docker
# docker swarm init
# cd ms-deployment
# ./start.sh

3. Stop stack
# ./stop.sh

