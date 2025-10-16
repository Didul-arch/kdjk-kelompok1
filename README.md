# Aplikasi Baserow

<h1 align="center"><img src="https://avatars.githubusercontent.com/u/1261496?v=4"></h1>

# Sekilas Tentang

Baserow adalah platform open source no-code database yang memungkinkan pengguna membuat, mengelola, dan berbagi data layaknya Airtable. Ia bisa di-self-hosted, berbasis PostgreSQL, serta menyediakan API untuk integrasi dengan aplikasi lain.

# Instalasi

### Kebutuhan Sistem :
- Unix/Linux, macOS, atau Windows.
- Docker & Docker Compose: Versi terbaru.
- RAM: Minimal 2 GB.
- Penyimpanan: Tergantung jumlah data, disarankan minimal 10 GB kosong.

### Proses Instalasi


# Konfigurasi (opsional)

Setting server tambahan yang diperlukan untuk meningkatkan fungsi dan kinerja aplikasi, misalnya:

- batas upload file
- batas memori
- dll

Plugin untuk fungsi tambahan

- login dengan Google/Facebook
- editor Markdown
- dll

# Maintenance (opsional)

Setting tambahan untuk maintenance secara periodik, misalnya:

- buat backup database tiap pekan
- hapus direktori sampah tiap hari
- dll

# Otomatisasi (opsional)

Skrip shell untuk otomatisasi instalasi, konfigurasi, dan maintenance.

# Cara Pemakaian

- Tampilan aplikasi web
- Fungsi-fungsi utama
- Isi dengan data real/dummy (jangan kosongan) dan sertakan beberapa screenshot

1. Sebelum menggunakan applikasi, kita perlu melakukan login terlebih dahulu.
![Login](cara_pakai/login.png)

2. Setelah login berhasil, akan masuk ke halaman home Baserow. Pada menu sidebar terdapat beberapa pilihan yang dapat dilakukan.
![Home](cara_pakai/homepage.png)

3. Fungsi utama pada aplikasi ini adalah mengolah database. Klik add new pada sidebar dan pilih database. 
![Database](cara_pakai/addDatabase.png)

4. Pilih untuk membuat database baru atau bisa import database. 
![Add Database](cara_pakai/nameDatabase.png)

5. Setelah itu akan masuk ke halaman dashboard database. Kita bisa menambah tabel pada database, dan bisa mengatur isi dari tabel tersebut. 
![Name Database](cara_pakai/database.png)
![Edit Database](cara_pakai/addColloumn.png)
![Add Colloumn](cara_pakai/add.png)

6. Tampilan lengkap tabel mahasiswa berisi NIM sebagai primary key, Nama, Email, dan Phone number
![Tabel mahasiswa](cara_pakai/database_Mahasiswa.png)

# Pembahasan

- Pendapat anda tentang aplikasi web ini
  - kelebihan
  - kekurangan
- Bandingkan dengan aplikasi web lain yang sejenis

Baserow adalah platform database no-code sumber terbuka (open-source) yang memungkinkan pengguna untuk membuat dan mengelola database tanpa perlu menulis satu baris kode pun. Sebagai salah-satu platform no-code yang sedang naik daun, aplikasi ini menawarkan berbagai kelebihan, diantaranya:

- Antarmuka yang Intuitif: Tampilannya mirip seperti spreadsheet (misalnya Excel atau Google Sheets), sehingga sangat mudah dipelajari dan digunakan bahkan oleh pengguna non-teknis sekalipun.

- Fleksibilitas Tinggi: Pengguna dapat membuat berbagai jenis kolom data, menghubungkan tabel, dan membangun aplikasi sederhana langsung di atas database yang dibuat.

- Kolaborasi Real-time: Memungkinkan beberapa pengguna untuk bekerja pada database yang sama secara bersamaan, sangat ideal untuk kerja tim.

- Open-Source: Kode sumbernya tersedia secara bebas. Ini memberikan kebebasan untuk melakukan self-hosting (instalasi di server sendiri) yang memberikan kontrol penuh atas data dan privasi.

- Integrasi dan API: Menyediakan API (Application Programming Interface) yang kuat, sehingga mudah dihubungkan dengan aplikasi atau layanan lain untuk otomatisasi alur kerja.

- Skalabilitas: Mampu menangani database dengan jumlah baris yang sangat besar tanpa mengalami penurunan performa yang signifikan.

Tentu saja, sebuah aplikasi pasti memiliki kekurangan. Kekurangan yang dimiliki Baserow antara lain:

- Fitur Lanjutan yang Terbatas: Meskipun kuat untuk manajemen data dasar hingga menengah, beberapa fitur database relasional yang sangat kompleks mungkin belum tersedia selengkapnya.

- Komunitas yang Masih Berkembang: Dibandingkan dengan kompetitor yang lebih lama, komunitas penggunanya belum sebesar alternatif lain, sehingga sumber daya belajar atau solusi dari komunitas mungkin lebih terbatas.

- Memerlukan Pengetahuan Teknis untuk Self-Hosting: Meskipun opsi self-hosting adalah kelebihan, proses instalasi dan pemeliharaannya memerlukan pemahaman teknis tentang server dan database.

- Kurva Belajar untuk Fitur Otomatisasi: Walaupun antarmukanya mudah, untuk memanfaatkan fitur API dan otomatisasi secara maksimal, pengguna tetap memerlukan sedikit pemahaman konsep teknis.

Jika dibandingkan dengan aplikasi sejenisnya seperti Limbas, Baserow memiliki beberapa keunggulan dan kelemahan. Berikut adalah beberapa perbandingan antara kedua aplikasi ini:

- Target Pengguna: Baserow lebih ditujukan untuk pengguna bisnis dan individu yang memerlukan database online yang fleksibel dan mudah digunakan, mirip seperti Airtable. Sedangkan Limbas lebih berfokus pada solusi enterprise untuk manajemen proses bisnis (Business Process Management), manajemen dokumen, dan pengembangan aplikasi low-code yang lebih terstruktur dan kompleks.

- Antarmuka dan Kemudahan Penggunaan: Baserow unggul dalam kemudahan penggunaan dengan antarmuka spreadsheet-nya yang familier. Limbas, dengan fokus pada proses bisnis, memiliki antarmuka yang lebih kompleks dan memerlukan waktu belajar yang lebih lama.

- Fleksibilitas vs. Struktur: Baserow menawarkan kebebasan dan fleksibilitas dalam menstrukturkan data sesuai keinginan pengguna. Sebaliknya, Limbas menyediakan kerangka kerja dan modul yang lebih terstruktur untuk membangun solusi bisnis yang spesifik, seperti sistem CRM atau manajemen proyek.

- Instalasi dan Teknologi: Keduanya merupakan open-source dan berbasis PHP. Namun, fokus Baserow pada pengalaman pengguna membuatnya terasa lebih modern dan ringan untuk tugas manajemen data. Limbas dirancang untuk alur kerja perusahaan yang lebih rumit dan terintegrasi.

- Komunitas dan Ekosistem: Sebagai solusi enterprise, dukungan untuk Limbas mungkin lebih terfokus pada layanan komersial dan dokumentasi resmi. Baserow, dengan sifatnya yang lebih umum, memiliki potensi untuk membangun komunitas pengguna yang lebih luas dan beragam di masa depan.

# Referensi

1. [Baserow](https://baserow.io/)
2. [Github Baserow](https://github.com/bram2w/baserow)
