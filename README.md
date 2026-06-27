**Website Resmi Masjid Al-Huda** 🕌

Desain website modern dan responsif untuk Masjid Al-Huda. Dilengkapi dengan fitur lengkap yang mendukung pengelolaan masjid dan pelayanan jamaah secara digital.

### Fitur Utama
- Jadwal sholat otomatis & countdown waktu sholat
- Informasi kegiatan masjid, kajian, dan event
- Halaman donasi / infaq online
- Program pendidikan Islam & kursus (Quran, dll)
- Panduan Umroh & artikel keislaman
- Tampilan elegan, responsif, dan ramah mobile

### Demo Langsung
[**🕌 Buka Website Masjid Al-Huda**](https://wahyuartadianto.github.io/website_masjid_alhuda/)

---

**Teknologi:** HTML, CSS, JavaScript

Website ini cocok digunakan sebagai template atau referensi untuk masjid, musholla, atau lembaga Islam lainnya yang ingin memiliki kehadiran digital yang profesional.

#masjid #website-masjid #islamicwebsite #jadwalsholat #umroh #kajianislam #donasi #webislam

Noted:
untuk versi terbaru sudah terkoneksi dengan AI:
Berikut adalah rekapitulasi fitur-fitur yang sudah berhasil terpasang:

1. 🕌 Fitur Jadwal Sholat & Waktu
Jadwal Sholat Otomatis: Mengambil data real-time dari API (MyQuran) berdasarkan tanggal saat ini. Dilengkapi dengan sistem offline fallback (data cadangan) jika internet/API mati.

Deteksi Lokasi GPS Akurat: Pengguna bisa menekan tombol "Sholat" untuk melacak lokasi via GPS. Sistem akan mengubah koordinat menjadi nama kota (misal: "Malang, Jawa Timur") menggunakan API Nominatim, dan mengambil jadwal presisi menggunakan API Aladhan (Metode Kemenag RI).

Hitung Mundur (Countdown): Menampilkan waktu hitung mundur menuju sholat berikutnya yang sinkron antara Header (PC) dan Floating Card (Mobile).

Pengingat Suara Adzan Otomatis: Sistem akan memutar audio pengingat secara otomatis tepat 20 menit sebelum waktu sholat tiba. Sistem juga cukup cerdas untuk membedakan pemutaran adzan-subuh.mp3 khusus untuk Subuh, dan adzan.mp3 untuk sholat lainnya.

Waktu Iqamah & Dhuha: Menampilkan estimasi waktu Iqamah (Adzan + 15 menit) dan waktu Dhuha (Terbit + 20 Menit).

Desain Teardrop: Tampilan kotak jadwal sholat dengan desain teardrop (tetesan air) yang modern dan interaktif saat di-hover.

2. 📖 Fitur Al-Qur'an Digital & Audio
Murottal Player (Satu Surat Penuh): Memutar lantunan Al-Qur'an menggunakan data dari API AlQuran.cloud dan file audio berkualitas dari MP3Quran.net.

Pilihan Qari (Reciter): Pengguna bisa memilih 5 suara Syekh/Qari terkenal (seperti Abdurrahman as-Sudais, Misyari Rasyid Al-Afasi, dll). Audio otomatis berganti tanpa error.

Auto-Next Surah: Jika dicentang, pemutar akan otomatis memutar surah berikutnya (misal dari Al-Fatihah lanjut ke Al-Baqarah) saat audio selesai.

Talaqi & Text-To-Speech (TTS): Skrip bawaan untuk membaca teks sapaan Islami dan fitur Auto-Repeat untuk menghafal (Talaqi) dengan suara Bahasa Indonesia dari sistem operasi.

3. 📱 Fitur Khusus Mobile (UI/UX App-Like)
Bottom Navigation Bar: Menu navigasi lengket di bawah layar khusus HP (Umroh, Kesehatan, Ngaji, Sholat) layaknya aplikasi Android/iOS.

Floating Header & Card: Tampilan Header khusus mobile dengan kartu jadwal sholat yang melayang (menumpuk) di atas background hijau.

Horizontal Scroll Acara: Daftar acara masjid (Kajian, Santunan) yang bisa di-geser/swipe ke kiri-kanan oleh pengguna HP.

Slider Adaptif: Gambar Hero Slider (Banner atas) yang dibedakan antara PC (memanjang) dan HP (mengotak) agar gambar tidak terpotong.

Smart Auto-Close Modal: Jika pengguna membuka satu menu (misal Umroh), lalu mengklik menu lain di navigasi bawah (misal Kesehatan), sistem otomatis menutup popup lama dengan rapi sebelum membuka yang baru.

4. 📚 Fitur Layanan & Interaksi Jamaah
Layanan Digital Berbasis Modal (Popup): Buku panduan Umroh, Kesehatan Islami, dan Belajar Ngaji yang dimuat di dalam iFrame (Popup layar penuh) tanpa harus berpindah halaman dan sudah terkoneksi dengan AI.

Ensiklopedia Rukun Islam: Penjelasan detail tentang ke-5 Rukun Islam (termasuk Syahadat) yang muncul di dalam modal dengan teks berparagraf yang rapi.

Donasi & Infaq Cepat: Menampilkan QRIS Masjid Al-Huda lengkap dengan tombol "Download QRIS" agar jamaah bisa menyimpan gambarnya langsung ke galeri HP.

Countdown Khutbah Jumat: Hitung mundur khusus yang menargetkan hari Jumat terdekat secara terus-menerus.

Scroll to Top (Progress Button): Tombol panah ke atas yang posisinya sudah disesuaikan agar tidak tertumpuk oleh Bottom Navigation di HP.

Website ini sekarang bukan sekadar profil masjid, melainkan sudah berevolusi menjadi Pusat Layanan Digital (Islamic Center) yang interaktif!
