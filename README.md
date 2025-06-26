# Portfolio Website

Website portfolio profesional dengan desain modern, responsive, dan fitur PWA (Progressive Web App).

## 🚀 Fitur

- **Responsive Design** - Optimal di semua perangkat
- **Modern UI/UX** - Desain clean dan profesional
- **PWA Support** - Dapat diinstall sebagai aplikasi
- **Offline Support** - Tetap berfungsi tanpa internet
- **Fast Loading** - Optimasi performa
- **SEO Friendly** - Meta tags dan struktur yang baik
- **Contact Form** - Form kontak yang fungsional
- **Smooth Animations** - Animasi yang halus dan menarik

## 🛠️ Teknologi

- **HTML5** - Struktur semantik
- **CSS3** - Styling modern dengan CSS Grid & Flexbox
- **JavaScript (ES6+)** - Interaktivitas dan animasi
- **Service Worker** - Offline functionality
- **PWA** - Progressive Web App features

## 📁 Struktur File

```
portfolio-website/
├── assets/
│   ├── css/
│   │   └── style.css
│   ├── js/
│   │   └── script.js
│   └── images/
│       ├── logo.png
│       ├── profile.jpg
│       ├── ecommerce.jpg
│       ├── taskmanagemen.jpg
│       └── favico.ico
├── index.html
├── offline.html
├── sw.js
├── manifest.json
├── package.json
├── README.md
├── LICENSE
├── robots.txt
├── sitemap.xml
└── .gitignore
```

## 🚀 Cara Menjalankan

### Menggunakan Python (Recommended)
```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```

### Menggunakan Node.js
```bash
# Install dependencies (jika ada)
npm install

# Start development server
npm start
```

### Menggunakan Live Server (VS Code)
1. Install extension "Live Server"
2. Right-click pada `index.html`
3. Pilih "Open with Live Server"

## 📱 PWA Features

Website ini mendukung fitur PWA:

- **Installable** - Dapat diinstall di mobile/desktop
- **Offline Support** - Cache resources untuk offline access
- **Push Notifications** - Support untuk notifikasi (perlu backend)
- **Background Sync** - Sync data saat online kembali

## 🎨 Customization

### Mengubah Informasi Personal
1. Edit `index.html` - Ganti nama, deskripsi, dan informasi kontak
2. Edit `manifest.json` - Update nama aplikasi dan metadata
3. Ganti gambar profil di `profile.jpg`

### Mengubah Warna
Edit CSS variables di `style.css`:
```css
:root {
    --primary-color: #000000;    /* Warna utama */
    --bg-color: #ffffff;         /* Background */
    --text-primary: #1a1a1a;     /* Text utama */
    --text-secondary: #666666;   /* Text sekunder */
}
```

### Menambah Proyek
Edit section projects di `index.html`:
```html
<div class="project-card">
    <div class="project-image">
        <img src="your-project-image.jpg" alt="Project Name">
        <!-- ... -->
    </div>
    <div class="project-content">
        <h3>Project Name</h3>
        <p>Project description</p>
        <!-- ... -->
    </div>
</div>
```

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

## 📄 License

MIT License - lihat file [LICENSE](LICENSE) untuk detail.

## 🤝 Contributing

1. Fork repository ini
2. Buat branch baru (`git checkout -b feature/AmazingFeature`)
3. Commit perubahan (`git commit -m 'Add some AmazingFeature'`)
4. Push ke branch (`git push origin feature/AmazingFeature`)
5. Buat Pull Request

## 📞 Kontak

- Email: hello@example.com
- LinkedIn: [Your LinkedIn]
- GitHub: [Your GitHub]

---

**Note**: Website ini dibuat sebagai template portfolio. Silakan customize sesuai kebutuhan Anda. 