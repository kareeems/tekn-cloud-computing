# Step 2: Link Extractor Module with Full URI and Anchor Text

``git checkout step2``

``tree``

![](../minggu-11/images/image13.jpg)

``cat linkextractor.py``

![](../minggu-11/images/image14.jpg)

``docker image build -t linkextractor:step2 .``

![](../minggu-11/images/image15.jpg)

``docker image ls``

![](../minggu-11/images/image16.jpg)

``docker container run -it --rm linkextractor:step2 https://training.play-with-docker.com/``

![](../minggu-11/images/image17.jpg)
![](../minggu-11/images/image18.jpg)

``docker container run -it --rm linkextractor:step1 https://training.play-with-docker.com/``

![](../minggu-11/images/image19.jpg)