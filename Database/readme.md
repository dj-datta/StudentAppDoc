#### Create Docker Image

````
docker build -t mysql .
````

#### Create Container

````
docker run -itd --name mysql-db -p 3306:3306 mysql
````
#### Copy Container IP and add to context.xml file in Backend folder

````
docker inspect <containerID>
````

![Screenshot (695)](https://github.com/user-attachments/assets/45c4610c-06f0-4ed1-9b5c-c7ffe4e9ad11)


**Login to DB Container**
````
docker exec -it dac6  mariadb --user root -p1234
```` 
