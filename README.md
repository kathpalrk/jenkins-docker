#Jenkins configured on Docker Containers
You would need to configure the following things to build up the Jenkins over the Container

# Jenkins would need the JAVA installation on the sever

So, we are using the offical Jenkins repo from docker hub so that JDK can be installed or you can install manually also, if you
are using any Ubuntu, Centos or Rhel infrastructure.

# So Guys you just need to execute the two steps

docker build -t rahulkathpal/jenkins .

# Once its initalized then you would need to run the container

docker run -itd --name Jenkins-Server rahulkathpal/jenkins

That's all 
