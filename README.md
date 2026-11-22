# Anti Boncos

Kalkulator harga jual gratis untuk seller Shopee, TikTok Shop, dan jualan langsung (QRIS).
Isi modal dan untung yang kamu mau, aplikasi menghitung harga yang perlu dipasang supaya untung tetap utuh setelah potongan marketplace.

**Pakai langsung:** https://toni2411.github.io/anti-boncos/ (bisa dipasang ke layar utama HP dan jalan offline)

## Fitur
- Harga Jual: harga minimum, pembulatan harga, uang masuk, untung bersih, rincian potongan, harga di toko lain
- Cek Produk: status aman, untung tipis, atau rugi untuk banyak produk sekaligus, plus saran harga
- Modal dari resep: hitung HPP per pcs untuk jualan makanan dan minuman
- Tarif Toko: semua potongan bisa disesuaikan, lengkap dengan sumber resmi
- Data tersimpan di perangkat pengguna saja, tanpa login, tanpa server

## Dasar perhitungan
Semua rumus dijelaskan di dalam aplikasi (tombol "Dasar hitungan & sumber"). Ringkasnya:

- Potongan persen = (harga di toko − voucher yang ditanggung penjual) × tarif, dibatasi batas maksimal bila ada (rumus resmi Shopee)
- Untung bersih = uang masuk − (modal + kemasan)
- Harga minimum = (modal + kemasan + biaya tetap + untung) ÷ ((1 − voucher) × (1 − total tarif)); dicari numerik (bisection) bila ada batas maksimal atau tarif bertingkat
- Pembulatan ke akhiran 900 mengikuti left-digit effect, dan selalu dicek ulang supaya target untung tetap tercapai

## Sumber
1. Shopee Seller Centre: Ringkasan Jenis Biaya untuk Berjualan di Shopee, https://seller.shopee.co.id/edu/article/3489
2. Shopee Seller Centre: Biaya Administrasi Penjual Shopee, https://seller.shopee.co.id/edu/article/7187
3. Bisnis.com: Biaya Wajib Seller, TikTok Shop vs Shopee (21 Mei 2026)
4. Metrotvnews: Komisi TikTok Shop Dipangkas, Maksimal Rp60 Ribu/Item
5. Bank Indonesia: MDR QRIS Bagi Merchant, https://www.bi.go.id/id/publikasi/ruang-media/cerita-bi/Pages/mdr-QRIS.aspx
6. AccountingCoach: Gross Margin and Markup, https://www.accountingcoach.com/blog/gross-margin-markup
7. AccountingTools: What is Cost of Goods Sold, https://www.accountingtools.com/articles/what-is-cogs-cost-of-goods-sold.html
8. Thomas & Morwitz (2005), The Left-Digit Effect in Price Cognition, Journal of Consumer Research 32(1), https://doi.org/10.1086/429600
9. UU No. 8 Tahun 1999 tentang Perlindungan Konsumen, Pasal 9 ayat (1) huruf a dan Pasal 62

Tarif dicek 23 November 2026. Tarif marketplace bisa berubah, jadi selalu cocokkan dengan Seller Centre dan Rincian Penghasilan.

Dibuat oleh Muhammad Fathoni · https://lynk.id/toniii24 · https://toni2411.github.io
