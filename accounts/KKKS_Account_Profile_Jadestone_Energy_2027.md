# Profil Akun: Jadestone Energy (Lemang) Pte. Ltd.
**Intelijen akun 2027 | Batas riset: 11 November 2026**

## 1. Ringkasan akun
Jadestone Energy memiliki 100% working interest dan bertindak sebagai operator Lemang PSC di darat Sumatra, Indonesia, yang mencakup lapangan gas Akatara. Informasi ini tercantum pada halaman operasi resmi Jadestone. [S1]

Akatara telah berproduksi. Laporan hasil 2025 Jadestone menyebut rata-rata produksi 6.067 boe/d sepanjang 2025, dibandingkan 977 boe/d pada 2024. Produksi terdiri dari gas dan cairan (LPG serta kondensat). Fasilitas pemrosesan gas Akatara mencatat uptime tahunan 94,4% di luar planned downtime pada tahun operasi penuh pertamanya. [S2]

Laporan interim 2026 menyebut rata-rata produksi Akatara 5.590 boe/d pada H1 2026, dengan penjualan gas 3,1 Bscf dan LPG/kondensat 0,5 juta barel. Angka tersebut adalah net production Jadestone sesuai working interest yang dilaporkan dan bukan produksi bruto seluruh WK. [S3]

## 2. Fakta dan sinyal operasional
- Lemang PSC dioperasikan Jadestone Energy (Lemang) Pte. Ltd. dengan 100% working interest menurut halaman operasi perusahaan. [S1]
- Akatara merupakan lapangan gas yang telah berproduksi dan memiliki fasilitas pemrosesan untuk menghasilkan sales gas, LPG, dan kondensat. [S2]
- H1 2026 Akatara mencatat rata-rata produksi 5.590 boe/d. [S3]
- Laporan operasional Jadestone yang dipublikasikan pada November 2026 menyatakan Akatara berjalan sesuai ekspektasi, dengan uptime rata-rata sekitar 96% sejak kembali beroperasi setelah shutdown pemeliharaan singkat pada April 2026. [S4]
- Prakualifikasi *Provision of Manpower Services* oleh Jadestone Energy (Lemang) Pte. Ltd. diumumkan pada 15–21 September 2026. Paket tersebut adalah penyediaan tenaga kerja, bukan pengadaan cybersecurity. [S5]

## 3. Struktur dan pemangku kepentingan
| Entitas/fungsi | Relevansi | Status bukti |
|---|---|---|
| Jadestone Energy (Lemang) Pte. Ltd. | Kontraktor PSC/operator Lemang | Nama operator dipublikasikan [S1] |
| Jadestone Energy plc | Grup induk dan pemilik portofolio operasi lintas negara | Halaman operasi grup [S1] |
| Asset / Operations / Production | Pemilik dampak kontinuitas produksi dan fasilitas Akatara | Fungsi relevan; nama lokal belum dipetakan |
| IT / Digital / Cybersecurity | Arsitektur, layanan TI, dan kontrol keamanan | Fungsi sasaran; struktur lokal belum diketahui |
| OT / Instrumentation / Control Systems | Sistem kendali dan pemantauan fasilitas pemrosesan gas | Hipotesis fungsi; struktur aktual perlu divalidasi |
| Supply Chain / Procurement | Prakualifikasi dan pengadaan vendor | Sinyal prakualifikasi manpower tersedia [S5] |
| HSE / Risk / Legal / HR | Keselamatan, risiko, kontrak, tenaga kerja dan data pribadi | Perlu dipetakan sesuai organisasi lokal |

## 4. Hipotesis peluang keamanan siber dan UU PDP
1. **OT/ICS security assessment:** pemetaan sistem kontrol, historian, jaringan fasilitas, remote access, dan aset kritis Akatara.
2. **Industrial network segmentation:** evaluasi pemisahan jaringan IT/OT, zona keamanan, dan jalur komunikasi ke pihak ketiga.
3. **Remote access / PAM:** tata kelola akses OEM, kontraktor maintenance, dan engineering.
4. **SOC / incident response:** validasi integrasi telemetri fasilitas dengan monitoring grup, prosedur eskalasi, dan pemulihan.
5. **Third-party risk:** persyaratan keamanan bagi penyedia tenaga kerja, engineering, maintenance, dan layanan fasilitas.
6. **UU PDP:** pemetaan data karyawan, tenaga kerja kontraktor, data kesehatan/HSE, akses fasilitas, dan pemrosesan oleh vendor.

Hipotesis tersebut bukan klaim bahwa Akatara memiliki kelemahan keamanan atau Jadestone sedang mencari vendor cybersecurity.

## 5. Pertanyaan discovery
- Apakah kontrol IT/OT Akatara dikelola lokal atau mengikuti standar grup Jadestone?
- Siapa pemilik sistem DCS/SCADA, historian, dan jaringan fasilitas?
- Bagaimana remote access OEM dan kontraktor diotorisasi, direkam, dan dicabut?
- Apakah monitoring OT terintegrasi dengan SOC grup atau MSSP?
- Apakah pernah dilakukan ICS/OT risk assessment dan kapan tindak lanjut berikutnya?
- Apa model procurement dan supplier qualification yang berlaku untuk layanan teknologi?
- Apakah pengadaan cybersecurity ditentukan oleh operasi Indonesia, regional, atau kantor pusat?

## 6. Arah pendekatan komersial
Pendekatan sebaiknya berpusat pada keandalan fasilitas pemrosesan gas Akatara dan pengendalian akses pihak ketiga. Gunakan data uptime dan operasi sebagai konteks bisnis, bukan sebagai indikasi adanya masalah. Cari tahu lebih dahulu apakah keputusan teknologi dan keamanan ditetapkan oleh tim Indonesia atau grup. Untuk masuk ke pengadaan, validasi jalur supplier qualification dan persyaratan lokal pada paket terkait.

## 7. Kesenjangan intelijen
Belum ditemukan nama CIO/CISO/IT/OT lead Indonesia, struktur pelaporan keamanan, vendor SOC/OT security, arsitektur Akatara, insiden siber, anggaran 2027, tender cybersecurity, atau hasil assessment keamanan.

## 8. Sumber
- [S1] Jadestone Energy, Operations: https://www.jadestone-energy.com/operations/
- [S2] Jadestone Energy, 2025 Full-Year Results: https://www.investegate.info/announcement/rns/jadestone-energy--jse/2025-full-year-results-/9574255
- [S3] Jadestone Energy, Interim/Quarterly Report 2026: https://financialfilings.com/filings/jadestone-energy-plc/interim-quarterly-report/2026/57654755/
- [S4] London Stock Exchange, Jadestone Operational Update, November 2026: https://www.londonstockexchange.com/en/news/article/JSE/operational-update/d2d7-1d-10-a6-82-47ddbf
- [S5] Petromindo Tenders, Provision of Manpower Services, 15–21 September 2026: https://www.petromindo.com/tenders/detail/provision-of-manpower-services

**Keyakinan:** Tinggi untuk status operator dan angka produksi yang dilaporkan perusahaan; sedang untuk sinyal operasional terbaru; rendah untuk hipotesis kebutuhan cybersecurity sampai discovery dilakukan.
