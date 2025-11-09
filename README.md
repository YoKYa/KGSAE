# 🥥 Landing Page UMKM — **KGSAE (Klepon Gempo SAE)**

Landing page sederhana untuk promosi UMKM **Klepon & Gempo SAE**.  
Dibuat ringan dan responsif menggunakan **HTML, CSS, dan Bootstrap** — cocok untuk campaign produk, pengenalan brand, dan konversi pesanan via CTA (mis. WhatsApp).

Repo: `YoKYa/KGSAE`

---

## ✨ Fitur Utama

- ✅ **Hero Section** dengan headline, subheadline, harga, dan tombol **Pesan Sekarang**
- ✅ **Navigasi**: Beranda, Tentang, Jajanan, Testimoni, FAQ, Kontak
- ✅ **Section Produk/Jajanan** (grid/list) + deskripsi singkat
- ✅ **Section Testimoni** pelanggan
- ✅ **FAQ** (pertanyaan umum seputar produk & pemesanan)
- ✅ **Kontak** & CTA (WhatsApp / Telepon / Maps)
- ✅ **Responsif** (mobile–tablet–desktop) berbasis Bootstrap
- ✅ Tanpa framework JS tambahan — mudah dipelihara

> *Opsional:* Tambahkan integrasi formulir pemesanan (Google Form) atau link langsung ke **WhatsApp**.

---

## 🧱 Teknologi

- **HTML5**
- **CSS3**
- **Bootstrap 5** (Grid, Utilities, Components)
- *(Opsional)* JavaScript untuk interaksi tambahan

---

## 🚀 Cara Menjalankan

Tidak butuh server khusus. Cukup buka `index.html`.

```bash
# 1) Clone repo
git clone https://github.com/YoKYa/KGSAE.git
cd KGSAE

# 2) Buka file
# - Double click index.html, atau
# - (opsional) gunakan Live Server (VS Code)
```

---

## 📂 Struktur Direktori (Ringkas)

```
KGSAE/
├─ index.html
├─ /assets
│  ├─ /css/        # style.css, bootstrap.min.css (opsional/CDN)
│  ├─ /img/        # gambar produk, logo
│  └─ /js/         # script opsional (mis. interaksi FAQ)
└─ README.md
```

> Penamaan folder bisa disesuaikan — pastikan path di `index.html` mengikuti struktur yang dipakai.

---

## 🧩 Kustomisasi Cepat

1. **Ganti Branding** (nama, logo) pada bagian `<nav>` & hero `index.html`
2. **Ubah Warna/typography** di `assets/css/style.css` (mis. warna hijau/oranye brand KGSAE)
3. **Kelola Produk/Jajanan** pada section `#jajanan`
4. **Perbarui CTA** (tujuan tombol “Pesan Sekarang” → WhatsApp/Marketplace)
5. **Isi Testimoni & FAQ** sesuai konten UMKM
6. *(Opsional)* Tambahkan Schema.org (LocalBusiness) untuk SEO lokal

**Contoh pemasangan Bootstrap (CDN):**

```html
<!-- Bootstrap CSS -->
<link
  href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css"
  rel="stylesheet">

<!-- Bootstrap JS Bundle (opsional) -->
<script
  src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js">
</script>
```

---

## 📜 Lisensi

Proyek ini bersifat **open‑source**. Silakan modifikasi untuk kebutuhan promosi UMKM Anda.

---

Jika landing page ini bermanfaat, jangan lupa beri ⭐ di GitHub!  
**KGSAE — Klepon & Gempo SAE: Kehangatan Tradisi dalam Setiap Sajian.**
