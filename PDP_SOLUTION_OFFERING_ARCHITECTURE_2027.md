# PDP Solution & Offering Architecture 2027
**Panduan desain layanan untuk Sales, Presales, Solution Architect, dan Delivery**  
**Edisi:** 2027  
**Konteks:** KKKS hulu migas Indonesia  
**Status:** Kerangka penawaran; ruang lingkup dan estimasi setiap engagement wajib divalidasi

---

## 1. Tujuan dan prinsip desain

Dokumen ini menerjemahkan kebutuhan Pelindungan Data Pribadi (PDP) menjadi portofolio layanan konsultasi, asesmen, desain kontrol, implementasi teknis, dan dukungan operasional. Tujuannya adalah menghasilkan penawaran yang konsisten, dapat dikualifikasi, dapat dihitung, dan dapat diterima hasil kerjanya.

Arsitektur ini bukan pernyataan bahwa suatu KKKS telah melanggar UU PDP, memiliki kelemahan tertentu, atau membutuhkan seluruh layanan. Setiap peluang dimulai sebagai hipotesis dan baru menjadi ruang lingkup proyek setelah proses, pemilik, bukti, kebutuhan, serta jalur komersial divalidasi bersama pelanggan.

### Prinsip wajib

1. **Berangkat dari aktivitas pemrosesan.** Ruang lingkup ditentukan oleh proses bisnis, kategori data, tujuan, sistem, pihak yang terlibat, dan peran aktual para pihak.
2. **Pisahkan nasihat hukum dan pekerjaan teknologi.** Interpretasi hukum, penetapan dasar pemrosesan, penentuan peran pengendali/prosesor, dan kesimpulan kepatuhan harus dipimpin atau divalidasi fungsi Legal/penasihat hukum pelanggan.
3. **Bukti mendahului kesimpulan.** Temuan harus dapat ditelusuri ke wawancara, dokumen, konfigurasi, observasi, atau sampel yang disetujui.
4. **Tidak menjanjikan sertifikasi atau kepatuhan otomatis.** Pembelian atau implementasi DLP, IAM, enkripsi, SIEM, atau platform privasi tidak dengan sendirinya membuktikan kepatuhan.
5. **Modular dan bertahap.** Pelanggan dapat memulai dari discovery atau satu proses prioritas, lalu memperluas berdasarkan hasil.
6. **Minimalkan paparan data.** Asesmen sedapat mungkin menggunakan metadata, sampel tersamarkan, dan akses baca-saja. Pengumpulan salinan data pribadi harus memiliki persetujuan, tujuan, pengamanan, dan masa simpan yang jelas.
7. **Jaga independensi dan batas pengujian.** Pengujian teknis tidak boleh mengganggu operasi produksi, keselamatan, atau sistem OT/ICS.

## 2. Arsitektur portofolio layanan

| Kode | Layanan | Tujuan utama | Posisi dalam perjalanan |
|---|---|---|---|
| PDP-01 | PDP Readiness Assessment | Memahami kondisi awal, tata kelola, dan area prioritas | Discover |
| PDP-02 | Personal Data Inventory & Data Mapping | Mendokumentasikan aktivitas pemrosesan dan aliran data | Map |
| PDP-03 | DPIA Support | Mendukung penilaian dampak untuk pemrosesan berisiko tinggi | Assess |
| PDP-04 | Privacy Governance & Operating Model | Menetapkan peran, proses, kebijakan, dan mekanisme pengawasan | Govern |
| PDP-05 | Technical Privacy Controls | Mendesain dan/atau menerapkan kontrol teknologi yang disepakati | Control |
| PDP-06 | Managed Privacy Operations | Mendukung operasi, pemantauan, dan perbaikan berkelanjutan | Operate |

Layanan dapat dijual terpisah atau sebagai program bertahap. PDP-01 dapat menjadi pintu masuk, tetapi tidak wajib menjadi prasyarat apabila pelanggan telah menyediakan ruang lingkup dan bukti yang memadai. PDP-03 hanya dilakukan bila karakteristik pemrosesan aktual memenuhi kriteria yang relevan dan pelanggan menyetujui tujuan serta metodologinya.

## 3. Standar delivery lintas layanan

### 3.1 Siklus engagement

1. **Qualify:** konfirmasi masalah yang dinyatakan pelanggan, sponsor, process owner, technical authority, entitas kontrak, dan jalur pengadaan.
2. **Scope:** sepakati proses, unit, lokasi, sistem, periode, sampel, metode, batas akses, serta pengecualian.
3. **Mobilize:** kickoff, RACI, jadwal, daftar permintaan informasi, aturan akses, dan protokol penanganan data.
4. **Discover and assess:** wawancara, telaah dokumen, walkthrough proses, observasi, dan validasi bukti.
5. **Validate:** diskusikan fakta dan ketidakpastian dengan pemilik proses; catat tanggapan pelanggan.
6. **Deliver:** serahkan keluaran sesuai kriteria penerimaan.
7. **Close and transition:** paparkan prioritas, risiko residual, keputusan yang dibutuhkan, dan opsi tahap berikutnya.

