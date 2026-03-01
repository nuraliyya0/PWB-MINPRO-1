# Mini Project Portofolio Website
## Nama: Nur Aliyya 
## Nim: 2409116094
## Kelas: Sistem Informasi-C
# Deskripsi
Project ini merupakan website portfolio pribadi yang dibuat menggunakan HTML dan CSS. Website ini bertujuan untuk menampilkan profil diri, kemampuan (skills), pengalaman organisasi, serta sertifikat yang telah diperoleh. Website ini dirancang dengan tampilan sederhana, modern, dan bernuansa pink sesuai dengan preferensi desain pribadi.
# Teknologi yang digunakan
## - HTML
HTML digunakan untuk membangun struktur utama website seperti navbar, beranda, skills, pengalaman, dan sertifikat. 
## - CSS
CSS digunakan untuk mengatur tampilan visual seperti warna, layout, font, serta membuat progress bar dan card agar terlihat rapi dan modern. Seluruh desain dibuat secara manual untuk melatih pemahaman dasar front-end development.
# Struktur setiap tampilan section
## Navbar
Navbar berfungsi sebagai navigasi utama yang menghubungkan setiap section dalam satu halaman menggunakan anchor link.
<img width="1788" height="112" alt="image" src="https://github.com/user-attachments/assets/47cc2538-b604-4004-a034-20be99e12ba0" />

## Section Beranda
Merupakan bagian pembuka yang menampilkan nama lengkap, tagline, deskripsi singkat, serta foto profil. Bagian ini menjadi identitas utama dan kesan pertama dari website portfolio.
<img width="1874" height="869" alt="image" src="https://github.com/user-attachments/assets/6a49d9c5-633a-4fb2-bd90-07c9de58939c" />

## Section Skills
Menampilkan daftar kemampuan dalam bentuk progress bar dengan persentase tertentu. Progress bar dibuat menggunakan elemen div dan pengaturan width pada CSS, sehingga menampilkan visualisasi tingkat penguasaan setiap kemampuan.
<img width="1767" height="437" alt="image" src="https://github.com/user-attachments/assets/b5d8a081-f341-4051-b395-c3ebb689d229" />

## Section Pengalaman
Berisi daftar pengalaman organisasi dan kepanitiaan yang ditampilkan dalam bentuk card. Setiap card memuat gambar kegiatan, nama kegiatan, tahun, serta deskripsi singkat peran yang dijalankan.
<img width="1840" height="860" alt="image" src="https://github.com/user-attachments/assets/e3857c51-23a4-4dc7-ae9c-53e4c383744d" />
<img width="1829" height="849" alt="image" src="https://github.com/user-attachments/assets/8de2fa01-317d-412a-883a-d7c80aeffc49" />
<img width="1852" height="855" alt="image" src="https://github.com/user-attachments/assets/ada42c58-f2fd-4b4c-9d68-7001f6254b32" />

## Section Sertifikat
Menampilkan beberapa sertifikat dalam bentuk card yang berisi gambar, judul, dan tahun. Bagian ini berfungsi untuk menunjukkan pencapaian dan partisipasi dalam kegiatan akademik maupun organisasi.
<img width="1831" height="831" alt="image" src="https://github.com/user-attachments/assets/e052d3f9-cd1e-4d13-af38-889f7e1ed78d" />

## Footer 
Penjelasan paling bawah, Di isi dengan nama dan penjelasan singkat

# Struktur Folder
<img width="243" height="362" alt="image" src="https://github.com/user-attachments/assets/3ae49b2b-5a64-49cc-af86-1a30fb8b2a52" />

# Penjelasan Code
## Navbar
Digunakan elemen <nav> dengan class navbar yang berisi logo dan menu navigasi. Menu dibuat menggunakan tag <a> dengan anchor link yang mengarah ke id setiap section, sehingga pengguna dapat berpindah ke bagian tertentu dalam satu halaman. Styling pada CSS menggunakan Flexbox untuk mengatur posisi logo dan menu agar sejajar serta terlihat rapi.

<img width="518" height="234" alt="image" src="https://github.com/user-attachments/assets/c8564e86-3a3e-48a8-88c1-515be36bfdc5" />

## Section Beranda
Dengan id dan class tertentu untuk memisahkan bagian pembuka website. Di dalamnya terdapat untuk nama, untuk tagline, untuk deskripsi, Dan ntuk foto profil. CSS digunakan untuk mengatur ukuran gambar agar tidak terlalu besar, membuatnya berbentuk bulat dengan border-radius, serta mengatur teks agar berada di tengah.
<img width="1015" height="446" alt="image" src="https://github.com/user-attachments/assets/3987cc80-5e9a-4314-ad1d-00220857479b" />

## Section Skills
Setiap skill dibuat menggunakan container <div> yang berisi nama skill dan persentase. Progress bar dibuat dari elemen <div> bertingkat, di mana bagian dalamnya diberi width sesuai persentase pada atribut style. CSS mengatur warna, tinggi, dan bentuk progress bar agar terlihat seperti indikator kemampuan.
<img width="978" height="766" alt="image" src="https://github.com/user-attachments/assets/43cda119-a88c-4211-9d28-e4a6e9453136" />

## Section Pengalaman
Pada section Pengalaman, setiap pengalaman ditampilkan dalam bentuk card menggunakan <div class="exp-card">. Di dalamnya terdapat gambar kegiatan dan deskripsi yang dibungkus dalam container lain. Layout menggunakan Flexbox agar gambar dan teks bisa sejajar, sementara CSS menambahkan shadow dan border-radius agar tampilan lebih modern.
<img width="902" height="796" alt="image" src="https://github.com/user-attachments/assets/82e0d6a8-b7e5-4dc3-8dca-bf9904e048cf" />
<img width="1014" height="721" alt="image" src="https://github.com/user-attachments/assets/73af2276-e163-486c-8e3b-4bfc49c1c9e9" />
<img width="1024" height="254" alt="image" src="https://github.com/user-attachments/assets/7fa1b757-46f0-4405-8803-9447f3a5784f" />

## Section Sertifikat
Digunakan struktur card yang hampir sama dengan pengalaman, tetapi ditampilkan dalam bentuk grid atau flex agar beberapa sertifikat dapat tersusun rapi dalam satu baris. Setiap card berisi gambar, judul, dan tahun sertifikat. CSS digunakan untuk mengatur ukuran gambar dan jarak antar card.
<img width="1011" height="678" alt="image" src="https://github.com/user-attachments/assets/f8441eba-648b-4a95-89f2-900f88756143" />
<img width="1005" height="217" alt="image" src="https://github.com/user-attachments/assets/0bf2cf1d-0add-41c7-a896-62422dad86c4" />

## Flooter
bagian footer menggunakan tag <footer> untuk menampilkan informasi copyright di bagian bawah halaman. CSS mengatur posisi, warna, dan perataan teks agar terlihat sederhana dan konsisten dengan tema website.
<img width="953" height="115" alt="image" src="https://github.com/user-attachments/assets/a5b4aae6-043e-4ff3-bf43-2011922c8deb" />


