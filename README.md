

# Image:
 docker build -t node-rest-api .
 
# Run: 
docker run -it -p 3080:3070 --name=nodeapi node-rest-api

# Output :
http://localhost:3080/users

# Interact with container :
docker exec -it nodeapi bash