### 3.2 Klasifikasi hasil

Setiap laporan menggunakan label yang konsisten:

- **Fakta:** didukung bukti yang dapat ditelusuri.
- **Temuan:** kondisi yang diamati dan dibandingkan dengan kriteria yang disepakati.
- **Inferensi:** interpretasi atas fakta/temuan, dinyatakan sebagai interpretasi.
- **Risiko:** kemungkinan dan dampak yang perlu dipertimbangkan; metode penilaian harus dijelaskan.
- **Rekomendasi:** tindakan yang diusulkan, pemilik, prioritas, dan dependensi.
- **Belum diketahui:** informasi yang belum tersedia atau belum dapat diuji.

Hindari label “patuh/tidak patuh” kecuali penilaian hukum memang termasuk ruang lingkup, kriteria dan otoritas penilai telah disepakati, serta Legal pelanggan terlibat. Untuk layanan teknologi, gunakan istilah seperti “kontrol tersedia”, “kontrol belum dibuktikan”, “kesenjangan desain”, atau “kesenjangan implementasi”.

### 3.3 Bukti dan pengelolaan data

- Gunakan daftar bukti dengan ID, pemilik, tanggal, sumber, status, dan keterbatasan.
- Catat apakah bukti berasal dari wawancara, dokumen, konfigurasi, observasi, atau sampel.
- Jangan meminta dataset produksi penuh jika metadata atau sampel tersamarkan cukup.
- Tentukan kanal transfer, enkripsi, hak akses, lokasi penyimpanan, retensi, dan penghapusan artefak proyek.
- Catat pengecualian dan area yang tidak dapat diakses; jangan menganggapnya telah diuji.
- Pelanggan bertanggung jawab atas keabsahan pemberian akses dan otorisasi penggunaan data/sistem.

## 4. Definisi layanan

### PDP-01 — PDP Readiness Assessment

**Tujuan**  
Mendapatkan gambaran awal tentang proses pemrosesan data pribadi, tata kelola, kontrol yang telah tersedia, kesenjangan yang dapat dibuktikan, dan prioritas tindak lanjut.

**Ruang lingkup standar**
- Kickoff dan penetapan unit/proses dalam cakupan.
- Wawancara terbatas dengan Legal/Compliance, HR, HSE, Procurement, Operations, dan IT/Security sesuai relevansi.
- Telaah kebijakan, prosedur, pemberitahuan privasi, kontrak vendor, catatan pemrosesan, dan artefak yang disediakan.
- Pemeriksaan tingkat tinggi terhadap pengumpulan, penggunaan, akses, pembagian, penyimpanan, retensi, penghapusan, dan penanganan permintaan/insiden.
- Penilaian kesiapan tata kelola dan kontrol berdasarkan kriteria yang disepakati.
- Penyusunan prioritas perbaikan dan rekomendasi tahapan lanjutan.

**Metodologi**
1. Tetapkan batas organisasi dan proses.
2. Kirim information request list.
3. Lakukan wawancara dan walkthrough.
4. Telaah bukti dan catat keterbatasan.
5. Nilai kondisi terhadap kriteria yang disepakati.
6. Validasi temuan faktual dengan pemilik proses.
7. Susun laporan dan sesi paparan.

**Keluaran**
- Executive summary.
- Scope, metodologi, dan batasan asesmen.
- Process and stakeholder overview.
- Readiness/gap register beserta bukti dan tingkat keyakinan.
- Risk and priority register.
- Rekomendasi roadmap 90–180 hari sebagai rancangan awal, bukan komitmen implementasi.
- Daftar informasi yang masih diperlukan.

**Personel indikatif**
- Engagement Lead / Project Manager.
- Privacy/PDP Consultant.
- Business Process Analyst.
- Technical Security Consultant bila kontrol teknologi masuk cakupan.
- Legal adviser pelanggan sebagai reviewer/otoritas interpretasi hukum.

**Asumsi dan dependensi**
- Pelanggan menunjuk sponsor dan process owner.
- Dokumen dan narasumber tersedia sesuai jadwal.
- Penilaian dibatasi pada unit, proses, lokasi, dan periode yang disepakati.
- Tidak termasuk penetration testing, audit forensik, legal opinion, sertifikasi, atau pemeriksaan seluruh sistem.

**Kriteria penerimaan**
- Laporan mencantumkan cakupan, metode, bukti, temuan, keterbatasan, dan rekomendasi.
- Temuan faktual telah melalui sesi validasi pelanggan.
- Daftar area yang tidak dapat dinilai dinyatakan eksplisit.

