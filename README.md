# Portofolio Website Alvionej Resna Lawrend Pandiangan | 2409116073

## Deskripsi
Sebuah website portofolio pribadi yang dibangun dengan HTML, CSS, Bootstrap 5, dan Vue JS untuk menyajikan informasi profil, keahlian, pengalaman, dan sertifikat secara responsif dan informatif.

## 1. Struktur File

```plaintext
MINI_PROJECT_1_PBW/
│
├── index.html
├── style.css
└── img/
    ├── aplikasi.jpg
    ├── foto_profile.jpeg
    ├── insevent.jpg
    └── upgrading.png
```

## 2. Teknologi yang digunakan:

- index.html → halaman utama website
- style.css → styling tambahan (custom CSS)
- img/ → semua gambar (profil, sertifikat, proyek, dll)

## 3. Tampilan Setiap Section / Fitur
 
 ### - home
 
 <img width="935" height="494" alt="image" src="https://github.com/user-attachments/assets/ae698828-5ae1-4cdb-82d0-e79e89c54245" />

  - kode:
```plaintext
  <section id="home" class="hero">
      <div class="container hero-content">
        <h1>Hello, I’m Lawrend</h1>
        <p>
          Information Systems student with a passion for structured systems and efficient solutions.
        </p>
      </div>
    </section>
```
Penjelasan Kode:
Section ini merupakan bagian Home (Hero Section) pada website portofolio yang berfungsi sebagai tampilan pembuka. Di dalam section ini terdapat elemen judul (h1) yang menampilkan nama pemilik website serta elemen  paragraf (p) yang berisi deskripsi singkat atau tagline. Class hero digunakan untuk memberikan styling khusus pada bagian ini, seperti pengaturan tinggi section, background, dan tampilan visual lainnya. Class container berfungsi untuk membatasi lebar konten agar tetap rapi dan terpusat sesuai standar layout Bootstrap. Sementara itu, class hero-content digunakan untuk pengaturan tambahan seperti perataan teks dan spasi antar elemen.

 ### About Me

 <img width="929" height="556" alt="image" src="https://github.com/user-attachments/assets/024d24eb-5a40-47c0-8ca6-87adfc35bcfe" />

  - kode:
```plaintext
  <section id="about" class="section">
      <div class="container">
        <h2 class="section-title">About Me</h2>

        <div class="row align-items-center gx-5 gy-4">
          <div class="col-12 col-md-4 text-center pe-md-4">
            <img
              src="img/foto profile.jpeg"
              alt="Loren"
              class="img-fluid rounded shadow-sm"
            />
          </div>

          <div class="col-12 col-md-8 text-start">
            <p>
            <p>
              I’m an Information Systems student who likes things to be planned and well-organized.
              I have experience working as a Public Relations officer in several organizational activities,
              and I’ve also served as a coordinator in an organization.
            </p>

            <p>
              Outside of my academic and organizational life, I enjoy singing and cooking.
              Singing makes me happy because it helps me express myself.
              I also really enjoy cooking, especially when I can cook for other people and see them enjoy my food.
            </p>

            <p>
              My goal is to become a Database Administrator (DBA),
              while continuing to grow and explore other skills and interests.
            </p>
          </div>
        </div>
      </div>
    </section>
```
Penjelasan Kode:
Section ini merupakan bagian (About Me) yang berfungsi untuk menampilkan informasi singkat mengenai profil dan latar belakang pemilik website. Section ini dibungkus dengan elemen (section) yang memiliki atribut (id="about") sehingga dapat diakses melalui navigasi, serta class (section) yang digunakan untuk pengaturan gaya secara konsisten.

Di dalam section ini terdapat elemen (div) dengan class (container) yang berfungsi sebagai pembatas lebar konten agar tampilan tetap rapi dan terpusat. Judul bagian ditampilkan menggunakan elemen (h2) dengan class (section-title) untuk memberikan penekanan visual pada judul (About Me).

Layout konten disusun menggunakan (Bootstrap Grid System) dengan elemen (row) yang dikombinasikan dengan class (align-items-center) agar konten sejajar secara vertikal. Class (gx-5) dan (gy-4) digunakan untuk mengatur jarak horizontal dan vertikal antar kolom sehingga tampilan lebih proporsional.

Bagian kiri menggunakan kolom (col-12 col-md-4) untuk menampilkan foto profil. Pada ukuran layar kecil, foto akan ditampilkan memenuhi satu baris, sedangkan pada ukuran layar menengah ke atas akan menempati empat kolom. Gambar menggunakan class (img-fluid) agar bersifat responsif serta class (rounded) dan (shadow-sm) untuk memberikan tampilan yang rapi dan profesional.

Bagian kanan menggunakan kolom (col-12 col-md-8) yang berisi beberapa paragraf deskripsi diri. Konten ini menjelaskan latar belakang akademik, pengalaman organisasi, hobi, serta tujuan karier pemilik website. Dengan pembagian kolom tersebut, informasi dapat disampaikan secara jelas dan mudah dibaca pada berbagai ukuran layar.






