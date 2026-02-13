# project-1397/IF-25 — Teknik Informatika

Situs statis profil angkatan **TI 2025**: kumpulan halaman HTML sederhana untuk menampilkan informasi tentang angkatan, anggota, proyek, dan blog.

## Tentang

Project ini dibuat sebagai situs profil untuk angkatan Teknik Informatika. Konten utama meliputi halaman: `index.html`, `about.html`, `projects.html`, `members.html`, dan `blog.html`. Situs ini merupakan karya komunitas mahasiswa **Universitas Nurul Jadid** (lihat footer pada halaman).

---

## Fitur

* Halaman statis (HTML/CSS/JS) untuk:

  * Beranda (landing)
  * Tentang angkatan
  * Daftar proyek (showcase)
  * Daftar anggota
  * Blog singkat
* Struktur sederhana yang mudah dikembangkan oleh mahasiswa
* Lisensi: GPL-3.0

---

## Teknologi

* HTML
* CSS (folder `css/`)
* JavaScript (folder `js/`)
* Asset statis (folder `assets/`)

---

## Cara Menjalankan (lokal)

Sangat sederhana—cukup buka file `index.html` di browser, atau jalankan server statis untuk fitur relatif path:

1. Clone repositori:

```bash
git clone https://github.com/project-1397/IF-25.git
cd IF-25
```

2. Cara cepat (buka langsung):

* Buka `index.html` di browser.

3. Cara menggunakan server lokal (direkomendasikan):

* Dengan Python 3:

```bash
python -m http.server 8000
# lalu buka http://localhost:8000
```

* Atau gunakan ekstensi Live Server (VS Code) untuk live reload saat mengedit.

---

## Struktur Direktori (singkat)

```
/assets/      # gambar, icon, dll
/blog/        # konten blog (jika ada pengelolaan terpisah)
css/          # stylesheet
js/           # javascript
index.html
about.html
projects.html
members.html
blog.html
LICENSE
README.md
```

---

## Cara Mengedit / Kustomisasi

* Ubah teks halaman pada file HTML di root (`index.html`, `about.html`, dsb).
* Ganti gambar di `assets/` dan ubah referensi di HTML.
* Tambah anggota/proyek pada `members.html` / `projects.html`.
* Jika ingin mengubah styling global, edit file di `css/`.

---

## Deploy

Beberapa opsi cepat:

* **GitHub Pages**:

  * Masuk ke *Settings* → *Pages* pada repositori GitHub dan pilih branch `main` (atau `gh-pages`) sebagai sumber.
* **Netlify / Vercel / Surge**:

  * Koneksikan repo ke layanan tersebut dan deploy sebagai situs statis.

---

## Kontribusi

1. Fork repo.
2. Buat branch fitur: `git checkout -b fix/update-profile`
3. Commit perubahan: `git commit -m "Perbarui halaman anggota"`
4. Push dan buat Pull Request.

Atau untuk perubahan kecil, buka tab **Issues** di repositori dan ajukan permintaan/perubahan yang diinginkan.

---

## Lisensi

Project ini dilisensikan di bawah **GPL-3.0**. Lihat file `LICENSE` untuk detail.

---

## Kontak / Pertanyaan

* Gunakan fitur **Issues** pada repositori untuk melaporkan bug, request fitur, atau pertanyaan.
* Untuk kontribusi tim, sebutkan peran dan perubahan yang ingin diajukan pada PR.

---
