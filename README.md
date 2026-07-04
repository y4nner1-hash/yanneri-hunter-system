# Yanneri Hunter System

Solo Leveling–themed interactive HUD/dashboard, dibangun dengan React + Tailwind CSS (via CDN), dikemas sebagai single-file HTML.

## 🚀 Cara Menjalankan

**Opsi 1 — Langsung buka di browser:**
Cukup buka `index.html` di browser mana pun. Tidak perlu instalasi apa pun.

**Opsi 2 — GitHub Pages (akses via link publik):**
1. Push repo ini ke GitHub.
2. Buka **Settings > Pages** di repo.
3. Pilih source: `Deploy from a branch` → branch `main` → folder `/ (root)`.
4. Simpan. Dalam 1–2 menit, situs akan aktif di:
   `https://<username-kamu>.github.io/yanneri-hunter-system/`

## 📁 Struktur

```
yanneri-hunter-system/
├── index.html      # Aplikasi utama (React + Tailwind, semua dalam 1 file)
├── README.md
└── .gitignore
```

## 🛠️ Tech Stack

- React 18 (CDN, production build)
- Tailwind CSS (CDN)
- Vanilla JS, tanpa build step

## 📝 Catatan

File ini murni client-side — tidak ada backend/database. Cocok untuk hosting statis (GitHub Pages, Netlify, Vercel, dll).
