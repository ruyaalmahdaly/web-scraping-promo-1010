# Web Scraping Data X — Promo Digital 10.10

## Deskripsi Proyek
Proyek ini bertujuan mengumpulkan unggahan dari platform X (Twitter) yang berkaitan dengan promo digital 10.10 menggunakan Tweet Harvest melalui Google Colab.

## Tujuan
- Mengumpulkan data unggahan X berdasarkan kata kunci terkait promo 10.10.
- Membersihkan data dan menghapus unggahan duplikat.
- Menyimpan hasil pengumpulan data ke dalam format CSV.

## Metode
1. Melakukan crawling data X menggunakan Tweet Harvest.
2. Menggunakan kata kunci `promo 10.10` dengan rentang tanggal 12 September 2026 sampai sebelum 13 Oktober 2026.
3. Memilih unggahan berbahasa Indonesia.
4. Membersihkan teks dan menghapus data duplikat.
5. Menyimpan data akhir dalam format CSV.

## Hasil
Dataset akhir berisi 23 baris data unik dan 21 kolom.

File hasil tersedia di `output/dataset_promo_1010_final.csv`.

## Tools
- Google Colab
- Python
- Tweet Harvest
- Pandas

## Catatan
Dataset merupakan hasil pengumpulan berdasarkan kata kunci dan rentang tanggal yang digunakan. Tidak semua unggahan otomatis membahas pengalaman konsumen terhadap promo; relevansi data perlu diperiksa sesuai tujuan penelitian.
