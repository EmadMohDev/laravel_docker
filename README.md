# <p align="center">Docker</p>

<p align="center">
    <img src="https://raw.githubusercontent.com/EmadMohDev/laravel_docker/main/imgs/docker.png" alt="Docker" width="300px">


    
</p>


# Description

- this demo help to create laravel app by use docker
- also here we install mysql and phpmyadmin by docker images


to start run this command : 
  
```bash
    docker compose up
```




# Steps that will installed through docker compose file :

<p>1-we will install php8.0.2 and install composer and make expose at port 8000  </p>

<p>2-we will create mysql that will expose on port 33060
and here we create database :  admin  </p>

<p> 3-we will create phpmyadmin that depend on mysql we create on step2  that will expose on port 9090  http://localhost:9090/ and you can login with  :

<b>serve name :  </b>admin_db
<b>userName :  </b>root
<b>password :  </b>root
</p>

<p>
    <img src="https://raw.githubusercontent.com/EmadMohDev/laravel_docker/main/imgs/phpmyadmin.PNG" alt="list posts">
</p>


<p>4-then you will find that laravel app will serve at :  http://localhost:8000/</p>

<p>
    <img src="https://raw.githubusercontent.com/EmadMohDev/laravel_docker/main/imgs/serve.PNG" alt="list posts">
</p>



