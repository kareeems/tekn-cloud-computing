# Step 3: Link Extractor API Service

``git checkout step3``

``tree``

![](../minggu-11/images/image20.jpg)

``cat Dockerfile``

![](../minggu-11/images/image21.jpg)

``cat main.py``

![](../minggu-11/images/image22.jpg)

``docker image build -t linkextractor:step3 .``

![](../minggu-11/images/image23.jpg)
![](../minggu-11/images/image24.jpg)

``docker container run -d -p 5000:5000 --name=linkextractor linkextractor:step3``

![](../minggu-11/images/image25.jpg)

``docker container ls``

![](../minggu-11/images/image26.jpg)

``curl -i http://localhost:5000/api/http://example.com/``

![](../minggu-11/images/image27.jpg)

``docker container logs linkextractor``

![](../minggu-11/images/image28.jpg)

``docker container rm -f linkextractor``

![](../minggu-11/images/image29.jpg)