**Model komersial**  
Fixed fee untuk cakupan dan jumlah proses/wawancara yang jelas; time and material untuk discovery awal yang batasnya belum dapat dipastikan. Variabel harga: jumlah entitas, unit, proses, lokasi, narasumber, kompleksitas vendor, dan kedalaman pemeriksaan.

### PDP-02 — Personal Data Inventory & Data Mapping

**Tujuan**  
Membangun inventaris aktivitas pemrosesan dan peta aliran data yang dapat digunakan pelanggan untuk tata kelola, pengendalian, evaluasi risiko, dan pemeliharaan berkala.

**Ruang lingkup standar**
- Identifikasi proses bisnis yang memproses data pribadi.
- Inventaris kategori subjek data dan kategori data.
- Dokumentasi tujuan pemrosesan sebagaimana dinyatakan pemilik proses.
- Pemetaan sistem, media, lokasi, penerima, vendor, dan pihak lain yang terlibat.
- Pencatatan retensi/penghapusan sesuai informasi pelanggan.
- Pemetaan aliran data masuk, internal, keluar, dan akses lintas entitas/lokasi jika ada.
- Pencatatan peran para pihak sebagai input untuk validasi Legal, bukan penetapan hukum oleh tim teknologi.

**Metodologi**
1. Tetapkan taksonomi dan template inventaris.
2. Pilih proses prioritas dan pemilik proses.
3. Lakukan workshop per proses.
4. Telusuri aliran data melalui sistem, formulir, kontrak, dan pihak penerima.
5. Validasi diagram dengan process owner dan system owner.
6. Konsolidasikan inventaris, data-flow map, dan gap informasi.

**Keluaran**
- Personal Data Processing Inventory.
- Data Flow Diagram per proses atau kelompok proses.
- System/application and third-party register.
- Data recipient and transfer register berdasarkan bukti yang tersedia.
- Retention and disposal register berdasarkan kebijakan/informasi pelanggan.
- Assumption, issue, dan unresolved-question log.
- Rekomendasi pemeliharaan inventaris.

**Personel indikatif**
- Project Manager.
- Privacy Consultant.
- Business Analyst / Data Mapper.
- System Analyst atau Application Architect.
- Perwakilan process owner dan system owner dari pelanggan.

**Asumsi dan dependensi**
- Pelanggan menunjuk pemilik proses dan sistem.
- Data mapping dilakukan melalui workshop, dokumen, dan walkthrough; bukan discovery otomatis atas seluruh repositori.
- Jumlah proses, sistem, entitas, vendor, dan lokasi dibatasi dalam SOW.
- Akses ke sistem produksi tidak termasuk kecuali disepakati khusus.

**Kriteria penerimaan**
- Setiap proses dalam cakupan memiliki pemilik dan status validasi.
- Diagram menunjukkan sumber, penggunaan, penyimpanan, penerima, dan titik perpindahan yang diketahui.
- Unknowns, asumsi, serta area yang belum divalidasi ditandai.
- Pelanggan menyetujui inventaris sebagai representasi proses yang disampaikan, bukan sebagai jaminan kelengkapan absolut.

**Model komersial**  
Per proses atau work package; dapat menggunakan fixed fee setelah jumlah proses dan kompleksitas dipastikan. Variabel utama: jumlah proses, sistem, integrasi, entitas, vendor, variasi lokasi, dan kebutuhan workshop.

### PDP-03 — DPIA Support

**Tujuan**  
Mendukung pelanggan dalam mengidentifikasi dan mendokumentasikan dampak serta risiko terhadap pelindungan data pribadi untuk aktivitas pemrosesan yang dinilai berisiko tinggi, sesuai kriteria yang ditetapkan bersama Legal pelanggan.

**Ruang lingkup standar**
- Konfirmasi aktivitas pemrosesan yang akan dinilai.
- Pengumpulan konteks, tujuan, kategori data, subjek data, sistem, penerima, dan pihak pemroses.
- Workshop identifikasi kebutuhan dan proporsionalitas pemrosesan dari sisi proses/teknologi.
- Identifikasi skenario risiko privasi dan keamanan.
- Evaluasi kontrol yang telah tersedia dan rencana mitigasi.
- Penyusunan dokumentasi pendukung dan action register.
- Review bersama process owner, security, privacy, dan Legal pelanggan.

**Metodologi**
1. Legal/privacy lead pelanggan mengonfirmasi alasan dan dasar dilakukannya DPIA.
2. Tetapkan aktivitas, batas, dan metodologi penilaian.
3. Petakan aliran data dan konteks pemrosesan.
4. Identifikasi risiko terhadap subjek data dan proses.
5. Nilai kontrol dan mitigasi yang direncanakan.
6. Dokumentasikan residual risk dan keputusan pemilik risiko.
7. Lakukan review dan persetujuan sesuai tata kelola pelanggan.

