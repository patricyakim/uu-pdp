# Sales Playbook KKKS 2027
**Panduan utama tim Sales dan Account Manager**  
**Batas intelijen: 11 November 2026**  
**Cakupan: Peluang Pelindungan Data Pribadi (PDP) dan keamanan siber pada KKKS hulu migas Indonesia**

---

## Cara menggunakan repositori ini

**Mulai dari dokumen ini.** Sales tidak perlu membaca seluruh dokumen riset untuk mulai bekerja. Playbook ini merangkum konteks akun, peluang yang layak diuji, pintu masuk percakapan, dan langkah berikutnya.

Dokumen lain di repositori adalah bahan pendukung. Buka hanya jika membutuhkan detail fakta, sumber, struktur buying center, atau hipotesis teknis. Untuk desain layanan, scope, deliverable, dan kerangka komersial PDP, gunakan [PDP Solution & Offering Architecture 2027](PDP_SOLUTION_OFFERING_ARCHITECTURE_2027.md). Untuk menyusun dokumen penawaran pelanggan, gunakan [PDP Proposal & SOW Template 2027](PDP_PROPOSAL_SOW_TEMPLATE_2027.md).

| Kelompok | Dokumen | Siapa yang perlu membaca | Kegunaan |
|---|---|---|---|
| **Bacaan utama sales** | **Sales Playbook KKKS 2027 (dokumen ini)** | Sales, Account Manager, Business Development | Ringkasan akun, strategi PDP, prioritas discovery, dan langkah komersial |
| **Prioritas akun** | [Master KKKS Account Prioritization Matrix 2027](KKKS_ACCOUNT_PRIORITIZATION_MATRIX_2027.md) | Sales Lead / Account Manager | Skor, cakupan bukti, dan urutan engagement KEI, Jadestone, Conrad/WNEL |
| **Eksekusi pursuit** | [Account Pursuit Plan — Top 3 KKKS](KKKS_ACCOUNT_PURSUIT_PLAN_TOP3_2027.md) | Account Manager / Sales / Presales | Buying center, entry point, penawaran awal, discovery, qualification gate, dan rencana 30/60/90 hari |
| **Arsitektur solusi** | [PDP Solution & Offering Architecture 2027](PDP_SOLUTION_OFFERING_ARCHITECTURE_2027.md) | Sales / Presales / Solution Architect / Delivery | Katalog layanan, scope, metodologi, deliverable, asumsi, batas tanggung jawab, dan kerangka estimasi |
| **Template proposal/SOW** | [PDP Proposal & SOW Template 2027](PDP_PROPOSAL_SOW_TEMPLATE_2027.md) | Sales / Presales / Delivery / Commercial | Template siap duplikasi untuk proposal, SOW, RACI, acceptance criteria, estimasi, dan persetujuan internal |
| Bacaan pendukung sales | [KKKS Target Account Intelligence 2027](KKKS_Target_Account_Intelligence_2027.md) | Account Manager / Sales Lead | Universe akun, snapshot produksi, kerangka prioritisasi |
| Bacaan pendukung sales | [KKKS Account Profiling Index 2027](KKKS_Account_Profiling_Index_2027.md) | Account Manager | Ringkasan profil delapan akun dan tautan profil rinci |
| Bacaan pendukung sales | [KKKS Buying-Center Intelligence 2027](KKKS_Buying_Center_Intelligence_2027.md) | Account Manager saat menyiapkan engagement | Peta fungsi pembeli, jalur akses, dan pertanyaan discovery |
| Bacaan pendukung sales | [KKKS Cybersecurity Opportunity Intelligence 2027](KKKS_Cybersecurity_Opportunity_Intelligence_2027.md) | Sales bersama Solution Architect | Bukti sinyal proyek/pengadaan dan status hipotesis peluang |
| **Bahan riset / referensi** | Semua dokumen individual di folder [accounts/](accounts/) | Solution Architect, presales, researcher, sales saat pendalaman | Fakta rinci, sumber, batasan, buying center, dan analisis per akun |
| Bahan riset regulasi | [Regulatory Intelligence Validation — UU PDP 2027](Regulatory_Intelligence_Validation_UU_PDP_2027.md) | Presales, Legal/Compliance, Solution Architect | Validasi isu hukum dan batas klaim regulasi |

**Folder `accounts/` tetap dipertahankan.** Tidak ada profil akun, buying-center profile, atau opportunity profile yang dihapus atau dipindahkan. Folder tersebut adalah repositori bukti dan bahan pendalaman, bukan daftar bacaan wajib.

### Cara membaca label intelijen

- **Fakta:** informasi yang dinyatakan oleh sumber yang dirujuk.
- **Sinyal (E1/E2):** bukti pengadaan atau aktivitas/proyek yang relevan, tetapi belum tentu merupakan peluang cybersecurity.
- **Inferensi:** interpretasi yang diturunkan dari fakta.
- **Hipotesis (H):** kemungkinan kebutuhan yang harus diuji langsung.
- **Terkualifikasi (Q):** kebutuhan, sponsor, jalur komersial, dan langkah berikutnya telah divalidasi bersama pelanggan.
- **Belum diketahui:** jangan diisi dengan asumsi.

Jangan mengubah sinyal proyek operasional menjadi klaim tender cybersecurity. Jangan mengasumsikan insiden, kelemahan, ketidakpatuhan, anggaran, vendor incumbent, atau sponsor tanpa bukti.

---

## 1. Ringkasan eksekutif untuk sales

UU No. 27 Tahun 2022 tentang Pelindungan Data Pribadi berlaku terhadap pemrosesan data pribadi. Relevansinya pada KKKS perlu ditentukan berdasarkan aktivitas pemrosesan dan peran entitas sebagai Pengendali Data Pribadi atau Prosesor Data Pribadi. Status sebagai operator migas tidak otomatis menentukan peran tersebut.

