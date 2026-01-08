## Application containers

- Logical app isolation boundary 
- Entire app or sinle app component 


### Microservices

- Specific app functionality
- A large application may be split into microservices to execute specific tasks or code
- These microservices could be run as seperate app containers
- Containers allow for app component decoupling but still allow them to all work together


### Application containers

- Running containers are based on container images 
- Images contain software and settings for running a container
- Containers are runtime instances of images

#### Application container contents

- Scripts
- Binaries
- Container filesystem
- App specific libraries, components
- Runtime environments like Linux, python, web servers
- Config files, software tools etc

#### Application container benefits 

- App portability across container hosts
- Quick app startup time compared to VMs due to the container not running the OS
- Code changes, updated and testing done per container 


### Application Migration using App2Container (A2C)

- This is a command line tool that allows you to migrate Non-containerised applications to containers
- Migrates a Java or .NET app into a container