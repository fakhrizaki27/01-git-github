# Langkah-langkah Praktik

## 1. Menginstall Git
Untuk menginstal git bisa dilakukan pada [halaman download Git](https://git-scm.com/downloads). Setelah mendowndload dan menginstall git, periksa penginstalan dengan cara menuliskan ``` $ git --version ``` pada git console.

![cek instalasi git](1-gitver.JPG)

Jika muncul versi gitnya, maka penginstalan berhasil.

## 2. Melakukan Konfigurasi Git
Konfigurasi git bertujuan agar git mengetahui siapa yang melalukan commit atau melakukan perubahan pada repo. Konfigurasi git dilakukan dengan cara :
```
$ git config --global user.name "Nama Anda di GitHub"
$ git config --global user.email email@domain.tld
```
contoh :
```
$ git config --global user.name "fakhrizaki27"
$ git config --global user.email fakhrizaki27@gmail.com
```
menuliskan ``` $ git config --list ``` pada console git untuk melihat konfigurasi git.

![konfigurasi git](2-konfig.JPG)

## 3. Mengelola Repo

### 3.1. Membuat Personal Access Token
Untuk membuat personal access token dapat dilakukan dengan mengikuti langkah-langkah pada https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token

### 3.2. Membuat Repository
langkah - langkah :
- Klik tanda '+' dan pilih New Repository
![new repo](3-newrepo.png)

- Isikan nama repo, keterangan bila perlu, kemudian pilih private atau public tersserah. disini saya menambahkan README.md agar repo tidak kosong saat di clone
![nama repo](4-namarepo.png)

- Klik Create Repository
![create repo](5-createrepo.png)

### 3.3. Menduplikat Repo ke Komputer Lokal (CLoning)
Untuk mengclone dapat dilakukan dengan menuliskan perintah seperti berikut :
```
$ git clone https://github.com/fakhrizaki27/coba-coba.git
```
![clone](6-clone.JPG)

Untuk mengetahui file clone disimpan di directory mana bisa dengan cara menuliskan ``` $pwd ```
![clone direct](7-clone.JPG)

### 3.4. Mengubah Isi Repository
