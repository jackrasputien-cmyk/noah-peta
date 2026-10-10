# noah-peta

Data peta offline untuk aplikasi **N.O.A.H.** (No-Internet Offline AI Helper), aplikasi darurat dan bencana yang tetap berguna tanpa internet.

Berkas peta (`.mwm`) dibuat sendiri dari data **OpenStreetMap** dan diterbitkan sebagai **Releases** di repo ini. Aplikasi mengunduh wilayah yang dibutuhkan langsung dari sini; setelah tersimpan di HP, peta dipakai tanpa internet.

## Isi

- Satu rilis per versi data, nama rilis = versi (mis. `261010` = data 10 Okt 2026).
- Setiap rilis berisi berkas peta per wilayah Indonesia dan `countries.json` (daftar wilayah, ukuran, dan kode pemeriksa).
- Repo ini **hanya berisi data peta**, tanpa kode aplikasi dan tanpa data pribadi.

## Sumber & lisensi

Peta © kontributor OpenStreetMap, https://www.openstreetmap.org/copyright

Data OpenStreetMap berlisensi **Open Database License (ODbL) 1.0**. Berkas peta di repo ini adalah *produced work* dari data tersebut dan dibagikan dengan syarat yang sama: cantumkan atribusi "© OpenStreetMap contributors". Lihat `LICENSE.md`.

Ekstrak data diambil dari Geofabrik (https://download.geofabrik.de). Peta dibuat dengan alat `generator_tool` dari proyek Organic Maps (kode Apache 2.0); **tidak memakai berkas data Organic Maps**.
