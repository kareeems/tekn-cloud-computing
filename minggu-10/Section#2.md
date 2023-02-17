# Section #2 - Bridge Networking

## Step 1: The Basics

``docker network ls``

![image9.jpg](https://github.com/kareeems/tekn-cloud-computing/blob/main/minggu-10/image/image9.jpg)

``apk update``

![image10.jpg](https://github.com/kareeems/tekn-cloud-computing/blob/main/minggu-10/image/image10.jpg)

``apk add bridge``

![image11.jpg](https://github.com/kareeems/tekn-cloud-computing/blob/main/minggu-10/image/image11.jpg)

``brctl show``

![image12.jpg](https://github.com/kareeems/tekn-cloud-computing/blob/main/minggu-10/image/image13.jpg)

``ip a``

![image13.jpg](https://github.com/kareeems/tekn-cloud-computing/blob/main/minggu-10/image/image13.jpg)
![image14.jpg](https://github.com/kareeems/tekn-cloud-computing/blob/main/minggu-10/image/image14.jpg)

## Step 2: Connect a container

``docker run -dt ubuntu sleep infinity``

![image15.jpg](https://github.com/kareeems/tekn-cloud-computing/blob/main/minggu-10/image/image15.jpg)

``docker ps``

![image16.jpg](https://github.com/kareeems/tekn-cloud-computing/blob/main/minggu-10/image/image16.jpg)

``brctl show``

![image17.jpg](https://github.com/kareeems/tekn-cloud-computing/blob/main/minggu-10/image/image17.jpg)

``docker network inspect bridge``

![image18.jpg](https://github.com/kareeems/tekn-cloud-computing/blob/main/minggu-10/image/image18.jpg)
![image19.jpg](https://github.com/kareeems/tekn-cloud-computing/blob/main/minggu-10/image/image19.jpg)
## Step 3: Test network connectivity

``ping -c5 172.17.0.2``

![image20.jpg](https://github.com/kareeems/tekn-cloud-computing/blob/main/minggu-10/image/image20.jpg)

``docker ps``

![image21.jpg](https://github.com/kareeems/tekn-cloud-computing/blob/main/minggu-10/image/image21.jpg)


## Step 4: Configure NAT for external connectivity

``docker run --name web1 -d -p 8080:80 nginx``

![image22.jpg](https://github.com/kareeems/tekn-cloud-computing/blob/main/minggu-10/image/image22.jpg)

``docker ps``

![image23.jpg](https://github.com/kareeems/tekn-cloud-computing/blob/main/minggu-10/image/image23.jpg)

``curl 127.0.0.1:8080``

![image24.jpg](https://github.com/kareeems/tekn-cloud-computing/blob/main/minggu-10/image/image24.jpg)
![image25.jpg](https://github.com/kareeems/tekn-cloud-computing/blob/main/minggu-10/image/image25.jpg)