Area data yang layak menjadi bahan discovery di lingkungan hulu migas:

1. Data karyawan, kandidat, ekspatriat, dan tenaga kerja kontraktor.
2. Data kesehatan dan keselamatan kerja (HSE), termasuk data kesehatan yang bersifat spesifik.
3. Identitas pengunjung, kontrol akses fasilitas, CCTV, dan kemungkinan biometrik.
4. Data kru offshore, personel proyek, dan tenaga kerja pihak ketiga.
5. Akun pengguna, log, surel, dan catatan TI yang mengidentifikasi individu.
6. Data vendor perorangan dan data yang diproses oleh penyedia layanan.
7. Data komunitas atau pelapor yang dikelola dalam program hubungan masyarakat.

**Pesan komersial utama:** bantu pelanggan memahami data pribadi apa yang diproses, di mana data berada, siapa yang mengaksesnya, pihak ketiga mana yang memprosesnya, serta bagaimana kontrol dan bukti penerapannya dikelola.

Jangan memulai percakapan dengan ancaman denda atau tuduhan ketidakpatuhan. Mulailah dari proses bisnis, data, pihak ketiga, dan kontrol operasional.

### Penawaran PDP yang dapat dibentuk

| Tahap | Layanan | Hasil yang diharapkan |
|---|---|---|
| 1. Discover | Workshop dan asesmen awal PDP | Ruang lingkup pemrosesan, isu prioritas, dan pemangku kepentingan |
| 2. Map | Inventaris data pribadi dan data-flow mapping | Daftar proses, sistem, kategori data, penerima, dan aliran data |
| 3. Assess | Gap assessment dan DPIA support bila memenuhi kriteria | Daftar kesenjangan, risiko, dan rekomendasi |
| 4. Control | Rekomendasi kontrol akses, enkripsi, DLP, retensi, logging, dan vendor control | Desain kontrol dan rencana implementasi |
| 5. Operate | Dukungan tata kelola, monitoring, respons insiden, dan review berkala | Proses operasional dan bukti kontrol yang dapat ditinjau |

Pekerjaan interpretasi hukum, penetapan dasar pemrosesan, dan penilaian kewajiban hukum harus melibatkan fungsi Legal/penasihat hukum pelanggan. Tim teknologi membantu menerjemahkan kebutuhan yang telah disepakati menjadi kontrol dan proses.

---

## 2. Ringkasan delapan akun

Urutan di bawah adalah urutan kerja dan strategi engagement awal, bukan ranking anggaran, tingkat risiko siber, kematangan PDP, atau probabilitas kemenangan.

| Akun | Konteks yang diketahui | Arah percakapan sales | Status peluang PDP |
|---|---|---|---|
| **Pertamina Hulu Rokan (PHR)** | Operator dengan skala produksi minyak besar; aktivitas pengembangan dan layanan lapangan | Data pekerja/kontraktor, akses vendor, HR/HSE, dan pembagian tata kelola PHR–PHE | H — discovery |
| **ExxonMobil Cepu (EMCL)** | Operator Blok Cepu; bagian dari organisasi global; tata kelola lokal dan global perlu dipetakan | Data tenaga kerja dan kontraktor, sistem global, transfer lintas negara, standar privasi grup | H — discovery |
| **Pertamina EP (PEP)** | Portofolio lapangan luas dalam ekosistem Subholding Upstream Pertamina | Konsistensi pengelolaan data tenaga kerja/kontraktor lintas regional dan field; RACI PEP–PHE | H — discovery |
| **PetroChina International Jabung (PCJL)** | Operator WK Jabung; program drilling, workover, well service dan fasilitas gas | Data pekerja/vendor, akses pihak ketiga, data HSE dan proses vendor lintas mitra PSC | H — discovery |
| **Medco E&P Natuna** | Aset offshore South Natuna Sea Block B; sinyal pengadaan ICS Risk Assessment pada level Medco E&P Operations perlu ditindaklanjuti | Data kru offshore dan kontraktor, data HSE, vendor assurance, hubungan grup–aset | H — perlu validasi lingkup dan hasil assessment |
| **Kangean Energy Indonesia (KEI)** | Operator WK Kangean; produksi gas dari Pagerungan dan TSB; Rancak dan West Kangean menjadi konteks pengembangan | Data tenaga kerja proyek dan vendor, kontraktor drilling/engineering, HR/HSE, e-Procurement | H — discovery dengan pintu masuk proyek/vendor |
| **Jadestone Energy (Lemang)** | Operator Lemang PSC; Akatara telah berproduksi dengan fasilitas pemrosesan gas | Data personel Akatara dan manpower contractor, data HSE, akses vendor, aliran data ke grup | H — discovery |
| **Conrad Asia Energy / WNEL** | WNEL operator Duyung PSC/Mako; FID Maret 2026; first gas ditargetkan Q4 2027; lebih dari 90% capex contracts/LOA telah diterbitkan menurut laporan perusahaan | Data kru proyek/offshore, kontraktor MOPU/subsea/drilling, tata kelola data JV dan vendor, kesiapan operasi | H — project signal kuat, peluang PDP belum tervalidasi |

### Prioritas engagement PDP yang disarankan

Untuk perbandingan berbobot tiga akun fokus—KEI, Jadestone, dan Conrad/WNEL—gunakan [Master KKKS Account Prioritization Matrix 2027](KKKS_ACCOUNT_PRIORITIZATION_MATRIX_2027.md). Untuk langkah masuk, discovery, penawaran awal, dan rencana 30/60/90 hari, gunakan [Account Pursuit Plan — Top 3 KKKS](KKKS_ACCOUNT_PURSUIT_PLAN_TOP3_2027.md). Skor matriks bersifat indikatif dan harus dibaca bersama cakupan bukti; bukan probabilitas kemenangan atau bukti kebutuhan pelanggan.

