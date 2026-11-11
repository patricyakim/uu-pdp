# Profil Akun: PT Pertamina Hulu Rokan (PHR)
**Intelijen akun 2027 | Batas riset: 11 November 2026**

## 1. Ringkasan akun
PHR mengoperasikan Wilayah Kerja Rokan di Provinsi Riau. Dalam snapshot produksi minyak, kondensat, dan NGL hingga 31 Mei 2026 yang mengutip paparan Kepala SKK Migas kepada Komisi XII DPR pada 3 Juni 2026, PHR tercatat menghasilkan 131.040 barel per hari. Angka ini merupakan snapshot periode berjalan, bukan produksi tahunan atau angka produksi terkini pada tanggal dokumen ini. [S1]

Sumber industri yang diperiksa mencatat produksi bruto WK Rokan sepanjang 2025 sebesar 151.547 BOPD minyak dan 33,5 MMSCFD gas. Sumber tersebut juga melaporkan rata-rata minyak Januari–Juli 2026 sebesar 133.581 BOPD. [S2] Kedua angka tidak boleh dicampur dengan snapshot produksi KKKS per 31 Mei 2026 karena basis dan periodenya berbeda.

## 2. Fakta dan sinyal operasional
- PHR mengambil alih pengelolaan WK Rokan pada 9 Agustus 2021; akhir kontrak yang dicantumkan sumber industri adalah 8 Agustus 2041. [S2]
- Sumber yang sama melaporkan sumur pengembangan Tiang 00004 mulai berproduksi pada 24 Oktober 2026 dengan produksi awal 1.246 BOPD, dibandingkan target 230 BOPD. [S2]
- Pengumuman prakualifikasi CIVD pada Oktober 2026 menampilkan kebutuhan jasa sewa rig workover 550 HP dan jasa penyewaan/pengoperasian gas compressor beserta peralatan pendukung oleh PHR. [S3]
- PHE memuat proyek Rokan HO Development Phase 1 dan Phase 2 serta HO NDD Arewa 14 Stage 2 dalam daftar proyek dengan rentang penyelesaian 2024–2026. Ini merupakan konteks grup/subholding; status rinci per paket perlu dikonfirmasi langsung. [S4]

## 3. Peta pemangku kepentingan — hipotesis fungsi
| Fungsi | Relevansi percakapan | Status |
|---|---|---|
| IT / Digital / Enterprise Architecture | Arsitektur, integrasi, identitas, jaringan, layanan TI | Fungsi sasaran; nama pejabat belum dipetakan |
| OT / Automation / Control Systems | Segmentasi OT, akses jarak jauh, inventaris aset, pemantauan | Hipotesis kebutuhan; kondisi aktual belum diketahui |
| Information Security / Cybersecurity | Tata kelola keamanan, SOC, incident response, third-party risk | Fungsi sasaran; struktur dan sponsor belum diketahui |
| Operations / Production / Engineering | Dampak gangguan terhadap produksi dan keselamatan | Fungsi pengguna/mitra; prioritas aktual perlu discovery |
| Procurement / SCM / Vendor Management | Kualifikasi vendor dan jalur pengadaan | CIVD merupakan kanal publik pengadaan hulu migas; alur internal PHR perlu dikonfirmasi [S5] |
| Legal / Compliance / Privacy | Data pribadi, kontrak pemrosesan, tata kelola kepatuhan | Keterlibatan bergantung pada pemetaan data dan proses aktual |

## 4. Hipotesis peluang keamanan siber dan UU PDP
Hipotesis berikut adalah agenda discovery, bukan pernyataan bahwa PHR memiliki kelemahan:
1. **OT/IT security assessment:** pemetaan jalur konektivitas antara lingkungan korporat, fasilitas produksi, dan pihak ketiga.
2. **Privileged access dan remote access governance:** kontrol akses vendor/kontraktor, akun istimewa, pencatatan sesi, dan review berkala.
3. **SOC use case untuk operasi migas:** korelasi log identitas, endpoint, jaringan, dan akses jarak jauh; validasi kemampuan respons lintas IT/OT.
4. **Third-party cyber risk:** penilaian risiko penyedia jasa rig, compressor, engineering, dan maintenance yang memiliki akses ke sistem atau fasilitas.
5. **UU PDP:** identifikasi data pribadi pekerja, kontraktor, pengunjung, dan kandidat; pemetaan tujuan, dasar pemrosesan, retensi, akses, dan hubungan pengendali/prosesor.

## 5. Pertanyaan discovery
- Sistem produksi, engineering, dan fasilitas mana yang dikelola langsung PHR dan mana yang dikelola vendor/operator layanan?
- Bagaimana pemisahan jaringan IT dan OT, serta mekanisme akses jarak jauh untuk vendor?
- Apakah tersedia inventaris aset OT dan daftar koneksi eksternal yang disetujui?
- Bagaimana pengelolaan akun istimewa, kredensial bersama, dan sesi remote maintenance?
- Apakah SOC memantau sumber log OT atau hanya lingkungan IT?
- Data pribadi apa yang diproses dalam proses tenaga kerja, kontraktor, akses fasilitas, dan layanan kesehatan?
- Bagaimana persyaratan keamanan siber dimasukkan ke dokumen tender dan kontrak vendor?

## 6. Arah pendekatan komersial
Mulai dari workshop discovery berbasis risiko operasi dan pemetaan IT/OT, bukan langsung menawarkan platform. Gunakan pengumuman pengadaan rig dan compressor sebagai konteks meningkatnya aktivitas vendor, bukan bukti adanya proyek keamanan siber. Kembangkan peluang menjadi assessment terukur, roadmap prioritas, dan pilot dengan ruang lingkup yang disepakati.

## 7. Kesenjangan intelijen
Belum ditemukan bukti publik yang cukup untuk menyimpulkan arsitektur keamanan PHR, vendor keamanan yang digunakan, insiden siber, anggaran 2027, rencana tender keamanan, struktur pelaporan CISO, atau tingkat kematangan UU PDP. Semua hal tersebut harus divalidasi melalui discovery dan sumber primer.

## 8. Sumber
- [S1] Katadata Databoks, *Top 20 Contractors with the Largest Oil, Condensate, and NGL Production in Indonesia as of May 2026*, 19 Juni 2026: https://databoks.katadata.co.id/en/energy/statistics/6a34a54325d45/top-20-contractors-with-the-largest-oil-condensate-and-ngl-production-in-indonesia-as-of-may-2026
- [S2] Sorot Energi, profil Wilayah Kerja Rokan, diperiksa 11 November 2026: https://sorotenergi.com/peta-migas/wilayah-kerja/rokan/
- [S3] CIVD/SKK Migas, daftar undangan prakualifikasi 2026 (hasil indeks pencarian publik): https://civdmigas.skkmigas.go.id/index.jwebs
- [S4] Pertamina Hulu Energi, Laporan Keberlanjutan 2024/2025, ikhtisar proyek: https://phe.pertamina.com/uploads/2025/09/aec1d57a-1084-4385-8cbf-7e6b7eff8894.pdf
- [S5] CIVD/SKK Migas, portal Centralized Integrated Vendor Database: https://civdmigas.skkmigas.go.id/vnd/index.jwebs

**Keyakinan:** Tinggi untuk identitas operator dan snapshot produksi yang dikutip; sedang untuk sinyal proyek/pengadaan karena berasal dari publikasi sekunder/portal; rendah untuk hipotesis kebutuhan keamanan siber hingga divalidasi.
