---
layout: default
title: "Kebijakan Privasi BereaNote"
lang: id
---

# Kebijakan Privasi BereaNote

> Terjemahan ini disediakan hanya untuk kemudahan. Jika terdapat perbedaan makna, [versi bahasa Inggris](privacy.en.html) yang berlaku.

Tanggal berlaku: 1 Desember 2026

BereaNote adalah aplikasi pencatat untuk pelajaran Alkitab pribadi di Mac, iPad, dan iPhone. Halaman ini menjelaskan apa yang terjadi pada data Anda saat Anda menggunakannya.

## Ringkasan

- BereaNote tidak mengumpulkan data apa pun tentang Anda.
- Tidak ada akun, tidak ada iklan, tidak ada analitik, dan tidak ada kode pihak ketiga di dalam aplikasi.
- Apa yang Anda tulis disimpan di perangkat Anda, dan aplikasi tidak mengirimkannya ke mana pun. Jika Anda menyalakan sinkronisasi iCloud, data itu juga disimpan di basis data iCloud pribadi Anda sendiri, yang tidak dapat dibaca oleh pengembang.

## Apa yang disimpan aplikasi, dan di mana

| Data | Tempat penyimpanannya |
| --- | --- |
| Catatan, folder, lini masa, properti, pengaturan | Di perangkat Anda, dalam penyimpanan milik aplikasi sendiri |
| Rekaman audio | Di perangkat Anda. Sinkronisasi iCloud tidak mengunggah audionya |
| Alkitab yang Anda impor | Aplikasi membaca berkas EPUB yang Anda pilih dan membuat indeks pencarian di perangkat Anda. Berkas itu tidak pernah diunggah |
| Cadangan | Berkas ZIP yang ditulis ke tempat yang Anda pilih. Apa yang terjadi pada berkas itu setelahnya sepenuhnya terserah Anda |

Aplikasi itu sendiri tidak pernah mengunggah rekaman atau Alkitab Anda. Cadangan bawaan perangkat Anda — Cadangan iCloud, cadangan iPhone atau iPad di komputer, Time Machine di Mac — mencakup data aplikasi, termasuk rekaman, sebagaimana untuk aplikasi lainnya. Cadangan tersebut dibuat oleh sistem sesuai pengaturan Anda, bukan oleh BereaNote.

## Sinkronisasi iCloud

Sinkronisasi iCloud bersifat opsional dan mati sampai Anda menyalakannya di Pengaturan.

Saat sinkronisasi menyala, item berikut disimpan di basis data pribadi akun iCloud Anda sendiri, melalui CloudKit milik Apple, agar perangkat Anda yang lain yang masuk dengan Akun Apple yang sama dapat membacanya: catatan, folder, jalur dan peristiwa lini masa, tokoh, definisi properti, serta catatan kata sandi kunci halaman (berupa hash dengan salt, tidak pernah kata sandinya sendiri).

Pengembang tidak memiliki akses ke data ini. Apple menyimpannya berdasarkan kebijakan privasi Apple sendiri.

Halaman yang dikunci disinkronkan seperti catatan lainnya. Kunci halaman menyembunyikan halaman di dalam aplikasi; kunci itu tidak mengenkripsinya.

Sinkronisasi iCloud ditawarkan sebagai langganan bulanan yang diperpanjang otomatis. Apple menangani langganan dan pembayarannya; aplikasi tidak pernah menerima atau menyimpan informasi pembayaran (kartu, nama, atau alamat). Jika langganan berakhir, hanya sinkronisasi yang berhenti sementara, dan data di perangkat Anda tetap ada.

Mematikan sinkronisasi membiarkan data Anda tetap ada, baik di perangkat maupun di iCloud, dan salinan di iCloud tetap ada di sana sampai Anda menghapusnya. Untuk menghapus data aplikasi dari iCloud, gunakan **Pengaturan → Zona Berbahaya → Data iCloud → Hapus…** (tindakan ini juga mematikan sinkronisasi di perangkat Anda yang lain; data di setiap perangkat tetap disimpan), atau hapus melalui pengaturan penyimpanan iCloud di perangkat Anda.

## Mikrofon

Aplikasi meminta akses mikrofon saat pertama kali Anda memulai rekaman. Mikrofon hanya digunakan untuk merekam audio yang Anda lampirkan ke catatan, dan hanya selama Anda merekam. Di iPhone dan iPad, rekaman yang sudah Anda mulai tetap berjalan saat layar terkunci atau saat Anda beralih ke aplikasi lain, sampai Anda menghentikannya. Aplikasi tidak mengunggah rekaman.

## Kunci halaman

Kata sandi kunci halaman menyembunyikan isi halaman yang dikunci di dalam aplikasi. Kata sandi itu tidak mengenkripsi berkas di perangkat Anda. Kata sandi hanya disimpan sebagai hash dengan salt.

## Apa yang diterima pengembang

Tidak ada apa pun dari aplikasi. Jika Anda menulis ke alamat dukungan, pengembang menerima apa yang Anda kirimkan. Jika Anda memilih untuk berbagi data diagnostik dengan pengembang aplikasi di pengaturan perangkat Anda, Apple dapat meneruskan laporan kerusakan anonim.

## Menghapus data Anda

- Hapus catatan di dalam aplikasi. Catatan di Sampah dihapus permanen setelah 30 hari, atau seketika jika Anda memilihnya.
- Hapus data iCloud aplikasi seperti dijelaskan di atas.
- Di iPhone dan iPad, menghapus aplikasi akan menghapus semua yang disimpannya di perangkat tersebut.
- Di Mac, memindahkan aplikasi ke Tempat Sampah membiarkan folder datanya tetap ada. Untuk menghapusnya juga, buka **Pengaturan → Info → Lokasi Penyimpanan → Tampilkan di Finder** sebelum menghapus aplikasi, lalu pindahkan folder itu ke Tempat Sampah (folder itu ada di dalam `~/Library/Containers/com.chan.BereaNote`).
- Berkas cadangan yang Anda buat, dan salinan yang tersimpan di cadangan bawaan perangkat Anda, tidak dihapus oleh langkah-langkah di atas.

## Anak-anak

BereaNote tidak ditujukan untuk anak-anak dan tidak mengumpulkan data pribadi dari siapa pun.

## Perubahan pada kebijakan ini

Jika kebijakan ini berubah, versi barunya diterbitkan di halaman ini dengan tanggal berlaku yang baru.

## Kontak

Chan Jung — john1913@naver.com
