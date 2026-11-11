# Opportunity Intelligence 2027: Pertamina Hulu Rokan
**Batas riset: 11 November 2026 | Fokus: keamanan siber, IT/OT, dan UU PDP**

## 1. Kesimpulan akun
Belum ditemukan pengumuman tender publik yang secara eksplisit menyebut SOC, OT security, ICS assessment, IAM, atau layanan UU PDP untuk PHR dalam sumber yang diperiksa. Karena itu, belum ada peluang cybersecurity PHR yang dapat diklasifikasikan sebagai pengadaan teridentifikasi.

Aktivitas operasi dan pengadaan PHR memberi konteks untuk discovery, tetapi bukan bukti kebutuhan keamanan siber. PHR tercatat mengumumkan pengadaan jasa pengamanan fisik untuk kantor pusat, gudang, dan perumahan VIP pada 28 September–5 Oktober 2026. Paket tersebut mencakup pengendalian akses dan penjagaan, tetapi klasifikasi dan ruang lingkupnya adalah jasa pengamanan fisik, bukan cybersecurity. [S1]

## 2. Opportunity hypotheses
| Area solusi | Hipotesis kebutuhan | Bukti saat ini | Langkah validasi |
|---|---|---|---|
| OT/ICS security assessment | Pemetaan aset, konektivitas, segmentasi, dan kontrol akses OT | Aktivitas operasi WK Rokan; belum ada tender OT security yang ditemukan | Temukan OT owner dan tanyakan assessment terakhir serta scope aset |
| Remote access / PAM | Kontrol akses vendor, OEM, dan kontraktor | Pengadaan jasa operasi dan pemeliharaan memberi konteks vendor; tidak membuktikan akses sistem | Petakan remote access, akun bersama, approval, dan session recording |
| SOC / MDR | Korelasi log IT/OT dan respons insiden | Belum ada bukti publik tentang platform atau tender SOC PHR | Validasi SOC model, cakupan log, MSSP, SLA, dan gap operasional |
| Third-party cyber risk | Assurance kontraktor yang memiliki akses sistem/fasilitas | Ekosistem kontraktor dan tender jasa teridentifikasi secara umum | Uji vendor access inventory, security clauses, dan assurance evidence |
| UU PDP / data governance | Pemetaan data pekerja, kontraktor, akses fisik, CCTV, dan HR | Pengadaan pengamanan fisik mencantumkan pengendalian akses; tidak membuktikan sistem atau pemrosesan data tertentu | Petakan data controller/processor, retensi, akses, CCTV, dan vendor pemroses |

## 3. Sinyal pengadaan yang perlu dibedakan
- **Sinyal berdekatan, bukan cybersecurity:** prakualifikasi jasa pengamanan fisik kantor pusat PHR (28 September–5 Oktober 2026), termasuk pengendalian akses. Jangan memasukkannya sebagai tender cybersecurity. [S1]
- **Sinyal operasi:** CIVD memuat pengumuman jasa pemeliharaan integritas tiang listrik dan pendukung operasi PGT Zona Rokan dengan tayang hingga 11 November 2026. Paket ini adalah pekerjaan kelistrikan/operasi, bukan keamanan siber. [S2]
- **Proses vendor:** kebijakan procurement PHI dan penggunaan CIVD dapat menjadi pembanding proses Regional 3, tetapi bukan bukti alur procurement PHR. [S3]

## 4. Prioritas solusi untuk discovery
1. OT/ICS security assessment dan asset visibility.
2. Remote access governance dan privileged access untuk vendor.
3. Third-party cyber risk assessment.
4. SOC use case dan incident response readiness.
5. Data mapping dan privacy control untuk proses tenaga kerja/akses fasilitas.

Urutan ini adalah urutan discovery yang disarankan, bukan ranking anggaran atau probabilitas tender.

## 5. Pertanyaan kualifikasi peluang
- Apakah PHR telah melakukan OT security assessment dalam 24 bulan terakhir? Siapa pemilik laporan dan tindak lanjut?
- Apakah terdapat daftar aset OT dan koneksi remote vendor yang disetujui?
- Siapa pemilik SOC, dan apakah monitoring mencakup OT?
- Apakah PHR menggunakan MSSP atau kontrak SOC bersama di level PHE?
- Apakah ada rencana 2027 yang telah masuk RKAP atau tahap business case?
- Apakah procurement cybersecurity dilakukan PHR, PHE, atau fungsi bersama?
- Apakah perusahaan dan mitra sudah memenuhi persyaratan CIVD/SPDA, TKDN, dan kualifikasi teknis yang relevan?

## 6. Opportunity qualification saat ini
**Status:** Hypothesis / discovery required.  
**Belum diketahui:** sponsor, budget owner, nilai anggaran, timeline, incumbent, tender route, dan decision criteria.  
**Next action:** discovery meeting dengan technical owner IT/OT dan operational owner; jangan membuat proposal komersial sebelum scope dan sponsor teridentifikasi.

## 7. Sumber
- [S1] Petromindo Tenders, *Penyediaan Jasa Pengamanan untuk Wilayah Operasional Kantor Pusat Pertamina Hulu Rokan Regional 1*, 28 September–5 Oktober 2026: https://www.petromindo.com/tenders/detail/enyediaan-jasa-pengamanan-untuk-wilayah-operasional-kantor-pusat-pertamina-hulu-rokan-regional-1
- [S2] CIVD SKK Migas, hasil pengumuman jasa pemeliharaan integritas tiang listrik dan pendukung operasi PGT Zona Rokan, tayang hingga 11 November 2026: https://civdmigas.skkmigas.go.id/ajax/search/tnd.jwebs
- [S3] Pertamina Hulu Indonesia, Pengadaan Barang dan Jasa: https://phi.pertamina.com/id/relasi-investor-dan-pengadaan/pengadaan-barang-dan-jasa
- [S4] Ditjen Migas ESDM, Forum Verifikasi Kematangan Keamanan Siber PSE IIV subsektor migas, 22 Juni 2026: https://migas.esdm.go.id/post/Perkuat-Benteng-Infrastruktur-Informasi-Vital-Ditjen-Migas-Gelar-Forum-Verifikasi-Kematangan-Keamanan-Siber

**Keyakinan:** Tinggi bahwa tender pengamanan fisik bukan tender cybersecurity; rendah untuk peluang cybersecurity PHR karena belum ditemukan pengadaan langsung yang relevan.
