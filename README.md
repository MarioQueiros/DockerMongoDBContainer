# DockerMongoDBContainer

A MongoDB docker container
<br />
<br />

#####Command to build the container
`$ sudo docker build --tag marioqueiros/mongodb .`

<br />

#####Basic way
######Usage: sudo docker run --name \<name for container\> -d \<user-name\>/\<repository\>
`$ sudo docker run --name mongo_instance_001 -d marioqueiros/mongodb`
 
<br />
 
#####Dockerized MongoDB, lean and mean!
######Usage: sudo docker run --name \<name for container\> -d \<user-name\>/\<repository\> --noprealloc --smallfiles
`$ sudo docker run --name mongo_instance_001 -d marioqueiros/mongodb --noprealloc --smallfiles`

<br />
 
#####Need to install the MongoDB client for ubuntu
`apt-get install mongodb-clients`
