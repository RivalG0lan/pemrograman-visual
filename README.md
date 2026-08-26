# Pemrograman Visual

[![Mata Kuliah](https://img.shields.io/badge/Mata%20Kuliah-Pemrograman%20Visual-blue)](.)
[![Program Studi](https://img.shields.io/badge/Prodi-D3%20Teknik%20Informatika-informational)](.)
[![Universitas](https://img.shields.io/badge/Universitas-USU-orange)](.)
[![Tahun Ajaran](https://img.shields.io/badge/Tahun%20Ajaran-2024-lightgrey)](.)

Repository ini berisi catatan dan progres belajar **Pemrograman Visual** pada mata kuliah D3 Teknik Informatika, Universitas Sumatera Utara (USU), tahun ajaran 2026.

---

## Daftar Isi

- [Pertemuan 1 - Pengenalan Visual Programming](#pertemuan-1---pengenalan-visual-programming)
  - [Apa itu Visual Programming?](#apa-itu-visual-programming)
  - [Karakteristik Visual Programming](#karakteristik-visual-programming)
  - [Tujuan dan Manfaat](#tujuan-dan-manfaat)
  - [Keterbatasan Visual Programming](#keterbatasan-visual-programming)
  - [Platform yang Umum Digunakan](#platform-yang-umum-digunakan)
  - [Software yang Digunakan dalam Praktikum](#software-yang-digunakan-dalam-praktikum)
  - [Cara Pemasangan / Instalasi](#cara-pemasangan--instalasi)
- [Pertemuan 2 - Komponen Visual](#pertemuan-2---komponen-visual)
  - [Konsep Dasar Komponen](#konsep-dasar-komponen)
  - [Properti Penting Form dan Komponen](#properti-penting-form-dan-komponen)
  - [Event](#event)
  - [Cara Memulai Project Visual Programming](#cara-memulai-project-visual-programming)
  - [Penggunaan Komponen Dasar](#penggunaan-komponen-dasar)
  - [Syntax yang Dipelajari](#syntax-yang-dipelajari)

---

## Pertemuan 1 - Pengenalan Visual Programming

### Apa itu Visual Programming?

Visual Programming adalah pendekatan pemrograman yang dilakukan melalui interaksi objek visual, sehingga pengguna tidak perlu memahami syntax atau kode terlebih dahulu.

### Karakteristik Visual Programming

1. Logika program direpresentasikan melalui blok, diagram, atau elemen grafis yang saling terhubung membentuk alur program.
2. Komponen program maupun antarmuka disusun dengan metode drag-and-drop.
3. Perubahan pada rancangan atau struktur program dapat langsung diamati, sehingga proses evaluasi dan pengembangan menjadi lebih mudah.

### Tujuan dan Manfaat

- Mempermudah pemahaman konsep dasar pemrograman
- Menyajikan alur program secara visual dan terstruktur
- Mempersiapkan pengguna sebelum mempelajari sintaks kode
- Meminimalisir kesalahan dalam penulisan kode

### Keterbatasan Visual Programming

- Fleksibilitas terbatas
- Kurang efisien untuk proyek berskala besar
- Ketergantungan pada platform tertentu

### Platform yang Umum Digunakan

| Platform | Keterangan |
|---|---|
| Scratch | Berbasis blok, cocok untuk pemula |
| MIT App Inventor | Untuk membangun aplikasi mobile Android |
| Visual Basic | Berbasis IDE Microsoft |
| Java FX | Framework Java untuk GUI |

### Software yang Digunakan dalam Praktikum

Praktikum ini menggunakan **Visual Basic**, bahasa pemrograman dari Microsoft yang menyediakan Integrated Development Environment (IDE) untuk membangun aplikasi dengan pendekatan visual.

### Cara Pemasangan / Instalasi

1. Unduh Visual Studio langsung dari situs resmi [visualstudio.microsoft.com](https://visualstudio.microsoft.com/), lalu pilih **"Get Free Download"**.
2. Pilih **Visual Studio Community** beserta tahun rilisnya. Untuk kompatibilitas, disarankan memilih versi **2022**, atau versi terbaru sesuai tahun saat ini.
3. Klik **Modify** dan unduh workload yang diperlukan, yaitu **.NET Desktop Development**, dengan mencentang opsinya.
4. Centang komponen instalasi tambahan yang dibutuhkan pada menu **"Installation Details"**. Disarankan berkonsultasi dengan AI mengenai komponen apa saja yang diperlukan untuk praktikum Vispro dengan Visual Basic.
5. Setelah semua komponen dipilih, klik **Modify**, lalu berikan izin (allow) kepada Visual Studio Installer agar proses instalasi dapat dimulai.
6. Tunggu hingga muncul tulisan **"All installations are up to date"**.

---

## Pertemuan 2 - Komponen Visual

### Konsep Dasar Komponen

| Komponen | Penjelasan |
|---|---|
| **Control** | Elemen UI untuk membangun aplikasi di Visual Studio. Control membuat user dapat berinteraksi dengan aplikasi melalui berbagai jenis input dan output. |
| **Form** | Jendela atau wadah utama (canvas) tempat meletakkan komponen visual aplikasi Visual Basic. Form menjadi area kerja pengguna untuk berinteraksi, tempat menempatkan objek seperti tombol, label, textbox, dan kontrol lainnya. |
| **Command Button** | Tombol perintah untuk menjalankan aksi tertentu saat diklik oleh user, misalnya tombol OK, Cancel, Exit, atau Apply. |
| **Label** | Menampilkan teks statis sebagai keterangan atau informasi pada form. Label biasanya menjelaskan isi dari input atau komponen lain. |
| **Textbox** | Menerima atau mengambil input dari user berupa karakter huruf maupun angka. |

### Properti Penting Form dan Komponen

| Properti | Fungsi |
|---|---|
| Name | Identitas unik komponen di kode program untuk pemanggilan |
| Text | Teks yang terlihat oleh user pada komponen |
| StartPosition (Form) | Menentukan posisi awal Form saat dijalankan |
| BackColor | Mengatur warna latar belakang komponen atau form |
| ForeColor | Mengatur warna teks pada komponen |
| Font | Mengatur jenis, ukuran, dan gaya tulisan |
| Enable | Menentukan apakah komponen bisa digunakan user |
| Visible | Menentukan apakah komponen ditampilkan atau disembunyikan |

### Event

Event adalah peristiwa yang terjadi pada komponen yang bisa memicu jalannya kode program. Event muncul karena adanya interaksi user atau perubahan status pada aplikasi.

### Cara Memulai Project Visual Programming

1. Buka Visual Studio.
2. Pilih **Create a new project**.
3. Cari template **"Windows Forms App"** dengan logo VB (Visual Basic).
4. Beri nama project, tentukan lokasi penyimpanan, lalu centang opsi **"Place solution and project in the same directory"** agar `NamaProject.sln` berada di dalam folder project, kemudian klik **Next**.
5. Pilih framework versi **Long Term Support (LTS)**, lalu klik **Create**.
6. Tunggu proses loading (cukup lama) hingga `Form1.vb` muncul dengan template form-nya.

### Penggunaan Komponen Dasar

- Cari toolbar di bagian **View** paling atas, lalu di dalam toolbar cari komponen visual yang diinginkan, misalnya Label, Button, dan Textbox.
- Untuk melihat properti suatu komponen, klik komponen tersebut lalu tekan **F4**, atau gunakan panel **Solution Explorer** dan **Properties** di sidebar.
- Di dalam panel Properties, nama variabel komponen dapat diatur pada bagian **Design (Name)**.
- Untuk melihat atau memodifikasi kode program dari suatu komponen, klik dua kali (double click) pada komponen tersebut untuk masuk ke `Form1.vb`.
- Visual Basic bersifat OOP (Object-Oriented Programming), di mana `Form1` merupakan class utama.

### Syntax yang Dipelajari

| Syntax | Fungsi |
|---|---|
| `MessageBox.Show()` | Menampilkan kotak popup |
| `&` | Penggabung string atau nilai variabel data |
| `vbCrLf` | Membuat baris baru (new line / enter) |
| `namaKomponen.Clear()` | Mengosongkan isi atau nilai variabel data pada komponen tertentu yang sudah diisi, seperti textbox |

---

*Repository ini akan terus diperbarui seiring progres pembelajaran Pemrograman Visual.*