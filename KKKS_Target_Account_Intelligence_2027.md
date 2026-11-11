# KKKS Target Account Intelligence 2027
**Edisi:** Master Target Account dan Prioritas Awal  
**Tanggal penyusunan:** 11 November 2026  
**Cakupan:** Kontraktor Kontrak Kerja Sama (KKKS) hulu minyak dan gas bumi Indonesia  
**Pengguna:** Sales, Account Manager, Business Development, Solution Architect

---

## 1. Tujuan dan cara menggunakan dokumen

Dokumen ini menetapkan daftar awal akun KKKS untuk pengembangan peluang keamanan siber dan pelindungan data pada 2027. Dokumen ini merupakan alat prioritisasi penjualan, bukan penilaian kepatuhan, audit keamanan, atau pernyataan bahwa suatu KKKS memiliki kelemahan tertentu.

Daftar awal dibangun dari indikator publik yang dapat membantu memilih akun untuk riset lanjutan, terutama skala produksi minyak/kondensat, posisi pada produksi gas, dan kompleksitas operasi yang secara wajar perlu diuji dalam proses account profiling.

**Prinsip penting:** besarnya produksi bukan bukti adanya kebutuhan keamanan siber, anggaran, proyek, insiden, atau ketidakpatuhan. Prioritas di bawah adalah hipotesis komersial untuk menentukan urutan riset dan pendekatan awal.

### Klasifikasi informasi

| Label | Arti | Cara menggunakan |
|---|---|---|
| Fakta bersumber | Informasi yang dinyatakan dalam sumber yang dicantumkan | Dapat dipakai dengan konteks, tanggal, dan batasan sumber |
| Inferensi | Penalaran yang diturunkan dari fakta yang tersedia | Harus dinyatakan sebagai interpretasi, bukan fakta pelanggan |
| Hipotesis akun | Dugaan kebutuhan yang perlu diuji langsung | Tidak boleh dipresentasikan sebagai kondisi aktual pelanggan |
| Belum diketahui | Informasi yang belum didukung sumber memadai | Menjadi agenda riset atau pertanyaan discovery |

## 2. Ringkasan intelijen pasar

Sumber publik yang ditinjau memberikan beberapa petunjuk untuk membangun universe akun:

1. Publikasi SKK Migas yang dikutip dalam pemberitaan mencantumkan 20 KKKS teratas berdasarkan produksi minyak, kondensat, dan NGL per 31 Mei 2026. Daftar tersebut dapat menjadi titik awal pemilihan akun berdasarkan skala produksi. [Sumber: Katadata Databoks, 2026](https://databoks.katadata.co.id/en/energy/statistics/6a34a54325d45/top-20-contractors-with-the-largest-oil-condensate-and-ngl-production-in-indonesia-as-of-may-2026).
2. Pemberitaan berbasis paparan SKK Migas mencantumkan 20 KKKS teratas berdasarkan realisasi penyaluran gas hingga 31 Mei 2026. Ini memperluas universe ke operator yang profil produksinya dominan gas. [Sumber: CNBC Indonesia, 15 Juni 2026](https://www.cnbcindonesia.com/news/20260615105238-4-742854/hasilkan-5207-juta-kaki-kubik-hari-ini-sejumlah-raja-gas-di-ri).
3. Cuplikan Laporan Tahunan SKK Migas 2025 yang tersedia melalui sumber sekunder menyebut 165 wilayah kerja pada 31 Desember 2025: 105 wilayah kerja eksploitasi, 46 wilayah kerja eksplorasi aktif, dan 13 dalam proses terminasi. Angka ini adalah jumlah wilayah kerja, bukan jumlah perusahaan/KKKS. [Sumber sekunder atas Laporan Tahunan SKK Migas 2025](https://www.scribd.com/document/1075794271/Laporan-Tahunan-2025).
4. Situs SKK Migas menyediakan ringkasan capaian dan kanal publikasi resmi. Data operasional dan daftar operator terbaru perlu ditarik kembali dari sumber resmi sebelum daftar akun dianggap final. [SKK Migas](https://www.skkmigas.go.id/).

### Implikasi untuk penjualan

- Universe awal sebaiknya menggabungkan operator minyak dan operator gas; pemeringkatan berdasarkan minyak saja akan melewatkan beberapa akun penting.
- Perusahaan dengan operasi lapangan, fasilitas, tenaga kerja, kontraktor, dan sistem lintas lokasi layak diuji lebih lanjut untuk kebutuhan IAM/PAM, endpoint, keamanan cloud, SOC, perlindungan data, dan tata kelola vendor. Ini merupakan hipotesis discovery, bukan kesimpulan tentang kondisi kontrol perusahaan.
- Akun yang berada dalam grup usaha besar dapat memiliki model pengadaan, arsitektur TI, dan tata kelola yang berbeda. Jangan menganggap keputusan grup otomatis berlaku pada setiap entitas KKKS.

## 3. Universe awal akun sasaran

### 3.1 Daftar berdasarkan produksi minyak, kondensat, dan NGL

Angka berikut adalah produksi minyak, kondensat, dan NGL per 31 Mei 2026 sebagaimana dikutip Katadata Databoks. Satuan: barel per hari (bopd). Angka ini merupakan snapshot tanggal tersebut, bukan angka produksi terkini atau proyeksi 2027.

| Peringkat sumber | KKKS | Produksi (bopd) | Catatan awal |
|---:|---|---:|---|
| 1 | PT Pertamina Hulu Rokan | 131.040 | Skala operasi besar; validasi entitas pembeli dan model pengadaan |
| 2 | ExxonMobil Cepu Ltd. | 129.915 | Operator besar; validasi tata kelola lokal dan global |
| 3 | PT Pertamina EP | 73.983 | Portofolio aset luas; petakan struktur regional dan unit pengambil keputusan |
| 4 | PetroChina International Jabung Ltd. | 27.478 | Operator besar non-Pertamina; telusuri kebutuhan lokal dan regional |
| 5 | PT Pertamina Hulu Energi Offshore North West Java | 26.473 | Operasi offshore; validasi ekosistem OT dan kontraktor |
| 6 | PT Pertamina Hulu Mahakam | 25.575 | Operasi lapangan; telusuri sistem dan rantai layanan |
| 7 | Medco E&P Natuna Ltd. | 24.023 | Operator swasta; validasi struktur grup dan keputusan akun |
| 8 | PT Pertamina Hulu Energi OSES | 18.036 | Operasi offshore; validasi kebutuhan akses dan pihak ketiga |
| 9 | PT Pertamina Hulu Sanga Sanga | 14.957 | Operasi lapangan; telusuri arsitektur dan kontraktor |
| 10 | JOB Pertamina-Medco E&P Tomori Sulawesi | 9.291 | Joint operating body; petakan pembagian peran para pihak |
| 11 | Saka Indonesia Pangkah Ltd. | 8.754 | Operator non-Pertamina; validasi sistem dan struktur pemilik |
| 12 | PT Pertamina Hulu Kalimantan Timur | 8.543 | Operasi regional; telusuri ketergantungan sistem grup |
| 13 | PT Bumi Siak Pusako | 7.352 | Operator domestik; validasi skala dan kesiapan pengadaan |
| 14 | BP Berau Ltd. | 7.076 | Aset gas besar; lihat pula daftar produksi gas |
| 15 | PT Pertamina Hulu Energi Jambi Merang | 5.303 | Operasi gas/minyak; validasi status aset dan sistem |
| 16 | Texcal Energy Mahato Inc. | 4.997 | Operator independen; validasi skala organisasi |
| 17 | PC Ketapang II Ltd. | 4.833 | Operator non-Pertamina; telusuri afiliasi dan pengadaan |
| 18 | PT Imbang Tata Alam | 4.654 | Validasi profil operator, aset, dan skala |
| 19 | Petrogas (Basin) Ltd. | 4.203 | Operator non-Pertamina; telusuri portofolio dan pihak terkait |
| 20 | PT Medco E&P Rimau | 4.039 | Bagian dari ekosistem Medco; validasi tata kelola grup |

**Sumber data:** [Katadata Databoks — Top 20 Contractors with the Largest Oil, Condensate, and NGL Production in Indonesia as of May 2026](https://databoks.katadata.co.id/en/energy/statistics/6a34a54325d45/top-20-contractors-with-the-largest-oil-condensate-and-ngl-production-in-indonesia-as-of-may-2026).

### 3.2 Akun penting berdasarkan penyaluran gas

Daftar ini menggunakan realisasi penyaluran gas hingga 31 Mei 2026 menurut pemberitaan yang merujuk paparan SKK Migas. Satuan: juta kaki kubik standar per hari (MMSCFD). Data ini melengkapi, bukan menggantikan, daftar produksi minyak.

| Peringkat sumber | KKKS | Realisasi penyaluran gas (MMSCFD) |
|---:|---|---:|
| 1 | BP Berau Ltd. | 1.494 |
| 2 | PT Pertamina EP | 555 |
| 3 | ENI East Sepinggan Ltd. | 474 |
| 4 | Medco E&P Grissik Ltd. | 458 |
| 5 | PT Pertamina Hulu Mahakam | 364 |
| 6 | JOB Pertamina-Medco E&P Tomori Sulawesi | 311 |
| 7 | Husky-CNOOC Madura Ltd. | 210 |
| 8 | Medco E&P Natuna Ltd. | 156 |
| 9 | PT Pertamina EP Cepu | 142 |
| 10 | PetroChina International Jabung Ltd. | 118 |
| 11 | PT Pertamina Hulu Energi Jambi Merang | 105 |
| 12 | ENI Muara Bakau B.V. | 103 |
| 13 | Premier Oil Natuna Sea B.V. | 102 |
| 14 | PT Pertamina Hulu Sanga Sanga | 74 |
| 15 | EMP Bentu Ltd. | 62 |
| 16 | PT Medco E&P Indonesia | 56 |
| 17 | PT Pertamina Hulu Energi Offshore North West Java | 47 |
| 18 | Energy Equity Epic (Sengkang) Pty. Ltd. | 46 |
| 19 | Kangean Energy Indonesia Ltd. | 45 |
| 20 | PC Ketapang II Ltd. | 40 |

**Sumber data:** [CNBC Indonesia — Hasilkan 5.207 Juta Kaki Kubik/Hari, Ini Sejumlah 'Raja' Gas di RI, 15 Juni 2026](https://www.cnbcindonesia.com/news/20260615105238-4-742854/hasilkan-5207-juta-kaki-kubik-hari-ini-sejumlah-raja-gas-di-ri).

## 4. Prioritas awal akun 2027

Prioritas berikut adalah **urutan riset dan engagement yang disarankan**, bukan ranking risiko siber atau peluang proyek yang telah dikonfirmasi.

### Tier 1 — Prioritas riset dan engagement awal

| Akun | Dasar pemilihan yang tersedia | Hipotesis peluang untuk diuji | Fokus riset berikutnya |
|---|---|---|---|
| PT Pertamina Hulu Rokan | Peringkat 1 produksi minyak/kondensat/NGL dalam snapshot Mei 2026 | Kompleksitas operasi dan ekosistem tenaga kerja dapat membuat tata kelola akses, endpoint, vendor, dan data relevan untuk ditelusuri | Struktur TI/OT, model pengadaan, program keamanan grup, proyek 2027 |
| ExxonMobil Cepu Ltd. | Peringkat 2 produksi minyak/kondensat/NGL | Kebutuhan koordinasi kontrol lokal dan standar korporat global perlu dipahami | Struktur pengambil keputusan lokal/global, standar vendor, jalur procurement |
| PT Pertamina EP | Peringkat 3 minyak dan peringkat 2 penyaluran gas dalam daftar sumber | Portofolio operasi dan sistem lintas aset dapat membuka kebutuhan standardisasi kontrol | Struktur regional, pemilik sistem, pengadaan, program grup Pertamina |
| PetroChina International Jabung Ltd. | Peringkat 4 minyak dan masuk 10 besar penyaluran gas | Integrasi sistem operasi, kontraktor, dan tata kelola akses menjadi tema discovery | Pemilik akun, struktur operator, sistem lapangan, kontrak layanan |
| PT Pertamina Hulu Energi ONWJ | Peringkat 5 minyak; masuk daftar 20 besar gas | Lingkungan offshore dan akses pihak ketiga dapat menjadi fokus discovery | OT/ICS boundary, remote access, vendor offshore, SOC coverage |
| PT Pertamina Hulu Mahakam | Peringkat 6 minyak dan peringkat 5 penyaluran gas | Operasi darat/lepas pantai dan ekosistem kontraktor perlu dipetakan | Sistem operasi, kontraktor, akses istimewa, ketergantungan grup |
| Medco E&P Natuna Ltd. | Peringkat 7 minyak dan peringkat 8 penyaluran gas | Peluang lintas fungsi TI, operasi, dan tata kelola grup perlu diuji | Struktur Medco, keputusan lokal/grup, proyek berjalan, vendor |
| BP Berau Ltd. | Peringkat 14 minyak dan peringkat 1 penyaluran gas | Skala operasi gas dan integrasi fasilitas dapat menjadi dasar discovery keamanan OT, akses, dan pihak ketiga | Struktur TI/OT, LNG/gas value chain, procurement, standar global |
| PT Pertamina Hulu Energi OSES | Peringkat 8 minyak | Operasi offshore dan kontraktor dapat menjadi fokus penggalian kebutuhan akses dan keamanan | Aset dan fasilitas, remote access, sistem HSE, vendor |
| JOB Pertamina-Medco E&P Tomori Sulawesi | Peringkat 10 minyak dan peringkat 6 penyaluran gas | Model joint operation berpotensi menambah kompleksitas pembagian tanggung jawab dan tata kelola akses | Operator/JOB governance, pembagian tanggung jawab TI, procurement, kontraktor |

### Tier 2 — Prioritas pendalaman berikutnya

| Akun | Alasan masuk daftar | Fokus validasi |
|---|---|---|
| ENI East Sepinggan Ltd. | Peringkat 3 penyaluran gas | Struktur grup global, fasilitas, operasi, dan jalur pengadaan |
| Medco E&P Grissik Ltd. | Peringkat 4 penyaluran gas | Hubungan dengan tata kelola Medco, sistem gas, dan kebutuhan lokal |
| Husky-CNOOC Madura Ltd. | Peringkat 7 penyaluran gas | Struktur joint venture, offshore, dan model pengadaan |
| PT Pertamina Hulu Kalimantan Timur | Peringkat 12 minyak | Struktur regional, sistem grup, dan vendor |
| PT Pertamina Hulu Sanga Sanga | Peringkat 9 minyak; masuk 20 besar gas | Sistem lintas lapangan dan kontraktor |
| PT Pertamina Hulu Energi Jambi Merang | Peringkat 15 minyak; peringkat 11 gas | Status aset, sistem, dan model pengelolaan |
| Saka Indonesia Pangkah Ltd. | Peringkat 11 minyak | Struktur grup, fasilitas, dan kebutuhan keamanan |
| PT Pertamina EP Cepu | Peringkat 9 penyaluran gas | Hubungan organisasi dengan Pertamina EP dan pengelolaan aset |
| ENI Muara Bakau B.V. | Peringkat 12 penyaluran gas | Struktur global-lokal dan ekosistem vendor |
| Premier Oil Natuna Sea B.V. | Peringkat 13 penyaluran gas | Struktur operator, operasi offshore, dan procurement |
| PetroChina International Jabung Ltd. | Masuk Tier 1; tercantum pada kedua indikator | Pendalaman lintas fungsi |
| PC Ketapang II Ltd. | Peringkat 17 minyak; peringkat 20 gas | Struktur pemilik, sistem, dan kontraktor |

Tier 2 bukan berarti akun tersebut kurang penting. Penempatannya mencerminkan urutan kerja awal dan kebutuhan pendalaman, bukan penilaian nilai komersial final.

## 5. Kerangka prioritisasi yang harus digunakan tim

Gunakan skor 1–5 untuk setiap dimensi setelah data akun tersedia. Jangan mengisi skor berdasarkan asumsi semata.

| Dimensi | Bobot awal | Bukti yang dibutuhkan |
|---|---:|---|
| Skala dan kompleksitas operasi | 20% | Jumlah aset/lokasi, operasi offshore/onshore, jumlah pekerja dan kontraktor |
| Relevansi kebutuhan keamanan siber | 20% | Arsitektur TI/OT, eksposur akses jarak jauh, kebutuhan SOC, endpoint, cloud |
| Relevansi UU PDP dan tata kelola data | 15% | Proses data pribadi, data kesehatan/biometrik, vendor pemroses, transfer lintas negara |
| Indikasi program/proyek 2027 | 20% | Rencana pengadaan, tender, modernisasi, audit finding, anggaran, roadmap |
| Akses dan sponsor | 15% | Hubungan stakeholder, sponsor bisnis, pemilik masalah, jalur ke pengambil keputusan |
| Kelayakan komersial | 10% | Kesesuaian portofolio, jalur procurement, kemampuan delivery, kompetisi |

**Rumus skor tertimbang:** jumlah dari (skor dimensi ÷ 5) × bobot. Hasil akhir 0–100.

### Aturan pemberian skor

- Skor 1: bukti menunjukkan relevansi rendah.
- Skor 2: relevansi terbatas atau indikasi lemah.
- Skor 3: relevansi masuk akal, tetapi bukti belum lengkap.
- Skor 4: bukti kuat dan kebutuhan telah diakui stakeholder.
- Skor 5: kebutuhan, sponsor, jalur anggaran/pengadaan, dan waktu telah tervalidasi.

Jika bukti tidak tersedia, gunakan status **Belum dinilai**, bukan skor 3. Skor awal dari data publik tidak boleh disamakan dengan skor kualifikasi peluang.

## 6. Hipotesis solusi per pola operasi

Tabel ini adalah panduan discovery. Solusi tidak boleh ditawarkan sebagai kebutuhan yang telah dipastikan sebelum validasi pelanggan.

| Pola operasi / konteks | Area discovery | Solusi yang dapat diuji |
|---|---|---|
| Operasi multi-aset dan multi-lokasi | Konsistensi identitas, akses, endpoint, dan pemantauan | IAM/IGA, PAM, EDR/XDR, SIEM/SOC |
| Operasi offshore dan fasilitas terpencil | Remote access, akses vendor, segmentasi, respons insiden | PAM, MFA, OT security, managed SOC |
| Ekosistem kontraktor besar | Onboarding/offboarding, akun sementara, akses pihak ketiga | IAM, PAM, third-party risk management |
| Sistem grup atau lintas negara | Lokasi pemrosesan, akses lintas yurisdiksi, kontrol vendor | Data mapping, DSPM, DLP, GRC |
| Pemrosesan data tenaga kerja dan kesehatan | Klasifikasi, akses, retensi, pembagian data | Data discovery, DLP, encryption, privacy management |
| Operasi gas/LNG dan rantai pasok terintegrasi | Ketergantungan OT, integrasi pihak ketiga, ketersediaan layanan | OT security, network monitoring, incident response |

## 7. Rencana kerja 30 hari untuk Task 1

### Minggu 1 — Baseline akun
- Konfirmasi universe KKKS dari daftar resmi SKK Migas/ESDM.
- Rekonsiliasi nama badan hukum, nama operator, nama wilayah kerja, dan induk perusahaan.
- Pisahkan operator, non-operator/partner, JOB/JOC, dan entitas afiliasi.
- Tetapkan owner internal untuk setiap akun Tier 1.

### Minggu 2 — Riset perusahaan
- Kumpulkan profil perusahaan, aset, lokasi, dan aktivitas operasi.
- Identifikasi informasi publik mengenai struktur grup dan kepemimpinan.
- Cari pengumuman proyek, tender, investasi, modernisasi, dan kemitraan teknologi.
- Catat setiap sumber beserta tanggal publikasi dan tanggal akses.

### Minggu 3 — Riset stakeholder dan teknologi
- Petakan CIO, CISO, IT, OT, procurement, Legal, Compliance, HR, dan HSE jika informasinya tersedia secara sah dan publik.
- Identifikasi sistem, vendor, dan arsitektur yang disebut dalam sumber publik.
- Tandai informasi yang belum diketahui; jangan menyimpulkan penggunaan produk dari lowongan kerja atau logo vendor saja.

### Minggu 4 — Validasi dan rencana engagement
- Lakukan validasi internal bersama sales/account owner.
- Uji hipotesis melalui discovery yang wajar dan sesuai etika.
- Perbarui skor hanya dengan bukti yang dapat ditelusuri.
- Tetapkan 3–5 akun untuk pendalaman Task 2 dan account profiling.

## 8. Template master data akun

Gunakan kolom berikut sebagai struktur data yang akan diperbarui pada tahap berikutnya:

| Field | Deskripsi |
|---|---|
| Account ID | Identifier internal yang konsisten |
| Nama KKKS | Nama entitas KKKS |
| Nama operator | Entitas operator wilayah kerja |
| Parent / group | Induk atau grup usaha, jika terverifikasi |
| Wilayah kerja | Nama WK |
| Status operasi | Eksplorasi, pengembangan, produksi, terminasi, atau belum diketahui |
| Jenis operasi | Onshore, offshore, gas, minyak, LNG, atau kombinasi |
| Indikator produksi | Angka, satuan, periode, dan sumber |
| Lokasi aset | Lokasi yang didukung sumber |
| Workforce / contractor | Data jumlah pekerja jika tersedia |
| IT / OT footprint | Sistem dan lingkungan yang diketahui |
| Security posture evidence | Bukti publik yang relevan; bukan asumsi |
| Privacy relevance | Proses data pribadi yang diketahui atau perlu divalidasi |
| Stakeholder | Nama/jabatan hanya jika sumber publik mendukung |
| Procurement route | Mekanisme pengadaan yang diketahui |
| Project signals 2027 | Tender, rencana, investasi, atau indikasi proyek yang bersumber |
| Opportunity hypothesis | Hipotesis solusi dan alasan |
| Evidence confidence | Tinggi / sedang / rendah dengan alasan |
| Account score | Skor tertimbang setelah data tersedia |
| Account owner | Penanggung jawab internal |
| Next action | Tindakan, PIC, dan tenggat |

## 9. Kesenjangan data dan batasan

Pada tahap ini, informasi yang tersedia belum cukup untuk menyimpulkan:
- Akun mana yang memiliki kelemahan keamanan siber atau ketidakpatuhan UU PDP.
- Produk keamanan apa yang telah digunakan setiap KKKS.
- Nilai anggaran TI/keamanan siber dan rencana pengadaan 2027 setiap KKKS.
- Identitas pengambil keputusan aktual dan sponsor proyek.
- Status tender, proyek berjalan, insiden, atau temuan audit yang tidak diumumkan.
- Hubungan kontraktual terkini antara operator, partner, dan penyedia layanan pada setiap wilayah kerja.

Daftar produksi menggunakan snapshot Mei 2026 dari sumber media yang mengutip paparan SKK Migas. Angka tersebut harus diperbarui dengan data resmi terbaru sebelum dipakai untuk keputusan final. Daftar ini juga tidak mencakup seluruh KKKS. Data produksi bukan proksi langsung bagi belanja TI atau tingkat risiko siber.

## 10. Registri sumber

| ID | Sumber | Jenis | Penggunaan | Batasan |
|---|---|---|---|---|
| S1 | [SKK Migas](https://www.skkmigas.go.id/) | Sumber resmi kelembagaan | Validasi data dan publikasi hulu migas | Data rinci perlu ditarik dari publikasi/dataset terkait |
| S2 | [Katadata Databoks — produksi minyak, kondensat, NGL per 31 Mei 2026](https://databoks.katadata.co.id/en/energy/statistics/6a34a54325d45/top-20-contractors-with-the-largest-oil-condensate-and-ngl-production-in-indonesia-as-of-may-2026) | Media/data sekunder | Universe akun dan indikator skala produksi minyak | Mengutip data SKK Migas; snapshot Mei 2026 |
| S3 | [CNBC Indonesia — penyaluran gas per 31 Mei 2026](https://www.cnbcindonesia.com/news/20260615105238-4-742854/hasilkan-5207-juta-kaki-kubik-hari-ini-sejumlah-raja-gas-di-ri) | Media, merujuk paparan SKK Migas | Universe akun gas | Perlu rekonsiliasi dengan data resmi |
| S4 | [Laporan Tahunan SKK Migas 2025 — salinan yang tersedia melalui Scribd](https://www.scribd.com/document/1075794271/Laporan-Tahunan-2025) | Salinan sekunder dokumen institusi | Konteks jumlah wilayah kerja dan kegiatan hulu migas | Bukan tautan publikasi resmi; verifikasi pada SKK Migas |
| S5 | [Kementerian ESDM — daftar KKKS CBM](https://migas.esdm.go.id/cms/uploads/uploads/daftar-kkks-cbm.pdf) | Sumber resmi ESDM | Contoh daftar operator untuk segmen CBM | Hanya mencakup CBM, bukan seluruh KKKS |

### Standar bukti untuk pembaruan

Setiap data akun yang material harus memiliki:
- Nama sumber dan URL langsung.
- Tanggal publikasi dan tanggal akses.
- Kutipan atau ringkasan fakta yang didukung sumber.
- Periode data dan satuan.
- Status fakta, inferensi, atau hipotesis.
- Tingkat keyakinan dan keterbatasan.

---

**Status dokumen:** Baseline awal untuk prioritisasi akun  
**Status prioritas:** Hipotesis urutan riset, belum merupakan kualifikasi peluang  
**Periode fokus:** 2027  
**Langkah berikutnya:** Validasi universe KKKS dari sumber resmi, lalu susun profil individual untuk akun Tier 1.
