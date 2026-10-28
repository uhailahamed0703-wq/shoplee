# Shoplee — e-commerce demo (iOS style)
Buka `index.html` di browser (butuh internet untuk foto produk dari Unsplash; jika gagal dimuat, otomatis tampil ikon cadangan).

## Fitur
Beranda + banner foto, pencarian live + saran, filter kategori, wishlist, detail produk (bottom sheet), keranjang (stepper, progres gratis ongkir), pesan/chat penjual dengan balasan otomatis, mode gelap otomatis.

## UCD (User-Centered Design)
- Pengguna: pembeli online Indonesia, mobile-first, sering belanja sambil multitasking.
- Tugas utama: cari produk -> bandingkan harga -> simpan/beli -> tanya penjual.
- Desain berdasarkan kebutuhan itu: pencarian di atas, kategori chip, harga coret + diskon, chat selalu terjangkau.
- Iterasi: uji dengan 5 pengguna, perbaiki titik bingung, ulangi.

## Heuristik Nielsen
1 Visibilitas status: skeleton loading, badge keranjang, toast, progres ongkir, indikator mengetik.
2 Sesuai dunia nyata: bahasa Indonesia, format Rp, ikon keranjang/hati.
3 Kontrol pengguna: tombol Urungkan di toast, hapus pencarian, Esc/tap luar menutup sheet.
4 Konsistensi: pola iOS (tab bar, sheet, large title), warna aksen tunggal.
5 Pencegahan error: tombol kirim nonaktif saat kosong, stepper tidak bisa minus tanpa konfirmasi urung.
6 Recognition: pencarian populer, chip kategori, balasan cepat chat.
7 Fleksibilitas: pintasan "Tanya penjual" dari produk, saran pencarian.
8 Minimalis: satu aksen warna, hierarki jelas.
9 Pemulihan error: pesan kosong menjelaskan langkah berikutnya.
10 Bantuan: chat penjual + Pusat bantuan di Akun.

## Persona: Nizar (21, mahasiswa)
| Kebutuhan / kendala | Solusi di aplikasi |
|---|---|
| Pencarian mudah | Pencarian live + saran, chip kategori, filter & urutkan (harga, rating, diskon) |
| Hemat & diskon | Flash Sale (timer + stok), voucher (HEMAT10, MAHASISWA, GRATISONGKIR), harga coret |
| Informasi tepercaya | Deskripsi, ringkasan rating, ulasan pembeli, bandingkan harga (data contoh) |
| Harga tidak konsisten | Harga sama di beranda, detail, keranjang, checkout; rincian subtotal, voucher, ongkir, PPN 11% |
| Pembayaran terbatas | QRIS, transfer bank VA, e-wallet, kartu, minimarket, COD (dengan batas) |
| Status pesanan tidak jelas | Halaman Pesanan: tahapan, estimasi tiba, nomor resi, linimasa, notifikasi |
| Lambat / error | Skeleton loading, gambar lazy, banner offline + coba lagi, pesan error yang jelas |
