📞 Aplikasi Pengelolaan Kontak
Selamat datang di proyek ini! 🎉 Aplikasi ini dirancang untuk membantu pengguna mengelola kontak mereka secara efisien menggunakan Java. Fitur utama meliputi CRUD (Create, Read, Update, Delete) kontak, pencarian, serta ekspor dan impor data menggunakan format CSV.

👨‍💻 Tentang Saya
Halo! Nama saya [Masukkan Nama Anda] 👋

📚 NPM: [Masukkan NPM Anda]
🎓 Jurusan: [Masukkan Jurusan Anda]
🌟 Saya senang belajar teknologi baru dan mengembangkan solusi praktis untuk kebutuhan sehari-hari.
💬 Jangan ragu untuk menghubungi saya untuk berdiskusi lebih lanjut tentang proyek ini! 🚀

📝 Deskripsi Program
Aplikasi ini memungkinkan pengguna untuk:

Mengelola Kontak:
Menambahkan kontak baru.
Mengedit informasi kontak yang ada.
Menghapus kontak yang tidak diperlukan.
Mencari Kontak:
Pencarian berdasarkan nama atau nomor telepon.
Ekspor dan Impor:
Ekspor data kontak ke file CSV.
Impor data kontak dari file CSV.
Validasi Input:
Memastikan nomor telepon valid dan tidak duplikat.
💻 Komponen GUI
Berikut adalah komponen utama yang digunakan dalam aplikasi ini:

JFrame: Jendela utama aplikasi.
JPanel: Mengatur tata letak komponen GUI.
JLabel: Menampilkan label teks.
JTextField: Untuk memasukkan nama, nomor telepon, atau kata kunci pencarian.
JComboBox: Memilih kategori kontak (Keluarga, Teman, Kantor).
JTable: Menampilkan daftar kontak.
JButton: Untuk melakukan tindakan seperti tambah, edit, hapus, ekspor, impor.
🔍 Logika Program
CRUD Kontak:
Menyimpan data kontak di database SQLite menggunakan JDBC.
Menggunakan pola MVC (Model-View-Controller) untuk pemisahan logika.
Validasi:
Memastikan nomor telepon hanya berisi angka.
Menolak nomor telepon duplikat.
Ekspor/Impor CSV:
Format header CSV: ID, Nama, Nomor Telepon, Kategori.
🎯 Fitur dan Events yang Diimplementasikan
Fitur CRUD
Tambah Kontak:

Memasukkan nama, nomor telepon, dan kategori kontak.
Menyimpan data ke database.
Edit Kontak:

Memilih data dari tabel.
Memperbarui data kontak di database.
Hapus Kontak:

Memilih kontak dari tabel.
Menghapus data dari database.
Tampilkan Data:

Menampilkan daftar kontak dari database ke tabel.
Fitur Pencarian
Mengetikkan kata kunci di JTextField pencarian untuk memfilter daftar kontak.
Fitur Ekspor dan Impor
Ekspor:

Menyimpan data kontak ke file CSV.
Impor:

Membaca data dari file CSV ke tabel kontak dengan validasi.
🔧 Cara Menggunakan Program
Masukkan nama kontak dan nomor telepon.
Pilih kategori kontak menggunakan JComboBox.
Klik tombol:
Tambah: Untuk menyimpan data ke tabel.
Edit: Untuk memperbarui data yang dipilih.
Hapus: Untuk menghapus data yang dipilih.
Export: Untuk menyimpan data ke file CSV.
Import: Untuk mengimpor data dari file CSV.
Gunakan kolom pencarian untuk mencari kontak dengan cepat.
💡 Teknologi yang Digunakan
Bahasa Pemrograman: Java
IDE: NetBeans
Database: SQLite
Library Eksternal: SQLite JDBC
✨ Variasi
Menambahkan kategori kontak tambahan jika diperlukan.
Menampilkan pesan error yang lebih deskriptif.
Mendukung ekspor/impor ke format lain seperti JSON.
🛠️ Cara Setup dan Menjalankan Program
Buat Proyek Baru di NetBeans:

Pilih Java Application.
Tambahkan library SQLite JDBC.
Hubungkan dengan GitHub:

Gunakan GitHub Desktop untuk mengelola repository.
Jalankan Program:

Klik kanan pada PengelolaanKontakFrame > Run File.
Ekspor dan Impor CSV:

Pastikan file CSV memiliki header: ID, Nama, Nomor Telepon, Kategori.
📜 Catatan
Semua data disimpan di database lokal (contacts.db).
Pastikan nomor telepon valid (8-15 digit angka).