1. **KEI:** pintu masuk praktis melalui proses tenaga kerja/vendor dan aktivitas proyek Rancak. Uji kebutuhan pengelolaan data kontraktor dan pihak ketiga.
2. **Jadestone:** masuk melalui operasi Akatara, manpower services, HR/HSE, dan pengelolaan vendor. Uji bagaimana data pekerja dan kontraktor diproses oleh entitas lokal dan grup.
3. **Conrad/WNEL:** manfaatkan fase menuju commissioning dan first gas untuk menguji tata kelola data personel proyek, kru offshore, kontraktor, dan vendor. Jangan menganggap paket proyek utama masih terbuka.
4. **Medco Natuna:** tindak lanjuti sinyal ICS Risk Assessment pada level Medco E&P Operations; untuk PDP, validasi proses data kru offshore dan kontraktor.
5. **PHR, EMCL, PEP, PCJL:** lakukan discovery terarah sesuai struktur grup, lapangan, dan model pengadaan masing-masing.

---

## 3. Strategi PDP khusus: Kangean Energy Indonesia Ltd.

### 3.1 Mengapa akun ini layak didekati

**Fakta bersumber dari riset akun:**
- KEI merupakan operator WK Kangean. Gas dari Pagerungan dan Terang Sirasun Batur (TSB) diproses dan disalurkan melalui East Java Gas Pipeline.
- EMP menyelesaikan akuisisi 25% participating interest Kangean dari JAPEX pada 25 November 2025 dan menyatakan menjadi pengendali Kangean melalui anak usahanya.
- EMP menyebut Rancak sebagai rencana pengembangan yang mencakup tiga sumur pengembangan, serta eksplorasi West Kangean.
- KEI memublikasikan prakualifikasi Project Management Team Services untuk Rancak Drilling Project pada Agustus 2026.
- KEI juga memublikasikan prakualifikasi layanan personel untuk fungsi procurement, inventory, transportation, commercial, dan legal pada November 2026. Paket tersebut bukan tender cybersecurity atau PDP.
- KEI memiliki kanal e-Procurement.

**Inferensi untuk sales:** kegiatan pengembangan lapangan dan penggunaan penyedia jasa menciptakan konteks yang masuk akal untuk menelusuri pemrosesan data personel, kontraktor, kandidat, pengunjung, dan vendor. Ini belum membuktikan adanya gap PDP.

### 3.2 Hipotesis kebutuhan PDP

| Area | Hipotesis yang perlu diuji | Bukti yang perlu diminta |
|---|---|---|
| Data tenaga kerja dan kontraktor | Data identitas, kredensial, dan penugasan personel mungkin dikelola lintas KEI dan penyedia jasa | Alur onboarding/offboarding, formulir, sistem, dan peran masing-masing pihak |
| Data HSE | Informasi kesehatan, pelatihan, dan insiden tenaga kerja dapat melibatkan data pribadi spesifik | Kategori data, hak akses, retensi, dan proses pembagian |
| Data proyek Rancak | Data personel project management, engineering, drilling, well testing, dan logistik dapat diproses oleh beberapa kontraktor | Daftar kategori vendor, aliran data, dan ketentuan kontrak |
| Pengadaan dan vendor | Proses prakualifikasi/e-Procurement dapat memproses data kontak dan dokumen personel/vendor | Pemberitahuan privasi, akses sistem, retensi, dan subprosesor |
| Akses fasilitas | Identitas, catatan pengunjung, CCTV, dan kemungkinan biometrik perlu dipetakan bila digunakan | Sistem kontrol akses, data yang direkam, tujuan, dan retensi |
| Grup EMP | Perlu diuji apakah data dipertukarkan atau diakses oleh fungsi grup | Entitas penerima, lokasi pemrosesan, dasar dan pengaturan transfer |

### 3.3 Proposisi nilai yang disarankan

**“Pemetaan dan pengendalian data tenaga kerja serta kontraktor untuk mendukung operasi lapangan dan proyek pengembangan Kangean.”**

Tawarkan program bertahap:
1. Workshop pemetaan proses data pekerja dan kontraktor.
2. Inventarisasi sistem dan aliran data untuk HR, HSE, procurement, akses fasilitas, dan penyedia jasa proyek.
3. Pemetaan peran KEI, EMP, dan vendor pada aktivitas pemrosesan yang dipilih.
4. Gap assessment terhadap kontrol akses, pembagian data, retensi, logging, dan pengamanan.
5. Rekomendasi DPIA bila aktivitas pemrosesan memenuhi kriteria berisiko tinggi.
6. Roadmap implementasi kontrol, bukan langsung menawarkan seluruh produk.

### 3.4 Buying center dan jalur masuk

| Fungsi sasaran | Peran yang perlu divalidasi | Agenda percakapan |
|---|---|---|
| Procurement / Supply Chain KEI | Gatekeeper vendor dan jalur pengadaan | Proses prakualifikasi, persyaratan vendor, dan data yang dikumpulkan |
| HR / fungsi pengelola tenaga kerja | Process owner data pekerja | Onboarding, data kandidat, kontraktor, dan retensi |
| HSE | Process owner data kesehatan dan keselamatan | Data kesehatan, akses, pembagian, dan retensi |
| IT / Digital / Cybersecurity | Technical authority | Sistem, akses, logging, keamanan aplikasi, dan vendor |
| Operations / Project Rancak | Pemilik proses operasional | Data personel proyek dan kontraktor di lokasi |
| Legal / Compliance | Interpretasi dan tata kelola | Peran pengendali/prosesor, kontrak, dan kebijakan |
| EMP | Group influencer / kemungkinan fungsi bersama | Kebijakan grup dan aliran data lintas entitas |

