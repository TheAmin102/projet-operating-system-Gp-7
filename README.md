
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
![Screenshot (4)](https://user-images.githubusercontent.com/106076684/174470293-33ad2428-8055-407e-8179-3cc25f8d01a0.png)
![Screenshot (8)](https://user-images.githubusercontent.com/106076684/174470295-98a96091-0077-429f-8f3f-0ffdd932487f.png)
![Screenshot (9)](https://user-images.githubusercontent.com/106076684/174470296-310bf927-9886-41ce-b5cd-56c3ff9296df.png)
![Screenshot (10)](https://user-images.githubusercontent.com/106076684/174470299-9d4422b5-6e0a-410c-9eda-3cfe6a11a841.png)

If you are using Mac you can choose the different version on the left side of the pages.
Give permission to the docker software and wait for the software to automatic install. 
After finishing click close to exit the software installations.<br>

How to start running docker:
Search docker on your desktops and click the docker, 
The docker will ask you to accept the term and you need to accept the term to continue.
## How to install WSL2.
 1)The first step, After downloading the Wsl2<br>
 2)Right-click on the Installer and give the administrator admission to install the program to the apps. 
 3)Wait for the apps to install and pop up we click the “Next” button.<br>
 ![01](https://github.com/TheAmin102/projet-operating-system-Gp-7/blob/main/file%20image/01.PNG)<br>
 4)Then, the installing windows Subsytem for Linux update for windows will start and wait until installer to be doned.
 5)Click Finish when the installer is done and click finish when it is done.


## Introduction to docker
 Examples of code and commands

3) The “ -d “ (detach) flag means that the docker will run in the background 
The container port “82 “  the MongoDB default is bound back to port 82 on your host. <br>
4) You will connect to your MongoDB instance on “ localhost:82 “
  The port number can be changed by modifying the -p flag, let said we want localhost to 44334 we just need to rewrite the command line to 
“ docker run -d -p 44334:44334 --name group-7-os mongo:latest “
5) “ name group-7-os mongo: latest “
group-7-os will be the name of our container in Docker
mongo: latest will be the version of MongoDB we will use 
6) docker exec -it group-7-os mongo 
By using the command “ exec- it “ it will launch an interactive Mongo shell session in the terminal. It will allow faster interaction with your database without external dependencies.
7) docker logs group-7-os --follow
In this command we use the  –follow flag will make your log continually streamed on your terminal 

8)If you want to host a real database in your Mongo container you must be using Docker Volumes..The data will not be lost when you stop the container or restart the Docker daemon, if you are using  Volume persist.<br>
9)The MongoDB image is configured to store all its data in the /data /db directory in the container filesystem. Mounting a volume to this location will ensure data is persisted outside the container.<br>
 
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
 

 
 
 
 

 
