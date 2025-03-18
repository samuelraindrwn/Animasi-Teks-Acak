# 🎮 Animasi Teks Acak ✨

Aplikasi web keren yang bikin teks berubah dari karakter acak jadi teks yang kamu mau secara bertahap. Seru banget! 🚀

## ✅ Fitur Kece

- 🔄 Mengubah karakter acak jadi teks target secara bertahap
- ✏️ Bebas pilih teks apapun yang kamu mau
- ⏱️ Atur sendiri durasi animasinya
- 🕐 Sesuaikan interval perubahan teksnya

## 🚀 Cara Pakai

1. **Buka Aplikasi** 📱

   - Tinggal buka file html yang ada di repo ini ke browser favoritmu

2. **Atur Parameter Animasi** ⚙️

   - **Teks Target**: Ketik teks yang pengen kamu tampilkan di akhir
   - **Durasi (ms)**: Mau berapa lama? (misal 3000 untuk 3 detik)
   - **Interval (ms)**: Seberapa cepat perubahannya? (misal 30ms untuk efek kece)

3. **Mulai Animasi** ▶️
   - Klik tombol "Mulai Animasi" dan lihat keajaibannya!
   - Teks bakal berubah dari acak-acakan jadi rapi sesuai keinginanmu

## 👀 Demo

Penasaran? Cek demo aplikasinya di sini:

[Demo Langsung] Cukup buka file `jqueryVersion.html` atau `normalJavascript.html` di browser kamu untuk melihat animasi keren ini! 🚀

## 🆓 Pakai Gratis!

Animasi ini **100% GRATIS** buat kamu pakai! Ada 2 versi yang bisa kamu pilih:

1. **Versi jQuery** - File `jqueryVersion.html`

   - Pakai jQuery untuk manipulasi DOM
   - Cocok buat yang udah biasa pakai jQuery

2. **Versi JavaScript Murni** - File `normalJavascript.html`
   - Tanpa library tambahan
   - Lebih ringan dan cepat

Tinggal copas aja script dari file yang kamu pilih dan langsung pakai di proyekmu! 🎉

## 🔧 Penjelasan Teknis

### 🧩 Komponen Utama

1. **Form Input** 📝

   - Input teks buat masukin teks targetmu
   - Input angka buat durasi animasi
   - Input angka buat interval perubahan

2. **Fungsi `dynamicText()`** 🧙‍♂️

   - Parameter:

     - `targetText`: Teks yang mau ditampilin di akhir
     - `duration`: Total durasi animasi dalam milidetik (default: 2000ms)
     - `interval`: Interval perubahan dalam milidetik (default: 50ms)

   - Proses:
     1. Bikin teks acak dengan panjang yang sama dengan teks target
     2. Ubah karakter satu-satu dari acak jadi bener
     3. Karakter di awal bakal bener duluan
     4. Makin lama, makin banyak karakter yang bener
     5. Setelah waktu habis, semua karakter jadi teks target. Taraaa! ✨

### 💻 Teknologi yang Dipakai

- HTML5 buat struktur halaman 🏗️
- CSS3 buat bikin tampilan kece 🎨
- JavaScript buat logika animasi 🧠
- jQuery 3.6.0 buat manipulasi DOM dan event handling 🔄

## 💡 Tips Jitu

- Pengen animasi kilat? Kurangin nilai durasi! ⚡
- Mau animasi mulus banget? Kurangin nilai interval! 🧈
- Teks panjang butuh durasi lebih lama biar kerennya maksimal 📏
- Hati-hati! Interval terlalu kecil (< 20ms) bisa bikin HP jadul nge-lag 🐢
