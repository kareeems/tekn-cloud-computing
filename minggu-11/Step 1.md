# Step 1: Containerized Link Extractor Script

``git checkout step1``

``tree``

![](../minggu-11/images/image6.jpg)

``git checkout step1``

![](../minggu-11/images/image7.jpg)

``docker image build -t linkextractor:step1 .``

![](../minggu-11/images/image8.jpg)
![](../minggu-11/images/image9.jpg)

``docker image ls``

![](../minggu-11/images/image10.jpg)

``docker container run -it --rm linkextractor:step1 http://example.com/``

![](../minggu-11/images/image11.jpg)
![](../minggu-11/images/image12.jpg)

