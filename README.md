
# <h1> projet-operating-system-Gp-7 

 
<pre>
Muhammad Muhaimin Bin Mazni (leader)  1917953<br>
Muhammad Nasrullah Bin Mat Radzi      2013677 <br>
Aneesa Nadira Binti Aminuddin         2016174<br>
Rabiatul Adawiyah Binti Mohammad Azmi 2013214
</pre>
 
*Lecturer Dr. Rizal Bin Mohd. Nor*
 

## How to Install Dockers
Next, We will download the docker, go to the link below to do:
https://docs.docker.com/desktop/windows/install/ 
 
If you are using Mac you can choose the different version on the left side of the pages.
Give permission to the docker software and wait for the software to automatic install. 
After finishing click close to exit the software installations.<br>

How to start running docker:
Search docker on your desktops and click the docker, 
The docker will ask you to accept the term and you need to accept the term to continue.
1) After you Accepot the term and continue, you will see the interface of docker , then you just follow the tutorial if you are new to this apps,eitherwise you can skip if you already know how use it.
 ![Screenshot (11)](https://user-images.githubusercontent.com/106076684/174476813-ce64af2b-5f59-4f41-b69c-eeddc605b680.png)
 2)CLick start and the clone pages will show up, click next step to proceed to the next pages or second phase.
![Screenshot (12)](https://user-images.githubusercontent.com/106076684/174476928-bbf788de-84db-48a9-b752-4f75f1c003ed.png)
 3)For the 3 phase, you need to give permission to the docker by allowing windows firewall to give full access to the docker and click allow access. then proceed to click next step in the 3 page after you give permission top docker. <br>
 ![Screenshot (13)](https://user-images.githubusercontent.com/106076684/174477183-b78e499c-eb8a-4757-9ae3-85b3196509a4.png)<br>
 4)close the docker and start to use the software.

