# AI Prompt Generator - README

![AI Prompt Generator Screenshot](screenshot.png)

## 📝 Deskripsi

AI Prompt Generator adalah alat berbasis web yang membantu Anda membuat prompt AI yang efektif dan terstruktur. Dengan antarmuka yang sederhana, Anda dapat dengan mudah menentukan peran AI, tujuan, batasan, dan parameter lainnya untuk menghasilkan prompt yang optimal untuk berbagai kebutuhan seperti penulisan konten, penelitian akademik, manajemen media sosial, dan banyak lagi.

## ✨ Fitur

- 🎭 **Definisi Peran** - Tentukan persona AI yang Anda butuhkan
- 🎯 **Tujuan Jelas** - Jelaskan output yang diharapkan secara spesifik
- ⚖️ **Batasan & Format** - Tetapkan aturan untuk hasil yang lebih terarah
- 📋 **Template Siap Pakai** - Pilihan preset untuk berbagai use case
- 📚 **Panduan Penyusunan** - Petunjuk membuat prompt efektif
- 📥 **Ekspor Hasil** - Simpan atau salin prompt dengan mudah
- 📱 **Responsif** - Bekerja dengan baik di desktop maupun mobile

## 🚀 Cara Menggunakan

1. **Pilih Mode**:
   - **Custom Prompt**: Buat prompt dari awal
   - **Preset Prompt**: Gunakan template siap pakai
   - **Panduan**: Pelajari cara membuat prompt efektif

2. **Isi Formulir**:
   - Masukkan detail peran, tujuan, dan batasan (wajib)
   - Tambahkan contoh, langkah-langkah, atau informasi tambahan (opsional)

3. **Generate Prompt**:
   - Klik tombol "Generate" untuk membuat prompt
   - Hasil akan muncul di panel sebelah kanan

4. **Gunakan Prompt**:
   - Salin ke clipboard
   - Simpan sebagai file teks
   - Gunakan langsung di AI favorit Anda

## 🛠️ Teknologi

- HTML5
- CSS3
- JavaScript Vanilla

## 🌐 Demo

