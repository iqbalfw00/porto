# Portfolio Site

Struktur:
```
├── index.html      # Halaman utama portofolio
├── roblox.html      # Showcase project Roblox hangout game
└── images/            # Taruh foto screenshot di sini
```

## Cara deploy ke GitHub Pages

1. Buat repo baru di GitHub, misal `portfolio`
2. Upload semua isi folder ini (index.html, roblox.html, folder images/) ke repo tersebut
   - Bisa lewat web: klik **Add file → Upload files**, drag semua file & folder
   - Atau lewat git:
     ```bash
     git init
     git add .
     git commit -m "Initial site"
     git remote add origin https://github.com/iqbalfw00/portfolio.git
     git push -u origin main
     ```
3. Di repo, buka **Settings → Pages**
4. Di bagian "Build and deployment", pilih Source: **Deploy from a branch**
5. Branch: `main`, folder: `/ (root)` → **Save**
6. Tunggu ~1 menit, situs live di:
   `https://iqbalfw00.github.io/portfolio/`
   dan halaman Roblox di:
   `https://iqbalfw00.github.io/portfolio/roblox.html`

## Update setelah live

Setiap kali edit file (misal tambah foto), upload ulang / push lagi ke repo yang sama —
GitHub Pages otomatis re-deploy dalam ~1 menit, tidak perlu setting ulang.
