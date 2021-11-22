# CONTAINERS

 #  WHAT IS CONTAINER?
 
 Containers are an executable unit of software in which application code is packaged along with its libraries and dependencies, so that it can be run in anywhere.
 
![containers](https://user-images.githubusercontent.com/54776422/142869919-dbf4195d-1a6a-4996-adbf-79e48c9ec69a.png)

# Difference Between Containers and Virtual Machines?

The difference is all about how the application uses underlying hardware like RAM and CPUs efficiently. Containerization reduces waste of underlying hardware because each container only holds the application and related binaries or libraries. Containerization is a lightweight alternative to full machine virtualization that involves encapsulating an application in a container with its own operating environment. By allowing more containers in the environment without the need for more servers, containe]rization increases scalability anywhere from 10 to 100 times that of traditional VM environments.

# After this little understanding of what is Container, Now the AWS Container management service which called Elastic Container Service (ECS) comes in the picture.

Elastic Container Service (ECS) Amazon Elastic Container Service (Amazon ECS) is a highly scalable, high-performance container orchestration service that supports Docker containers and allows you to easily run and scale containerized applications on AWS. You can host your cluster on a serverless infrastructure that is managed by Amazon ECS, by launching your services or tasks using the Fargate launch type. For more control, you can host your tasks on a cluster of Amazon Elastic Compute Cloud (Amazon EC2) instances that you manage by using the EC2 launch type.
