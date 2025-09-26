# Tugas-Pertemuan-6
# Tugas Pertemuan 6 — Penerapan JDialog pada GUI Database

Repository ini berisi implementasi GUI (Graphical User Interface) menggunakan Java Swing, khususnya penggunaan **JDialog**, untuk interaksi dengan database (CRUD: Create, Read, Update, Delete).

## 🎯 Tujuan

- Memahami cara menggunakan **JDialog** sebagai dialog modal / non-modal di Java Swing.  
- Menghubungkan GUI dengan database (misalnya MySQL, SQLite, atau lainnya).  
- Menyajikan operasi CRUD melalui form dialog (Tambah, Ubah, Hapus, Lihat Detail).  
- Memberi interaksi yang baik antara jendela utama (main frame) dan dialog (pop-up) sehingga user experience menjadi lebih baik.

## 🧰 Teknologi & Dependensi

- Java (versi minimum: Java 8 atau versi sesuai proyek)
- JDBC driver untuk database yang digunakan (MySQL, SQLite, atau lainnya)
- Swing (GUI built-in Java)
- (Opsional) Library eksternal jika digunakan — misalnya untuk koneksi pooling, validasi, dsb.

## 📌 Fitur Utama

1. **Main Window**  
   Menampilkan daftar data dari tabel dalam database (misalnya data mahasiswa, produk, pelanggan, dsb).  
   Menyediakan tombol: Tambah, Ubah, Hapus, Refresh, dsb.

2. **Dialog Form (berbasis JDialog)**  
   - Untuk **Tambah** data: membuka JDialog berisi form input.  
   - Untuk **Ubah** data: form diisi dengan data yang dipilih, lalu disimpan perubahan.  
   - Untuk **Hapus** data: bisa menampilkan dialog konfirmasi.  
   - Untuk **Detail / View** (jika ada): menampilkan informasi tambahan secara non-editable.

3. **Validasi Input**  
   Validasi sederhana (cek kosong, batas panjang, tipe data) sebelum melakukan operasi ke database.

4. **Koneksi & Handling Database**  
   Kelas koneksi dan utilitas (misalnya `DBHelper`, `ConnectionManager`) untuk membuka / menutup koneksi, eksekusi query, dsb.

## 🚀 Cara Menjalankan

1. Pastikan kamu sudah punya database (misalnya MySQL / SQLite) dan tabel yang sesuai.  
2. Konfigurasikan koneksi database di kode — biasanya di kelas koneksi (URL, username, password).  
3. Jalankan aplikasi dari IDE (misalnya `Main.java` atau kelas utama GUI).  
4. GUI akan terbuka, dan kamu bisa menggunakan tombol-tombol untuk menambah, ubah, hapus data lewat dialog.# PBO6
