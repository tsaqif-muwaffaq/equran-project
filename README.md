📖 Al-Qur'an Web App — Project Akhir Frontend JavaScript
🌟 Deskripsi Proyek

Website ini merupakan aplikasi Al-Qur’an interaktif berbasis web yang dibangun menggunakan HTML, CSS, dan JavaScript modular (ES Modules). Aplikasi ini memanfaatkan API publik equran.id
 untuk menampilkan daftar surat lengkap serta detail ayat beserta terjemahannya secara real-time.

Website ini dirancang responsif, ringan, dan mudah digunakan di berbagai perangkat (desktop & mobile). Proyek ini dibuat sebagai tugas akhir evaluasi pembelajaran Frontend JavaScript.

🚀 Fitur Utama

✅ Daftar Surat Lengkap — Menampilkan seluruh surat Al-Qur’an (114 surat) dari API equran.id.
✅ Pencarian Surat Real-Time — Fitur filter berdasarkan nama surat atau arti.
✅ Halaman Detail Surat — Menampilkan seluruh ayat beserta terjemahan berdasarkan surat yang dipilih.
✅ Caching Local Storage — Menyimpan data API agar loading lebih cepat saat dibuka kembali.
✅ Error Handling — Penanganan error ketika API gagal dimuat dengan tampilan pesan ramah.
✅ Responsif & Modern UI — Warna dominan biru tua dan putih dengan animasi halus.

## 📂 Struktur Folder

```plaintext
alquran-app/
├─ index.html
├─ detail.html
├─ assets/
│  ├─ css/
│  │  └─ styles.css
│  └─ img/
├─ src/
│  ├─ main.js
│  ├─ modules/
│  │  ├─ api.js
│  │  ├─ ui.js
│  │  ├─ storage.js
│  │  └─ utils.js
│  └─ components/
└─ README.md

```


🧑‍💻 Teknologi yang Digunakan

HTML5

CSS3

JavaScript (ES6+)

Web Fetch API (async/await)

localStorage & sessionStorage

Modular JavaScript (import/export)

🔌 Sumber Data (API)

Data Al-Qur’an diambil dari API publik:

📜 Daftar surat: https://equran.id/api/surat

📖 Detail surat & ayat: https://equran.id/api/surat/{id}

Contoh:

Daftar surat: https://equran.id/api/surat

Detail surat Al-Fatihah: https://equran.id/api/surat/1

🛠️ Cara Menjalankan Proyek (Lokal)

Clone repository atau ekstrak file ZIP.

Jalankan server lokal (karena fetch tidak berjalan dari file://):

# Python
python -m http.server 5500

# atau menggunakan Node.js
npx http-server


Buka di browser: http://localhost:5500

🌐 Deployment ke Vercel

Push project ke GitHub.

Hubungkan repository ke Vercel
.

Deploy dan dapatkan URL publik.

💡 Tips: Jika terjadi error CORS saat deploy, gunakan serverless function sebagai proxy atau aktifkan pengaturan CORS melalui backend.

🧠 Tantangan & Solusi
Tantangan	Solusi
CORS error saat fetch API	Menggunakan server lokal atau proxy saat deploy
Loading data lambat	Implementasi caching dengan localStorage
Struktur data API kompleks	Gunakan destructuring dan mapping array
UI terlalu sederhana	Tambahkan animasi hover & transisi CSS
Responsivitas	Gunakan layout fleksibel (grid/flex) dan media query
📌 Rencana Pengembangan Selanjutnya

Menambahkan fitur bookmark ayat favorit

Menambahkan tafsir dan audio untuk setiap ayat

Mode gelap (dark mode)

Fitur pencarian ayat global berdasarkan kata kunci

✨ Kontributor

👤 Nama: tsaqif muwaffaq
📍 Link Live: https://equran-online.vercel.app
📍 Link presentasi: 
