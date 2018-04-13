Course Code : dockerK8sbuildScale

## Docker and Kubernetes: Building and Scaling a Containerized Application Training Course

###### Requirements
*   Familiarity with the Linux command line
*   A basic understanding of virtualization concepts
*   An understanding of networking concepts
*   An understanding of how web applications work

###### Overview

Docker is an open-source platform for automating the process of building, shipping and running applications inside containers. Kubernetes goes one step further by providing the tools needed to deploy and manage containerized applications at scale in a clustered environment.


In this instructor-led training, participants will learn how to create and manage Docker containers, then deploy a sample application inside a container. Participants will also learn how to automate, scale, and manage their containerized applications within a Kubernetes cluster. Finally, the training goes on to more advanced topics, walking participants through the process of securing, scaling and monitoring a Kubernetes cluster.

By the end of this training, participants will be able to:

*   Set up and run a Docker container
*   Deploy a containerized server and web application
*   Build and manage Docker images
*   Set up a Docker and Kubernetes cluster
*   Use Kubernetes to deploy and manage a clustered web application
*   Secure, scale and monitor a Kubernetes cluster

###### Audience

*   DevOps Engineers
*   Software Developers
*   Architects
*   Deployment engineers

###### Format of the course

Part lecture, part discussion, exercises and heavy hands-on practice

            Note: Apache Tomcat and a Java EE application will be used as our demo servers and applications for containerization. 
                  However, *these are subject to change*. If you would like to see a specific application or related tool or technique
                  covered in this training, please contact us to arrange.



###### Course Outline
##### Segment - 1 

###### Introduction

*   Containers vs virtual machines
*   Speed and performance

###### Overview of Docker architecture

*   Docker and the Linux kernel
*   Docker components (Docker client, Docker daemon, images, registry, containers)

###### Using Docker to run and manage containers

*   Images, containers, volumes, networks
###### Brief overview of container orchestration

*   Installing Docker

*   Pulling an image from the internet

    *   Sample: Apache Tomcat
    *   Running the container

*   Docker registries

    *   Public vs private
*   Creating and managing Dockerfiles

*   Building a Docker image

*   Deploying a web application

       *    Sample application: Java EE application server
*   How Docker containers communicate with each other

*   Configuring volumes and networks in Docker

       *    Linking and state
       

##### Segment - 2

###### Deep dive into container orchestration with Kubernetes

*   Overview of Kubernetes architecture

    *   Pods, labels/selectors, replication controllers, services, API
*   Installing a Kubernetes cluster

*   Creating Kubernetes pods, volumes and deployments

*   Grouping and organizing your cluster

*   Discovering and publishing services

*   Discovering and connecting to containers

*   Deploying a web application

    *   Handling application components
    *   Handling Database connections
*   Kubernetes security

    *   Authentication & authorization
*   Advanced networking

    *   Docker networking vs Kubernetes networking
*   Monitoring Kubernetes

    *   Cluster logging with Elasticsearch and fluentd
    *   Container level monitoring (cAdvisor UI, Influxdb, Prometheus)

##### Segment - 3 

###### Scaling your Kubernetes cluster

*   Infrastructure for Kubernetes

    *   Provisioning, partitioning, networking
*   Building a high-availability cluster
    *   Load balancing and service discovery
*   Deploying a scalable application

    *   Horizontal pod autoscaling
    *   Database clustering in Kubernetes
*   Updating your application

    *   Releases in Kubernetes

###### Troubleshooting

Closing remarks
