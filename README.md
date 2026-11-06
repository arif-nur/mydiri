# Website Portofolio Pribadi

Website portofolio tema dark menggunakan HTML, CSS, dan JavaScript. Tidak membutuhkan database atau backend.

## Cara menjalankan di VS Code
1. Ekstrak folder `portfolio-dark`.
2. Buka folder tersebut di VS Code.
3. Jalankan `index.html` dengan ekstensi Live Server, atau buka `index.html` langsung di browser.

## Bagian yang perlu kamu edit
Buka `script.js`, lalu ubah isi objek `profileData`:
- `name`, `role`, `intro`: nama dan perkenalan.
- `facts`: domisili, kampus, minat, dan informasi singkat.
- `education`: riwayat pendidikan.
- `experiences`: organisasi, kepanitiaan, pelatihan, atau pengalaman.
- `projects`: proyek/karya.
- `email`, `whatsapp`, `instagram`, `linkedin`: kontak aktif.

Foto ada di folder `assets`. Foto utama menggunakan `assets/foto-utama.png`.
Untuk mengganti foto utama, ganti file tersebut dengan foto baru dan gunakan nama file yang sama.

## Deploy ke GitHub dan Vercel
1. Buat repository baru di GitHub.
2. Upload/push seluruh isi folder ini ke repository (pastikan `index.html` ada di root repository).
3. Login ke Vercel menggunakan akun GitHub.
4. Pilih **Add New → Project**, lalu import repository tadi.
5. Untuk proyek HTML statis ini, Framework Preset pilih **Other**. Build Command dan Output Directory dapat dikosongkan.
6. Klik **Deploy**. Vercel akan memberikan alamat website.

## Catatan
- Jangan masukkan password, token, atau data rahasia ke file publik.
- Periksa kembali informasi kontak sebelum website dipublikasikan.
- Teks pendidikan dan pengalaman yang ada sekarang masih contoh/template, jadi wajib diganti dengan data yang benar.
