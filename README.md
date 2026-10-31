# Sistem OPR PLC — Sekolah Kebangsaan Parit Merkom

Pakej ini sedia diterbitkan melalui GitHub Pages.

## Cara menerbitkan

1. Muat naik `index.html` dan folder `assets` ke bahagian utama repository GitHub.
2. Buka **Settings → Pages**.
3. Pada **Build and deployment**, pilih **Deploy from a branch**.
4. Pilih branch `main` dan folder `/(root)`, kemudian klik **Save**.
5. Tunggu sehingga pautan GitHub Pages dipaparkan.

Jangan ubah nama atau lokasi folder `assets` kerana header dan logo menggunakan fail di dalam folder tersebut.

## Status sambungan

- CSV rekod OPR telah dikonfigurasikan kepada `gid=0`.
- CSV nama guru telah dikonfigurasikan kepada `gid=1130301879`.
- URL Apps Script Web App baharu telah dimasukkan ke dalam `index.html`.
- Pastikan `Code.gs` menggunakan Sheet ID `1-lSY2YPu95Dau2ntsV3faYxsAnKPY21FWNWEGeKGFu0` dan Drive ID `1tjlS4cnTl6gThs9yzxhML-Ys4jPJ7r-Y`.

Moto sekolah pada header: **SKPM the best** dan **Melangkah dengan bergaya**.

Ujian pada 1 November 2026 mendapati kedua-dua CSV dan URL Apps Script boleh dicapai. Walau bagaimanapun, respons Apps Script masih memaparkan nama sistem lama **SMK Nipah**. Gantikan seluruh kod lama dengan fail `Code.gs` dalam pakej ini. Kemudian buka **Deploy → Manage deployments → Edit**, pilih **New version**, tetapkan **Execute as: Me** dan **Who has access: Anyone**, lalu klik **Deploy** sebelum menguji fungsi simpan dari GitHub Pages.

## Apps Script

Fail `Code.gs` yang lengkap turut disertakan. Jika perlu menggantikan backend, salin seluruh kandungannya ke projek Apps Script, jalankan `setupSistem`, kemudian deploy sebagai Web app (`Execute as: Me`, `Who has access: Anyone`).
