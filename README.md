Commands with screen shots

docker --version  (To know the version of code)


![Version](https://user-images.githubusercontent.com/93903474/196143868-fd56ae2f-4a47-4130-aed4-b93b8159d3a3.png)


docker build -t welcome-app .


![buiding docker](https://user-images.githubusercontent.com/93903474/196144286-34316b13-cd9c-42bd-a647-463144b98a8b.png)


docker inspect (container number)  (To know complete details of a container)


![complete details of a container](https://user-images.githubusercontent.com/93903474/196144301-a9ec757a-9560-4dad-9a3c-c6f1f568ee55.png)


docker images (To know all images present in docker)


![docker_images](https://user-images.githubusercontent.com/93903474/196144323-7bc92715-9eae-466d-a3f1-4d10ca1404ef.png)

docker ps -a (To know history of images which are present and deleted)


![History of all running or stopped](https://user-images.githubusercontent.com/93903474/196144346-11e66d2e-cd28-4c4c-9f43-9507cf633703.png)


docker pull docker/gettingstarted (To get the image to our local system)


![Pull](https://user-images.githubusercontent.com/93903474/196144498-7516feb3-5a9c-4acc-8302-5da70ddb77d1.png)


docker pull prudhvirajjallipeta/welcome:latest (To pull the images from docker hub to local system)


![pulling images](https://user-images.githubusercontent.com/93903474/196144515-a74166b5-22bf-480e-bd33-cec718c189ea.png)


docker push prudhvirajjallipeta/welcome:latest (To push the images from local system to docker hub)


![pushing_images](https://user-images.githubusercontent.com/93903474/196144528-f927814c-c4f4-42e6-b0b2-9be5d0635687.png)


docker run -d -p 80:50 docker/gettingstarted (To run images by giving host amd port numbers)
![run image](https://user-images.githubusercontent.com/93903474/196144571-050931c1-a950-445e-b451-d70767523b66.png)


docker run -d -p 5000:5000 docker/gettingstarted (To run images by in 5000 host amd port numbers)


![running 5000 port](https://user-images.githubusercontent.com/93903474/196144594-7e85b5ad-ee8f-49d3-a62d-22d31e600639.png)


docker start (container number)   (To start the container after being stopped)


![starting cotainer after stoping](https://user-images.githubusercontent.com/93903474/196144709-534d98e5-919d-49fd-b092-fc3bfdaf9fc5.png)


docker stop (container number)   (To stop the container)


![stop container](https://user-images.githubusercontent.com/93903474/196144726-31bcab5a-444a-45fe-996d-d780b0144847.png)


docker ps (To check imge running or not)


![To check imge running or not](https://user-images.githubusercontent.com/93903474/196144774-a59096a8-2ae3-44db-a67e-d304d6c4fe10.png)


docker rmi -f welcome-app (To untagg the container forcefully)


![untagging docker image](https://user-images.githubusercontent.com/93903474/196144798-ae7b3eb9-7785-4e00-9f0f-62f1bfc25c0f.png)


Hello world running at local port 
![Hello world](https://user-images.githubusercontent.com/93903474/196144824-20ba9013-bd73-41c1-8fb7-9b369c64eba6.png)
