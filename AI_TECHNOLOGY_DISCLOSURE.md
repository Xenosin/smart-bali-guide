# AI & Technology Disclosure - Smart Bali Guide

## AI di dalam produk
- Jenis AI: sistem rekomendasi berbasis konten (content-based recommender).
- Mekanisme: setiap tempat punya profil minat, wilayah, budget, dan rombongan. Skor = 40 x minat + 25 x wilayah + 20 x budget + 15 x rombongan. Jika peluang hujan 60% atau lebih, tempat outdoor dikurangi 15 poin dan tempat indoor ditambah 10 poin.
- Tidak ada model bahasa eksternal yang dipanggil oleh produk. Tidak ada API key produk. Tidak ada data pribadi pengguna yang dikirim ke server.

## Layanan eksternal yang dipakai produk
- Open-Meteo: prakiraan cuaca, gratis, tanpa API key.
- Frankfurter: kurs mata uang, gratis, tanpa API key.
- Keduanya hanya dibaca di browser pengguna. Jika gagal, produk tetap jalan dan menyatakan kegagalan itu dengan jujur.

## AI-assisted development
- Kode dibantu oleh asisten AI selama pengembangan di VM, atas arahan pemilik produk. Pemilik produk bertanggung jawab atas seluruh source code dan perilaku aplikasi.
- Tidak ada kode, data, atau kunci rahasia pihak ketiga yang disalin tanpa izin ke dalam produk ini.

## Status karya
- Development for competition: MVP ini dikembangkan untuk AI Web Innovation Challenge Bali Digifest 2026.
- Tidak ada bagian produk yang diklaim sebagai karya pihak ketiga. Template dan library yang dipakai adalah teknologi web standar (HTML, CSS, JavaScript) tanpa framework berbayar.

## Keamanan
- Tidak ada API key, password, token, atau kredensial di dalam repositori ini.
- Itinerary hanya tersimpan di perangkat pengguna melalui localStorage browser, bukan di server.
