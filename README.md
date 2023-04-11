# Web-Scrapping using Beautifulsoup
Perkenalkan saya dimas pujangga, dalam project ini saya mengerjakan tugas akhir dalam Data Analytics Specialization di kelas Algoritma Data Science Academy School.

Projek ini dikembangkan sebagai salah satu capstone project dari Algoritma Academy Data Analytics Specialization. Deliverables yang diharapkan dari projek ini adalah melakukan simple webscrapping untuk mendapatkan informasi. Saya juga akan memanfaatkan flask dashboard sederhana untuk menampilkan hasil scrap dan visualisasi yang saya buat.

# Hasil Insight yang saya dapatkan dalam kasus ini dapat berbeda sewaktu-waktu dengan hasil data yang telah didapat dalam web tersebut....

## Dependencies

- beautifulSoup4
- pandas
- flask
- matplotlib

## Rubics

- Environment preparation (2 points)
- Finding the right key to scrap the data  & Extracting the right information (5 points)
- Creating data frame & Data wrangling (5 points)
- Creating a tidy python notebook as a report. (2 points)
- Implement it on flask dashboard (2 points)


## What You Need to Do

Pada captsone kali ini, saya memilih salah satu soal dibawah ini untuk dikerjakan.

1. (Easy) Data Volume Penjualan Ethereum dari `https://www.coingecko.com/en/coins/ethereum/historical_data?start_date=2022-01-01&end_date=2023-03-30#panel`

   * Dari halaman tersebut carilah `Date`, dan `Volume`.
   * Buat lah plot pergerakan volume perdagangan dari Ethereum. 

2. (Medium) Data kurs US Dollar ke rupiah dari `https://www.exchange-rates.org/history/IDR/USD/T`

    * Dari halaman tersebut carilah `harga harian`, dan `tanggal`
    * Bualah plot pergerakan kurs USD 
    
3. (Hard) Data pekerjaan data di indonesia pada  `https://www.kalibrr.id/job-board/te/data/1`

    * Dari Halaman tersebut carilah `title pekerjaan` , `lokasi pekerjaan` , `tanggal pekerjaan di post dan dealine submit permohonan`, dan `perusahaan`
    * tariklah 15 halaman
    * Buatlah plot dari jumlah pekerjaan berdasarkan lokasi.


Saya memilih soal yang ke-3 dengan tingkat kesulitan hard, karena menurut saya dalam kasus tersebut yaitu data pekerjaan di indonesia lebih dibutuhkan masyarakat kita pada umumnya, karena setelah usai dalam masa pandemi ini dan diingat banyaknya mahasiswa freshgraduate yang belum menemukan pekerjaannya di bidang data membutuhkan informasi mengenai data pekerjaan indonesia ini.

Saya mencoba untuk melakukan insight yang ada dalam data pekerjaan tersebut dengan metode webscraping ini agar memudahkan masyarakat umum untuk menarik kesimpulan dengan insight yang saya dapat dan dapat melakukan analisis lebih lanjut terkait role pekerjaan apa saja yang banyak dibuka dan mempertimbangkan kembali lokasi pekerjaan yang akan mereka masuki.



