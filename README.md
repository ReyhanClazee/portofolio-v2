# 🌾 Portfolio Sawah & Langit

Website portfolio personal dengan tema pemandangan sawah dan langit Indonesia yang indah dan asri.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

## ✨ Features

- 🌤️ **Animated Sky** - Langit gradien dengan awan bergerak
- ☀️ **Glowing Sun** - Matahari dengan efek glow
- 🌾 **Swaying Rice Field** - Animasi padi bergoyang
- 📱 **Responsive Design** - Tampil sempurna di semua device
- ⚡ **Smooth Animations** - Scroll reveal & parallax effect
- 📧 **Contact Form** - Form dengan validasi

## 📁 Struktur File

```
Webporto2/
├── index.html    # Halaman utama
├── style.css     # Styling & animasi
├── script.js     # Interaksi JavaScript
└── README.md     # Dokumentasi
```

## 🚀 Cara Menggunakan

### 1. Buka Website

Double-click file `index.html` atau buka di browser.

### 2. Edit Informasi Personal

Buka `index.html` dan cari/ganti:

| Cari                | Ganti Dengan      |
| ------------------- | ----------------- |
| `Nama Anda`         | Nama lengkap Anda |
| `nama@email.com`    | Email Anda        |
| `+62 812-3456-7890` | No. HP Anda       |
| `Indonesia`         | Lokasi Anda       |

### 3. Edit Social Media

Cari bagian social media links dan ganti `username`:

```html
<a href="https://github.com/username" ...>
  <!-- GitHub -->
  <a href="https://linkedin.com/in/username" ...>
    <!-- LinkedIn -->
    <a href="https://instagram.com/username" ...>
      <!-- Instagram -->
      <a href="https://twitter.com/username" ...>
        <!-- Twitter/X -->
        <a href="https://wa.me/6281234567890" ...> <!-- WhatsApp --></a></a
      ></a
    ></a
  ></a
>
```

### 4. Edit Skills

Di section `skills-grid`, edit setiap skill card:

```html
<h3 class="skill-name">Nama Skill</h3>
<p class="skill-desc">Deskripsi singkat</p>
<div class="skill-progress" style="--progress: 90%"></div>
```

### 5. Edit Projects

Di section `projects-grid`, edit setiap project card:

```html
<h3 class="project-title">Nama Project</h3>
<p class="project-desc">Deskripsi project...</p>
<div class="project-tags">
  <span class="tag">React</span>
  <span class="tag">Node.js</span>
</div>
```

### 6. Ganti Foto Profile

Buka `index.html`, cari bagian about-img-placeholder dan ganti dengan foto:

```html
<div class="about-img-placeholder">
  <!-- Ganti dari ini: -->
  <span>👨‍💻</span>

  <!-- Menjadi: -->
  <img
    src="foto-anda.jpg"
    alt="Foto Profile"
    style="width:100%;height:100%;object-fit:cover;border-radius:24px;"
  />
</div>
```

## 🎨 Kustomisasi Warna

Buka `style.css` dan edit CSS Variables di bagian `:root`:

```css
:root {
  /* Sky Colors */
  --sky-light: #87ceeb; /* Langit atas */
  --sky-dark: #4a90d9; /* Langit bawah */

  /* Nature Colors */
  --rice-green: #7cb342; /* Warna padi */
  --golden-yellow: #ffd54f; /* Padi matang */
  --earth-brown: #795548; /* Tanah/footer */
}
```

## 📱 Responsive Breakpoints

| Device  | Width    |
| ------- | -------- |
| Mobile  | < 480px  |
| Tablet  | < 768px  |
| Laptop  | < 1024px |
| Desktop | > 1024px |

## 📝 Section yang Tersedia

1. **Home** - Hero dengan animasi sawah
2. **About** - Tentang saya + statistik
3. **Skills** - 6 skill cards
4. **Projects** - 3 project cards
5. **Contact** - Form + info kontak + social media
6. **Footer** - Copyright + logo

## 🛠️ Teknologi

- HTML5 Semantic
- CSS3 dengan Custom Properties
- Vanilla JavaScript (ES6+)
- Google Fonts (Poppins, Playfair Display)

## 📄 License

Free to use for personal projects.

---

Made with ❤️ and ☕ in Indonesia 🇮🇩
