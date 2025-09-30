# ChargeHub - Full Offline Website

Website e-commerce ChargeHub kini telah dikonfigurasi untuk berjalan sepenuhnya offline tanpa ketergantungan pada resource online.

## 🔧 **Perubahan yang Dilakukan**

### **Asset Offline**
- ✅ **Font Poppins**: Semua weight yang diperlukan (300, 400, 500, 600, 700, 800)
- ✅ **FontAwesome Icons**: Solid, Regular, dan Brands icons
- ✅ **Pure HTML5 & CSS**: Tidak ada JavaScript

### **Struktur Folder Asset**
```
src/
├── fonts/
│   ├── poppins.css
│   ├── Poppins-Light.woff2 (300)
│   ├── Poppins-Regular.woff2 (400)
│   ├── Poppins-Medium.woff2 (500)
│   ├── Poppins-SemiBold.woff2 (600)
│   ├── Poppins-Bold.woff2 (700)
│   └── Poppins-ExtraBold.woff2 (800)
├── icons/
│   ├── fontawesome.css
│   ├── fa-solid-900.woff2
│   ├── fa-regular-400.woff2
│   └── fa-brands-400.woff2
├── css/
│   ├── main.css
│   ├── products.css
│   ├── about.css
│   └── contact.css
└── img/
    └── [placeholder images]
```

### **File yang Diupdate**
1. **index.html** - Halaman utama dengan hero section dan showcase
2. **products.html** - Katalog produk charger
3. **about.html** - Informasi perusahaan dan nilai-nilai
4. **contact.html** - Kontak dan FAQ

## 🎨 **Tema USSR-Bakti**
- **Font**: Poppins (menggantikan Inter/sistem font)
- **Warna Utama**: #05595b (teal)
- **Warna Sekunder**: #e9eeee (light cream)  
- **Warna Aksen**: #e2d784 (gold)
- **Teks**: #062c30 (dark teal)

## 🚀 **Menjalankan Website**
1. Buka file `index.html` di browser
2. Semua asset akan dimuat dari folder lokal
3. Tidak memerlukan koneksi internet

## 📱 **Fitur**
- Responsive design untuk semua ukuran layar
- Navigation menu dengan hover effects
- Product showcase dengan rating bintang
- Contact form (static, tanpa JavaScript)
- FontAwesome icons untuk UX yang lebih baik
- Optimized untuk performa offline

## 🔄 **Migrasi dari Online ke Offline**
- ❌ **Sebelum**: Google Fonts CDN, FontAwesome Kit
- ✅ **Sesudah**: Local fonts, local icons
- 🎯 **Hasil**: Website 100% offline ready

Website ini sekarang dapat berjalan tanpa koneksi internet dan siap untuk deployment di environment offline manapun.