**Keluaran**
- DPIA working paper / supporting assessment.
- Processing context and data-flow summary.
- Risk scenario and control register.
- Mitigation/action plan dengan pemilik dan target.
- Residual-risk and decision log.
- Daftar isu yang memerlukan keputusan Legal atau manajemen.

**Personel indikatif**
- Privacy/DPIA Lead.
- Security Risk Consultant.
- Business Process Analyst.
- Technical SME sesuai sistem/proses.
- Legal counsel dan risk owner pelanggan.

**Batas tanggung jawab**
- Layanan ini adalah dukungan metodologi, proses, risiko, dan teknologi; bukan pengganti penasihat hukum.
- Tim tidak menetapkan dasar pemrosesan yang sah, tidak mengeluarkan legal opinion, dan tidak mengambil alih keputusan menerima risiko.
- Penentuan kewajiban DPIA dan persetujuan akhir dilakukan pelanggan dengan dukungan Legal.
- Tidak termasuk penilaian dampak lingkungan, keselamatan proses, atau HAZOP kecuali dinyatakan terpisah.

**Kriteria penerimaan**
- Aktivitas pemrosesan dan batas penilaian terdokumentasi.
- Skenario risiko, kontrol, mitigasi, dan residual risk tercatat.
- Keputusan yang membutuhkan Legal atau risk owner ditandai dan dieskalasikan.
- Dokumen direview oleh pemilik proses dan fungsi yang ditunjuk pelanggan.

**Model komersial**  
Per aktivitas pemrosesan atau use case. Harga bergantung pada kompleksitas data, jumlah sistem/pihak, tingkat risiko, jumlah workshop, dan kebutuhan SME. Jangan menjual DPIA generik tanpa aktivitas pemrosesan yang jelas.

### PDP-04 — Privacy Governance & Operating Model

**Tujuan**  
Membantu pelanggan membentuk atau memperbaiki tata kelola PDP agar peran, kebijakan, proses, eskalasi, dan pengawasan dapat dijalankan secara konsisten.

**Ruang lingkup standar**
- Review model tata kelola dan struktur tanggung jawab yang ada.
- Penyusunan target operating model dan RACI.
- Penyusunan atau perbaikan kebijakan/standar/prosedur prioritas.
- Desain proses permintaan subjek data, insiden, vendor review, retensi, penghapusan, dan perubahan pemrosesan.
- Desain mekanisme pelaporan, metrik, komite, dan eskalasi.
- Rencana awareness dan pelatihan berbasis peran.

**Keluaran**
- Privacy Governance Operating Model.
- RACI dan stakeholder map.
- Policy/procedure gap register dan dokumen prioritas sesuai SOW.
- Process workflow dan escalation matrix.
- KPI/KRI proposal dan management reporting template.
- Awareness/training material dan implementation roadmap.

**Personel indikatif**
- Governance/Privacy Lead.
- Business Process Consultant.
- Change/Training Consultant.
- Security Consultant bila kontrol teknis terkait.
- Legal pelanggan sebagai reviewer kebijakan dan interpretasi.

**Asumsi dan batasan**
- Keputusan struktur organisasi, penunjukan pejabat/fungsi, dan penerimaan kebijakan tetap pada manajemen pelanggan.
- Penyusunan dokumen tidak otomatis menjamin penerapan atau efektivitasnya.
- Legal review formal dan legal opinion dikecualikan kecuali disepakati dengan penasihat hukum yang berwenang.

**Kriteria penerimaan**
- Model, RACI, workflow, dan dokumen yang tercantum dalam SOW diserahkan.
- Pemilik proses dan jalur eskalasi telah direview pelanggan.
- Keputusan yang masih terbuka dicatat dalam decision log.

**Model komersial**  
Work package per domain tata kelola atau fixed fee untuk jumlah kebijakan/prosedur yang ditentukan. Perubahan besar pada struktur organisasi atau jumlah entitas diperlakukan sebagai change request.

### PDP-05 — Technical Privacy Controls

**Tujuan**  
Menerjemahkan kebutuhan dan risiko yang telah disepakati menjadi desain atau implementasi kontrol teknologi yang relevan dengan arsitektur pelanggan.

**Katalog kontrol potensial**
- Identity and Access Management (IAM), MFA, privileged access, access recertification.
- Data Loss Prevention (DLP) dan kontrol kanal perpindahan data.
- Enkripsi data at rest/in transit dan pengelolaan kunci.
- Data discovery/classification dan pelabelan.
- Logging, monitoring, audit trail, dan integrasi SIEM/SOC.
- Endpoint, email, collaboration, dan cloud security controls.
- Third-party access, remote access, dan vendor security controls.
- Backup, recovery, secure deletion, dan retention enforcement bila didukung platform.
- Workflow untuk permintaan subjek data dan insiden privasi melalui platform yang tersedia.

