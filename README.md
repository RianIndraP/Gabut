# 🚀 Cara Menjalankan Proyek Ini

## 🔄 Mode Development

Untuk memulai proyek dalam mode pengembangan (otomatis rebuild saat ada perubahan file), jalankan perintah berikut:

```bash
npm run dev
```

> Mode ini cocok saat kamu sedang aktif mengembangkan aplikasi dan ingin melihat hasil perubahan secara langsung.

## 🏁 Build Produksi

Jika kamu ingin menyiapkan aplikasi untuk deployment (versi final/produksi), gunakan:

```bash
npm run build
```

> Perintah ini akan menghasilkan versi teroptimasi dari aplikasi yang siap untuk diunggah ke server/hosting.

## 🎨 Skema Warna: Light & Dark Mode

| Elemen           | Light Mode             | Dark Mode                  | Catatan                                                                 |
|------------------|------------------------|----------------------------|-------------------------------------------------------------------------|
| Background       | `bg-white`             | `bg-neutral-950`           | `#ffffff` ≈ putih, `#0f0f0f` ≈ `neutral-950`                            |
| Komponen         | `bg-black/20`          | `bg-white/10`              | `rgba(0, 0, 0, 0.2)` dan `rgba(255, 255, 255, 0.1)` tersedia di Tailwind|
| Hover Komponen   | `hover:bg-[#8f00ff]`   | `dark:hover:bg-[#bf5eff]`  | Perlu pakai `hex` karena warna tidak tersedia langsung di Tailwind      |
| Hover Background | `hover:bg-[#8f00ff]`   | `dark:hover:bg-[#bf5eff]`  | Sama seperti di atas                                                    |

