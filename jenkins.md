# jenkins
To start docker jenkins container
```sudo docker run --name jenkins-master -p 8080:8080 -v /home/wangwb/jenkins_home:/var/jenkins_home -it -u root jenkins```
  
  ```jenkins-master``` is the name of container
  
  The first ```8080``` is the port host exposed. The second ```8080``` is port jenkins server is used.
  
  ```/home/wangwb/jenkins_home``` is the directory in the host. 
  
  ```/var/jenkins_home``` is the directory jenkins is using in the container. 
  
  ```root``` is the root user in container which has access to do the job. 
  
```docker exec -it [container id] /bin/bash``` goes into container bash