**Tahapan delivery**
1. Validasi use case, risiko, dan kebutuhan kontrol.
2. Assessment arsitektur dan kondisi teknologi saat ini.
3. Desain target state, integrasi, dan security architecture.
4. Pilot/PoC terbatas bila diperlukan.
5. Implementasi sesuai change window dan change management.
6. Uji fungsi, tuning, dokumentasi, dan knowledge transfer.
7. Serah terima operasional dan backlog perbaikan.

**Keluaran**
- Control requirement and traceability matrix.
- Current-state and target-state architecture.
- High-level/low-level design sesuai SOW.
- Implementation/configuration record.
- Test plan, test result, dan exception register.
- Operational runbook dan knowledge-transfer record.

**Personel indikatif**
- Solution Architect.
- Security/IAM/DLP/Cloud Engineer sesuai teknologi.
- Project Manager.
- SOC/Operations Engineer untuk integrasi monitoring.
- System owner dan change authority pelanggan.

**Asumsi dan pengecualian**
- Lisensi, perangkat, infrastruktur, konektivitas, dan biaya pihak ketiga dicantumkan terpisah.
- Akses admin, change approval, backup, dan maintenance window disediakan pelanggan.
- Implementasi pada OT/ICS memerlukan risk review, otorisasi asset owner, koordinasi operasi, dan prosedur keselamatan; tidak ada perubahan aktif pada sistem produksi tanpa persetujuan tertulis.
- Migrasi data, remediasi seluruh temuan, dan integrasi di luar daftar sistem tidak termasuk kecuali dinyatakan.
- Kontrol teknologi mendukung tujuan PDP; tidak menjamin kepatuhan hukum.

**Kriteria penerimaan**
- Desain dan konfigurasi sesuai requirement yang disetujui.
- Uji fungsi pada skenario yang disepakati lulus atau memiliki exception yang diterima.
- Dokumentasi, runbook, dan knowledge transfer diserahkan.
- Open issue dan risiko residual ditandatangani/diakui pemilik pelanggan.

**Model komersial**  
Pisahkan professional services, lisensi/subscription, perangkat, integrasi, dan managed services. Estimasi berdasarkan jumlah user/endpoint, workload, aplikasi, data source, site, integrasi, use case, kompleksitas kebijakan, dan jam implementasi.

### PDP-06 — Managed Privacy Operations

**Tujuan**  
Mendukung pelanggan menjalankan proses PDP secara berkelanjutan melalui layanan operasional terukur, tanpa mengambil alih akuntabilitas hukum dan keputusan bisnis pelanggan.

**Service tower yang dapat dipilih**
- Privacy operations coordination dan governance reporting.
- Pemeliharaan inventaris pemrosesan dan data-flow register.
- Koordinasi review vendor/privacy questionnaire.
- Koordinasi permintaan subjek data dan tracking SLA.
- Privacy incident triage dan koordinasi eskalasi.
- Retention/deletion review coordination.
- Control monitoring dan evidence collection.
- Awareness calendar dan reporting.
- Dukungan review berkala terhadap perubahan proses/sistem.

**Model layanan**
- **Advisory support:** jam konsultasi dan review berkala.
- **Co-managed:** tim penyedia menjalankan aktivitas operasional tertentu bersama tim pelanggan.
- **Managed operations:** penyedia mengoperasikan service tower yang didefinisikan dalam SLA dan RACI.

**Keluaran**
- Monthly/quarterly service report.
- Processing inventory change log.
- Vendor review tracker.
- Data subject request tracker.
- Incident and escalation log.
- Control/evidence status report.
- Improvement backlog dan service review minutes.

**Personel indikatif**
- Privacy Operations Lead.
- Privacy Analyst.
- Security Operations liaison.
- Service Delivery Manager.
- Legal, HR, IT, dan process owner pelanggan sesuai kasus.

**Batas tanggung jawab**
- Pelanggan tetap menjadi pemilik keputusan, kewajiban hukum, komunikasi regulator/subjek data, dan penerimaan risiko kecuali mandat yang sah dan eksplisit menyatakan lain.
- SLA hanya berlaku untuk aktivitas yang berada dalam kendali penyedia.
- Incident response teknis/forensik, legal representation, dan komunikasi regulator bukan bagian otomatis dari layanan ini.
- Jam layanan, kanal, severity, response target, dependency, dan escalation path wajib ditetapkan dalam SOW/SLA.

**Kriteria penerimaan**
- Service catalogue, RACI, SLA, dan runbook disetujui.
- Laporan periodik disampaikan sesuai kalender.
- Tiket, eskalasi, dan aktivitas tercatat.
- Pengecualian dan ketergantungan pelanggan dilaporkan secara transparan.

