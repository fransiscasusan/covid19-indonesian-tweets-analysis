# Analisis Topik-Topik Perbincangan Berbahasa Indonesia di Twitter Seputar Koronavirus

Pandemi koronavirus bisa dianggap sebagai peristiwa paling signifikan di tahun 2020: sampai tanggal 8 Juni, sudah ada lebih dari 6,9 juta orang yang terinfeksi dan paling tidak 400 ribu di antaranya meninggal dunia. Di Indonesia sendiri, banyaknya kasus positif telah mencapai lebih dari 31 ribu dengan jumlah kasus baru harian yang terus meningkat, menjadikan Indonesia sebagai negara dengan kasus koronavirus terbanyak ke-33 di dunia menurut New York Times (sumber: https://www.nytimes.com/interactive/2020/world/coronavirus-maps.html). Lebih buruknya, riset dari Centre for Mathematical Modelling of Infectious Diseases memperkirakan bahwa hanya sekitar 2 persen dari kasus positif koronavirus di Indonesia telah dilaporkan (sumber: https://www.bbc.com/news/world-asia-52124193).

Kita tidak bisa memungkiri bahwa pandemi koronavirus telah membawa akibat negatif bagi industri, pemerintah, dan masyarakat dalam berbagai aspek. Semenjak Indonesia mengumumkan kasus koronavirus pertamanya pada tanggal 2 Maret, berbagai usaha telah dilakukan pemerintah untuk mengurangi pesatnya penularan koronavirus. Hal ini tentunya berdampak pada pertumbuhan ekonomi dan perkembangan sosial.

Melalui studi ini, kami ingin memahami hal-hal yang umumnya dibicarakan masyarakat Indonesia semasa pandemi koronavirus ini. Kami memutuskan untuk mempelajari hal ini dengan cara menganalisis aktivitas pengguna Twitter dikarenakan kemudahan memperoleh twit-twit melalui API-nya. Selain itu, keberhasilan pelbagai studi di pelbagai disiplin (termasuk koronavirus; contoh: Ordun, Purushotham, dan Raff (2020)) dalam menggunakan data Twitter untuk mempelajari perilaku manusia menjadi faktor lain yang menjustifikasi metode riset ini.

Untuk mendapatkan twit-twit yang berkaitan dengan pandemi koronavirus, kami menggunakan kumpulan tweet ID yang disaring oleh Chen, Lerman, dan Ferrara (2020). Kami mengekstraksi twit-twit yang ditulis pada minggu terakhir Januari, Februari, Maret dan April, serta pertengahan Mei dikarenakan lamanya waktu ekstraksi akibat pembatasan yang diberlakukan Twitter dalam mengambil data menggunakan API-nya. Hal ini akan dijelaskan secara lebih mendetail di bagian selanjutnya.

Pertanyaan-pertanyaan yang akan kami jawab dalam studi singkat ini adalah:
- Apa topik-topik yang umumnya dibicarakan oleh masyarakat Indonesia semasa pandemi koronavirus ini? Adakah perbedaan dalam distribusi topik yang berarti setiap bulannya? Apakah kita bisa mengaitkan perbedaan tersebut dengan peristiwa-peristiwa seputar koronavirus yang terjadi di Indonesia?
- Bagaimanakah pola retweet dan like per topik? Twit-twit dengan topik apakah yang menyebar paling cepat di kalangan masyarakat Indonesia?
- Apa hashtag-hashtag yang umumnya digunakan dalam twit yang ditulis masyarakat Indonesia? Adakah perbedaan yang berarti setiap bulannya? Apakah kita bisa mengaitkan penggunaan hashtag dengan topik yang dibicarakan oleh masyarakat Indonesia?

### Daftar isi
1. Coronavirus-tweets-indonesia-analysis.ipynb: _notebook_
2. fdist.csv: pemetaan manual kata-kata
3. hydrate.py: pengambilan atribut-atribut sebuah twit dari _tweet ID_-nya - diambil dari https://github.com/echen102/COVID-19-TweetIDs
4. stop.txt: _stopwords_ bahasa Indonesia yang diperoleh dari https://github.com/stopwords-iso/stopwords-id