Demo langsung tersedia di: [https://contoh-demo.github.io/ai-prompt-generator](https://contoh-demo.github.io/ai-prompt-generator)

## 📥 Instalasi

Tidak memerlukan instalasi khusus. Cukup buka file `index.html` di browser Anda.

Atau clone repository ini:

```bash
git clone https://github.com/username/ai-prompt-generator.git
cd ai-prompt-generator
```

# Expanded AI Prompt Templates

Here's an enhanced version with many more specialized prompt templates covering various use cases:

```html
<!DOCTYPE html>
<html lang="id">
<head>
  <!-- Previous head content remains the same -->
</head>
<body>
  <!-- Previous header and main structure remains the same until presets section -->

      <div class="tab-content" id="presets-tab">
        <h2>Template Prompt</h2>
        <p>Pilih template untuk memulai cepat:</p>
        
        <div class="preset-category">
          <h3>🎨 Kreatif & Penulisan</h3>
          
          <button class="preset-btn" data-preset="blog-writer">
            <div class="preset-title">Penulis Blog</div>
            <div class="preset-desc">Untuk membuat outline atau artikel blog lengkap</div>
          </button>
          
          <button class="preset-btn" data-preset="story-writer">
            <div class="preset-title">Penulis Cerita</div>
            <div class="preset-desc">Untuk menulis cerpen atau novel</div>
          </button>
          
          <button class="preset-btn" data-preset="copywriter">
            <div class="preset-title">Copywriter Iklan</div>
            <div class="preset-desc">Untuk membuat teks iklan yang persuasif</div>
          </button>
          
          <button class="preset-btn" data-preset="poetry">
            <div class="preset-title">Puisi & Sajak</div>
            <div class="preset-desc">Untuk menulis puisi dengan gaya tertentu</div>
          </button>
        </div>
        
        <div class="preset-category">
          <h3>💼 Bisnis & Pemasaran</h3>
          
          <button class="preset-btn" data-preset="business-plan">
            <div class="preset-title">Rencana Bisnis</div>
            <div class="preset-desc">Untuk menyusun dokumen rencana bisnis</div>
          </button>
          
          <button class="preset-btn" data-preset="marketing-strategy">
            <div class="preset-title">Strategi Pemasaran</div>
            <div class="preset-desc">Untuk membuat rencana pemasaran digital</div>
          </button>
          
          <button class="preset-btn" data-preset="sales-script">
            <div class="preset-title">Naskah Penjualan</div>
            <div class="preset-desc">Untuk membuat script telemarketing atau sales</div>
          </button>
          
          <button class="preset-btn" data-preset="swot-analysis">
            <div class="preset-title">Analisis SWOT</div>
            <div class="preset-desc">Untuk melakukan analisis bisnis</div>
          </button>
        </div>
        
        <div class="preset-category">
          <h3>👨‍💻 Teknologi & Pemrograman</h3>
          
          <button class="preset-btn" data-preset="coding-assistant">
            <div class="preset-title">Asisten Pemrograman</div>
            <div class="preset-desc">Untuk membantu menulis atau debugging kode</div>
          </button>
          
          <button class="preset-btn" data-preset="tech-writer">
            <div class="preset-title">Penulis Teknis</div>
            <div class="preset-desc">Untuk membuat dokumentasi teknis</div>
          </button>
          
          <button class="preset-btn" data-preset="system-design">
            <div class="preset-title">Desain Sistem</div>
            <div class="preset-desc">Untuk merancang arsitektur software</div>
          </button>
          
          <button class="preset-btn" data-preset="sql-query">
            <div class="preset-title">Pembuat Query SQL</div>
            <div class="preset-desc">Untuk membantu menulis query database</div>
          </button>
        </div>
        
        <div class="preset-category">
          <h3>🎓 Pendidikan & Riset</h3>
          
          <button class="preset-btn" data-preset="academic-research">
            <div class="preset-title">Penelitian Akademik</div>
            <div class="preset-desc">Untuk membantu penulisan karya ilmiah</div>
          </button>
          
          <button class="preset-btn" data-preset="lesson-plan">
            <div class="preset-title">Rencana Pembelajaran</div>
            <div class="preset-desc">Untuk membuat silabus atau RPP</div>
          </button>
          
          <button class="preset-btn" data-preset="student-essay">
            <div class="preset-title">Esai Mahasiswa</div>
            <div class="preset-desc">Untuk membantu menulis esai akademik</div>
          </button>
          
          <button class="preset-btn" data-preset="language-learning">
            <div class="preset-title">Pembelajaran Bahasa</div>
            <div class="preset-desc">Untuk membuat materi belajar bahasa</div>
          </button>
        </div>
        
        <div class="preset-category">
          <h3>📱 Media Sosial & Konten</h3>
          
          <button class="preset-btn" data-preset="social-media">
            <div class="preset-title">Manajer Media Sosial</div>
            <div class="preset-desc">Untuk membuat konten media sosial</div>
          </button>
          
          <button class="preset-btn" data-preset="youtube-script">
            <div class="preset-title">Naskah YouTube</div>
            <div class="preset-desc">Untuk membuat script video</div>
          </button>
          
          <button class="preset-btn" data-preset="email-newsletter">
            <div class="preset-title">Newsletter Email</div>
            <div class="preset-desc">Untuk membuat konten email marketing</div>
          </button>
          
          <button class="preset-btn" data-preset="seo-article">
            <div class="preset-title">Artikel SEO</div>
            <div class="preset-desc">Untuk menulis konten yang dioptimalkan</div>
          </button>
        </div>
        
        <div class="preset-category">
          <h3>🛒 Produk & Layanan</h3>
          
          <button class="preset-btn" data-preset="product-description">
            <div class="preset-title">Deskripsi Produk</div>
            <div class="preset-desc">Untuk menulis deskripsi e-commerce</div>
          </button>
          
          <button class="preset-btn" data-preset="customer-service">
            <div class="preset-title">Layanan Pelanggan</div>
            <div class="preset-desc">Untuk membuat respon CS yang baik</div>
          </button>
          
          <button class="preset-btn" data-preset="faq-generator">
            <div class="preset-title">Pembuat FAQ</div>
            <div class="preset-desc">Untuk membuat daftar pertanyaan umum</div>
          </button>
          
          <button class="preset-btn" data-preset="review-response">
            <div class="preset-title">Respon Ulasan</div>
            <div class="preset-desc">Untuk menanggapi review pelanggan</div>
          </button>
        </div>
      </div>

  <!-- Rest of the HTML remains the same -->

  <script>
    // Updated presets object with many more templates
    const presets = {
      // Creative & Writing
      'blog-writer': {
        role: 'Penulis blog profesional dengan pengalaman 5 tahun di bidang teknologi',
        objective: 'Buat outline artikel blog tentang manfaat AI untuk bisnis kecil',
        constraints: 'Maksimal 8 poin utama, bahasa Indonesia semi-formal, sertakan call-to-action di akhir',
        examples: 'Input: Manfaat cloud computing\nOutput:\n1. Pengenalan cloud computing\n2. Skalabilitas yang fleksibel\n3. Penghematan biaya infrastruktur\n...',
        steps: '1. Identifikasi manfaat utama\n2. Urutkan berdasarkan dampak terbesar\n3. Sertakan contoh kasus\n4. Berikan data pendukung jika ada',
        audience: 'Pemilik bisnis kecil dengan pengetahuan teknologi dasar',
        variants: 'Formal, semi-formal, santai',
        tone: 'Semi-formal'
      },
      'story-writer': {
        role: 'Penulis cerita fiksi berpengalaman',
        objective: 'Buat cerpen tentang persahabatan di masa kecil yang bertahan hingga dewasa',
        constraints: 'Maksimal 1500 kata, alur yang emosional, twist ending',
        examples: 'Tema: Persahabatan\nContoh: Kisah dua sahabat yang terpisah selama 20 tahun dan bertemu kembali dalam keadaan tak terduga...',
        tone: 'Emosional'
      },
      'copywriter': {
        role: 'Copywriter iklan senior',
        objective: 'Buat teks iklan untuk produk kopi premium baru',
        constraints: 'Maksimal 100 kata, persuasif, highlight keunikan produk',
        examples: 'Produk: Kopi single origin\nTeks: "Nikmati cita rasa kopi single origin langsung dari perkebunan terbaik. Setiap tegukan membawa Anda pada petualangan rasa yang autentik..."',
        tone: 'Persuasif'
      },
      'poetry': {
        role: 'Penyair profesional',
        objective: 'Tulis puisi tentang keindahan alam Indonesia',
        constraints: '4 bait, setiap bait 4 baris, menggunakan majas personifikasi',
        examples: 'Contoh puisi:\n"Gemuruh ombak berbisik sayang\nPada pasir putih yang diam mendengar\nAngin laut menyampaikan rindu\nDari negeri seberang yang jauh"',
        tone: 'Puitis'
      },
      
      // Business & Marketing
      'business-plan': {
        role: 'Konsultan bisnis dengan pengalaman 10 tahun',
        objective: 'Buat executive summary untuk rencana bisnis startup edtech',
        constraints: 'Maksimal 300 kata, fokus pada value proposition dan model bisnis',
        audience: 'Calon investor venture capital',
        tone: 'Formal'
      },
      'marketing-strategy': {
        role: 'Spesialis pemasaran digital',
        objective: 'Buat strategi pemasaran 3 bulan untuk produk SaaS baru',
        constraints: 'Sertakan channel pemasaran, KPI, dan anggaran perkiraan',
        steps: '1. Analisis target pasar\n2. Identifikasi channel terbaik\n3. Buat timeline\n4. Tentukan KPI',
        tone: 'Profesional'
      },
      'sales-script': {
        role: 'Manajer penjualan berpengalaman',
        objective: 'Buat script penjualan untuk produk software HR',
        constraints: 'Dialog natural, sertakan handling objection, maksimal 2 menit',
        examples: 'Pembukaan: "Halo [Nama], saya [Nama] dari [Perusahaan]. Kami membantu perusahaan seperti [Contoh Klien] menyederhanakan proses HR mereka..."',
        tone: 'Persuasif'
      },
      'swot-analysis': {
        role: 'Konsultan manajemen bisnis',
        objective: 'Lakukan analisis SWOT untuk perusahaan e-commerce fashion',
        constraints: 'Format tabel, berikan 3 poin untuk setiap kategori',
        steps: '1. Identifikasi kekuatan\n2. Analisis kelemahan\n3. Temukan peluang\n4. Waspadai ancaman',
        tone: 'Analitis'
      },
      
      // Technology & Programming
      'coding-assistant': {
        role: 'Senior developer JavaScript berpengalaman',
        objective: 'Bantu saya memperbaiki bug dalam fungsi sorting ini',
        constraints: 'Gunakan ES6+, berikan penjelasan untuk setiap perubahan yang dibuat',
        examples: 'Input:\nfunction sortArray(arr) {\n  return arr.sort();\n}\n\nProblem: Tidak handle angka dengan benar\n\nOutput:\nfunction sortArray(arr) {\n  return arr.sort((a,b) => a - b);\n}',
        tone: 'Teknis'
      },
      'tech-writer': {
        role: 'Penulis dokumentasi teknis',
        objective: 'Buat panduan penggunaan API untuk developer',
        constraints: 'Sertakan contoh request/response, error codes, dan autentikasi',
        steps: '1. Penjelasan endpoint\n2. Parameter\n3. Contoh kode\n4. Kemungkinan error',
        tone: 'Jelas'
      },
      'system-design': {
        role: 'Arsitek software senior',
        objective: 'Rancang arsitektur untuk aplikasi e-commerce skala menengah',
        constraints: 'Sertakan diagram komponen, pertimbangkan skalabilitas',
        steps: '1. Identifikasi microservices\n2. Desain database\n3. Pertimbangkan caching\n4. Rencana deployment',
        tone: 'Teknis'
      },
      'sql-query': {
        role: 'Database administrator',
        objective: 'Buat query untuk laporan penjualan bulanan',
        constraints: 'Gunakan PostgreSQL, sertakan filter tanggal dan grouping',
        examples: 'Contoh: SELECT category, SUM(amount) FROM sales WHERE date BETWEEN X AND Y GROUP BY category',
        tone: 'Teknis'
      },
      
      // Education & Research
      'academic-research': {
        role: 'Asisten peneliti bidang ilmu sosial',
        objective: 'Buat kerangka penelitian tentang dampak media sosial pada kesehatan mental remaja',
        constraints: 'Gunakan format akademik, sertakan latar belakang, rumusan masalah, metode penelitian, dan referensi teori',
        steps: '1. Latar belakang penelitian\n2. Rumusan masalah\n3. Tinjauan pustaka\n4. Metodologi\n5. Hipotesis',
        tone: 'Akademik'
      },
      'lesson-plan': {
        role: 'Guru berpengalaman',
        objective: 'Buat rencana pembelajaran (RPP) untuk materi sejarah kelas 10',
        constraints: 'Sesuai kurikulum merdeka, sertakan tujuan, kegiatan, dan evaluasi',
        steps: '1. Tujuan pembelajaran\n2. Kegiatan pendahuluan\n3. Inti\n4. Penutup\n5. Evaluasi',
        tone: 'Formal'
      },
      'student-essay': {
        role: 'Tutor akademik',
        objective: 'Bantu tulis esai argumentatif tentang dampak positif media sosial',
        constraints: '500-700 kata, sertakan tesis, argumen, dan kesimpulan',
        examples: 'Contoh struktur:\n1. Paragraf pembuka dengan tesis\n2. 3 argumen utama dengan bukti\n3. Kesimpulan',
        tone: 'Akademik'
      },
      'language-learning': {
        role: 'Pengajar bahasa Inggris',
        objective: 'Buat materi pembelajaran tentang present perfect tense',
        constraints: 'Sertakan penjelasan, contoh kalimat, dan latihan',
        examples: 'Contoh:\nPenjelasan: Digunakan untuk menyatakan pengalaman\nContoh: "I have visited Bali three times"',
        tone: 'Edukatif'
      },
      
      // Social Media & Content
      'social-media': {
        role: 'Social media specialist untuk platform Instagram',
        objective: 'Buat 5 ide caption untuk postingan tentang produk kopi baru',
        constraints: 'Maksimal 150 karakter per caption, sertakan 2-3 hashtag relevan, gaya engaging',
        examples: 'Produk: Cold brew vanilla\nCaption: "Nikmati kesegaran cold brew dengan sentuhan vanilla yang lembut. Perfect untuk temani harimu! ☕️ #ColdBrewTime #KopiVanilla"',
        audience: 'Anak muda usia 18-35 tahun penggemar kopi',
        tone: 'Santai'
      },
      'youtube-script': {
        role: 'Script writer YouTube profesional',
        objective: 'Buat script video tutorial memasak nasi goreng',
        constraints: 'Durasi 5 menit, bahasa santai, sertakan call-to-action di akhir',
        steps: '1. Pembuka yang menarik\n2. Daftar bahan\n3. Langkah memasak\n4. Penutup dengan CTA',
        tone: 'Santai'
      },
      'email-newsletter': {
        role: 'Email marketing specialist',
        objective: 'Buat newsletter bulanan untuk komunitas pecinta buku',
        constraints: '3 bagian utama, maksimal 500 kata, sertakan promo buku terbaru',
        examples: 'Struktur:\n1. Pembuka: Kabar komunitas\n2. Fitur: Buku bulan ini\n3. Penutup: Event mendatang',
        tone: 'Ramah'
      },
      'seo-article': {
        role: 'Content writer SEO',
        objective: 'Tulis artikel tentang "Cara Memulai Bisnis Online"',
        constraints: '1000 kata, keyword density 1-2%, sertakan heading H2-H3',
        steps: '1. Riset keyword\n2. Buat outline\n3. Tulis konten\n4. Optimasi',
        tone: 'Informasional'
      },
      
      // Product & Services
      'product-description': {
        role: 'Product description specialist',
        objective: 'Tulis deskripsi untuk tas laptop premium',
        constraints: 'Sertakan fitur, benefit, dan spesifikasi teknis',
        examples: 'Contoh:\n"Tas laptop executive dengan bahan kulit asli. Dilengkapi dengan kompartemen anti gores dan saku tersembunyi untuk dokumen penting..."',
        tone: 'Deskriptif'
      },
      'customer-service': {
        role: 'Manajer layanan pelanggan',
        objective: 'Buat template respon untuk komplain pengiriman terlambat',
        constraints: 'Bahasa sopan, empatik, sertakan solusi konkret',
        examples: '"Kami sangat meminta maaf atas keterlambatan ini. Sebagai kompensasi, kami akan memberikan voucher diskon 15% untuk pembelian berikutnya..."',
        tone: 'Empatik'
      },
      'faq-generator': {
        role: 'Spesialis konten produk',
        objective: 'Buat daftar FAQ untuk layanan streaming baru',
        constraints: '10 pertanyaan umum beserta jawaban singkat',
        examples: 'Q: Bagaimana cara berlangganan?\nA: Anda bisa berlangganan melalui website atau aplikasi kami dengan beberapa metode pembayaran...',
        tone: 'Jelas'
      },
      'review-response': {
        role: 'Brand manager',
        objective: 'Buat template respon untuk review negatif produk',
        constraints: 'Sopan, profesional, tawarkan solusi',
        examples: '"Terima kasih atas masukan Anda. Kami sangat menyesal mendengar pengalaman Anda. Tim kami akan segera menghubungi untuk menawarkan solusi..."',
        tone: 'Profesional'
      }
    };

    // Rest of the JavaScript remains the same
  </script>
</body>
</html>
```

## Penambahan Template Baru

Saya telah menambahkan **24 template khusus** yang dikelompokkan dalam 6 kategori:

### 🎨 Kreatif & Penulisan
1. Penulis Blog
2. Penulis Cerita
3. Copywriter Iklan
4. Puisi & Sajak

### 💼 Bisnis & Pemasaran
5. Rencana Bisnis
6. Strategi Pemasaran
7. Naskah Penjualan
8. Analisis SWOT

### 👨‍💻 Teknologi & Pemrograman
9. Asisten Pemrograman
10. Penulis Teknis
11. Desain Sistem
12. Pembuat Query SQL

### 🎓 Pendidikan & Riset
13. Penelitian Akademik
14. Rencana Pembelajaran
15. Esai Mahasiswa
16. Pembelajaran Bahasa

### 📱 Media Sosial & Konten
17. Manajer Media Sosial
18. Naskah YouTube
19. Newsletter Email
20. Artikel SEO

### 🛒 Produk & Layanan
21. Deskripsi Produk
22. Layanan Pelanggan
23. Pembuat FAQ
24. Respon Ulasan

Setiap template telah dioptimalkan untuk:
- Peran yang spesifik
- Tujuan yang jelas
- Batasan yang terukur
- Contoh yang relevan
- Langkah-langkah terstruktur
- Nada yang sesuai

Template-template ini mencakup berbagai kebutuhan profesional dan pribadi, dari penulisan kreatif hingga analisis bisnis, dari pemrograman hingga layanan pelanggan.

## 🤝 Berkontribusi

Kontribusi selalu diterima! Berikut cara berkontribusi:

1. Fork proyek ini
2. Buat branch fitur (`git checkout -b fitur-baru`)
3. Commit perubahan Anda (`git commit -am 'Tambahkan fitur baru'`)
4. Push ke branch (`git push origin fitur-baru`)
5. Buat Pull Request

## 📜 Lisensi

Proyek ini dilisensikan di bawah [MIT License](LICENSE).

---

Dibuat dengan ❤️ oleh [Nama Anda] - Semoga bermanfaat untuk kebutuhan prompt AI Anda!
