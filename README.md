# 📞 Aplikasi Pengelolaan Kontak

Selamat datang di proyek ini! 🎉 Aplikasi ini dirancang untuk membantu pengguna mengelola kontak mereka secara efisien menggunakan Java. Fitur utama meliputi CRUD (Create, Read, Update, Delete) kontak, pencarian, serta ekspor dan impor data menggunakan format CSV.

---

## 👨‍💻 Tentang Saya

Halo! Nama saya **[Masukkan Nama Anda]** 👋  
- 📚 **NPM:** [Masukkan NPM Anda]  
- 🎓 **Jurusan:** [Masukkan Jurusan Anda]  
- 🌟 Saya senang belajar teknologi baru dan mengembangkan solusi praktis untuk kebutuhan sehari-hari.  

💬 Jangan ragu untuk menghubungi saya untuk berdiskusi lebih lanjut tentang proyek ini! 🚀  

---

## 📝 Deskripsi Program

Aplikasi ini memungkinkan pengguna untuk:
1. **Mengelola Kontak:**
   - Menambahkan kontak baru.
   - Mengedit informasi kontak yang ada.
   - Menghapus kontak yang tidak diperlukan.
2. **Mencari Kontak:**
   - Pencarian berdasarkan nama atau nomor telepon.
3. **Ekspor dan Impor:**
   - Ekspor data kontak ke file CSV.
   - Impor data kontak dari file CSV.
4. **Validasi Input:**
   - Memastikan nomor telepon valid dan tidak duplikat.

---

## 💻 Komponen GUI

Berikut adalah komponen utama yang digunakan dalam aplikasi ini:
- **JFrame:** Jendela utama aplikasi.
- **JPanel:** Mengatur tata letak komponen GUI.
- **JLabel:** Menampilkan label teks.
- **JTextField:** Untuk memasukkan nama, nomor telepon, atau kata kunci pencarian.
- **JComboBox:** Memilih kategori kontak (Keluarga, Teman, Kantor).
- **JTable:** Menampilkan daftar kontak.
- **JButton:** Untuk melakukan tindakan seperti tambah, edit, hapus, ekspor, impor.

---

## 🔍 Logika Program

1. **CRUD Kontak:**
   - Menyimpan data kontak di database SQLite menggunakan JDBC.
   - Menggunakan pola MVC (Model-View-Controller) untuk pemisahan logika.
2. **Validasi:**
   - Memastikan nomor telepon hanya berisi angka.
   - Menolak nomor telepon duplikat.
3. **Ekspor/Impor CSV:**
   - Format header CSV: `ID, Nama, Nomor Telepon, Kategori`.

---

## 🎯 Fitur dan Events yang Diimplementasikan

### **Fitur CRUD**
1. **Tambah Kontak:**  
   - Memasukkan nama, nomor telepon, dan kategori kontak.
   - Menyimpan data ke database.

2. **Edit Kontak:**  
   - Memilih data dari tabel.
   - Memperbarui data kontak di database.

3. **Hapus Kontak:**  
   - Memilih kontak dari tabel.
   - Menghapus data dari database.

4. **Tampilkan Data:**  
   - Menampilkan daftar kontak dari database ke tabel.

---

### **Fitur Pencarian**
- Mengetikkan kata kunci di `JTextField` pencarian untuk memfilter daftar kontak.

---

### **Fitur Ekspor dan Impor**
1. **Ekspor:**  
   - Menyimpan data kontak ke file CSV.

2. **Impor:**  
   - Membaca data dari file CSV ke tabel kontak dengan validasi.

---

## 🔧 Cara Menggunakan Program

1. Masukkan **nama kontak** dan **nomor telepon**.
2. Pilih kategori kontak menggunakan `JComboBox`.
3. Klik tombol:
   - **Tambah:** Untuk menyimpan data ke tabel.
   - **Edit:** Untuk memperbarui data yang dipilih.
   - **Hapus:** Untuk menghapus data yang dipilih.
   - **Export:** Untuk menyimpan data ke file CSV.
   - **Import:** Untuk mengimpor data dari file CSV.
4. Gunakan kolom pencarian untuk mencari kontak dengan cepat.

---

## 💡 Teknologi yang Digunakan

- **Bahasa Pemrograman:** Java
- **IDE:** NetBeans
- **Database:** SQLite
- **Library Eksternal:** SQLite JDBC

---

## ✨ Variasi

1. Menambahkan kategori kontak tambahan jika diperlukan.
2. Menampilkan pesan error yang lebih deskriptif.
3. Mendukung ekspor/impor ke format lain seperti JSON.

---

## 🛠️ Cara Setup dan Menjalankan Program

1. **Buat Proyek Baru di NetBeans:**
   - Pilih **Java Application**.
   - Tambahkan library SQLite JDBC.

2. **Hubungkan dengan GitHub:**
   - Gunakan GitHub Desktop untuk mengelola repository.

3. **Jalankan Program:**
   - Klik kanan pada `PengelolaanKontakFrame` > `Run File`.

4. **Ekspor dan Impor CSV:**
   - Pastikan file CSV memiliki header: `ID, Nama, Nomor Telepon, Kategori`.

---

## 📜 Catatan

- Semua data disimpan di database lokal (`contacts.db`).
- Pastikan nomor telepon valid (8-15 digit angka).

---

Selamat mencoba aplikasi ini! Jika ada pertanyaan atau masukan, silakan hubungi saya. 😊
