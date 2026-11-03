# Project Meridian

**Bertumbuh Bersama, Saling Membuka Jalan**

Prototype alat bantu keputusan transisi tenaga kerja untuk Direktur Human Capital. Konteksnya adalah otomatisasi (smart meter, IoT, operasi berbantuan AI) yang menggeser sekitar 4.200 FTE pekerjaan. Alat ini tidak menanyakan "siapa yang dipotong". Pertanyaannya adalah kapasitas mana yang benar-benar punya tempat tujuan, dan mana yang belum. Wilayah pilotnya Jawa Barat dan Jawa Timur.

Disusun oleh Nur Hadi Kusumo.

> Semua data dalam prototype ini **sintetis**.

## Menjalankan

Seluruh prototype ada dalam satu file HTML tanpa dependensi eksternal, tanpa build, dan tanpa server. Cukup buka file itu di browser:

```sh
open meridian-project.html
```

## Alur

Prototype ini terdiri dari empat langkah:

1. **Paparan**: paparan otomatisasi diuji terhadap kebutuhan nyata, lalu dipecah ke empat jalur transisi. Angka besar tidak dilaporkan seolah semua orang akan di-reskill.
2. **Open Talent Market**: unit penerima memasang kebutuhan peran. Kebutuhan baru dihitung bila punya pemilik, volume kerja, dan status anggaran. Pegawai terdampak didahulukan sebelum rekrutmen eksternal.
3. **Kandidat pilot**: profil keterampilan kandidat beserta status buktinya. Data yang kosong memicu asesmen, bukan penilaian rendah. Hanya bukti terverifikasi yang boleh memenuhi syarat wajib.
4. **Keputusan**: paket keputusan individual (penugasan percobaan, penugasan jembatan, asesmen), daftar keputusan yang dibutuhkan dari Direksi, dan kriteria evaluasi Hari ke-90. Paket ini bisa dicetak.

## Penanda sumber angka

Setiap angka diberi penanda sumber. Klik penanda itu untuk melihat dasarnya.

| Penanda | Arti |
|---|---|
| ● | Fakta dari brief |
| ○ | Asumsi |
| ◌ | Simulasi |
| ƒ | Rumus |

## Batas alat

- Rekomendasi dibuat dari aturan kategori, bukan skor persen. Setiap keputusan individual disetujui manusia.
- Pensiun dini sukarela tidak ditawarkan dari alat ini.
- Pegawai dapat melihat profilnya, mengoreksi bukti, dan mengajukan keberatan.
- Data payroll tidak digunakan. Data kinerja sebelum 2023 tidak dipakai.