Nama individu, sponsor, budget owner, dan approval authority belum teridentifikasi. Jangan menyebut EMP sebagai pengambil keputusan tunggal untuk seluruh paket tanpa validasi delegasi KEI–EMP.

### 3.5 Pertanyaan discovery prioritas

1. Sistem apa yang digunakan untuk mengelola data pekerja KEI dan personel kontraktor?
2. Siapa yang menentukan tujuan pemrosesan data tenaga kerja: KEI, EMP, atau masing-masing penyedia jasa?
3. Data apa saja yang dikumpulkan untuk onboarding, akses fasilitas, HSE, dan penugasan lapangan?
4. Bagaimana data kesehatan dan data akses fasilitas dibatasi dan disimpan?
5. Apakah kontraktor dapat mengakses atau mengunduh data personel di luar kebutuhan pekerjaan?
6. Apakah kontrak jasa memuat ketentuan pemrosesan, keamanan, retensi, dan penghapusan data?
7. Apakah ada pertukaran data dengan fungsi grup EMP atau penyedia sistem di luar Indonesia?
8. Siapa yang menangani permintaan subjek data dan insiden yang melibatkan data pribadi?

### 3.6 Paket solusi dan peluang lanjutan

**Paket awal — PDP Workforce & Contractor Discovery**
- Workshop lintas HR, HSE, Procurement, IT, dan Legal.
- Data inventory dan data-flow mapping terbatas.
- Pemetaan pengendali/prosesor per aktivitas.
- Daftar risiko dan prioritas kontrol.

**Paket lanjutan — Privacy Control Enablement**
- IAM/MFA dan review akses.
- DLP/enkripsi sesuai hasil asesmen.
- Logging dan monitoring aktivitas akses.
- Vendor/third-party risk management.
- Retensi dan penghapusan terkontrol.
- DPIA support bila dibutuhkan.

Jangan menjual DLP sebagai solusi tunggal untuk seluruh kewajiban PDP. Pilihan teknologi harus mengikuti hasil pemetaan dan gap assessment.

### 3.7 Risiko komersial dan mitigasi

- **Akses ke sponsor belum diketahui:** minta pengantar melalui Procurement atau Operations, lalu bangun percakapan lintas fungsi.
- **Paket pengadaan yang ditemukan bukan paket PDP:** gunakan sebagai konteks pemetaan vendor, bukan klaim tender.
- **Pengaruh EMP belum jelas:** validasi RACI dan kebijakan grup sebelum menentukan pihak pembeli.
- **Persyaratan TKDN pada paket tertentu:** periksa persyaratan untuk paket yang benar-benar akan diikuti; jangan menggeneralisasi minimum TKDN 90% dari satu paket ke seluruh pengadaan KEI.
- **Kebutuhan belum terbukti:** mulai dari discovery/assessment terarah dengan ruang lingkup kecil.

### 3.8 Rencana 30/60/90 hari

| Periode | Tindakan | Hasil |
|---|---|---|
| 0–30 hari | Validasi kontak Procurement, HR/HSE, Operations, IT, dan Legal; siapkan peta proses tenaga kerja/vendor | Peta stakeholder dan agenda discovery |
| 31–60 hari | Jalankan workshop; pilih satu proses prioritas, misalnya onboarding kontraktor atau data HSE | Data-flow awal, isu yang disepakati, dan ruang lingkup asesmen |
| 61–90 hari | Presentasikan temuan, roadmap kontrol, opsi implementasi, dan model pengadaan | Proposal asesmen/implementasi dengan sponsor dan jalur komersial yang divalidasi |

**Kriteria naik status dari H ke Q:** pelanggan mengakui masalah tertentu, menunjuk process owner dan sponsor, menyepakati ruang lingkup, serta menjelaskan jalur anggaran/pengadaan dan jadwal.

---

## 4. Strategi PDP khusus: Jadestone Energy (Lemang) Pte. Ltd.

### 4.1 Mengapa akun ini layak didekati

**Fakta bersumber dari riset akun:**
- Jadestone Energy (Lemang) Pte. Ltd. merupakan operator Lemang PSC dan mengoperasikan lapangan gas Akatara.
- Akatara telah berproduksi. Laporan perusahaan menyebut rata-rata produksi 2025 sebesar 6.067 boe/d dan produksi H1 2026 sebesar 5.590 boe/d.
- Fasilitas pemrosesan gas Akatara dilaporkan memiliki uptime 94,4% pada 2025; pembaruan November 2026 menyebut sekitar 96% sejak restart setelah shutdown pemeliharaan April 2026.
- Prakualifikasi Provision of Manpower Services diterbitkan pada September 2026. Ini merupakan sinyal proses vendor untuk layanan tenaga kerja, bukan tender PDP/cybersecurity.
- Tata kelola lokal versus grup dan pemilik anggaran keamanan/PDP belum diketahui.

**Inferensi untuk sales:** operasi fasilitas gas yang aktif dan penggunaan layanan tenaga kerja memberi konteks untuk memetakan data pekerja, kontraktor, HSE, akses fasilitas, dan data yang diproses oleh vendor. Uptime bukan bukti adanya insiden atau kelemahan keamanan.

### 4.2 Hipotesis kebutuhan PDP

