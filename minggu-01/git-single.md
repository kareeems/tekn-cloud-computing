 # Instalasi Git

Git tersedia untuk berbagai sistem operasi. *Precompiled binaries* bisa diperoleh di [halaman dowbload Git](https://git-scm.com/downloads) untuk 3 sistem operasi utama: Linux, Mac OS X, dan Windows. Git bisa menggunakan antarmuka grafis (GUI) maupun CLI (*command line interface*). Pada materi ini, kita akan banyak menggunakan antarmuka CLI melalui shell (Linux / Mac OS X) atau *command prompt* / PowerShell di Windows. Setelah instalasi, periksa keberhasilan instalasi dengan menggunakan:

```
$ git --version

git version 2.19.2
```
Jika muncul versi (tergantung versi yang terinstall), maka kita bisa mulai menggunakan Git.

## Linux
Git untuk Linux biasanya sudah ada pada masing-masing distro dan bisa diinstall dengan *package manager* dari distro yang bersangkutan. Sebagai contoh:

1. OpenSuSE: zypper in git
2. Arch Linux: pacman -S git
3. Debian/Ubuntu: apt-get install git

Silahkan melihat pada manual dari *package manager* di distro yang bersangkutan.
## Mac OS X
Git untuk Mac OS X juga sudah tersedia dan bisa diinstall menggunakan [Homebrew](https://brew.sh/) (package manager di Mac OS X):
```
brew install git
```
## Windows
1. Setelah download Git, double click pada file yang di-download. 
   
   ![gambar-01.JPG]( https://github.com/kareeems/tekn-cloud-computing/blob/main/minggu-01/gambar-01.JPG )

2. Akan dimunculkan lisensi. Klik **Next** untuk lanjut.
   
   ![gambar-02.JPG](https://github.com/kareeems/tekn-cloud-computing/blob/main/minggu-01/gambar-02.JPG)

3. Setelah itu, pilih lokasi instalasi. Secara default akan terisi *C:\Program Files\Git*. Ganti lokasi jika memang anda menginginkan lokasi lain, klik **Next**
   
   ![gambar-03.JPG](https://github.com/kareeems/tekn-cloud-computing/blob/main/minggu-01/gambar-03.JPG)

4. Pilih komponen. Tidak perlu diubah-ubah, sesuai dengan default saja. Klik pada **Next**.
   
   ![gambar-04.JPG](https://github.com/kareeems/tekn-cloud-computing/blob/main/minggu-01/gambar-04.JPG)
   
5. Mengisi shortcut untuk menu Start. Gunakan default (Git), ganti jika ingin mengganti - misalnya Git VCS.
   ![gambar-05.JPG](https://github.com/kareeems/tekn-cloud-computing/blob/main/minggu-01/gambar-05.JPG)

6. Pada saat instalasi, Git menyediakan akses git melalui Bash maupun command prompt. Pilih pilihan kedua supaya bisa menggunakan dari dua antarmuka tersebut. Bash adalah shell di Linux. Dengan menggunakan bash di Windows, pekerjaan di command line Windows bisa dilakukan menggunakan bash - termasuk ekskusi dari Git.
   
   ![gambar-06.JPG](https://github.com/kareeems/tekn-cloud-computing/blob/main/minggu-01/gambar-06.JPG)

7. Pilih pilihan pertama untuk konversi akhir baris (CR-LF).
   
   ![gambar-07.JPG](https://github.com/kareeems/tekn-cloud-computing/blob/main/minggu-01/gambar-07.JPG)

8. Selanjutnya pemilihan emulator terminal. Pilih saja yang bawah, kemudian klik **Next**.
   
   ![gambar-08.JPG](https://github.com/kareeems/tekn-cloud-computing/blob/main/minggu-01/gambar-08.JPG)

9. Untuk opsi ekstra, pilih serta aktifkan 1 dan 2.
    
    ![gambar-09.JPG](https://github.com/kareeems/tekn-cloud-computing/blob/main/minggu-01/gambar-09.JPG)

10. Selanjutnya pemilihan opsi ekspreimental, langsung saja klik Install untuk memaulai instalasi.
    
    ![gambar-10.JPG](https://github.com/kareeems/tekn-cloud-computing/blob/main/minggu-01/gambar-10.JPG)

11. Setelah itu proses instalasi akan dilakukan.
    
    ![gambar-11.JPG](https://github.com/kareeems/tekn-cloud-computing/blob/main/minggu-01/gambar-11.JPG)

12. Jika selesai akan muncul dialog pemberitahuan. Klik pada Finish.
    
    ![gambar-12.JPG](https://github.com/kareeems/tekn-cloud-computing/blob/main/minggu-01/gambar-12.JPG)

13. Untuk menjalankan, dari Start menu, ketikkan "Git", akan muncul beberapa pilihan. Pilih "Git Bash" atau "Git GUI".
    
    ![gambar-13.JPG](https://github.com/kareeems/tekn-cloud-computing/blob/main/minggu-01/gambar-13.jpg)

14. Tampilan jika akan menggunakan "Git Bash"
    
    ![gambar-14.JPG](https://github.com/kareeems/tekn-cloud-computing/blob/main/minggu-01/gambar-14.jpg)

15. Tampilan jika akan menggunakan "Git GUI"
    
    ![gambar-15.JPG](https://github.com/kareeems/tekn-cloud-computing/blob/main/minggu-01/gambar-15.jpg)

16. Untuk mencoba dari command prompt, masuk ke command prompt, setelah itu eksekusi "git --version" untuk melihat apakah sudah terinstall atau belum. Jika sudah terinstall dengan benar, makan akan muncul hasil berikut:
    
    ![gambar-16.JPG](https://github.com/kareeems/tekn-cloud-computing/blob/main/minggu-01/gambar-16.jpg)
    
