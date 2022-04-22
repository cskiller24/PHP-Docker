# PHP-Docker
Dockerize PHP App using NGINX and PHP-FPM

**How to use**
 1. Clone the repository
 2. Open terminal and change directory to docker `$ cd docker`
 3. Run `$ docker-compose up -d` this will build all the required images
 4. To check if installed successfully run at browser `localhost:8000`
 5. Enjoy! 
 
 You should see in `localhost:8000` like this
 ![image](https://user-images.githubusercontent.com/78188741/164603930-57d00623-de92-4480-80c8-81322f25791a.png)


**Configure the Ports**
 1. Access the file docker/docker-compose.yml file
 2. You will see the port `- 8000:80` change the `8000` part to any ports you want
 3. open terminal and change directory to docker `$ cd docker`
 4. Run `$ docker-compose up -d
 5. To check if installed successfully run at browser `localhost:<port>`
 6. Enjoy!

![image](https://user-images.githubusercontent.com/78188741/164604003-3a8d575e-70da-40ec-ac3d-8c61c8f99ad6.png)