| Area | Hipotesis yang perlu diuji | Bukti yang perlu diminta |
|---|---|---|
| Manpower services | Penyedia jasa dapat mengumpulkan dan memproses data kandidat serta personel | Kontrak, alur data, daftar data, dan peran vendor |
| Data HSE | Informasi kesehatan dan keselamatan pekerja Akatara mungkin diproses lintas sistem | Kategori data, akses, retensi, dan pembagian |
| Operasi fasilitas | Identitas kru, pengunjung, dan catatan akses dapat dikelola oleh beberapa sistem | Sistem akses, CCTV, tujuan, dan retensi |
| Vendor/OEM | Data personel teknis dan kredensial akses mungkin dibagikan kepada pihak ketiga | Proses otorisasi, kontrol akses, dan klausul pemrosesan |
| Tata kelola grup | Sistem atau fungsi grup mungkin menerima atau mengakses data dari Indonesia | Lokasi pemrosesan, entitas penerima, dan pengaturan transfer |
| Hak dan akuntabilitas | Alur penanganan permintaan subjek data dan insiden perlu dipastikan | SOP, RACI, catatan pemrosesan, dan eskalasi |

### 4.3 Proposisi nilai yang disarankan

**“PDP workforce, HSE, dan contractor assurance untuk operasi Akatara.”**

Fokus pada kemampuan Jadestone mengendalikan data personel dan kontraktor sepanjang siklus kerja, termasuk pihak ketiga dan kemungkinan akses lintas grup.

Tahapan penawaran:
1. Workshop PDP untuk HR, HSE, Operations, IT, dan Procurement.
2. Pemetaan data pekerja, manpower contractor, kru fasilitas, pengunjung, dan vendor.
3. Pemetaan aliran data lokal–grup dan identifikasi transfer lintas negara yang benar-benar terjadi.
4. Review peran pengendali/prosesor dan kontrol kontraktual bersama Legal.
5. Gap assessment atas akses, pembagian, retensi, logging, dan respons insiden.
6. Roadmap kontrol serta dukungan implementasi bila ada gap yang disepakati.

### 4.4 Buying center dan jalur masuk

| Fungsi sasaran | Peran yang perlu divalidasi | Agenda percakapan |
|---|---|---|
| Asset / Indonesia Operations leadership | Executive sponsor dan pemilik hasil operasi | Akuntabilitas data personel dan kontraktor Akatara |
| HR / manpower management | Process owner | Data kandidat, onboarding, dan data tenaga kerja |
| HSE | Process owner data kesehatan/keselamatan | Data spesifik, pembatasan akses, dan retensi |
| IT / Cybersecurity / OT | Technical authority | Sistem, akses, logging, keamanan dan integrasi |
| Procurement / Supply Chain | Gatekeeper vendor | Kualifikasi manpower provider dan klausul kontrak |
| Legal / Compliance / Privacy | Interpretasi dan tata kelola | Peran pengendali/prosesor, transfer, dan akuntabilitas |
| Jadestone Energy plc | Group influencer | Kebijakan grup, sistem bersama, dan kemungkinan aliran data |

Economic buyer, sponsor PDP, technical authority, dan budget owner belum teridentifikasi. Jangan mengasumsikan fungsi grup atau lokal memiliki kewenangan tertentu sebelum dikonfirmasi.

### 4.5 Pertanyaan discovery prioritas

1. Siapa yang menjadi pengendali data personel dan kandidat dalam hubungan Jadestone–manpower provider?
2. Data apa yang dikumpulkan selama rekrutmen, onboarding, penempatan, pemeriksaan kesehatan, dan offboarding?
3. Apakah data HSE atau kesehatan dapat diakses oleh kontraktor atau penyedia layanan?
4. Bagaimana akses terhadap data pekerja dan kru Akatara diberikan, ditinjau, dan dicabut?
5. Apakah vendor manpower memiliki subkontraktor atau sistem sendiri untuk memproses data?
6. Apakah data dari Lemang PSC diakses oleh fungsi Jadestone di luar Indonesia?
7. Bagaimana perusahaan menangani retensi dan penghapusan data setelah kontrak tenaga kerja berakhir?
8. Apakah program PDP telah memiliki pemilik, rencana kerja, dan bukti kontrol yang dapat ditinjau?

### 4.6 Paket solusi dan peluang lanjutan

**Paket awal — Akatara Workforce & Vendor Privacy Review**
- Workshop lintas fungsi.
- Pemetaan data HR/manpower, HSE, akses fasilitas, dan vendor.
- Review aliran data dan peran para pihak.
- Daftar kontrol prioritas dan rencana tindak lanjut.

**Paket lanjutan — Privacy and Access Control**
- IAM/MFA dan review akses.
- DLP/enkripsi pada kanal yang relevan.
- Pengelolaan akses pihak ketiga.
- Vendor privacy/security assessment.
- Logging, monitoring, dan incident workflow.
- DPIA support jika pemrosesan aktual memenuhi kriteria.

### 4.7 Risiko komersial dan mitigasi

- **Tata kelola grup belum jelas:** identifikasi apakah kebijakan dan sistem diputuskan di Indonesia atau oleh Jadestone Energy plc.
- **Manpower tender bukan tender PDP:** gunakan sebagai pintu untuk memahami ekosistem vendor; jangan mengklaim ada anggaran PDP.
- **Operasi berjalan dan prioritas produksi:** jaga agar workshop tidak mengganggu operasi; usulkan sesi singkat dan fokus.
- **Data lintas negara belum diketahui:** jangan menyatakan ada transfer; jadikan pertanyaan discovery.
- **Solusi mungkin sudah tersedia di grup:** tawarkan gap assessment dan integrasi/optimalisasi, bukan otomatis mengganti sistem.

### 4.8 Rencana 30/60/90 hari

| Periode | Tindakan | Hasil |
|---|---|---|
| 0–30 hari | Identifikasi kontak Asset/Operations, HR, HSE, Procurement, IT, dan Legal; validasi governance lokal–grup | Peta stakeholder dan jalur keputusan awal |
| 31–60 hari | Lakukan discovery pada satu proses, misalnya manpower onboarding atau data HSE | Data-flow awal, pemilik proses, dan gap yang diakui |
| 61–90 hari | Susun proposal workforce/vendor privacy review dan roadmap kontrol | Proposal dengan ruang lingkup, sponsor, dan jalur pengadaan yang tervalidasi |

