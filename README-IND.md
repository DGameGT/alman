# DGXO Alias Manager

> **Author's Note:**
> Alias itu kayak mantan. Lu bikin *shortcut* biar cepet nyampe, tapi kadang pas lu butuh yang asli, lu malah lupa namanya siapa.
>
> Jujur gw gatau ini *worth* engga buat banyak orang, tapi mungkin dibutuhkan :) jadi gw bikin ini.

## Overview

DGXO Alias Manager adalah sistem manajemen berbasis web yang dirancang untuk pengorganisasian, penyimpanan, dan pengambilan perintah terminal (alias) secara efisien. Solusi ini ditujukan bagi pengembang dan administrator sistem yang memerlukan repositori terpusat untuk skrip dan perintah kompleks guna meningkatkan produktivitas alur kerja.

## Key Features

  - **Local Data Persistence**: Menggunakan optimasi LocalStorage browser untuk retensi data tanpa memerlukan infrastruktur database eksternal.
  - **Localization Support**: Dilengkapi dengan sistem manajemen bahasa (ID/EN) untuk aksesibilitas pengguna global.
  - **Search Optimization**: Algoritma pencarian real-time berdasarkan kategori, nama alias, perintah, dan deskripsi.
  - **Data Portability**: Fitur ekspor dan impor berbasis JSON untuk prosedur pencadangan (backup) dan pemulihan (restore) data.
  - **Security Context Markers**: Identifikasi otomatis untuk perintah yang memerlukan hak akses administratif (SUDO) atau perintah berisiko tinggi (DANGER).

## Technical Specifications

  - **Architecture**: Single Page Application (SPA).
  - **Frontend Stack**:
      - HTML5 & CSS3 (Custom Properties & CSS Grid).
      - Vanilla JavaScript (ECMAScript 2021+).
  - **Typography**: JetBrains Mono (Technical) & Space Grotesk (Interface).
  - **Iconography**: Font Awesome 6.4.2 (Layanan CDN).

## Installation and Deployment

Aplikasi ini bersifat portabel dan tidak memerlukan instalasi server-side.

1.  Salin seluruh kode sumber ke dalam satu file berkestensi `.html`.
2.  Buka file tersebut menggunakan browser modern (Chrome, Firefox, Edge, atau Safari).
3.  Untuk integrasi intranet, simpan file di server web statis seperti Nginx atau Apache.

## Data Governance

Penting untuk diperhatikan bahwa sistem ini beroperasi sepenuhnya pada sisi klien (client-side).

1.  **Penyimpanan**: Data disimpan di dalam cache LocalStorage browser pengguna.
2.  **Risiko**: Penghapusan cache browser atau penggantian perangkat akan mengakibatkan hilangnya data jika tidak dicadangkan.
3.  **Prosedur Cadangan**: Pengguna diinstruksikan untuk menggunakan tombol 'Backup' secara periodik untuk menyimpan salinan data dalam format JSON.

## License

Lisensi : Apache 2.0

## Contact and Support

Pengembangan dan pemeliharaan oleh **DGXO (Dream & Driven Generation eXperience Operations)**.

  - Repository: [GitHub Repository](https://www.google.com/search?q=https://github.com/DGameGT/aliasmanager)
  - Website: [Official Link](https://alman.dgxo.my.id/)
  - Author Website: [Click:)!](https://dgxo.my.id/)