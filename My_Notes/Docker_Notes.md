# Docker Notes

- Why use Docker?
- &nbsp;&nbsp;&nbsp;Docker wants to make it easy to install and software on any computer or web server or any cloud-based computing platform
- &nbsp;&nbsp;&nbsp;Save time troubleshooting and solving errors
- What is Docker?
- &nbsp;&nbsp;&nbsp;Docker Ecosystem
- &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Docker Client
- &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Docker Server
- &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Docker Machine
- &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Docker Images
- &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Docker Hub
- &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Docker Compose
- &nbsp;&nbsp;&nbsp;Docker is a platform or ecosystem around creating and running containers
- What is Docker Image and Container?
- &nbsp;&nbsp;&nbsp;Docker Image – single file with all the dependencies and configurations required to run a program
- &nbsp;&nbsp;&nbsp;Docker Container – Instance of an Image. Runs a program
- Running a command
- &nbsp;&nbsp;&nbsp;Triggers the Docker CLI to reach out to the Docker Hub to download an Image with all the configurations required to download a program.
- &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;This image is a single file installed onto your computer
- Docker Client (CLI) – Tool we use to issue commands to
- Docker Server (Daemon) – Tool responsible for creating images, running containers, etc
- &nbsp;&nbsp;&nbsp;We never really reach out to the docker server, it runs behind the scenes

## Commands

### Docker run hello-world

- Starts up the docker client (CLI)
- &nbsp;&nbsp;&nbsp;Starts up the Docker Client (CLI)
- &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The CLI is in charge of taking commands and communicating them to the docker server which deos the heavy lifting
-   The CLI is in charge of taking commands and communicating them to the docker server which deos the heavy lifting
-	Server checks to see if there is a local copy of the “hello-world” file
-   Since the image cache was empty, docker reaches out to Docker Hub 
-   Docker Hub has free public images that u can download and run on your computer
-   Docker Server downloaded the hello-world image/file from Docker Hub and stored it in the image cache locally
