# VintiX Mini RC Website

Website katalog dan simulasi pembelian RC car berbasis `HTML`, `CSS`, dan `JavaScript` (tanpa framework).

## Fitur dan Cara Menggunakannya

1. Navbar sticky + active section
- Fitur: navbar tetap di atas saat scroll, dan menu aktif mengikuti section yang sedang terlihat.
- Cara pakai: klik menu `HOME`, `OUR MODELS`, `FEATURES`, atau `GALLERY`.

2. Hero CTA scroll
- Fitur: tombol `EXPLORE NOW` scroll halus ke section produk.
- Cara pakai: klik tombol `EXPLORE NOW` di hero.

3. Katalog produk 3D
- Fitur: setiap kartu produk menampilkan model 3D interaktif (`model-viewer`).
- Cara pakai: scroll ke section `OUR RC MODELS`, lalu lihat model pada tiap kartu.

4. Lazy load model 3D
- Fitur: model 3D dimuat saat mendekati viewport agar halaman terasa lebih ringan.
- Cara pakai: cukup scroll halaman; model akan load otomatis saat dibutuhkan.

5. Preview detail produk (modal 3D)
- Fitur: modal berisi viewer 3D lebih besar, deskripsi, spesifikasi, dan harga.
- Cara pakai: klik `VIEW DETAILS` di kartu produk.

6. Keranjang belanja
- Fitur: tambah produk, ubah quantity (`+`/`−`), hapus item, dan hitung total otomatis.
- Cara pakai:
1. Klik `ADD TO CART` pada produk.
2. Klik ikon cart (`🛒`) di navbar.
3. Gunakan tombol `+`, `−`, atau `Remove`.

7. Ringkasan subtotal, pajak, total
- Fitur: nilai `Subtotal`, `Tax (10%)`, dan `Total` selalu update realtime.
- Cara pakai: ubah isi keranjang, maka ringkasan berubah otomatis.

8. Checkout + simulasi pembayaran
- Fitur: form checkout dengan validasi required, tombol proses pembayaran, dan modal sukses.
- Cara pakai:
1. Dari cart, klik `PROCEED TO CHECKOUT`.
2. Isi form checkout.
3. Klik `COMPLETE PAYMENT`.

9. Modal sukses pembayaran
- Fitur: menampilkan `Order ID` dan total pembayaran.
- Cara pakai: setelah pembayaran simulasi selesai, modal sukses akan muncul otomatis.

10. Penyimpanan keranjang otomatis
- Fitur: cart disimpan di `localStorage` browser.
- Cara pakai: tambahkan produk ke cart lalu refresh halaman; item tetap tersimpan.

11. Aksesibilitas modal
- Fitur: modal bisa ditutup dengan `Esc`, fokus keyboard tertahan di dalam modal, dan atribut ARIA dialog dasar.
- Cara pakai: saat modal terbuka, tekan `Esc` untuk menutup atau gunakan `Tab` untuk navigasi elemen di dalam modal.

## Catatan

- Ini masih frontend-only (tanpa backend/database/payment gateway real).
- Data checkout tidak dikirim ke server.
- Total dan pembayaran adalah simulasi untuk demo UI/UX.
