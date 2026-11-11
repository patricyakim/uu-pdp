# Opportunity Intelligence 2027: PT Pertamina EP
**Batas riset: 11 November 2026 | Fokus: keamanan siber, IT/OT, dan UU PDP**

## 1. Kesimpulan akun
Belum ditemukan pengumuman tender publik PEP yang secara eksplisit menyebut SOC, OT/ICS security assessment, IAM, atau layanan UU PDP dalam sumber yang diperiksa. Terdapat paket jasa pengamanan operasional sekuriti di Tambun Field yang diperkirakan bernilai Rp66,96 miliar oleh agregator tender, tetapi ruang lingkupnya adalah pengamanan operasional fisik, bukan cybersecurity. Angka tersebut merupakan nilai estimasi dari agregator dan bukan nilai kontrak atau anggaran keamanan siber. [S1]

Aktivitas workover, well intervention, dan managed pressure drilling memberi konteks operasional bagi discovery OT/IT, tetapi bukan bukti kebutuhan keamanan siber.

## 2. Opportunity hypotheses
| Area solusi | Hipotesis kebutuhan | Bukti saat ini | Langkah validasi |
|---|---|---|---|
| OT/ICS assessment | Pemetaan aset dan kontrol OT lintas zona/field | Aktivitas lapangan dan produksi; tender OT security spesifik belum ditemukan | Tentukan zona/field, asset owner, dan standar PHE |
| Remote access / PAM | Kontrol akses engineer, OEM, dan kontraktor | Kegiatan well intervention dan drilling; akses sistem belum dibuktikan | Petakan akses jarak jauh dan akun vendor |
| SOC / MDR | Monitoring terpusat lintas lokasi | Tidak ada tender SOC PEP yang ditemukan | Validasi model SOC PEP/PHE dan integrasi log |
| Third-party security | Assurance vendor jasa lapangan dan integrator | Aktivitas tender jasa operasional | Uji security clauses, vendor access, dan assurance |
| UU PDP | Pemetaan data tenaga kerja, kontraktor, dan HSE | Proses tenaga kerja/kontraktor berpotensi memproses data pribadi | Validasi data inventory, role mapping, dan processor contracts |

## 3. Sinyal pengadaan dan batas interpretasi
- Tender jasa pengamanan operasional sekuriti PEP Regional 2 Zona 7 Tambun Field dipublikasikan dengan estimasi Rp66.959.815.615 dan TKDN minimum 90% oleh agregator tender. Klasifikasi ini adalah pengamanan operasional fisik, bukan keamanan informasi. [S1]
- Paket EWLPP dan Managed Pressure Drilling juga tercantum dalam daftar tender PEP; keduanya merupakan layanan operasi sumur, bukan tender cybersecurity. [S1]
- Belum ditemukan pengadaan PEP yang secara eksplisit mencantumkan SOC, ICS risk assessment, OT security, atau UU PDP.

## 4. Prioritas solusi untuk discovery
1. OT/ICS asset visibility dan security assessment pada zona/field terpilih.
2. Remote access governance dan PAM bagi kontraktor.
3. Third-party cyber risk untuk integrator dan penyedia jasa operasi.
4. SOC use case dan incident response lintas lokasi.
5. Data mapping dan privacy controls.

Urutan ini adalah urutan discovery, bukan prioritas anggaran PEP yang telah diketahui.

## 5. Pertanyaan kualifikasi peluang
- Apakah PEP mempunyai standar OT security sendiri atau mengikuti standar PHE?
- Zona/field mana yang menjadi prioritas untuk assessment?
- Siapa pemilik anggaran dan siapa yang menyetujui desain teknis?
- Apakah SOC dikelola PEP, PHE, atau penyedia layanan bersama?
- Bagaimana akses vendor dan kontraktor ke sistem operasi dikelola?
- Apakah ada program cybersecurity yang sudah masuk RKAP 2027?
- Apa persyaratan CIVD, TKDN, CSMS/HSSE, dan kualifikasi usaha untuk kategori solusi?

## 6. Opportunity qualification saat ini
**Status:** Hypothesis / discovery required.  
**Belum diketahui:** sponsor, budget owner, incumbent, nilai, timeline, dan procurement route untuk cybersecurity.  
**Next action:** validasi RACI PEP–PHE dan pilih satu zona/field untuk discovery teknis.

## 7. Sumber
- [S1] Tender-Indonesia.com, daftar tender PEP Zona 7 dan Tambun Field, estimasi undangan Oktober 2026: https://www.tender-indonesia.com/tender_home/detail-rubrik-3977
- [S2] Ditjen Migas ESDM, Forum Verifikasi Kematangan Keamanan Siber PSE IIV subsektor migas, 22 Juni 2026: https://migas.esdm.go.id/post/Perkuat-Benteng-Infrastruktur-Informasi-Vital-Ditjen-Migas-Gelar-Forum-Verifikasi-Kematangan-Keamanan-Siber

**Keyakinan:** Sedang untuk sinyal tender operasional dari agregator; rendah untuk peluang cybersecurity PEP karena belum ditemukan tender langsung.
