# MESOP_App

README 'MESOP WEBSITE'

Created By : Reza Fadilah Rohman (D-IV Broadband Multimedia)

==========================================================================================================================================DEFINISI :

Website Management Employee Stock Option Plan (MESOP) membantu perusahaan dalam melaksanakan dan mengelola program Management Employee Stock Option Plan (MESOP) dengan efisien.

==========================================================================================================================================
CARA PENGOPERASIAN SOURCE CODE :


1. Unduh dan Ekstrak: Unduh file zip source code MESOP. Ekstrak file tersebut ke direktori proyek Anda.

2. Instal XAMPP: Unduh dan instal XAMPP dari situs resmi. Pastikan Anda menjalankan server Apache dan MySQL melalui panel kontrol XAMPP.

4. Import Database: Buka phpMyAdmin melalui XAMPP atau peramban dengan mengakses http://localhost/phpmyadmin. Buat database baru dengan nama yang sesuai (misalnya mesop_db). Impor file SQL yang disertakan dalam folder "software" ke dalam database yang baru dibuat.

5. Buka Visual Studio Code: Buka Visual Studio Code dan pilih menu "File" > "Open Folder". Pilih direktori proyek MESOP yang telah diekstrak.

6. Instal Ekstensi: Jika Anda belum melakukannya, instal ekstensi "PHP Intelephense" untuk dukungan kode PHP dan ekstensi "Laravel Blade Snippets" untuk dukungan template Blade pada Visual Studio Code.

7. Buka Terminal: Buka terminal di dalam Visual Studio Code dengan cara klik menu "View" > "Terminal" atau menggunakan shortcut Ctrl + `.

8. Instal Dependensi: Di terminal, navigasi ke direktori proyek dan jalankan perintah berikut untuk menginstal dependensi menggunakan Composer. 
		
	"composer install"

9. Konfigurasi .env: mengatur koneksi database local dengan membuka file .env untuk mengatur DB_HOST, DB_PORT, DB_DATABASE, DB_USERNAME, dan DB_PASSWORD.

10. Generate Kunci Aplikasi: Generate kunci aplikasi baru dengan perintah berikut.

11. Jalankan Server: Jalankan server pengembangan Laravel

	"php artisan serve"

12. Akses Website: Buka browser dan akses http://localhost:8000 (atau port lain yang ditampilkan oleh perintah sebelumnya).

12. Lakukan login dengan dengan mengisi form login NIK Telkom Group dan Password. 

	Akun Master 
	- NIK TG = admin_1
	- Password = admin_1 
==========================================================================================================================================