## How to install WSL2.
1. To download wsl2 you need to go to the link provided :(https://aka.ms/wsl2kernel)
 2. Then you will see the manual installation steps, then read and check the requirement with your laptop either it is compatible or not then proceed to the 4 steps.<br>
![step 2 (2)](https://user-images.githubusercontent.com/106076684/174479734-85a0a413-bacb-470e-9113-0d99da1af36a.jpeg)
 3. Then you will see the picture above, click the blue link and it will auto download wsl2 into your laptop. 
 ![Screenshot (5)](https://user-images.githubusercontent.com/106076684/174479623-86db2722-6277-4d66-8dc5-4678d134f970.png)<br>
 4. click to your wsl2 after you download and it will show the picture above and click finish. 
 <img width="384" alt="4 (2)" src="https://user-images.githubusercontent.com/106076684/174479642-7d0f96f1-94e2-4191-a9cc-429cc273af20.png"><br>
 5. wait until the procees finish and when it doned , Open your docker and you can use your docker.


## Introduction to docker
Docker is a free and open platform for creating, distributing, and executing apps. Docker allows you to decouple your apps from your infrastructure, allowing you to swiftly release software. You can manage your infrastructure the same way you control your applications with Docker. You may drastically minimise the time between writing code and executing it in production by leveraging Docker's approaches for shipping, testing, and deploying code quickly.


## Example command in Docker and run 
 1) We can find out version of Docker we installed on Windows<br>
 ![31](https://github.com/TheAmin102/projet-operating-system-Gp-7/blob/main/file%20image%203/31.png)
 2) Assume you need to download a docker image from dockerhub (docker repository). The following is an example of a MYSQL image being pulled.
 If my Images on MYSQL is alredy download to latest it will show this. 
 ![32](https://github.com/TheAmin102/projet-operating-system-Gp-7/blob/main/file%20image%203/32.png)
 This is the process to pull Images MYSQL.
 ![33](https://github.com/TheAmin102/projet-operating-system-Gp-7/blob/main/file%20image%203/33.png)
 This is the completed process of Downloading the Images. P.S. need fast internet to speed up the progress
 ![34](https://github.com/TheAmin102/projet-operating-system-Gp-7/blob/main/file%20image%203/34.png)
 3) Using this code to list all of the docker images that have been pulled onto the system, along with image metadata like TAG/IMAGE ID/SIZE, and so on.
 ![35](https://github.com/TheAmin102/projet-operating-system-Gp-7/blob/main/file%20image%203/35.png)
 4) Next we execute the docker image that was mentioned in the command. This command will start a docker container that will run MYSQL.
 ![36](https://github.com/TheAmin102/projet-operating-system-Gp-7/blob/main/file%20image%203/36.png)
 5) Using " docker ps " shows all of the docker containers that are currently operating, along with container information.
 ![37](https://github.com/TheAmin102/projet-operating-system-Gp-7/blob/main/file%20image%203/37.png)
 6) Using " docker ps -a " to list all the docker containers that are currently operating, exited, or stopped, along with their details.
 ![38](https://github.com/TheAmin102/projet-operating-system-Gp-7/blob/main/file%20image%203/38.png)
 7) Also we can access the docker container and run commands inside the container. Right now we accessing the MYSQL container in this example.
 ![39](https://github.com/TheAmin102/projet-operating-system-Gp-7/blob/main/file%20image%203/39.png)
 ![40](https://github.com/TheAmin102/projet-operating-system-Gp-7/blob/main/file%20image%203/40.png)
 
 
## How to get Mongo Images install on Docker
 1) Open docker 
 ![24](https://github.com/TheAmin102/projet-operating-system-Gp-7/blob/main/file%20image%202/24.png)<br>
 2) On home page Docker look for Mongo
 ![25](https://github.com/TheAmin102/projet-operating-system-Gp-7/blob/main/file%20image%202/25.jpg)<br>
 3) Click run and make sure Your internet connection is On.<br>
 ![26](https://github.com/TheAmin102/projet-operating-system-Gp-7/blob/main/file%20image%202/26.png)<br>
 4) On imgaes page , We can see the progress bar . Fast internet speed required to speed up the progress
 ![27](https://github.com/TheAmin102/projet-operating-system-Gp-7/blob/main/file%20image%202/27.jpg)<br>
 5) After finish , we can see the mongo image in our Docker
 ![28](https://github.com/TheAmin102/projet-operating-system-Gp-7/blob/main/file%20image%202/28.jpg)<br>
 6) When status " IN USE " is green light mean that our container for Mongo is running.<br>
 ![29](https://github.com/TheAmin102/projet-operating-system-Gp-7/blob/main/file%20image%202/29.png)<br>
 
## Starting Docker Container and Create our MONGODDB Container
1) We can start the MongoDB container in docker by using the command in PowerShell 
 ![23](https://github.com/TheAmin102/projet-operating-system-Gp-7/blob/main/file%20image%202/23.png)
2) In PowerShell, u can type <br>
“ docker run -d -p 82:82 --name group-7-os mongo:latest “<br>
 ![20](https://github.com/TheAmin102/projet-operating-system-Gp-7/blob/main/file%20image%202/20.png)<br>
 3) If show no error meaning that your container is succesfully created<br>
 ![21](https://github.com/TheAmin102/projet-operating-system-Gp-7/blob/main/file%20image%202/21.png)<br>
 4) Check the container in Docker to see the new container has been created
 ![22](https://github.com/TheAmin102/projet-operating-system-Gp-7/blob/main/file%20image%202/22.jpg)

 
## Using Docker to run MONGODB 
example run mongodb on docker.
1) first step is to click run of your group container in docker 
![02](https://github.com/TheAmin102/projet-operating-system-Gp-7/blob/main/file%20image/02.png)

2) click cli to start coding for database
 ![03](https://github.com/TheAmin102/projet-operating-system-Gp-7/blob/main/file%20image/03.png)
 
3) typing mongosh to enter mongodb coding
 ![05](https://github.com/TheAmin102/projet-operating-system-Gp-7/blob/main/file%20image/05.png)

4) first we enter our database hodpital and create out first collection 
 
![06](https://github.com/TheAmin102/projet-operating-system-Gp-7/blob/main/file%20image/06.png)
 
5) using the db.instrumentone.insertMany()
 
![07](https://github.com/TheAmin102/projet-operating-system-Gp-7/blob/main/file%20image/07.png)
 
6) create collection for instrument one
 
![11](https://github.com/TheAmin102/projet-operating-system-Gp-7/blob/main/file%20image/11.png)
 
7) view database on collection one
 
![13](https://github.com/TheAmin102/projet-operating-system-Gp-7/blob/main/file%20image/13.png)

8) create collection for instrument two
 
![08](https://github.com/TheAmin102/projet-operating-system-Gp-7/blob/main/file%20image/08.png)
 
9) insert data for collection instrument two
 
![09](https://github.com/TheAmin102/projet-operating-system-Gp-7/blob/main/file%20image/09.png)
 
10) view collection for instucment two
 
 ![10](https://github.com/TheAmin102/projet-operating-system-Gp-7/blob/main/file%20image/10.png)
 <br>
 

 
 
 
 

 