**Model komersial**  
Biaya bulanan/kuartalan berdasarkan service tower, volume kasus, jumlah entitas/proses/vendor, jam layanan, coverage, SLA, dan kebutuhan personel. Biaya di luar kapasitas atau di luar jam layanan harus diatur sebagai mekanisme tambahan.

## 5. Paket komersial modular

Paket berikut adalah cara mengemas layanan, bukan produk baku dengan harga atau durasi tetap. Scope final harus ditentukan setelah discovery.

| Paket | Komponen utama | Hasil yang dijanjikan |
|---|---|---|
| PDP Discovery Sprint | PDP-01 terbatas pada proses prioritas | Baseline, gap awal, dan keputusan tahap berikutnya |
| Data Visibility Package | PDP-02 untuk proses/unit terpilih | Inventaris dan peta aliran data yang divalidasi |
| High-Risk Processing Review | PDP-02 terarah + PDP-03 | Dokumentasi risiko dan rencana mitigasi untuk use case terpilih |
| Privacy Governance Setup | PDP-04 | RACI, workflow, kebijakan/prosedur prioritas, dan roadmap |
| Privacy Control Enablement | PDP-05 | Desain/implementasi kontrol teknologi terpilih |
| Co-managed Privacy Operations | PDP-06 | Operasi service tower sesuai SLA/RACI |

**Urutan yang lazim:** Discovery → Mapping → Assess → Govern/Control → Operate. Urutan dapat disesuaikan dengan kesiapan dan prioritas pelanggan.

## 6. Penyesuaian use case untuk tiga akun fokus

Penyesuaian di bawah merupakan hipotesis engagement berdasarkan konteks akun dalam riset internal. Bukan klaim bahwa kebutuhan, gap, anggaran, atau tender telah dikonfirmasi.

### 6.1 Kangean Energy Indonesia (KEI)

**Hipotesis entry point:** data tenaga kerja, manpower provider, kontraktor proyek Rancak, HR/HSE, Procurement, dan sistem e-Procurement.

| Area | Modul yang relevan | Pertanyaan validasi |
|---|---|---|
| Workforce/vendor data | PDP-01, PDP-02 | Proses apa yang mengumpulkan data kandidat, personel, sertifikasi, dan vendor? |
| Rancak project contractors | PDP-02, PDP-03 bila relevan | Pihak mana yang mengakses atau menyimpan data personel proyek? |
| HR/HSE | PDP-02, PDP-04 | Bagaimana akses, retensi, dan pembagian data HSE dikelola? |
| Vendor access and systems | PDP-05 | Apakah terdapat kebutuhan kontrol akses pihak ketiga yang belum tercakup? |
| Ongoing governance | PDP-04, PDP-06 | Siapa process owner dan bagaimana RACI KEI–EMP dijalankan? |

**Penawaran awal yang dapat diuji:** *Contractor Workforce Data Discovery* — workshop terarah dan pemetaan satu atau dua proses tenaga kerja/vendor. Jangan menyimpulkan persyaratan TKDN/CIVD atau jalur pengadaan untuk paket PDP tanpa konfirmasi procurement.

### 6.2 Jadestone Energy (Lemang)

**Hipotesis entry point:** operasi Akatara, manpower services, HR/HSE, pengelolaan vendor/OEM, serta hubungan tata kelola lokal dan grup.

| Area | Modul yang relevan | Pertanyaan validasi |
|---|---|---|
| Manpower and contractor lifecycle | PDP-01, PDP-02 | Data apa yang dikelola oleh Jadestone dan manpower provider? |
| HSE and facility access | PDP-02, PDP-03 bila relevan | Apakah data kesehatan/akses diproses dan dibagikan lintas pihak? |
| Local–group data flow | PDP-02, PDP-04 | Apakah sistem atau fungsi grup mengakses data dari Indonesia? |
| Third-party access | PDP-05 | Bagaimana akses OEM/maintenance contractor diberikan dan dicabut? |
| Operating governance | PDP-04, PDP-06 | Apakah model privasi grup telah diterapkan pada entitas lokal? |

**Penawaran awal yang dapat diuji:** *Akatara Workforce & Vendor Privacy Review*. Validasi lebih dahulu apakah kebijakan, sistem, dan layanan grup sudah mencakup kebutuhan tersebut.

### 6.3 Conrad Asia Energy / WNEL — Duyung PSC/Mako

**Hipotesis entry point:** data personel proyek, kru offshore, kontraktor MOPU/subsea/drilling, data-sharing JV, dan transisi project-to-operations.