---

## 5. Strategi PDP khusus: Conrad Asia Energy / WNEL — Duyung PSC

### 5.1 Mengapa akun ini layak didekati

**Fakta bersumber dari riset akun:**
- WNEL merupakan operator Duyung PSC. Setelah farm-down, WNEL memegang 25% participating interest dan Nations Natuna Barat 75%; Conrad memiliki 91,5% saham WNEL sehingga kepentingan ekonomi efektif Conrad di Duyung 22,875%.
- Mako Gas Project mencapai FID pada Maret 2026. First gas ditargetkan Q4 2027.
- Proyek mencakup enam sumur subsea, MOPU, pemrosesan/kompresi, koneksi WNTS dan pipa Pemping menuju Batam.
- PLN EPI mengumumkan pasokan gas 111 MMSCFD selama 10 tahun; WNEL disebut sebagai operator.
- Laporan perusahaan menyebut lebih dari 90% komitmen capex proyek telah memiliki kontrak/letter of award.
- RACI JV, pemilik budget PDP, dan pembagian tanggung jawab cybersecurity belum ditemukan.

**Inferensi untuk sales:** fase konstruksi, commissioning, dan persiapan operasi berpotensi menjadi waktu yang tepat untuk memeriksa tata kelola data personel proyek, kru offshore, kontraktor, dan vendor. Namun, lebih dari 90% capex telah dikontrak/LOA; jangan mengasumsikan masih ada paket proyek utama yang terbuka.

### 5.2 Hipotesis kebutuhan PDP

| Area | Hipotesis yang perlu diuji | Bukti yang perlu diminta |
|---|---|---|
| Data personel proyek | Data pekerja konstruksi, engineering, drilling, dan commissioning dapat diproses oleh beberapa kontraktor | Daftar proses, sistem, kategori data, dan kontrak |
| Kru offshore dan akses fasilitas | Data identitas, sertifikasi, kesehatan, dan akses kru dapat dipertukarkan antarentitas | Proses onboarding, akses, dan pembagian data |
| Kontraktor MOPU/subsea | Vendor dan subkontraktor mungkin memproses data personel atas instruksi operator atau untuk tujuan sendiri | Peran masing-masing pihak dan klausul pemrosesan |
| Struktur JV | Data dapat diakses atau dipertukarkan antara WNEL, Conrad, dan Nations sesuai tata kelola proyek | RACI, data-sharing arrangement, dan approval matrix |
| Operasi pasca-handover | Proses data personel dan vendor akan berlanjut setelah first gas | Operating model, pemilik proses, retensi, dan SOP |
| Sistem global | Akses atau penyimpanan data di luar Indonesia perlu diuji, bukan diasumsikan | Lokasi sistem, penerima data, dan mekanisme transfer |

### 5.3 Proposisi nilai yang disarankan

**“PDP project-to-operations readiness untuk WNEL dan ekosistem Mako.”**

Pendekatan ini menghubungkan fase proyek dengan operasi mendatang:
1. Pemetaan data pribadi proyek dan kru yang terlibat dalam konstruksi, commissioning, dan operasi.
2. Identifikasi peran WNEL, Conrad, Nations, kontraktor, dan penyedia layanan untuk tiap aktivitas pemrosesan.
3. Review data-sharing dan klausul pemrosesan dengan dukungan Legal.
4. Penilaian kontrol akses, retensi, logging, dan penghapusan saat kontrak proyek berakhir.
5. DPIA support untuk aktivitas pemrosesan berisiko tinggi bila kriteria aktual terpenuhi.
6. Penetapan proses PDP dan kontrol untuk masa operasi setelah handover.

### 5.4 Buying center dan jalur masuk

| Fungsi sasaran | Peran yang perlu divalidasi | Agenda percakapan |
|---|---|---|
| WNEL project leadership | Operational owner dan calon sponsor | Kesiapan proses data menuju commissioning/operasi |
| WNEL project/technical authority | Pemilik proses dan sistem proyek | Data personel, kontraktor, sistem proyek, dan handover |
| Conrad executive/project leadership | Group influencer dan kemungkinan sponsor | Kebijakan grup, tata kelola proyek, dan investasi |
| Nations Natuna Barat | JV influencer dan pihak dengan kepentingan PSC | Hak keputusan dan pembagian tanggung jawab |
| HR / HSE / crewing | Process owner | Data kru, kesehatan, sertifikasi, dan akses |
| Procurement / Contracts | Gatekeeper kontrak | Klausul vendor, subprosesor, retensi, dan penghapusan |
| IT / OT / Security | Technical authority | Sistem, identitas, logging, dan keamanan |
| Legal / Compliance | Interpretasi dan tata kelola | Peran para pihak, perjanjian berbagi data, dan transfer |

WNEL adalah pintu masuk operasional utama. Conrad dan Nations perlu dipetakan sebagai bagian governance JV. PLN EPI adalah pembeli gas berdasarkan GSA, bukan otomatis pembeli atau pengambil keputusan cybersecurity/PDP di sisi operator.

### 5.5 Pertanyaan discovery prioritas

