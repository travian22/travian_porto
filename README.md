# Portfolio Travian - Septaro Travian Gadha

Website portfolio profesional dengan fokus pada jaringan komputer, pengembangan web, dan teknologi modern. Dibuat dengan desain responsive dan fitur PWA (Progressive Web App).

## 👨‍💻 Tentang

Portfolio ini menampilkan karya dan pengalaman **Septaro Travian Gadha**, seorang mahasiswa yang berfokus pada jaringan komputer dengan pengalaman dalam berbagai teknologi jaringan dan pengembangan web.

## 🚀 Fitur

- **Responsive Design** - Optimal di semua perangkat (desktop, tablet, mobile)
- **Modern UI/UX** - Desain clean dan profesional dengan animasi smooth
- **PWA Support** - Dapat diinstall sebagai aplikasi di mobile/desktop
- **Offline Support** - Tetap berfungsi tanpa internet
- **Fast Loading** - Optimasi performa dan loading cepat
- **SEO Friendly** - Meta tags dan struktur HTML yang baik
- **Contact Form** - Form kontak yang fungsional
- **Smooth Animations** - Animasi yang halus dan menarik
- **Multi-page** - Halaman utama dan halaman proyek terpisah

## 🛠️ Teknologi

- **HTML5** - Struktur semantik dan modern
- **CSS3** - Styling modern dengan CSS Grid, Flexbox, dan Custom Properties
- **JavaScript (ES6+)** - Interaktivitas, animasi, dan PWA functionality
- **Service Worker** - Offline functionality dan caching
- **PWA** - Progressive Web App features
- **Font Awesome** - Icon library
- **Google Fonts** - Typography (Inter font family)

## 📁 Struktur File

```
portofolio/
├── assets/
│   ├── css/
│   │   └── style.css          # Main stylesheet
│   ├── js/
│   │   └── script.js          # JavaScript functionality
│   └── images/
│       ├── logo.png           # Logo website
│       ├── profile.jpg        # Foto profil
│       ├── topologi.png       # Proyek topologi jaringan
│       ├── projek_admin.png   # Proyek admin dashboard
│       ├── batik_alam.png     # Proyek website batik
│       └── favico.ico         # Favicon
├── index.html                 # Halaman utama
├── projects.html              # Halaman proyek
├── sw.js                      # Service Worker
├── README.md                  # Dokumentasi ini
├── DEPLOYMENT.md              # Panduan deployment
└── .gitignore                 # Git ignore rules
```

## 🎯 Proyek yang Ditampilkan

### 1. Topologi Jaringan Warnet
- **Deskripsi**: Topologi jaringan warnet dengan 3 switch dan 1 router
- **Teknologi**: Winbox, GNS3, Mikrotik, VMware Workstation
- **Fokus**: Jaringan komputer dan konfigurasi router

### 2. Admin Dashboard
- **Deskripsi**: Admin Dashboard dengan fitur CRUD dan autentikasi
- **Teknologi**: HTML5, CSS, JavaScript, PHP
- **Fokus**: Pengembangan web dan sistem admin

### 3. Batik Alam Website
- **Deskripsi**: Website batik alam dengan desain modern, responsive, dan optimasi SEO
- **Teknologi**: HTML5, CSS3, JavaScript, PWA
- **Fokus**: Web design dan e-commerce

## 🚀 Cara Menjalankan

### Menggunakan Python (Recommended)
```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```

### Menggunakan Live Server (VS Code)
1. Install extension "Live Server"
2. Right-click pada `index.html`
3. Pilih "Open with Live Server"

### Menggunakan XAMPP/WAMP
1. Copy folder ke direktori `htdocs` (XAMPP) atau `www` (WAMP)
2. Akses melalui `http://localhost/portofolio`

## 📱 PWA Features

Website ini mendukung fitur PWA:

- **Installable** - Dapat diinstall di mobile/desktop
- **Offline Support** - Cache resources untuk offline access
- **App-like Experience** - Navigasi dan UI seperti aplikasi native
- **Background Sync** - Sync data saat online kembali

## 🎨 Customization

### Mengubah Informasi Personal
1. Edit `index.html` - Ganti nama, deskripsi, dan informasi kontak
2. Ganti gambar profil di `assets/images/profile.jpg`
3. Update social media links di section hero

### Mengubah Warna
Edit CSS variables di `assets/css/style.css`:
```css
:root {
    --primary-color: #000000;    /* Warna utama */
    --bg-color: #ffffff;         /* Background */
    --text-primary: #1a1a1a;     /* Text utama */
    --text-secondary: #666666;   /* Text sekunder */
}
```

### Menambah Proyek
1. Tambahkan gambar proyek di `assets/images/`
2. Edit section projects di `index.html` dan `projects.html`
3. Update deskripsi dan teknologi yang digunakan

## 🔧 Troubleshooting

### Service Worker Tidak Berfungsi
- Pastikan website dijalankan melalui HTTP server (bukan file://)
- Check browser console untuk error messages
- Clear browser cache dan reload

### Gambar Tidak Muncul
- Pastikan path file gambar benar
- Check apakah file gambar ada di folder yang tepat
- Pastikan nama file sesuai dengan yang direferensikan di HTML

### Form Kontak Tidak Berfungsi
- Form saat ini hanya simulasi (tidak ada backend)
- Untuk implementasi nyata, perlu backend server
- Bisa menggunakan services seperti Formspree, Netlify Forms, atau custom backend

## 📊 Statistik Portfolio

- **30+ Proyek Selesai** - Berbagai proyek jaringan dan web development
- **3+ Tahun Pengalaman** - Pengalaman dalam teknologi jaringan
- **20+ Klien Puas** - Kepuasan klien dalam berbagai proyek

## 🌐 Social Media

- **GitHub**: [travian22](https://github.com/travian22)
- **LinkedIn**: [septarotraviangadha](https://www.linkedin.com/in/septarotraviangadha/)
- **Instagram**: [trvngdh](https://www.instagram.com/trvngdh/)

## 📄 License

MIT License - lihat file [LICENSE](LICENSE) untuk detail.

## 🤝 Contributing

1. Fork repository ini
2. Buat branch baru (`git checkout -b feature/AmazingFeature`)
3. Commit perubahan (`git commit -m 'Add some AmazingFeature'`)
4. Push ke branch (`git push origin feature/AmazingFeature`)
5. Buat Pull Request

## 📞 Kontak

- **Email**: hello@example.com
- **LinkedIn**: [Septaro Travian Gadha](https://www.linkedin.com/in/septarotraviangadha/)
- **GitHub**: [travian22](https://github.com/travian22)

---

**Note**: Portfolio ini dibuat untuk menampilkan karya dan pengalaman dalam bidang jaringan komputer dan pengembangan web. Silakan customize sesuai kebutuhan Anda. 