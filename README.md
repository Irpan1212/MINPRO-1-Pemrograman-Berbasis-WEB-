# 🌐 Website Portfolio — Muhamad Irpan Santoso

Website portofolio statis pribadi yang dibuat menggunakan HTML dan CSS murni.

---

## 🛠️ Teknologi yang Digunakan

- HTML5
- CSS3
- Google Fonts (Poppins)

---

## 📁 Struktur File

portfolio/
├── index.html
├── style.css
├── image.png
---

## 📸 Tampilan Setiap Section

### 1. Navbar
Navbar fixed di bagian atas halaman dengan logo UrMyMine dan menu navigasi Home, About Me, Certificates. Navbar tetap terlihat saat halaman di-scroll.

### 2. Home (Hero Section)
Section pertama yang tampil saat membuka website. Berisi foto profil bulat, nama Muhamad Irpan Santoso, role, deskripsi singkat, dan dua tombol navigasi yaitu Tentang Saya dan Lihat Sertifikat.

### 3. About Me
Section berisi deskripsi diri, daftar pengalaman, dan skill progress bar. Skills yang ditampilkan yaitu Tidur 90%, Baring 80%, Pejamkan Mata 70%, dan Lelap 65%.

### 4. Certificates
Section berisi tiga card sertifikat dalam layout grid. Setiap card memiliki efek hover naik ke atas dengan border emas.
- Sertifikat 1 — Top 1 Pencinta Tidur (2024)
- Sertifikat 2 — The Best 3 Sleeping (2024)
- Sertifikat 3 — Penghargaan Tidur Nasional (2025)

### 5. Footer
Bagian bawah halaman berisi teks hak cipta.

---

## 💻 Penjelasan Code Setiap Section

### Navbar
Menggunakan tag nav dengan position fixed agar selalu tampil di atas saat scroll. Menu navigasi menggunakan href yang mengarah ke id masing-masing section.

### Hero Section
Menggunakan tag section dengan id home. Foto profil diberi border-radius 50% agar berbentuk lingkaran. Background menggunakan linear-gradient CSS. Tombol dibuat dari tag a dengan class btn.

### About Me Section
Layout menggunakan CSS Grid dengan 2 kolom agar deskripsi dan skills tampil berdampingan. Progress bar dibuat dari dua div bertumpuk, skill-bar sebagai latar dan skill-fill sebagai isian. Lebar skill-fill diatur langsung di HTML menggunakan style width.

### Certificates Section
Layout menggunakan CSS Grid repeat 3 kolom. Setiap card memiliki efek hover menggunakan CSS transition dan transform translateY untuk animasi naik.

### Footer
Menggunakan tag footer dengan border-top tipis berwarna emas sebagai pemisah.

---

## 🎨 Palet Warna

- Background Utama : #0d0d14
- Background Section : #111119
- Background Card : #141420
- Emas Aksen : #c8a050
- Teks Utama : #f0ece4
- Teks Abu : #8a8678

---

## 📱 Responsif

- Layar 768px ke bawah : layout grid berubah menjadi 1 kolom
- Layar 480px ke bawah : ukuran font hero diperkecil
