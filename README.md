# DockerMongoDB

#Docker MongoDB scripts

#Docker MongoDB Dokcerfile, configuration, Installation & configuratiton document


#Create MongoDB 3.6.2 image using below command

docker build -t cms/mongodb .


#Create Docker container Mongodb 3.6.2 

docker run --user root --name mongodb -d cms/mongodb



#Run the mongo (MongoDB) using below docker command

docker exec -it mongodb mongo
