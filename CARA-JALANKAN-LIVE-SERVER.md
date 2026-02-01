# 🚀 CARA MENJALANKAN DI LIVE SERVER

## ✅ LANGKAH MUDAH

### 1️⃣ Install Live Server Extension (Jika Belum)

1. Buka VS Code
2. Tekan `Ctrl + Shift + X` (Windows) atau `Cmd + Shift + X` (Mac)
3. Cari "Live Server" oleh Ritwick Dey
4. Klik **Install**

### 2️⃣ Jalankan Website

**Ada 3 Cara:**

#### **Cara 1: Klik Kanan**

1. Klik kanan pada file `index.html`
2. Pilih **"Open with Live Server"**
3. Browser akan otomatis terbuka! 🎉

#### **Cara 2: Tombol "Go Live"**

1. Pastikan file `index.html` terbuka
2. Lihat status bar di bawah (warna biru)
3. Klik tombol **"Go Live"** di pojok kanan bawah
4. Browser akan otomatis terbuka! 🎉

#### **Cara 3: Command Palette**

1. Tekan `Ctrl + Shift + P` (Windows) atau `Cmd + Shift + P` (Mac)
2. Ketik: `Live Server: Open with Live Server`
3. Enter
4. Browser akan otomatis terbuka! 🎉

---

## 🌐 URL DEFAULT

Website akan berjalan di:

```
http://127.0.0.1:5500/index.html
```

atau

```
http://localhost:5500/index.html
```

---

## 📝 DEMO LOGIN

**Username:** student  
**Password:** kampus123

---

## 🎯 FITUR YANG SUDAH SIAP

✅ **Responsive Design** - Coba resize browser  
✅ **Mobile Menu** - Buka di mobile atau resize kecil  
✅ **Login System** - Klik "Login Mahasiswa"  
✅ **Smooth Scroll** - Klik menu navigasi  
✅ **Form Validation** - Coba kirim form contact  
✅ **Accessibility** - Tab key navigation  
✅ **Dark Mode Ready** - Otomatis jika OS dark mode  

---

## 🔧 TROUBLESHOOTING

### Masalah: File tidak terbuka di browser

**Solusi:**

1. Pastikan VS Code tidak readonly
2. Restart VS Code
3. Uninstall & install ulang Live Server extension

### Masalah: CSS tidak muncul / style rusak

**Solusi:**

1. Pastikan file `styles.css` ada di folder yang sama
2. Hard refresh browser: `Ctrl + Shift + R` (Windows) atau `Cmd + Shift + R` (Mac)

### Masalah: JavaScript tidak jalan

**Solusi:**

1. Pastikan file `script.js` ada di folder yang sama
2. Buka Console (F12) dan cek error
3. Hard refresh browser

### Masalah: Port 5500 sudah dipakai

**Solusi:**

1. Klik "Go Live" lagi untuk stop
2. File → Preferences → Settings
3. Cari "Live Server Port"
4. Ganti ke port lain (misal: 5501)

---

## 📁 STRUKTUR FILE (YANG DIBUTUHKAN)

```
zaza/
├── index.html          ← FILE UTAMA (buka ini!)
├── styles.css          ← CSS file
├── script.js           ← JavaScript file
├── dashboard.html      
├── courses.html
├── calendar.html
├── forum.html
├── quiz.html
├── profile.html
├── downloads.html
└── ... (file lainnya)
```

---

## ⚙️ LIVE SERVER SETTINGS (Optional)

Customize Live Server di VS Code Settings:

```json
{
  "liveServer.settings.port": 5500,
  "liveServer.settings.root": "/",
  "liveServer.settings.CustomBrowser": "chrome",
  "liveServer.settings.donotShowInfoMsg": true,
  "liveServer.settings.donotVerifyTags": true
}
```

---

## 🎨 HALAMAN YANG BISA DIAKSES

Setelah Live Server jalan, kamu bisa akses:

- `http://localhost:5500/index.html` - Landing Page
- `http://localhost:5500/dashboard.html` - Dashboard (harus login dulu)
- `http://localhost:5500/courses.html` - Katalog Kursus
- `http://localhost:5500/calendar.html` - Kalender
- `http://localhost:5500/forum.html` - Forum
- `http://localhost:5500/quiz.html` - Quiz
- `http://localhost:5500/profile.html` - Profil
- `http://localhost:5500/downloads.html` - Download Materi

---

## 🔥 TIPS PRO

1. **Auto Reload**: Live Server otomatis reload saat save file!
2. **Multiple Devices**: Akses dari HP via IP komputer (misal: `192.168.1.5:5500`)
3. **Browser Sync**: Buka di multiple browser sekaligus
4. **Inspect Mode**: Tekan F12 untuk dev tools

---

## ✅ CHECKLIST SEBELUM MULAI

- [ ] VS Code terinstall
- [ ] Live Server extension terinstall
- [ ] File `index.html`, `styles.css`, `script.js` ada
- [ ] Semua file di folder yang sama
- [ ] Browser terinstall (Chrome/Firefox/Edge)

---

## 🎉 SELESAI

Kamu siap coding! Happy learning! 🚀

**Pertanyaan?** Cek README-PERFECT-10.md untuk dokumentasi lengkap.
