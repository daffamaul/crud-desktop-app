# CRUD Mahasiswa Berbasis Desktop
Aplikasi mahasiswa berbasis desktop ini dapat melakukan operasi seperti tambah mahasiswa, ubah mahasiswa berdasarkan NIM (Nomor Induk Mahasiswa), hapus mahasiswa berdasarkan NIM (Nomor Induk Mahasiswa) dan membaca data mahasiswa dari database.

Aplikasi ini berjalan pada mesin Ubuntu 22.04, kemungkinan besar dapat juga berjalan pada mesin lainnya hanya saja dalam sumber kode terdapat konfigurasi-konfigurasi seperti:

- Koneksi database
- Struktur folder

> Penulis menyiapkan [skema tabel SQL](./netbeans_kampus.sql)
## Kebutuhan Aplikasi
> Kebutuhan dibawah dapat disesuaikan dengan masing-masing sistem operasi pada komputer
- [Netbeans Versi 23](https://netbeans.apache.org/front/main/download/)
- [Java JVM versi 17](https://www.oracle.com/java/technologies/javase/jdk17-archive-downloads.html)
- [MySQL Versi Windows](https://dev.mysql.com/downloads/installer/)
- [MySQL Java Connector](https://dev.mysql.com/downloads/connector/j/)
- [Git Bash Versi Windows](https://git-scm.com/downloads/win)

## Cara Menjalankan Aplikasi
- Buka Git Bash atau Terminal pada masing-masing mesin komputer
- Cloning repo pada git bash: ```git clone https://github.com/daffamaul/crud-desktop-app``` 
- Buka NetBeans
- Pilih **Tab File > Open Project... > Tempat folder crud-desktop-app berada**
- Pada NetBeans, pilih **Projects > crud-desktop-app > Source Package > praktikum.enam > CRUDMahasiswa.java**
- Ketika sumber kode java sudah terbuka, tekan **SHIFT + F6**

## Konfigurasi Database
- Pada NetBeans, pilih **Projects > crud-desktop-app > Source Package > praktikum.lima > DBConnection.java**
- Ketika sumber kode java sudah terbuka, ubah ```jdbc:mysql://localhost:3306/<nama_database>```, **username**, **password** 