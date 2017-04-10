# Aplikasi Web "My FluxBB"


## Sekilas Tentang

FluxBB adalah aplikasi forum open source. Bercabang dari Mempawah pada tahun 2008, FluxBB adalah aplikasi forum ringan, cepat, dan mudah digunakan. FluxBB sangat populer, powering forum untuk Arch Linux dan uTorrent 


## Instalasi


#### Software Requirement

	-Install Apache
	-Install MySQL, PHP

#### Server Requirement :

	-Apache 2.2+
	-MySQL Server 4.1+
	-PHP versi 4.4+
	-PostgreSQL 7.0 
	-SQLite 2.
  
#### Cara instalasi

1. Unduh arsip ZIP untuk instalasi 
``$ wget https://fluxbb.org/download/releases/1.5.10/fluxxbb-1.5.10.zip``

2. Unzip arsip yang sudah terunduh
``$ unzip fluxxbb-1.5.10.zip``

3. Pindahkan direktori pagekit ke var/www/html/(direktori sekarang “pagekit”)
``$ sudo mv . . /var/www/html/``

## Konfigurasi (opsional)

Pada konfigurasi hanya dilakukan pemilihan bahasa yang akan digunakan.

## Otomatisasi

(**_tidak ada_**)


## Cara Pemakaian

- Register
	- Fungsi ini digunakan untuk mendaftarkan akun baru agar user dapat memposting atau berkomentar di dalam forum. Menu regist ini terdapat di bar menu di sebelah tombol login
	![](http://i.imgur.com/pxpCa5h.png)
	- Isilah semua field yang ditanyakan
	- Setelah semua terisi, klik tombol sign up. Halaman akan di direct menuju halaman utama. Pemberitahuan bahwa akun berhasil dibuat terdapat di bagian atas page
- Untuk masuk ke dalam akun, klik tombol login yang terdapat di menu bar
	![](http://i.imgur.com/ZMtFXjz.png)
	
- Setelah login, user di direct menuju tampilan utama yaitu index, sebagai berikut
	
## Pembahasan

- Pendapat tentang aplikasi web ini
	- Pros:
		- Situs My FluxBB merupakan sebuah aplikasi berbasis web yang ringan sehingga tidak berat saat me-load halaman, diskusi yang dilakukan pada my FluxBB juga terhindar dari spam, hal ini dikarenakan salah satu peraturan My FluxBB dimana user hanya post selama 30 menit sekali.		
	- Cons:
		- Tidak ada validasi email ketika mengisi form registrasi user
		- Untuk Register, hanya dapat dilakukan 1 jam sekali
		- Post hanya dapat dilakukan 30 menit sekali
		

## Referensi

https://fluxbb.org/docs/v1.4/installing
