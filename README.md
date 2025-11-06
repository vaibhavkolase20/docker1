# docker1

# How to install docker in ubuntu oprating system 

      1) apt-get install docker.io -y

# if you are using 1st time docker then you have to give permision to your ubuntu user 
# how can we give permision to our ubuntu user there are one command

      2) sudo usermod -aG docker $USER

# after using this command refresh our ingine using bellow command
      3) newgrp docker

# and try to apply 
      4) docker ps
========================================================================================================================

# How to install docker compose
                  sudo curl -L "https://github.com/docker/compose/releases/download/v2.20.2/docker-compose-$(uname -s)-$(uname -m)" \
                    -o /usr/local/bin/docker-compose

                 
                  sudo chmod +x /usr/local/bin/docker-compose
                  
                 
                  docker-compose --version


# To delate all stop containers
                  docker container prune -f

# To delete all images
                  docker rmi -f $(docker images -q)



                  
