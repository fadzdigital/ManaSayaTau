```markdown
# Pesanan Digital Automation Tools

Proyek ini dirancang untuk membantu para **seller digital** mengelola pesanan di marketplace, seperti pengisian data pesanan, kalkulasi harga, dan penghitungan penghasilan bersih. Tools ini dirancang ringan dan tidak mencatat aktivitas pengguna, sehingga menjamin privasi seller.

## Fitur Utama

### 1. **Salin Data Pesanan**
- Mengisi nomor resi, nomor pesanan, dan email seller.
- Menyalin informasi pesanan ke clipboard.
- Membuka halaman Shopee Seller Center secara otomatis.

### 2. **Hitung Total Harga Produk**
- Menghitung total harga produk sebelum dan sesudah dikenakan biaya admin Shopee (8% dari harga total).
- Menampilkan hasil perhitungan secara langsung di layar.

### 3. **Hitung Penghasilan Bersih**
- Menghitung penghasilan bersih setelah dipotong biaya admin Shopee.
- Menampilkan total penghasilan bersih dan biaya admin.

### 4. **Hitung Harga Satuan**
- Menghitung harga satuan sebelum dan sesudah dikenakan biaya admin Shopee.
- Menampilkan perbedaan harga karena potongan biaya admin untuk setiap produk.

### 5. **Animasi Responsif**
- Animasi interaktif seperti efek hover, loading spinner, dan transisi saat melakukan kalkulasi.
- Memberikan pengalaman pengguna yang lebih menarik dan modern.

---

## Struktur Proyek

```
📦 Pesanan-Digital-Automation-Tools
├── index.html          # Halaman utama (HTML)
├── styles.css          # File CSS untuk styling
├── script.js           # File JavaScript untuk logika
└── README.md           # Dokumentasi proyek
```

---

## Cara Menggunakan

1. **Clone Repository**  
   Jalankan perintah berikut untuk meng-clone repository ke perangkat Anda:
   ```bash
   git clone https://github.com/username/pesanan-digital-tools.git
   cd pesanan-digital-tools
   ```

2. **Buka di Browser**  
   Buka file `index.html` di browser Anda untuk mulai menggunakan aplikasi.

3. **Fungsi Utama**  
   - Isi data pada input yang tersedia.
   - Klik tombol yang sesuai untuk melakukan aksi seperti menyalin data atau menghitung harga.

---

## Teknologi yang Digunakan

- **HTML**: Untuk struktur halaman.
- **CSS**: Untuk memberikan tampilan menarik, termasuk animasi responsif.
- **JavaScript**: Untuk logika aplikasi seperti kalkulasi otomatis dan navigasi.

---

## Keamanan dan Privasi

- **Tidak mencatat aktivitas pengguna**: Website ini hanya melakukan kalkulasi lokal di browser dan tidak mengirimkan data ke server atau menyimpan aktivitas pengguna.
- **Privasi seller terjamin**: Semua informasi yang dimasukkan hanya digunakan sementara di sisi pengguna.

---

## Preview

![Screenshot](https://via.placeholder.com/800x400?text=Preview+Pesanan+Digital+Automation+Tools)

---

## Kontribusi

Kami menyambut kontribusi dari siapa saja! Untuk berkontribusi:
1. Fork repository ini.
2. Buat branch baru untuk fitur atau perbaikan Anda.
3. Ajukan pull request setelah selesai.

---

## Lisensi

Proyek ini dilisensikan di bawah [MIT License](LICENSE).

---

**Dibuat dengan ❤️ untuk membantu seller digital.**
```

---

### Tambahan Animasi pada **CSS**

Untuk mempercantik tampilan, berikut adalah beberapa animasi tambahan yang dapat Anda gunakan pada file `styles.css`:

```css
/* Animasi Hover pada Tombol */
button {
    transition: background-color 0.3s ease, transform 0.2s ease;
}

button:hover {
    background-color: #f39c12;
    transform: scale(1.05);
}

/* Animasi Loading */
#loading {
    display: none;
    position: fixed;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    background-color: rgba(0, 0, 0, 0.8);
    display: flex;
    justify-content: center;
    align-items: center;
    z-index: 1000;
}

.spinner {
    width: 40px;
    height: 40px;
    border: 5px solid rgba(255, 255, 255, 0.3);
    border-top: 5px solid #ffcc00;
    border-radius: 50%;
    animation: spin 1s linear infinite;
}

@keyframes spin {
    from {
        transform: rotate(0deg);
    }
    to {
        transform: rotate(360deg);
    }
}
```
