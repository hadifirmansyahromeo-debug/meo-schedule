# meo schedule

website sederhana untuk membuat dan mengatur jadwal pelajaran sekolah.

## fitur

- memilih mata pelajaran yang tersedia atau menambahkan nama pelajaran sendiri
- mengatur hari, jam mulai, dan jam selesai
- menambahkan ruang kelas atau catatan
- mengedit dan menghapus jadwal
- memfilter jadwal berdasarkan hari
- menyimpan jadwal otomatis di browser menggunakan `localStorage`
- tampilan responsif untuk HP dan desktop

## cara menjalankan secara lokal

1. download `index.html`.
2. simpan file di folder proyek.
3. buka `index.html` menggunakan browser.

## cara deploy dengan GitHub Pages

1. buat repository baru di GitHub, misalnya `meo-schedule`.
2. upload `index.html` dan `README.md` ke root repository.
3. buka **Settings → Pages**.
4. pada bagian **Build and deployment**, pilih **Deploy from a branch**.
5. pilih branch `main` dan folder `/ (root)`, lalu klik **Save**.
6. tunggu proses deployment selesai. URL website akan muncul di halaman GitHub Pages.

## catatan penyimpanan

Jadwal disimpan secara lokal di browser melalui `localStorage`. Artinya, data tidak otomatis tersinkron ke perangkat lain dan dapat hilang jika data situs/browser dihapus.

## teknologi

- HTML
- CSS
- JavaScript

## lisensi

Bebas digunakan dan dimodifikasi untuk kebutuhan pribadi.
