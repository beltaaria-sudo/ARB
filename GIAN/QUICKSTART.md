# 🚀 QUICK START GUIDE

## ⚡ 5 MENIT SETUP

### Langkah 1: Buka File
Cukup **double-click** pada `index.html` di folder `d:\C1\CCC\`

### Langkah 2: Nikmati!
```
Slide 1: Sambutan Awal
         ↓ Klik "Ayo Diklik"
Slide 2: Galeri Utama (scroll horizontal)
         ↓ Klik "Galeri Foto"
Slide 3: Grid 2×2 Foto Romantic
         ↓ Klik "Galeri Kenangan"
Slide 4: 16 Foto Animasi Bertahap + Floating Hearts 💕
         ↓ Klik "Lanjut"
Slide 5: Pesan Anniversary Spesial
         ↓ Klik "Next"
Slide 6: Kue Special
         ↓ Selesai!
```

---

## 🎵 MUSIK

Tombol musik ada di **pojok kanan bawah**. Klik untuk:
- Putar musik (otomatis pas ke Slide 2)
- Pause musik

---

## 📱 BUKA DI SMARTPHONE

1. **Transfer file** `d:\C1\CCC\` ke HP via kabel USB atau cloud
2. **Buka folder** di file manager HP
3. **Klik** `index.html`
4. **Browser akan membuka** website

Atau buka di Telegram/WA:
1. Zip folder `d:\C1\CCC\`
2. Share ke HP
3. Extract dan buka `index.html`

---

## 🎨 WANT TO CUSTOMIZE?

### Tambah Foto di Galeri Akhir (Slide 4)

Edit `index.html`, cari:
```html
<div class="memory-gallery">
    <!-- Tambahkan lebih banyak foto di sini -->
    <img src="images/yourphoto.jpg" alt="Foto" loading="lazy">
</div>
```

### Ubah Warna Pink

Edit `css/style.css`, cari:
```css
background-color: #ff6f61; /* Ubah warna sini */
background: linear-gradient(135deg, #ff9a9e, #fad0c4); /* Atau sini */
```

### Ubah Delay Animasi

Edit `js/script.js`, cari:
```javascript
const delay = index * 350; // Ubah 350 ke 250 (lebih cepat) atau 500 (lebih lambat)
```

---

## 🔍 TESTING DI BROWSER

Untuk memastikan responsive di semua device:

1. Buka `index.html` di Chrome/Firefox
2. Tekan **F12** atau kanan → Inspect
3. Klik icon device (Ctrl+Shift+M)
4. Pilih ukuran device:
   - iPhone SE (375×667) - Mobile
   - iPad (768×1024) - Tablet
   - Desktop HD (1920×1080) - Monitor
5. Resize untuk test responsive

---

## ❓ COMMON QUESTIONS

**Q: Foto tidak muncul**
A: Pastikan folder `images/` ada dengan file `.jpg` atau `.jpeg`

**Q: Animasi lambat**
A: Normal, tergantung performa PC. Di HP akan lebih smooth.

**Q: Musik tidak bunyi**
A: Pastikan `music/A1.mp3` ada. Beberapa browser butuh klik manual.

**Q: Layout berantakan di HP**
A: Clear cache (pull down → clear cache). Atau buka di browser lain.

---

## 📁 FOLDER STRUCTURE

```
Tidak perlu diubah, tapi good to know:

index.html           ← Buka ini!
css/
  └── style.css      ← Semua design
js/
  └── script.js      ← Semua logic
images/
  ├── 1.jpeg         ← Foto-foto
  ├── 2.jpeg
  └── ...
music/
  └── A1.mp3         ← Musik background
```

---

## 💡 TIPS

1. **Best viewing**: Fullscreen mode (F11)
2. **Best music**: Dengerin dengan volume pas
3. **Best experience**: Buka di HP yang bagus
4. **Best sharing**: Share link jika udah di server
5. **Best untuk**: Dibikin spesial untuk orang tercinta ❤️

---

## 🎉 ENJOY!

Website ini dibuat dengan hati untuk moment spesial.

**Happy Birthday!** 🎂🎉💕

---

Butuh bantuan? Lihat:
- `PANDUAN_GALERI.md` - Customization lengkap
- `IMPLEMENTASI.md` - Technical details
- `README.md` - Overview umum
