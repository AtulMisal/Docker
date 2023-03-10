Docker Overview --
  Docker is a contenerization tool. Containers are nothing but a virtual machines in terms of linux which are used to store some data and carry that to others.
  Docker is an company and their product is docker engine but we call it as docker simply.
  
How docker works --
   In our system we have hardware on this the O.S is installed. On this operating system we will install docker engine which will create containers for us.
   
Why we need docker --

   In organization developer will write the code and it will be tested by tester on server but sometime the code will not work on tester's system coz of some software      unavailability, but using docker this can be removed.
   Before docker we are using hypervisors to create VM's but in this each VM requirs it's own O.S
      Suppose we have a system with 16 GB RAM and 1 TB storage.
      When we install hypervisor on our system's hardware, while creating VM we have to give some RAM and storage for that VM but if that VM is not in working condition 
      then also it will take that storage and to avoid this we use docker.
      
  Docker will create containers which use the OS on the system means it will take that much of space that it requires.
  Then by creating images of that container we will share this to others so that this app can be running fine in other system.
  
  Steps to install docker --
    1. First create one linux server using AWS ec2.  (We will take ubuntu)
    2. Then connect to this server using git bash or putty
    3. Now you are looged as a ec2 user so change it to root by -- sudo -i   (Instead of this you can use sudo in front of all command)
    4. apt update   -- Will update the packages
    5. apt install docker.io    -- Will install docker
    6. docker --version         -- Will show the version of docker engine
    7. service docker status
    8. Now the docker is installed on your system. You can use ready made images from docker hub -- which is a storage of docker images
    9. Basic syntax ---
             docker  _______ ls       -- use image,container,network
  
