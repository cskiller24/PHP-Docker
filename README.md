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
 4. Run `$ docker-compose up -d`
 5. To check if installed successfully run at browser `localhost:<port>`
 6. Enjoy!

![image](https://user-images.githubusercontent.com/78188741/164604003-3a8d575e-70da-40ec-ac3d-8c61c8f99ad6.png)

**Run commands in Docker Container**
 1. Open terminal and run `$ docker ps`
 2. You will see all the running docker container, find the name where the php runs _Usually at port 9000/tcp_ (Highlighted part)
 ![image](https://user-images.githubusercontent.com/78188741/164604766-6fe8997d-2b06-4d7c-9329-8bfc92e5afeb.png)
 4. Run `$ docker exec -it <name> bash`
 5. To check if success run `$ php -v`
 6. Enjoy
 
 ![image](https://user-images.githubusercontent.com/78188741/164605070-9654db41-bb36-42a6-ac6d-7fd7fe0b302f.png)