| Area | Modul yang relevan | Pertanyaan validasi |
|---|---|---|
| Project workforce and vendors | PDP-01, PDP-02 | Proses data personel apa yang dikelola WNEL dan kontraktor? |
| JV data governance | PDP-02, PDP-04 | Bagaimana RACI dan hak akses WNEL, Conrad, serta Nations ditetapkan? |
| Contractor data-sharing | PDP-03 bila relevan, PDP-04 | Apakah klausul kontrak mengatur pemrosesan, retensi, dan penghapusan? |
| Project-to-operations handover | PDP-02, PDP-04, PDP-06 | Siapa yang akan memiliki proses dan inventaris setelah handover? |
| Technical controls | PDP-05 | Kontrol apa yang belum tercakup dalam kontrak proyek dan sistem yang ada? |

**Penawaran awal yang dapat diuji:** *Mako Project-to-Operations Data Readiness*. Lebih dari 90% capex contracts/LOA telah diterbitkan menurut riset akun; jangan mengasumsikan paket proyek utama masih terbuka. Cari ruang lingkup yang belum tercakup atau kebutuhan assurance/handover yang disetujui.

## 7. Kerangka estimasi dan commercial qualification

Jangan menetapkan harga atau durasi baku sebelum variabel ruang lingkup diketahui. Gunakan faktor berikut untuk menyusun estimasi:

| Variabel | Pengaruh terhadap effort |
|---|---|
| Jumlah entitas dan unit kerja | Jumlah stakeholder, RACI, dan variasi proses |
| Jumlah proses pemrosesan | Workshop, inventaris, validasi, dan dokumentasi |
| Jumlah sistem/aplikasi dan integrasi | Kedalaman walkthrough dan kebutuhan SME |
| Jumlah lokasi/site | Mobilisasi, koordinasi, dan variasi operasional |
| Jumlah vendor/pihak ketiga | Review kontrak, aliran data, dan akses |
| Kompleksitas OT/ICS | Kebutuhan asset owner, safety review, dan pembatasan akses |
| Ketersediaan bukti dan narasumber | Effort klarifikasi dan validasi |
| Kedalaman implementasi | Desain, konfigurasi, pengujian, change window |
| SLA dan coverage | Kapasitas personel, shift, response target, dan eskalasi |

**Komponen biaya yang dipisahkan**
1. Professional services.
2. Software license/subscription.
3. Hardware/infrastructure.
4. Third-party services.
5. Travel/mobilization.
6. Managed service recurring fee.
7. Optional scope dan change request.

**Data minimum sebelum proposal final**
- Legal contracting entity dan lokasi kerja.
- Sponsor, process owner, technical authority, procurement contact.
- Proses dan sistem yang masuk cakupan.
- Jumlah unit, lokasi, user, vendor, dan data source.
- Deliverable dan acceptance criteria.
- Jadwal, dependency, akses, dan change window.
- Kebutuhan Legal review dan pihak yang menyediakannya.
- Budget status dan procurement route, bila telah diketahui.

## 8. Template struktur Statement of Work (SOW)

Setiap proposal/SOW sekurang-kurangnya mencakup:

1. Latar belakang dan masalah yang dinyatakan pelanggan.
2. Tujuan engagement dan hasil yang diharapkan.
3. Entitas, unit, proses, lokasi, sistem, dan periode dalam cakupan.
4. Metodologi dan aktivitas per fase.
5. Deliverable dan format penyerahan.
6. Kriteria penerimaan yang objektif.
7. Jadwal dan milestone.
8. Tim penyedia dan peran pelanggan.
9. RACI dan decision authority.
10. Information/access requirement dan protokol data.
11. Asumsi, dependensi, pengecualian, dan batasan.
12. Change control.
13. Biaya, termin pembayaran, lisensi, dan biaya pihak ketiga.
14. Kerahasiaan, keamanan informasi, retensi, dan penghapusan artefak.
15. Risiko, eskalasi, dan mekanisme penyelesaian isu.

### Contoh batasan SOW yang perlu dipertimbangkan

- Tidak termasuk legal opinion atau representasi hukum.
- Tidak termasuk audit sertifikasi atau pernyataan kepatuhan menyeluruh.
- Tidak termasuk penetration test atau vulnerability assessment kecuali disebutkan.
- Tidak termasuk perubahan sistem produksi/OT tanpa persetujuan tertulis.
- Tidak termasuk remediasi di luar daftar tindakan yang disepakati.
- Hasil didasarkan pada informasi dan akses yang disediakan pelanggan; keterbatasannya dicatat.
- Penambahan proses, sistem, lokasi, entitas, atau vendor setelah baseline scope melalui change request.

## 9. Qualification gate dan aturan no-go

Peluang belum siap menjadi proposal final jika masalah pelanggan, pemilik proses, ruang lingkup, atau jalur keputusan belum jelas.

