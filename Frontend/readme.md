#### Edit index.html file and add backend URL 

#### Create Docker Image
````
docker build -t apache .
````

#### Create Docker COntainer
````
docker run -itd --name apache-fe -p 80:80 apache
````
#### Go to browser add public ip of instance you will see following UI

![Screenshot (694)](https://github.com/user-attachments/assets/6b4ab6d2-d923-41b6-aca1-dbb77552fea4)


#### Click on ***Enter to Student Application*** it will redirect you to backend page
 
![Screenshot (696)](https://github.com/user-attachments/assets/ece35e24-6c39-42d9-bb8f-eade963757ae)


#### Student Data is saved into Database
![Screenshot (697)](https://github.com/user-attachments/assets/2910cfd9-37ce-4ee3-9ebf-596aab1cf198)



