# Lab3Web.
Praktikum 4 - CSS Dasar
Praktikum ini membahas mengenai konsep dasar penggunaan CSS (Cascading Style Sheets) dalam pemrograman web, mencakup penggunaan CSS Internal, Inline, dan Eksternal, serta implementasi Selector (Element, ID, dan Class).

📸 Dokumentasi Kode dan Hasil Tampilan
1. Struktur HTML & CSS Internal
Gambar Kode HTML & CSS Internal:
<img width="1920" height="1080" alt="Screenshot 2026-10-10 205107" src="https://github.com/user-attachments/assets/f74f9c31-9ea4-4c26-bb3d-9252666b1772" />


Gambar Tampilan Hasil Browser:
<img width="1920" height="1080" alt="Screenshot 2026-10-10 205042" src="https://github.com/user-attachments/assets/cd1ddf98-33bf-45e8-9300-83fa6c4ff7fe" />

2. Penerapan Inline CSS & Navigation Bar
Gambar Kode Navigasi & Inline CSS:
<img width="1920" height="1080" alt="Screenshot 2026-10-10 205225" src="https://github.com/user-attachments/assets/b6132f22-0ba3-4399-980b-3dadbd0f5710" />
<img width="1920" height="1080" alt="Screenshot 2026-10-10 205621" src="https://github.com/user-attachments/assets/b74308a8-d3d1-405b-b581-b42c9aea0adf" />
<img width="1920" height="1080" alt="Screenshot 2026-10-10 205510" src="https://github.com/user-attachments/assets/ccc83dad-375e-4c85-b9e4-7b6e95e9a17c" />
<img width="1920" height="1080" alt="Screenshot 2026-10-10 205757" src="https://github.com/user-attachments/assets/992d44ad-6738-49d4-a492-c2e79054499e" />


Gambar Tampilan Hasil Navigasi:
<img width="1920" height="1080" alt="Screenshot 2026-10-10 205235" src="https://github.com/user-attachments/assets/5fd3d1da-8786-4649-acb0-098283c96baa" />
<img width="1920" height="1080" alt="Screenshot 2026-10-10 205524" src="https://github.com/user-attachments/assets/985b329b-cd57-44cc-9c97-8485690998de" />
<img width="1920" height="1080" alt="Screenshot 2026-10-10 205813" src="https://github.com/user-attachments/assets/de2d07e3-dad5-44dc-8c81-9b17353a5f48" />
<img width="1920" height="1080" alt="Screenshot 2026-10-10 205637" src="https://github.com/user-attachments/assets/3757a25d-3d48-4490-af32-1a03d10410ec" />


3. Menyisipkan CSS Eksternal
Gambar Kode CSS Eksternal:
<img width="1920" height="1080" alt="Screenshot 2026-10-10 205907" src="https://github.com/user-attachments/assets/2b30d755-84bc-4689-95ca-78ec6960b9ec" />


Gambar Tampilan Hasil Akhir:
<img width="1920" height="1080" alt="Screenshot 2026-10-10 205929" src="https://github.com/user-attachments/assets/e0e2bf2c-dee1-4718-b527-0540c80fe073" />


📝 Pertanyaan dan Tugas Praktikum
1. Eksperimen Properti CSS
Telah dilakukan eksperimen dengan menambahkan beberapa properti CSS dari CSS Cheat Sheet, antara lain:

font-family: Menentukan jenis font ('Open Sans', sans-serif).

padding dan margin: Mengatur jarak dalam dan jarak luar elemen.

background-color: Mengatur warna latar belakang navigasi.

text-decoration: none: Menghilangkan garis bawah pada tautan atau link (a).

:hover: Memberikan efek visual ketika kursor mengarah ke elemen navigasi.

2. Perbedaan Deklarasi h1 { ... } dengan #intro h1 { ... }
h1 { ... } (Element Selector):
Mengatur tampilan seluruh tag  yang ada di dalam dokumen HTML secara universal tanpa terkecuali.

#intro h1 { ... } (Descendant Selector dengan ID):
Hanya mengatur tag  yang berada di dalam elemen yang memiliki id="intro". Tag  di luar elemen #intro tidak akan terpengaruh.

3. Prioritas Penggunaan CSS (Inline, Internal, dan Eksternal)
Jika sebuah elemen diatur menggunakan ketiga metode CSS secara bersamaan, aturan prioritas (Cascading & Specificity) yang berlaku adalah:

Inline CSS (Prioritas Tertinggi)

Internal CSS / Eksternal CSS (Tergantung urutan penulisan paling bawah di dalam tag head)

Contoh:

Di dalam tag head diset CSS Internal: p { color: blue; }

Di dalam elemen HTML diset Inline CSS: Teks ini akan berwarna MERAH.

Penjelasan: Teks paragraf tersebut akan berwarna merah karena Inline CSS memiliki tingkat hirarki dan prioritas paling tinggi dibandingkan Internal maupun Eksternal CSS.

4. Prioritas Selector ID vs Class pada Element ()
Apabila terdapat konflik gaya antara selector ID (#paragraf-1) dan selector Class (.text-paragraf), maka deklarasi dari ID Selector yang akan ditampilkan pada browser.

Penjelasan Nilai Specificity CSS:

ID Selector (#): Memiliki nilai bobot kekhasan 100.

Class Selector (.): Memiliki nilai bobot kekhasan 10.

Karena nilai bobot ID (100) lebih tinggi dari Class (10), aturan pada ID akan mengalahkan aturan pada Class.

Contoh:

ID #paragraf-1 diset berwarna hijau (color: green;).

Class .text-paragraf diset berwarna kuning (color: yellow;).

Penjelasan: Meskipun class diset berwarna kuning, teks pada elemen  tetap akan berwarna hijau karena diatur oleh ID yang memiliki prioritas lebih tinggi.