1. Siapa yang mengendalikan data personel proyek dan kru offshore pada setiap tahap proyek?
2. Apakah WNEL, Conrad, dan Nations memiliki akses ke sistem atau data yang sama?
3. Bagaimana kontrak MOPU, drilling, subsea, dan pipeline mengatur penggunaan serta penghapusan data personel?
4. Apakah vendor dan subkontraktor bertindak sebagai prosesor atas instruksi WNEL atau memiliki tujuan pemrosesan sendiri?
5. Apakah persyaratan privasi dan keamanan data sudah masuk dalam kontrak utama dan paket vendor?
6. Bagaimana data kesehatan, sertifikasi, identitas, dan akses kru dilindungi?
7. Apakah sistem proyek atau HR/crewing diakses dari luar Indonesia?
8. Siapa yang akan menerima tanggung jawab proses PDP setelah commissioning dan first gas?
9. Apakah ada kebutuhan pemetaan data atau readiness review sebelum operational handover?

### 5.6 Paket solusi dan peluang lanjutan

**Paket awal — Mako Project Workforce & Vendor Data Readiness**
- Workshop WNEL/Conrad dan fungsi proyek.
- Inventaris proses data personel, kru, vendor, dan subkontraktor.
- Pemetaan aliran data dan peran para pihak.
- Review klausul pemrosesan dan data-sharing bersama Legal.
- Daftar gap dan rencana mitigasi.

**Paket lanjutan — Project-to-Operations Privacy Controls**
- IAM/MFA dan kontrol akses pihak ketiga.
- DLP/enkripsi untuk alur data yang relevan.
- Retensi dan penghapusan data kontraktor setelah handover.
- Logging dan incident workflow.
- Vendor assurance.
- DPIA support bila diperlukan.

**Peluang tambahan:** integrasikan PDP readiness dengan independent OT/ICS assurance atau secure commissioning hanya bila ada ruang lingkup yang belum tercakup kontrak proyek. Jangan mencampur proposal PDP dengan OT security tanpa pemilik kebutuhan dan anggaran yang jelas.

### 5.7 Risiko komersial dan mitigasi

- **Lebih dari 90% capex sudah dikontrak/LOA:** cari scope yang belum tercakup, independent review, kebutuhan handover, atau operasi pasca-first gas; jangan mengasumsikan tender baru.
- **Struktur JV kompleks:** validasi approval matrix dan siapa yang berwenang membeli layanan.
- **WNEL dan Conrad bukan entitas yang sama:** pastikan calon kontrak, pemilik data, dan pihak pembayar.
- **Nations memiliki 75% PI:** pahami hak persetujuan sesuai JV documents; jangan menganggap Conrad dapat memutuskan sendiri.
- **PLN EPI bukan otomatis buyer keamanan:** gunakan sebagai konteks ketahanan pasokan, bukan target pembeli PDP operator.
- **Jadwal first gas dapat berubah:** ikat proposal pada milestone aktual setelah dikonfirmasi, bukan tanggal asumsi.

### 5.8 Rencana 30/60/90 hari

| Periode | Tindakan | Hasil |
|---|---|---|
| 0–30 hari | Identifikasi WNEL project leadership, project contracts, HR/HSE/crewing, IT/security, Legal; minta pemahaman governance JV | Peta stakeholder dan daftar kontrak/proses yang relevan |
| 31–60 hari | Workshop data proyek dan vendor; validasi proses personel, kru, dan data-sharing | Data-flow map awal dan scope readiness review |
| 61–90 hari | Susun proposal PDP project-to-operations readiness; validasi kontrak yang sudah mencakup kontrol dan jalur persetujuan | Proposal terarah dengan pembeli, ruang lingkup, dan milestone yang disepakati |

---

## 6. Playbook percakapan PDP lintas akun

### Pembuka untuk Legal / Compliance

“Kami ingin memahami bagaimana perusahaan menerjemahkan kewajiban UU PDP menjadi proses dan kontrol operasional, khususnya ketika data pekerja, kontraktor, dan vendor diproses oleh beberapa entitas. Apakah perusahaan sudah memiliki inventaris proses dan aliran data untuk area tersebut?”

### Pembuka untuk HR / HSE

“Dalam operasi hulu migas, data pekerja dan kontraktor dapat melibatkan identitas, data kesehatan, sertifikasi, dan akses fasilitas. Bagaimana data tersebut dikelola ketika prosesnya melibatkan vendor atau subkontraktor?”

### Pembuka untuk IT / Cybersecurity

“Kami ingin memahami apakah tim memiliki visibilitas atas lokasi data pribadi, hak akses, perpindahan data, serta aktivitas vendor yang memproses data. Apakah kontrol tersebut sudah terintegrasi dengan IAM, DLP, logging, dan monitoring yang ada?”

### Pembuka untuk Procurement

“Dalam proses prakualifikasi dan pengelolaan vendor, apakah perusahaan sudah memiliki persyaratan yang mengatur pemrosesan data pribadi oleh penyedia jasa, termasuk akses, retensi, penghapusan, dan pelaporan insiden?”

### Pertanyaan kualifikasi peluang

Sebelum membuat proposal, pastikan:
- Masalah atau proses yang perlu diperbaiki telah disebutkan oleh pelanggan.
- Process owner dan technical authority telah diketahui.
- Peran pengendali/prosesor dan entitas yang terlibat mulai jelas.
- Ruang lingkup asesmen atau implementasi disepakati.
- Sponsor dan budget owner telah dipetakan.
- Jalur pengadaan dan jadwal keputusan diketahui.
- Kriteria keberhasilan dan hasil kerja yang diharapkan jelas.

Jika hal-hal tersebut belum tersedia, peluang tetap berstatus hipotesis.

---

## 7. Panduan regulasi: apa yang boleh dan tidak boleh dikatakan sales

