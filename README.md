# Docker
![image](https://user-images.githubusercontent.com/88156993/135049338-c479364d-10d6-4d84-91f6-a8ccf8757c73.png)
<br>
Docker is a set of platform as a service (PaaS) products that use OS-level virtualization to deliver software in packages called containers. Containers are isolated from one another and bundle their own software, libraries and configuration files; they can communicate with each other through well-defined channels. Because all of the containers share the services of a single operating system kernel, they use fewer resources than virtual machines.
## How to set up Docker (on Windows 10)
1. Visit https://docs.docker.com/desktop/windows/install/
2. Make sure `WSL 2 backend` is selected and download the installer
3. Run the installer and restart PC when prompted to
4. Docker should start on system startup to finalize installation. 
5. When this error shows:
![image](https://user-images.githubusercontent.com/88156993/135050408-6afcb6f2-3303-40d9-95c2-ff898783f939.png)
Click on the link to go to Microsoft Docs page with the latest WSL2 kernel update. Then click on ‘download the latest WSL2 Linux kernel’ link on the page to download ‘wsl_update_x64’ setup file.
6. Run the `wsl_update_x64` file
7. Verify installation by typing `docker version` in a command line.
8. Start docker, go to Settings --> Resources and tick `Enable integration with my default WSL distro`
![image](https://user-images.githubusercontent.com/88156993/135050987-a5bba51c-ead1-4f9a-ac1f-84c2b8fc07f2.png)

## Docker benefits 
1. Introduces the philosophy of Separation of Concerns and ensures Agile Development of software applications in both simple and complex domains
2. The standalone ability or independent nature of microservices open doors for following benefits:
- Reduces complexity by allowing developers to break into small teams, each of which builds/maintains one or more services
- Reduces risk by allowing deployment in chunks rather than rebuilding the whole application for every change
- Easy maintenance by allowing flexibility to incrementally update/upgrade the technology stack for one or more services, rather than the entire application in a single point in time
- In addition to giving you the flexibility to build services in any language, thereby making it language independent, it also allows you to maintain separate data models of each of the given services
3. You can build a fully automated deployment mechanism for ensuring individual service deployments, service management and autoscaling of the application
## Microservices architecture 
![image](https://user-images.githubusercontent.com/88156993/135049227-4af3559f-ca21-46c1-91fb-a18bb17c6e04.png)

## Microservices vs monolith architecture 
<img width="494" alt="monovsmicro" src="https://user-images.githubusercontent.com/88156993/135048402-7c7be67d-8018-4717-a7bd-3da3718a5723.png">
## VM vs Docker
<br>
![image](https://user-images.githubusercontent.com/88156993/135048936-d711e9d9-7bc8-46ad-b582-98c84c3a9e06.png)

