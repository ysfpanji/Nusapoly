🎲 Monopoli 3D - Jelajah Nusantara

Monopoli 3D Jelajah Nusantara adalah adaptasi game monopoli WebGL modern berbasis browser yang terinspirasi oleh visual arcade miring (tilted isometric) bergaya LINE Let's Get Rich. Game ini dibuat sepenuhnya menggunakan teknologi web murni tanpa ketergantungan game engine berat.

✨ Fitur Utama

🎨 Visual 3D WebGL (Let's Get Rich Style): Rendering 3D real-time menggunakan Three.js lengkap dengan tata cahaya studio hangat, bayangan halus (soft shadows), dan pola warna pastel khas game arcade casual.

👾 Karakter Chibi 3D Custom: Pion berbentuk karakter Chibi 3D imut bermahkota dengan animasi lompatan parabola (arc jump) antar-ubin yang mulus.

🏙️ Sistem Kepemilikan & Bangunan 3D:

Ring Glow 3D & Bendera: Petak yang dibeli langsung ditandai dengan ring cahaya dan bendera sesuai warna pemain.

Model Rumah & Hotel 3D: Pembangunan bertahap hingga Landmark/Hotel megah 3D.

🎲 Dadu 3D Interaktif: Fisik dadu 3D berpola titik (pips 1-6) yang berputar dinamis dan mendarat sesuai angka acakan.

🎥 Mode Kamera POV & Smooth Follow: Kamera secara otomatis berpindah mendekat ke sudut pandang karakter (POV Camera) saat melangkah, lalu kembali ke tampilan overview.

🔄 Orbit Controls (Rotasi Manual): Pemain dapat memutar papan 360°, menggeser, dan memperbesar/memperkecil (zoom in/out) tampilan papan secara manual menggunakan mouse atau layar sentuh.

🤖 Bot AI Opponent: Dukungan mode bermain melawan Bot AI cerdas secara otomatis maupun multi-pemain (hingga 4 pemain).

🔒 Aturan Bangun 1 Putaran: Tombol bangun kota diuji dengan aturan strategis di mana pembangunan baru aktif setelah melewati 1 putaran penuh (lap 1+).

🛠️ Teknologi yang Digunakan

HTML5 & CSS3 – Struktur UI Arcade & Glassmorphism HUD Overlay.

JavaScript (ES6+) – Logika permainan, state management, dan rule engine.

Three.js – Rendering grafik WebGL 3D, pencahayaan, penciptaan tekstur kanvas dinamis, dan kalkulasi koordinat ubin.

Tween.js – Animasi pergerakan karakter, rotasi dadu, dan transisi kamera halus.

OrbitControls.js – Kontrol kamera 3D interaktif via sentuhan/drag mouse.

📁 Struktur File Proyek

monopoli-3d/
│
├── index.html         # File aplikasi tunggal (HTML, CSS, 3D WebGL Canvas, & JS Logic)
├── README.md          # Dokumentasi repositori GitHub
└── LICENSE            # Lisensi proyek (MIT)


🚀 Cara Menjalankan Game

1. Bermain Langsung di Browser (Lokal)

Clone atau unduh repositori ini ke komputer Anda:

git clone https://github.com/username-anda/monopoli-3d.git


Buka folder proyek dan jalankan file index.html dengan double-click atau drag ke web browser favorit Anda (Google Chrome, MS Edge, Firefox, Safari).

2. Live Demo (GitHub Pages)

Game ini dapat dimainkan langsung secara online tanpa instalasi melalui GitHub Pages:
👉 Mainkan Monopoli 3D Sekarang

🎮 Cara Bermain

Pilih Jumlah Pemain: Gunakan menu dropdown di panel kiri atas untuk memilih bermain melawan Bot AI atau 2–4 Pemain.

Lempar Dadu: Ketuk ikon dadu 3D di panel bawah untuk memutar dadu dan melangkah.

Beli & Bangun Kota:

Beli Tanah: Ketuk tombol Beli jika hinggap di kota yang belum berpemilik.

Bangun Rumah/Hotel: Setelah menyelesaikan minimal 1 putaran, Anda bisa meng-upgrade kota Anda.

Navigasi Kamera: Drag mouse atau geser layar di luar UI untuk memutar sudut pandang papan 3D. Gunakan tombol RESET untuk mengembalikan sudut kamera awal.

🤝 Kontribusi

Kontribusi, saran fitur, dan perbaikan bug sangat disambut baik!

Fork repositori ini.

Buat branch fitur baru (git checkout -b fitur/FiturKeren).

Commit perubahan Anda (git commit -m 'Menambahkan fitur keren').

Push ke branch (git push origin fitur/FiturKeren).

Buat Pull Request.

📜 Lisensi

Proyek ini dirilis di bawah lisensi MIT License. Terbuka untuk dipelajari, dimodifikasi, dan dikembangkan lebih lanjut.
