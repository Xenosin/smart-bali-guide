# Smart Bali Guide

MVP website rekomendasi wisata dan UMKM Bali untuk AI Web Innovation Challenge, Bali Digifest 2026.
Bidang: Bali Smart Society. Kategori: Mahasiswa/Umum. Peserta: individu, Muhammad Alva Rayno.

## Masalah
Wisatawan dan warga kesulitan memilih destinasi dan UMKM di Bali yang sesuai minat, wilayah, budget, dan rombongan. Informasi tersebar, tempat viral mendominasi, UMKM lokal yang bagus kalah, dan wisatawan asing sering tidak tahu bahasa, harga wajar, jarak antar wilayah, dan etika setempat.

## Solusi
Website satu halaman yang meminta minat, wilayah, budget, rombongan, tanggal kunjungan, dan kata kunci, lalu memberi rekomendasi terurut dengan skor dan alasan yang bisa dijelaskan.

## Fitur utama
- Rekomendasi AI berbasis konten dengan skor transparan: 40 minat + 25 wilayah + 20 budget + 15 rombongan, maksimum 100.
- Penyesuaian cuaca: bila peluang hujan 60% atau lebih, tempat outdoor dikurangi 15 poin, tempat indoor budaya, kuliner, dan UMKM ditambah 10 poin.
- Bahasa Indonesia dan Inggris.
- Tips dan etika per tempat, estimasi biaya, dan durasi kunjungan.
- Pencarian dan filter wisata atau UMKM.
- Itinerary tersimpan di perangkat, dikelompokkan per wilayah, dengan total estimasi biaya.
- Konverter mata uang IDR ke USD dan EUR.
- Nomor darurat publik Indonesia dan estimasi waktu tempuh antar wilayah.
- Bagikan itinerary lewat WhatsApp atau salin teks.

## Teknologi AI
Sistem rekomendasi berbasis konten (content-based recommender). Tidak ada panggilan model bahasa eksternal, tidak ada API key, tidak ada server, dan tidak ada data pribadi yang dikirim keluar. Cuaca dari Open-Meteo (gratis, tanpa API key). Kurs dari Frankfurter (gratis, tanpa API key). Jika layanan eksternal gagal, aplikasi tetap jalan dengan pesan yang jujur dan kurs cadangan yang dinyatakan sebagai estimasi.

## Cara menjalankan
Buka file `index.html` di browser modern. Tidak perlu instalasi, tidak perlu server, tidak perlu API key. Untuk demo juri, cukup buka URL deployment dan isi formulir.

## Struktur data
24 destinasi dan UMKM contoh di Bali, dengan kategori, wilayah, budget, rombongan yang cocok, estimasi biaya, durasi, deskripsi dua bahasa, dan tips dua bahasa. Harga adalah estimasi MVP, bukan harga resmi, dan bisa berubah. Jam buka tidak diklaim karena tidak diverifikasi dari sumber resmi per tempat.

## Anggota tim
Muhammad Alva Rayno, Universitas Teuku Umar, Program Studi Teknik Mesin, NIM 2405903010094, Kabupaten Aceh Barat, Aceh.

## Keterbatasan
- Data contoh terbatas, belum mencakup seluruh Bali.
- Cuaca hanya tersedia sekitar 16 hari ke depan dari Open-Meteo.
- Waktu tempuh adalah estimasi kondisi normal, bukan data lalu lintas real-time.
- Kurs berubah setiap hari dan hanya estimasi.

## Credits pihak ketiga
- Open-Meteo untuk prakiraan cuaca.
- Frankfurter untuk kurs mata uang.
- Data tempat bersifat umum dan ditulis ulang sebagai data contoh MVP, bukan salinan dari situs pihak ketiga.
