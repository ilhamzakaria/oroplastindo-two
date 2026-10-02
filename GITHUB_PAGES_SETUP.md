# Setup GitHub Pages untuk ORO PLASTINDO

Website Anda sudah berhasil di-push ke GitHub! Sekarang ikuti langkah-langkah berikut untuk mengaktifkan GitHub Pages:

## Langkah-Langkah:

1. **Buka Repository di GitHub**
   - Kunjungi: https://github.com/ilhamzakaria/oroplastindo-two

2. **Masuk ke Settings**
   - Klik tab **Settings** di bagian atas repository
   - Pilih **Pages** dari menu sebelah kiri

3. **Konfigurasi GitHub Pages**
   - Pada bagian "Source", pilih:
     - Branch: **main**
     - Folder: **/ (root)**
   - Klik **Save**

4. **Tunggu Deployment**
   - GitHub akan secara otomatis build dan deploy website Anda
   - Tunggu beberapa menit sampai status berubah menjadi "Your site is live at..."

5. **Akses Website**
   - URL website Anda akan menjadi: `https://ilhamzakaria.github.io/oroplastindo-two/`
   - Atau bisa mengakses langsung ke: `https://ilhamzakaria.github.io/oroplastindo-two/index.html`

## Catatan:
- File `index.html` akan otomatis redirect ke `oroplastindo.html`
- Semua file gambar (.jpg, .png, .jfif) sudah terupload dan akan berfungsi dengan baik
- CSS dan JavaScript internal sudah terintegrasi dalam file HTML

## Update Website di Masa Depan:

Setiap kali Anda ingin update website, cukup:

```bash
# Edit file Anda
git add .
git commit -m "Deskripsi perubahan"
git push origin main
```

GitHub akan otomatis rebuild dan deploy perubahan Anda dalam beberapa menit.

---

**Terima kasih telah menggunakan Kiro untuk membuat website ORO PLASTINDO! 🎉**
