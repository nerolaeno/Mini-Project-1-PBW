# 💻 Portofolio Website Alvionej Resna Lawrend Pandiangan | 2409116073

## 📝Deskripsi
Sebuah website portofolio pribadi yang dibangun dengan HTML, CSS, Bootstrap, dan Vue JS untuk menyajikan informasi profil, keahlian, pengalaman, dan sertifikat secara responsif dan informatif.

## 📁1. Struktur Project

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

## 🛠️2. Teknologi yang digunakan:

- index.html → halaman utama website
- style.css → styling tambahan (custom CSS)
- img/ → semua gambar (profil, sertifikat, proyek, dll)

## 🧩3. Tampilan Setiap Section / Fitur
 
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

 ### - About Me

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
Section ini merupakan bagian (About Me) yang berfungsi untuk menampilkan informasi profil dan latar belakang pemilik website. Section dibungkus dengan elemen (section) yang memiliki atribut (id="about") dan class (section) agar dapat diakses melalui navigasi serta menjaga konsistensi tampilan. Konten ditempatkan di dalam elemen (container) untuk membatasi lebar tampilan, dengan judul menggunakan elemen (h2) dan class (section-title). Layout disusun menggunakan (Bootstrap Grid System) dengan elemen (row) serta class (align-items-center), (gx-5), dan (gy-4) untuk pengaturan jarak dan perataan. Bagian kiri menggunakan kolom (col-12 col-md-4) untuk menampilkan foto profil yang responsif dengan class (img-fluid), (rounded), dan (shadow-sm), sedangkan bagian kanan menggunakan kolom (col-12 col-md-8) untuk menampilkan deskripsi diri yang mencakup latar belakang akademik, pengalaman, hobi, dan tujuan karier secara jelas dan mudah dibaca.

### - Skill

<img width="935" height="578" alt="image" src="https://github.com/user-attachments/assets/edf7d9e6-52e2-41b0-80e0-22b02ffe9dfa" />

- kode:
  ```plaintext
  <section id="skills" class="section bg-strawberry">
      <div class="container">
        <h2 class="section-title">Skills</h2>

        <div class="skills-container">
          <div class="skill-item">
            <span>Public Relations</span>
            <div class="progress-bar">
              <div class="progress-fill" style="width: 95%"></div>
            </div>
          </div>

          <div class="skill-item">
            <span>Database Developer</span>
            <div class="progress-bar">
              <div class="progress-fill" style="width: 70%"></div>
            </div>
          </div>

          <div class="skill-item">
            <span>Design</span>
            <div class="progress-bar">
              <div class="progress-fill" style="width: 80%"></div>
            </div>
          </div>
        </div>

        <div class="experience">
          <h3>Experience</h3>
          <ul>
            <li>Public Relations Coordinator – INFORSA Mengabdi 2025</li>
            <li>Public Relations Member – INSEVENT 2025</li>
            <li>Event Members – Upgrading INFORSA 2025</li>
          </ul>
        </div>
      </div>
    </section>
    ```
Penjelasan Kode:
Section ini merupakan bagian (Skills) yang digunakan untuk menampilkan keahlian dan pengalaman pemilik website. Section dibungkus dengan elemen (section) dengan atribut (id="skills") dan class (section bg-strawberry) untuk pengaturan tampilan latar belakang. Daftar keahlian ditampilkan dalam elemen (skills-container) yang berisi beberapa (skill-item), masing-masing menampilkan nama keahlian dan indikator kemampuan berupa (progress-bar) dan (progress-fill) dengan pengaturan (width) berbentuk persentase. Selain itu, terdapat bagian pengalaman dalam elemen (experience) yang menampilkan daftar pengalaman organisasi menggunakan elemen (ul) dan (li) agar informasi tersaji secara rapi dan mudah dibaca.

### - Certificates

<img width="936" height="602" alt="image" src="https://github.com/user-attachments/assets/83cf06f5-a921-4f58-ae7d-9697cabdc833" />

- kode:
  ```plaintext
  <section id="certificates" class="section section-soft">
      <div class="container">
        <h2 class="section-title">Certificates</h2>

        <div class="card-grid">
          <div class="card">
            <img
              src="img/aplikasi.jpg"
              class="card-img-top"
              alt="Committee Certificate"
            />
            <div>
              <h3 class="mt-2">Committee Certificate</h3>
              <p>APLIKASI – 2025</p>
            </div>
          </div>

          <div class="card">
            <img
              src="img/insevent.jpg"
              class="card-img-top"
              alt="Committee Certificate"
            />
            <div>
              <h3 class="mt-2">Committee Certificate</h3>
              <p>INSEVENT – 2025</p>
            </div>
          </div>

          <div class="card">
            <img
              src="img/upgrading.png"
              class="card-img-top"
              alt="Committee Certificate"
            />
            <div>
              <h3 class="mt-2">Committee Certificate</h3>
              <p>Upgrading INFORSA – 2025</p>
            </div>
          </div>
        </div>
      </div>
    </section>
  ```
Penjelasan Kode:
Section ini merupakan bagian (Certificates) yang berfungsi untuk menampilkan daftar sertifikat yang dimiliki oleh pemilik website. Section dibungkus dengan elemen (section) yang memiliki atribut (id="certificates") serta class (section section-soft) untuk mengatur tata letak dan tampilan latar belakang agar terlihat lebih lembut dan rapi. Konten ditempatkan di dalam elemen (container) untuk menjaga lebar tampilan tetap terpusat, dengan judul section menggunakan elemen (h2) dan class (section-title).

Daftar sertifikat ditampilkan dalam bentuk grid menggunakan elemen (div) dengan class (card-grid) yang berisi beberapa elemen (card). Setiap (card) menampilkan gambar sertifikat menggunakan elemen (img) dengan class (card-img-top) agar gambar responsif dan proporsional. Informasi sertifikat ditampilkan menggunakan elemen (h3) sebagai judul dan elemen (p) sebagai keterangan nama kegiatan dan tahun. Dengan tampilan berbasis kartu ini, informasi sertifikat dapat ditampilkan secara visual, terstruktur, dan mudah dipahami oleh pengunjung website.







