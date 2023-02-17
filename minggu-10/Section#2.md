# Section #2 - Bridge Networking

## Step 1: The Basics

``docker network ls``

![image1.jpg]

``apk update``

![image2.jpg]

``apk add bridge``

![image]

``brctl show``

``ip a``

## Step 2: Connect a container

``docker run -dt ubuntu sleep infinity``

``docker ps``

``brctl show``

``docker network inspect bridge``

## Step 3: Test network connectivity

``docker network inspect``



## Step 4: Configure NAT for external connectivity

## 