**Qualification gate**
- [ ] Masalah/kebutuhan dinyatakan oleh pelanggan.
- [ ] Process owner dan sponsor teridentifikasi.
- [ ] Entitas kontrak dan pihak yang memiliki kewenangan pembelian dipahami.
- [ ] Proses, sistem, unit, dan lokasi dalam cakupan ditetapkan.
- [ ] Bukti awal atau akses untuk validasi tersedia.
- [ ] Legal pelanggan tersedia untuk isu interpretasi hukum.
- [ ] Technical authority dan change authority tersedia untuk kontrol teknologi.
- [ ] Acceptance criteria dan jadwal keputusan disepakati.
- [ ] Budget status dan procurement route diketahui atau memiliki rencana validasi.

**Hold/no-go**
- Pelanggan meminta klaim “pasti patuh” atau jaminan bebas sanksi.
- Tidak ada otorisasi untuk mengakses atau memproses bukti.
- Ruang lingkup OT/ICS berpotensi mengganggu keselamatan/operasi dan tidak ada approval asset owner.
- Tidak ada pemilik keputusan untuk menerima risiko atau menyetujui perubahan.
- Permintaan mencakup pengumpulan data pribadi berlebihan tanpa tujuan, otorisasi, dan pengamanan yang jelas.
- Jadwal, deliverable, atau harga diminta tanpa informasi minimum dan pelanggan tidak menerima asumsi/pengecualian.

## 10. KPI dan pengukuran keberhasilan

KPI harus mengukur hasil layanan yang berada dalam kendali proyek. Jangan menjadikan “kepatuhan UU PDP” sebagai KPI tunggal tanpa kriteria dan penilaian hukum yang disepakati.

| Layanan | Contoh indikator |
|---|---|
| PDP-01 | Persentase proses dalam cakupan yang diwawancarai; bukti tervalidasi; gap dengan owner dan prioritas |
| PDP-02 | Persentase proses yang memiliki inventaris; peta aliran data tervalidasi; unresolved data points |
| PDP-03 | Skenario risiko terdokumentasi; mitigasi dengan owner; keputusan residual risk |
| PDP-04 | RACI disetujui; prosedur prioritas disahkan; workflow dan escalation path diuji |
| PDP-05 | Requirement traceability; test pass/exception; kontrol yang berhasil dioperasikan |
| PDP-06 | SLA attainment; backlog aging; laporan tepat waktu; tiket dan eskalasi terdokumentasi |

Baseline dan target KPI ditetapkan pada awal engagement atau kontrak layanan, bukan diasumsikan oleh penyedia.

## 11. Regulatory and professional boundary

Dokumen ini merupakan arsitektur penawaran layanan, bukan nasihat hukum. UU No. 27 Tahun 2022 dan ketentuan pelaksananya perlu dibaca berdasarkan naskah autentik, konteks pemrosesan, serta peran aktual para pihak. Setiap interpretasi mengenai dasar pemrosesan, kewajiban penunjukan fungsi/pejabat PDP, transfer data lintas negara, DPIA, retensi, dan kewajiban lain harus divalidasi oleh Legal/penasihat hukum pelanggan.

Status dan ketentuan PP No. 33 Tahun 2026 tidak boleh dijadikan klaim proposal sebelum naskah autentik dan tanggal berlakunya diperiksa. Jangan menggunakan tanggal atau ringkasan publikasi sekunder sebagai satu-satunya dasar legal.

## 12. Checklist internal sebelum proposal dikirim

- [ ] Kebutuhan berasal dari pelanggan atau ditandai jelas sebagai hipotesis.
- [ ] Tidak ada klaim insiden, kelemahan, ketidakpatuhan, anggaran, tender, atau incumbent tanpa bukti.
- [ ] Entitas pelanggan dan peran para pihak tidak dicampur.
- [ ] Scope, deliverable, acceptance criteria, asumsi, dan pengecualian konsisten.
- [ ] Batas legal dan teknis dinyatakan.
- [ ] Kebutuhan OT/ICS memiliki safety/operations approval.
- [ ] Lisensi dan biaya pihak ketiga dipisahkan.
- [ ] Estimasi didasarkan pada variabel scope yang tercatat.
- [ ] Pemilik keputusan, jalur pengadaan, dan next step diketahui atau dinyatakan belum diketahui.
- [ ] Setiap klaim regulasi ditinjau terhadap sumber primer dan Legal.

---

**Dokumen terkait:** [Sales Playbook KKKS 2027](SALES_PLAYBOOK_KKKS_2027.md) · [Account Pursuit Plan — Top 3 KKKS](KKKS_ACCOUNT_PURSUIT_PLAN_TOP3_2027.md) · [Regulatory Intelligence Validation — UU PDP 2027](Regulatory_Intelligence_Validation_UU_PDP_2027.md)

**Catatan penggunaan:** seluruh paket dan use case akun dalam dokumen ini adalah rancangan penawaran. Finalisasi hanya dilakukan setelah discovery, validasi bukti, persetujuan ruang lingkup, dan kualifikasi komersial.
