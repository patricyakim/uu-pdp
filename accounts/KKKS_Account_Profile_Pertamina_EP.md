# Profil Akun: PT Pertamina EP (PEP)
**Intelijen akun 2027 | Batas riset: 11 November 2026**

## 1. Ringkasan akun
PT Pertamina EP merupakan salah satu KKKS dengan skala produksi minyak besar. Dalam snapshot produksi minyak, kondensat, dan NGL hingga 31 Mei 2026 yang mengutip paparan Kepala SKK Migas kepada Komisi XII DPR pada 3 Juni 2026, PEP tercatat sebesar 73.983 BOPD. Angka ini merupakan snapshot periode berjalan, bukan produksi tahunan atau angka produksi terkini. [S1]

PEP berada dalam ekosistem Subholding Upstream Pertamina. Riset lanjutan perlu memisahkan keputusan yang berada pada level entitas PEP, regional/field, subholding, dan kebijakan grup agar pendekatan penjualan tidak salah sasaran.

## 2. Fakta dan sinyal operasional
- Pertamina Hulu Indonesia mempublikasikan pada Oktober 2026 bahwa intervensi sumur BN-38 di Bunyu Field yang dikelola PEP meningkatkan produksi minyak dari sekitar 8 barel menjadi 733 barel pada awal produksi setelah intervensi; produksi gas dilaporkan mencapai 0,52 MMSCFD dibandingkan target 0,10 MMSCFD. [S2]
- Publikasi tersebut menjelaskan penggunaan pembaruan analisis data subsurface, data saturasi log, water shut off, dan perforasi untuk mengoptimalkan sumur. [S2]
- Laporan PwC 2026 yang merujuk sumber SKK Migas mencantumkan proyek Akasia Bagus Stage-1 PEP onstream pada September 2025 dengan produksi 7.250 BOPD, serta proyek Upgrading Puspa Asri dengan rencana onstream Q4 2026 dan angka 1.034 BOPD. Status aktual proyek Q4 2026 perlu diperiksa kembali. [S3]
- PHE memuat Rokan HO Development sebagai proyek grup, tetapi tidak boleh dianggap sebagai proyek PEP karena operator dan asetnya berbeda. [S4]

## 3. Peta pemangku kepentingan — hipotesis fungsi
| Fungsi | Relevansi percakapan | Status |
|---|---|---|
| Direktorat/VP IT dan Digital | Arsitektur dan layanan TI, standardisasi, integrasi | Sasaran pemetaan; nama pejabat belum dipastikan |
| Cybersecurity / IT Risk | Kebijakan, SOC, assurance, respons insiden | Sasaran pemetaan; struktur aktual belum diketahui |
| Field IT / OT / Automation | Kontrol akses dan keamanan sistem operasi lapangan | Hipotesis relevansi; variasi per field perlu dipetakan |
| Operations / Asset / Production | Keandalan produksi dan dampak operasional | Fungsi pengguna/mitra |
| SCM / Procurement | Kualifikasi vendor, tender, kontrak | Jalur pengadaan per entitas dan paket perlu divalidasi |
| Legal / Compliance / Privacy | Data pekerja, kontraktor, kepatuhan | Perlu dipetakan sesuai aliran data aktual |

## 4. Hipotesis peluang keamanan siber dan UU PDP
1. **Enterprise-to-field security baseline:** penilaian keseragaman kontrol keamanan antara kantor pusat, regional, dan field.
2. **OT asset visibility:** inventaris perangkat OT, pemetaan komunikasi, klasifikasi aset kritis, dan proses perubahan.
3. **Identity governance:** pengelolaan akun pekerja, kontraktor, akun teknis, serta akses lintas lokasi.
4. **SOC modernization/use case:** korelasi telemetri endpoint, jaringan, identitas, dan sistem operasi dengan prioritas pada deteksi yang dapat ditindaklanjuti.
5. **Data protection & UU PDP:** pemetaan data pribadi dalam HR, layanan kesehatan, rekrutmen, kontraktor, akses lokasi, dan aplikasi operasional yang memuat identitas individu.

## 5. Pertanyaan discovery
- Bagaimana pembagian kewenangan keamanan siber antara PEP, Subholding Upstream, dan fungsi korporat Pertamina?
- Apakah kontrol keamanan lapangan distandardisasi atau dikelola per regional/field?
- Sistem apa yang digunakan untuk pengelolaan akses vendor dan remote maintenance?
- Bagaimana inventarisasi dan pemantauan aset OT dilakukan?
- Apakah terdapat standar minimum keamanan untuk integrator dan penyedia jasa lapangan?
- Aplikasi dan proses mana yang paling banyak memproses data pribadi pekerja/kontraktor?
- Apakah terdapat rencana penguatan SOC, OT security, IAM, atau data protection untuk siklus RKAP 2027?

## 6. Arah pendekatan komersial
Gunakan pendekatan bertingkat: validasi sponsor dan standar pada level subholding/korporat, lalu identifikasi kebutuhan operasional di regional/field. Mulai dengan assessment yang menghasilkan baseline dan prioritas lintas lokasi. Hindari menawarkan solusi per field sebelum diketahui apakah keputusan dan arsitektur berada di tingkat yang lebih tinggi.

## 7. Kesenjangan intelijen
Belum ditemukan bukti publik yang memadai mengenai arsitektur TI/OT PEP, produk keamanan yang dipakai, kontrak vendor, insiden, rencana tender keamanan 2027, struktur CISO, maupun status implementasi UU PDP. Data produksi yang tersedia bersifat snapshot dan tidak menggambarkan profil tiap field.

## 8. Sumber
- [S1] Katadata Databoks, produksi KKKS hingga 31 Mei 2026, 19 Juni 2026: https://databoks.katadata.co.id/en/energy/statistics/6a34a54325d45/top-20-contractors-with-the-largest-oil-condensate-and-ngl-production-in-indonesia-as-of-may-2026
- [S2] Pertamina Hulu Indonesia, *Keberhasilan Well Intervention PT Pertamina EP Bunyu Field Tambah Produksi Sumur BN-38*, Oktober 2026: https://phi.pertamina.com/id/media-informasi/keberhasilan-well-intervention-pt-pertamina-ep-bunyu-field-tambah-produksi-sumur-bn-38
- [S3] PwC Indonesia, *Oil and Gas in Indonesia: Investment, taxation and regulatory guide*, edisi ke-15, 2026: https://www.pwc.com/id/en/energy-utilities-mining/assets/oil-gas/oil-gas-guide-2026.pdf
- [S4] Pertamina Hulu Energi, laporan keberlanjutan dan ikhtisar proyek: https://phe.pertamina.com/uploads/2025/09/aec1d57a-1084-4385-8cbf-7e6b7eff8894.pdf

**Keyakinan:** Tinggi untuk snapshot produksi dan contoh aktivitas lapangan yang dipublikasikan; sedang untuk sinyal proyek 2026 karena status akhir perlu diperiksa; rendah untuk kebutuhan dan struktur keamanan siber.
