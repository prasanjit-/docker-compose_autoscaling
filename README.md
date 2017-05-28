# docker-compose_autoscaling
A demo on scaling up docker images with docker compose


Architecture: Sets up a cluster with webnodes, redis-backend and haproxy loadbalancer


# Commands-

To check process:
#docker-compose ps 

To start the cluster
#docker-compose up -d

To stop the cluster
#docker-compose down
#docker-compose down --volumes

# Scaling Up/Down:

docker-compose scale web=3   # Sets web node count to 3
docker-compose logs
