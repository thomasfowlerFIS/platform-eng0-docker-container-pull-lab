# Lab - Docker `pull`

## **Objectives**

1. Describe what the `docker pull` command does and its relation to
container images.
1. Understand the importance of container registries and how Docker
manages its library of container images.

-------------------------------------------------

### **Requirements**

1. Docker container runtime
1. Docker Hub account

-------------------------------------------------

### **Steps**

1. First, make sure Docker is installed by running:
`$ docker --version`

You should see something similar to the following:

```shell
Docker version 20.10.13, build a224086
```

1. Now create an account on Docker Hub. Visit the following URL and follow
the instructions:
[Docker Hub](https://hub.docker.com/signup)

1. Next, we want to retrieve the container image `hello-world`:

1. Finally, run the `hello-world` container iamge and record the results.

### **Container Images and Registries**

What you just did was "pull" and existing container image from the Docker
Hub container image registry. Docker Hub and other registries like it
allow us to share and leverage existing container images and their
functionality for our own purposes. This greatly reduces the time to
market for developing your own solutions because you are able to leverage
existing solutions of others.

It also enables us to replace or experiment with different container
images for the same purposes or to introduce all new functionality. The
fact container registries are available enables us to deliver solutions
faster and in some cases use functionality we would not otherwise be able
to accomplish due to costs, technical limitations, or lack of capability.

-------------------------------------------------

### **Deliverables**

In order to successfully complete this lab you must:

* Pull down the `hello-world` container image from Docker Hub.
* Run the `hello-world` container image and record the results.

-------------------------------------------------

### **Resources**

* [Manage Images in Docker](https://docs.docker.com/develop/develop-images/image_management/)

-------------------------------------------------
