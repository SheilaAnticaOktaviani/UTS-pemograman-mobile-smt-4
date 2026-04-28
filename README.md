# UTS-pemograman-mobile-smt-4
# Nama : SHEILA ANTICA OKTAVIANI
# Kelas: TI.24.A1
# NIM : 312410002
# Mata Kuliah : Pemrogaman Mobile 1 (UTS & UAS)
# Dosen : Donny Maulana, S.Kom., M.M.S.I.,
## UI 
<img width="1057" height="434" alt="WhatsApp Image 2026-04-28 at 9 26 45 AM" src="https://github.com/user-attachments/assets/a26d633b-8c12-45e6-ace3-947f4cc985e6" />

# 1. Loading Screen
Halaman ini adalah titik awal saat aplikasi pertama kali dibuka.
Fungsi: Melakukan inisialisasi aplikasi dan memuat aset yang diperlukan.
Visual: Menampilkan logo "Kuis Pintar" dengan progress bar sebagai indikator pemuatan sistem agar pengguna mengetahui aplikasi sedang bekerja.
# 2. Splash Screen
Setelah proses pemuatan selesai, pengguna akan diarahkan ke Splash Screen.
Fungsi: Membangun branding aplikasi dan menyediakan pintu masuk utama.
Interaksi: Terdapat tombol "Mulai Kuis Sekarang" yang akan mengarahkan pengguna ke tahap otentikasi atau menu utama.
# 3. Home Screen (Login)
Halaman ini berfungsi sebagai gerbang keamanan dan identitas pengguna.
Fungsi: Mengelola akses masuk menggunakan email dan password.
Fitur: Form input kredensial dan opsi pendaftaran bagi pengguna baru untuk memastikan data skor tersimpan dengan benar.
# 4. Implementasi Izin Lokasi (Permission)
Sebagai bagian dari keamanan dan fitur berbasis lokasi, aplikasi meminta izin akses perangkat.
Fungsi: Meminta izin ACCESS_FINE_LOCATION kepada pengguna.
Logika: * Jika pengguna memberikan izin, aplikasi akan melanjutkan ke kuis.
Jika ditolak, aplikasi akan menampilkan dialog penjelasan edukatif yang mengarahkan pengguna ke menu Pengaturan (Settings) untuk mengaktifkan izin secara manual.
# 5. Mulai Kuis (Gameplay)
Inti dari aplikasi di mana pengguna menjawab berbagai pertanyaan seputar teknologi jaringan.
## Fitur Utama:
Timer: Memberikan batas waktu menjawab untuk meningkatkan tantangan.

Pilihan Ganda: Empat opsi jawaban (A, B, C, D) yang interaktif.

Feedback Instan: Tombol akan berubah warna (Hijau jika benar, Merah jika salah) setelah tombol "JAWAB" ditekan.
# 6. Skor Akhir & Analisis AI
Halaman hasil yang merangkum performa pengguna selama kuis.
## Fitur Utama:
Skor Angka: Menampilkan total poin yang dikumpulkan secara jelas.
Feedback AI: Integrasi dengan OpenAI API untuk memberikan analisis cerdas, motivasi, dan penjelasan mengenai hasil kuis secara otomatis.
## Opsi Navigasi: * Coba Lagi: Mengulang kuis dari awal untuk memperbaiki skor.
## Kembali ke Menu: Keluar dari sesi kuis menuju halaman utama.
# Teknologi yang Digunakan:
Bahasa: Java (Android Studio)
API: OpenAI API (GPT-3.5 Turbo) untuk feedback kuis.
Permissions: Android Location Services.
Layout: XML dengan ConstraintLayout untuk responsivitas antar layar.

LInk ClickUpp : https://app.clickup.com/90181770669/v/b/4-90187071231-2
