-----------DOCKER--------

Build
Get a head start on your coding by leveraging Docker images to efficiently develop your own unique applications on Windows and Mac.  Create your multi-container application using Docker Compose.
Integrate with your favorite tools throughout your development pipeline – Docker works with all development tools you use including VS Code, CircleCI and GitHub.
Package applications as portable container images to run in any environment consistently from on-premises Kubernetes to AWS ECS, Azure ACI, Google GKE and more.

![image](https://github.com/xeroxpro/LinuxDistroInstall/assets/40662677/c28d9906-f871-40ec-8324-295436b04bd1)

Docker, a subset of the Moby project, is a software framework for building, running, and managing containers on servers and the cloud. The term "docker" may refer to either the tools (the commands and a daemon) or to the Dockerfile file format.

It used to be that when you wanted to run a web application, you bought a server, installed Linux, set up a LAMP stack, and ran the app. If your app got popular, you practiced good load balancing by setting up a second server to ensure the application wouldn't crash from too much traffic.

Times have changed, though, and instead of focusing on single servers, the Internet is built upon arrays of inter-dependent and redundant servers in a system commonly called "the cloud". Thanks to innovations like Linux kernel namespaces and cgroups, the concept of a server could be removed from the constraints of hardware and instead became, essentially, a piece of software. These software-based servers are called containers, and they're a hybrid mix of the Linux OS they're running on plus a hyper-localized runtime environment (the contents of the container).

Understanding containers
Container technology can be thought of as three different categories:

Builder: a tool or series of tools used to build a container, such as distrobuilder for LXC, or a Dockerfile for Docker.

Engine: an application used to run a container. For Docker, this refers to the docker command and the dockerd daemon. For others, this can refer to the containerd daemon and relevant commands (such as podman.)

Orchestration: technology used to manage many containers, including Kubernetes and OKD.

Containers often deliver both an application and configuration, meaning that a sysadmin doesn't have to spend as much time getting an application in a container to run compared to when an application is installed from a traditional source. Dockerhub and Quay.io are repositories offering images for use by container engines.

The greatest appeal of containers, though, is their ability to "die" gracefully and respawn when load balancing demands it. Whether a container's demise is caused by a crash or because it's simply no longer needed because server traffic is low, containers are "cheap" to start, and they're designed to seamlessly appear and disappear. Because containers are meant to be ephemeral and to spawn new instances as often as required, it's expected that monitoring and managing them is not done by a human in real time, but is instead automated.

Alternatives to Docker
Linux containers have facilitated a massive shift in high-availability computing. There are many toolsets out there to help you run services, or even your entire operating system, in containers. The Open Container Initiative (OCI) is an industry standards organization that encourages innovation while avoiding the danger of vendor lock-in. Thanks to the OCI, you have a choice when choosing a container toolchain, including Docker, CRI-O, Podman, LXC, and others.

Container utilities
By design, containers can multiply quickly, whether you're running lots of different services or you're running many instances of a few services. Should you decide to run services in containers, you probably need software designed to host and manage those containers. This is broadly known as container orchestration. While Docker and other container engines like Podman and CRI-O are good utilities for container definitions and images, it's their job to create and run containers, not help you organize and manage them. Projects like Kubernetes and OKD provide container orchestration for Docker, Podman, CRI-O, and more.

When running any of these in production, you may want to invest in support through a downstream project like OpenShift (which is based on OKD.)

![image](https://github.com/xeroxpro/LinuxDistroInstall/assets/40662677/96bcb7bf-0ad4-440f-a272-c739a31ac654)

-----INSTALLATIONS STEPS-----------

!!!P.S.:I am gibing the commandliine specs with "sudo" as if you are running without root user in order provide confidence.

1.)Install git For Debian Or Ubuntu Environment:

"sudo apt update"
"sudo apt install git -y"




![image](https://github.com/xeroxpro/LinuxDistroInstall/assets/40662677/cca17cf3-5e32-400d-a6eb-9556e20b7827)


2.)Clone The repository to your machne.

sudo git clone https://github.com/xeroxpro/LinuxDistroInstall 

3.)"cd LinuxDistroInstall" in order to install docker and its original docker.hub7docker.io components


![image](https://github.com/xeroxpro/LinuxDistroInstall/assets/40662677/94c8cf5b-fcc4-4d36-9ded-1c2536066d8c)



4.)"./setup.sh" or "sh setup.sh" (if you dont execute setup.sh.Please type "chmod +x setup.sh" than execute)


![image](https://github.com/xeroxpro/LinuxDistroInstall/assets/40662677/91f00e9f-44bb-45be-acea-0f68b71afeef)


5.)Docker Engine and Application have been installed in your system.In order to check type "sudo docker ps"


![image](https://github.com/xeroxpro/LinuxDistroInstall/assets/40662677/a443e9bc-f7bb-47a2-8485-33540ce8904a)


6.Everything is ready .Now in your favorite browser please type "http://127.0.0.1" or "http://localhost" in regards to navigate to the application.
