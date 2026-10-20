# Montinary Website

Website profil **Montinary** — Rumah Stimulasi berbasis Montessori Islam di Malang.
_Tumbuh Optimal dalam Dekapan Islami._

Website statis (HTML, CSS, JS) yang di-hosting di **GitHub Pages**.

## Struktur

```
.
├── index.html              # Landing page satu halaman
├── css/style.css           # Styling
├── js/main.js              # Interaksi (menu mobile, dll)
├── assets/logo-montinary/  # Logo
├── .nojekyll               # Nonaktifkan proses Jekyll di GitHub Pages
└── CNAME                   # (opsional) domain kustom via Cloudflare
```

## Menjalankan secara lokal

Buka `index.html` langsung di browser, atau jalankan server statis sederhana:

```bash
python3 -m http.server 8000
# lalu buka http://localhost:8000
```

## Deploy ke GitHub Pages

1. Push ke branch `main`.
2. Buka repo di GitHub → **Settings → Pages**.
3. Pada **Build and deployment → Source**, pilih **Deploy from a branch**.
4. Pilih branch `main` dan folder `/ (root)`, lalu **Save**.
5. Tunggu beberapa menit, situs akan tersedia di
   `https://fiardika.github.io/montinary-website/`.

## Menambah foto galeri

Taruh foto di folder `assets/`, lalu ganti elemen placeholder di `index.html`
(bagian `#galeri` dan `#popup`) dengan tag `<img>`:

```html
<div class="gallery-item"><img src="assets/nama-foto.jpg" alt="Deskripsi" /></div>
```

## Kontak

Admin Montinary: 0851-2805-0336 · Jl. Bumi Meranti Wangi G1B
