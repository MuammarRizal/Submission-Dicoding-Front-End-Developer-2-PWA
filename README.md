# Submission Front-end Developer Expert 2 dan PWA

### Fitur yang harus ada / Kriteria yang harus dipenuhi

<details>
  <summary>Syarat</summary>
  <ol>
    <li>
      Halaman Utama (Daftar Restoran)
      <ul>
        <li>Menampilkan daftar restoran yang datanya bersumber dari API https://restaurant-api.dicoding.dev/. Silakan lihat dokumentasinya pada halaman tersebut.</li>
        <li>Wajib menampilkan nama, gambar dan minimal salah satu diantara kota, rating, dan atau deskripsi pada restoran.</li>
        <li>Terdapat tautan/CTA yang mengarah ke detail restoran pada tiap itemnya.</li>
        <li>Hero elemen tetap dipertahankan.</li>
      </ul>
    </li>
    <li>
      Halaman Detail Restoran
      <ul>
        <li>Menampilkan detail dari restoran yang dipilih dari halaman utama (daftar restoran) atau halaman favorit restoran.</li>
        <li>
        Pada halaman detail restoran harus terdapat:
            <ul>
                <li>Nama Restoran</li>
                <li>Gambar</li>
                <li>Alamat</li>
                <li>Kota</li>
                <li>Deskripsi</li>
                <li>Menu Makanan</li>
                <li>Menu Minuman</li>
                <li>Customer Reviews</li>
            </ul>
        </li>
        <li>Terdapat tombol favorite untuk memasukkan atau menghapus restoran favorit dari database (gunakan IndexedDB).</li>
      </ul>
    </li>
    <li>
    Daftar Restoran
        <ul>
            <li>Menampilkan daftar restoran berdasarkan data yang sudah disediakan di dalam project starter (src → DATA.json), untuk menampilkannya boleh melalui cara hardcoded di berkas HTML, atau menggunakan DOM manipulation menggunakan JavaScript.</li>
            <li>Wajib menampilkan nama, gambar dan minimal salah satu diantara kota, rating, dan atau deskripsi pada restoran.</li>
        </ul>
    </li>
    <li>
    Halaman Daftar Restoran Favorit
        <ul>
            <li>Halaman Daftar Restoran dapat diakses melalui menu navigasi favorit.</li>
            <li>Menampilkan restoran yang difavoritkan oleh pengguna (data diambil dari indexedDB).</li>
            <li>Wajib menampilkan nama, gambar dan minimal salah satu diantara kota, rating, dan atau deskripsi pada restoran.</li>
            <li>Terdapat tautan/CTA yang mengarah ke detail restoran pada tiap itemnya.</li>
        </ul>
    </li>
    <li>
    Native Capability
        <ul>
            <li>Aplikasi dapat diakses dalam keadaan offline tanpa ada aset yang gagal dimuat, termasuk data yang didapatkan dari API. Anda bebas menggunakan strategi caching apapun, bahkan menggunakan workbox.</li>
            <li>Aplikasi harus menampilkan icon Add to Home Screen.</li>
            <li>Aplikasi memiliki custom icon yang ditampilkan pada home screen dan splash screen.</li>
        </ul>
    </li>
    <li>
    Code Quality
        <ul>
            <li>Menggunakan ESLint sebagai linter ketika menuliskan kode JavaScript. Harap lampirkan berkas konfigurasi ESLint ya.</li>
            <li>Menerapkan salah satu style guide baik itu Google JavaScript Code Style, AirBnB JavaScript Code Style, atau StandardJS Code Style.</li>
            <li>Periksa kembali sebelum mengirimkan submission, apakah project yang Anda kirimkan sesuai dengan kriteria yang ditetapkan atau tidak, ditandai dengan tidak adanya satupun error ketika menjalankan eslint.</li>
        </ul>
    </li>
    <li>Pertahankan syarat yang ada pada submission sebelumnya. Seperti responsibilitas tampilan, aksesibilitas pada website, appbar, footer dan sebagainya.</li>
  </ol>

- Catatan
  <ul>
    <li>Dalam mengerjakan submission ini, Anda tidak diperkenankan menggunakan css framework (seperti Bootstrap, Materialize, Tailwind, dll) yang dapat membantu dalam menyusun tampilan yang responsif. Tuliskan kode CSS from scratch, sistem layouting CSS murni saat ini sudah cukup powerful untuk membuat tampilan website responsif.</li>
  </ul>
</details>

### Pada aplikasi Katalog restoran ini saya menerapkan dan telah menerapkan semua kriteria

    1. Menggunakan ESLint sebagai linter ketika menuliskan kode JavaScript (Using ESLint).
    2. Membuat website dengan arsitektur Application Shell (Practice: Application Shell).
    3. Menerapkan Web App Manifest (Practice: Web App Manifest).
    4. Menerapkan Service Worker (Practice: Service Worker).
    5. Menerapkan Cache API pada Service Worker (Practice: Cache API).
    6. Menggunakan IndexedDB untuk menyimpan data dalam bentuk objek (Practice: IndexedDB).
    7. Serta menerapkan WebSocket dan Notification (Practice: Web Socket & Notification).

### Dokumentasi

1. Clone repository ini

```bash
    git clone https://github.com/MuammarRizal/Submission-Dicoding-Front-End-Developer-Expert-2-pwa.git
```

2. Masuk ke folder Submission Dicoding Front End Developer Expert 2 pwa

```bash
    cd Submission Dicoding Front End Developer Expert 2 pwa
```

3. Install Dependencies

```bash
    $ npm install
```

4. Build App

```bash
    $ npm run build
```

5. Jalankan dalam mode Development

```bash
    $ npm run start-dev
```
