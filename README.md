
# ♟️ NUGREEN 3D Chess

Game catur 3D berbasis web dengan tampilan gelap, bidak metalik, animasi, dan lawan komputer. Game dipublikasikan menggunakan GitHub Pages.

## 🎮 Mainkan Game

**[Buka NUGREEN 3D Chess](https://nuugreen.github.io/game-catur/)**

## ✨ Fitur

- Papan catur tiga dimensi.
- Bidak emas untuk pemain dan bidak gelap untuk komputer.
- Model bidak dengan geometri 3D.
- Kamera 3D yang dapat diputar dan diperbesar.
- Lawan komputer dengan tiga tingkat kesulitan.
- Riwayat langkah permainan.
- Tombol permainan baru dan undo.
- Tombol reset kamera dan putar papan.
- Tampilan responsif untuk desktop dan perangkat seluler.
- Tautan dokumentasi langsung dari halaman permainan.

## 🕹️ Cara Bermain

1. Buka tautan game di atas.
2. Pilih tingkat kesulitan komputer.
3. Klik salah satu bidak emas.
4. Klik kotak tujuan yang ditandai.
5. Tunggu komputer melakukan langkahnya.
6. Gunakan **Undo** untuk membatalkan langkah terakhir atau **Permainan Baru** untuk memulai ulang.

## 📁 Struktur Repository

```text
game-catur/
├── index.html
└── README.md
```

### `index.html`

File utama yang berisi HTML, CSS, JavaScript, papan catur 3D, model bidak, kontrol kamera, dan logika permainan.

### `README.md`

File dokumentasi proyek yang menjelaskan fitur, cara bermain, teknologi, dan proses publikasi.

**Catatan:** versi ini tidak memerlukan file CSS atau JavaScript terpisah karena kode tersebut berada di dalam `index.html`.

## 🧰 Teknologi

- HTML5
- CSS3
- JavaScript
- Three.js 0.147.0
- Three.js OrbitControls
- chess.js 0.10.3
- GitHub Pages

Pustaka eksternal dimuat melalui CDN, sehingga koneksi internet diperlukan ketika menjalankan game.

## 🚀 Cara Mengaktifkan GitHub Pages

1. Buka repository [nuugreen/game-catur](https://github.com/nuugreen/game-catur).
2. Pilih menu **Settings**.
3. Buka menu **Pages**.
4. Pada bagian **Build and deployment**, pilih **Deploy from a branch**.
5. Pilih branch `main`.
6. Pilih folder `/(root)`.
7. Klik **Save**.
8. Tunggu hingga proses publikasi selesai.

Alamat game:

https://nuugreen.github.io/game-catur/

## 🔧 Pemecahan Masalah

### Game tidak muncul

- Pastikan koneksi internet aktif.
- Muat ulang halaman menggunakan `Ctrl + F5`.
- Pastikan file `index.html` berada di folder utama repository.
- Pastikan URL CDN Three.js, OrbitControls, dan chess.js benar.
- Tekan `F12`, buka tab **Console**, lalu periksa pesan error.

### GitHub Pages menampilkan 404

- Pastikan GitHub Pages sudah diaktifkan.
- Pastikan branch dan folder publikasi benar.
- Pastikan nama file adalah `index.html`, dengan huruf kecil.
- Tunggu beberapa saat setelah melakukan commit.

## 🔄 Memperbarui Game

1. Buka file `index.html` di repository.
2. Klik **Edit**.
3. Lakukan perubahan kode.
4. Klik **Commit changes**.
5. Tunggu GitHub Pages memperbarui halaman.

## 📜 Lisensi

Proyek ini dikembangkan untuk pembelajaran dan pengembangan game catur 3D. Perhatikan lisensi masing-masing pustaka eksternal yang digunakan.
