# Menginstal dan Menyiapkan kubectl

## Menginstal program kubectl menggunakan curl pada Linux 

1. Unduh versi terbarunya dengan perintah:

```
curl -LO https://storage.googleapis.com/kubernetes-release/release/`curl -s https://storage.googleapis.com/kubernetes-release/release/stable.txt`/bin/linux/amd64/kubectl
```

![](/minggu-14/images/image1.jpg)

2. Jadikan program ``kubectl`` dapat dieksekusi.

```
chmod +x ./kubectl
```

3. Pindahkan ke PATH

```
sudo mv ./kubectl /usr/local/bin/kubectl
```

![](/minggu-14/images/image2.jpg)

4. pengecekan versi

```
kubectl version --client
```

![](/minggu-14/images/image3.jpg)

## Menginstal dengan manajer paket (package manager) bawaan

```
sudo apt-get update && sudo apt-get install -y apt-transport-https gnupg2
curl -s https://packages.cloud.google.com/apt/doc/apt-key.gpg | sudo apt-key add -
echo "deb https://apt.kubernetes.io/ kubernetes-xenial main" | sudo tee -a /etc/apt/sources.list.d/kubernetes.list
sudo apt-get update
sudo apt-get install -y kubectl
```

![](/minggu-14/images/image4.jpg)
![](/minggu-14/images/image5.jpg)

## Menginstal dengan manajer paket lain

```
snap install kubectl --classic
```

![](/minggu-14/images/image6.jpg)

```
kubectl version --client
```

![](/minggu-14/images/image7.jpg)


## Mengunduh sebagai bagian dari Google Cloud SDK

1. Instal Google Cloud SDK.

2. Jalankan perintah instalasi ``kubectl``:

```
gcloud components install kubectl
```

3. Pastikan instalasinya sudah berhasil dengan melakukan pengecekan versi:

```
kubectl version --client
```

## Memeriksa konfigurasi kubectl

```
kubectl cluster-info
```

```
The connection to the server <server-name:port> was refused - did you specify the right host or port?
```

```
kubectl cluster-info dump
```
![](/minggu-14/images/image8.jpg)


