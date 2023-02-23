# Step 6: Swap Python API Service with Ruby

``git checkout step6``

``tree``

![](../minggu-11/images/image48.jpg)

``cat api/linkextractor.rb``

![](../minggu-11/images/image49.jpg)
![](../minggu-11/images/image50.jpg)

``cat api/Dockerfile``

![](../minggu-11/images/image51.jpg)

``cat docker-compose.yml``

![](../minggu-11/images/image52.jpg)

``docker-compose up -d --build``

![](../minggu-11/images/image53.jpg)
![](../minggu-11/images/image54.jpg)

``curl -i http://localhost:4567/api/http://example.com/``

![](../minggu-11/images/image55.jpg)

``docker-compose down``

![](../minggu-11/images/image56.jpg)

``cat logs/extraction.log``

![](../minggu-11/images/image57.jpg)
