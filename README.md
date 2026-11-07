# Kelok Nona Rental dan Wisata

Website company profile Kelok Nona, Solusi Rental & Wisata Anda, Jalan Tua Pejat - Rokot KM 12, Mentawai.

Website ini statis (HTML dan CSS saja), jadi tidak perlu install apa pun dan tidak ada proses build.

## Isi folder

- `index.html` : isi halaman
- `style.css` : tampilan
- `assets/` : logo dan foto
- `favicon.svg` : ikon di tab browser
- `vercel.json` : pengaturan Vercel

## Cara melihat di komputer

Klik dua kali `index.html`, atau jalankan `npx serve` di folder ini.

## Cara upload ke GitHub

Lewat situs (paling mudah):

1. Login ke github.com, klik **New repository**, beri nama, misalnya `kelok-nona`, lalu **Create repository**.
2. Klik **uploading an existing file**, tarik semua isi folder ini (termasuk folder `assets`), lalu klik **Commit changes**.

Lewat terminal:

```bash
git init
git add .
git commit -m "Website Kelok Nona"
git branch -M main
git remote add origin https://github.com/USERNAME/kelok-nona.git
git push -u origin main
```

Ganti `USERNAME` dengan nama akun GitHub kamu.

## Cara hosting di Vercel

1. Login ke vercel.com dengan akun GitHub.
2. Klik **Add New**, pilih **Project**, lalu **Import** repository `kelok-nona`.
3. Pada **Framework Preset** pilih **Other**. Kosongkan Build Command dan Output Directory.
4. Klik **Deploy**. Dalam beberapa detik website langsung online di alamat `nama-proyek.vercel.app`.

Setiap kali kamu mengubah file di GitHub, Vercel otomatis memperbarui website.

## Pakai domain sendiri

Di Vercel buka **Settings**, lalu **Domains**, tambahkan domain kamu dan ikuti petunjuk DNS yang muncul.

## Mengubah isi

- Nomor WhatsApp: cari `6285264101818` dan `0852 6410 1818` di `index.html`.
- Alamat: cari `Jalan Tua Pejat` di `index.html`.
- Teks tentang kami, layanan, dan keunggulan: ada di `index.html`.
- Warna: ada di bagian `:root` di `style.css`.
- Foto: ganti file di folder `assets` dengan nama yang sama.