1. UU No. 27 Tahun 2022 telah berlaku sejak 17 Oktober 2022.
2. Kewajiban PDP bergantung pada pemrosesan dan peran para pihak. Jangan menganggap semua KKKS selalu menjadi pengendali untuk seluruh aktivitas.
3. Pasal 34 mengatur penilaian dampak untuk pemrosesan berisiko tinggi. Tidak semua pemrosesan otomatis membutuhkan DPIA.
4. Kewajiban penunjukan pejabat/fungsi PDP harus dinilai berdasarkan kriteria UU dan putusan MK yang relevan; jangan menyatakan semua perusahaan wajib menunjuk DPO.
5. Transfer data lintas negara perlu dianalisis berdasarkan aliran dan penerima data yang nyata. Jangan menyatakan semua data wajib disimpan di Indonesia.
6. Teknologi seperti DLP, IAM, enkripsi, dan SIEM dapat mendukung kontrol, tetapi pembelian produk tidak otomatis membuktikan kepatuhan.
7. PP No. 33 Tahun 2026 tercatat dalam bahan riset sebagai peraturan pelaksana. Tanggal efektif dan ketentuan rinci harus diperiksa pada naskah autentik yang diundangkan sebelum disampaikan sebagai nasihat hukum. Riset sebelumnya mencatat adanya perbedaan tanggal dalam publikasi sekunder; jangan mengulang tanggal tanpa validasi primer.

**Kalimat yang aman:** “Kami dapat membantu memetakan proses pemrosesan data pribadi dan mengevaluasi kontrol teknis-operasional yang relevan. Penetapan kewajiban hukum dan interpretasi regulasi perlu divalidasi bersama fungsi Legal atau penasihat hukum.”

**Hindari:** “Perusahaan pasti melanggar UU PDP”, “semua data harus berada di Indonesia”, “semua perusahaan wajib memiliki DPO”, atau “implementasi DLP menjamin kepatuhan”.

---

## 8. Rencana kerja sales 30 hari

| Minggu | Fokus | Aktivitas minimum | Output |
|---|---|---|---|
| 1 | Persiapan | Pilih akun, baca ringkasan playbook, tetapkan account owner dan tujuan engagement | Account brief satu halaman |
| 2 | Akses | Petakan HR, HSE, Legal, Procurement, IT/Cybersecurity, Operations | Stakeholder map |
| 3 | Discovery | Lakukan percakapan awal dan pilih satu proses PDP prioritas | Catatan discovery dan masalah yang diakui |
| 4 | Kualifikasi | Validasi sponsor, scope, anggaran, jalur pengadaan, dan next step | Opportunity record dan rencana tindak lanjut |

### Format catatan setiap pertemuan

- Akun dan entitas yang ditemui:
- Tanggal dan peserta:
- Proses bisnis yang dibahas:
- Kategori data pribadi:
- Sistem dan pihak ketiga:
- Masalah yang dinyatakan pelanggan:
- Bukti atau dokumen yang tersedia:
- Pemilik proses:
- Sponsor / budget owner:
- Jalur pengadaan:
- Solusi yang diminta atau layak diuji:
- Hal yang belum diketahui:
- Next action, PIC, dan tanggal:

---

## 9. Dokumen pendalaman per akun

Gunakan dokumen individual hanya ketika perlu memperdalam konteks atau menyiapkan pertemuan/proposal.

### Profil akun
- [Pertamina Hulu Rokan](accounts/KKKS_Account_Profile_Pertamina_Hulu_Rokan.md)
- [ExxonMobil Cepu](accounts/KKKS_Account_Profile_ExxonMobil_Cepu.md)
- [Pertamina EP](accounts/KKKS_Account_Profile_Pertamina_EP.md)
- [PetroChina International Jabung](accounts/KKKS_Account_Profile_PetroChina_Jabung.md)
- [Medco E&P Natuna](accounts/KKKS_Account_Profile_Medco_Natuna.md)
- [Kangean Energy Indonesia](accounts/KKKS_Account_Profile_Kangean_Energy_2027.md)
- [Jadestone Energy (Lemang)](accounts/KKKS_Account_Profile_Jadestone_Energy_2027.md)
- [Conrad Asia Energy / WNEL](accounts/KKKS_Account_Profile_Conrad_Energy_2027.md)

### Buying-center intelligence
- [Indeks Buying-Center Intelligence](KKKS_Buying_Center_Intelligence_2027.md)
- Profil buying center masing-masing akun tersedia di folder `accounts/` dengan awalan `KKKS_Buying_Center_`.

### Opportunity intelligence
- [Indeks Cybersecurity Opportunity Intelligence](KKKS_Cybersecurity_Opportunity_Intelligence_2027.md)
- Profil peluang masing-masing akun tersedia di folder `accounts/` dengan awalan `KKKS_Opportunity_Intelligence_`.

---

## 10. Batasan dan disiplin penggunaan

- Batas riset dokumen ini adalah 11 November 2026. Informasi operasional dan procurement dapat berubah.
- Data produksi pada dokumen target account merupakan snapshot Mei 2026 dari sumber sekunder yang mengutip paparan SKK Migas. Jangan menggunakannya sebagai angka produksi terkini atau proyeksi 2027.
- Tidak ada bukti publik yang cukup untuk menyatakan ketiga akun target memiliki insiden, kelemahan, ketidakpatuhan, anggaran PDP, atau tender cybersecurity.
- Sinyal tender manpower, drilling, engineering, dan project services bukan tender PDP/cybersecurity.
- Semua stakeholder dalam playbook adalah fungsi sasaran, bukan nama atau jabatan individu yang telah dikonfirmasi sebagai pengambil keputusan.
- Jangan mengasumsikan seluruh KKKS memiliki struktur, sistem, proses, atau kewajiban yang sama.
- Perbarui bukti dan tanggal validasi setiap kali ada percakapan baru dengan pelanggan.

**Dokumen ini adalah panduan penjualan dan intelijen awal, bukan nasihat hukum, audit kepatuhan, atau hasil asesmen teknis pada sistem pelanggan.**
