> Bahasa Indonesia: Terjemahan dengan bantuan mesin dari sumber bahasa Inggris resmi. Koreksi dalam bahasa asli dipersilakan. [Bahasa inggris](../../15-Why-a-Language-Model-Is-a-Replaceable-Tool.md) | [Semua bahasa](../README.md)

# Gunakan model bahasa untuk pekerjaan, bukan sebagai memori

![Alat, file terlatih, dan koleksi sumber menyimpan catatan terpisah tentang asal dan istilahnya.](../../illustrations/tool-model-source-index.png)

Robot Brain bukan model bahasa dengan memori ekstra. Ini adalah perangkat lunak pencatatan, analisis, perakitan, dan pemeriksaan yang memutuskan kapan model bahasa akan membantu dan pekerjaan terbatas apa yang dapat dilakukan.

Model paling kuat yang tersedia tidak selalu merupakan pilihan terbaik untuk pekerjaan tersebut.

Model bahasa berbayar mungkin cocok untuk penelitian atau penulisan yang sulit. Model lokal kecil mungkin cukup untuk menjelaskan latar belakang. Pencarian mungkin cukup untuk menemukan sebuah bagian. Proses yang tetap mungkin lebih aman bila jawabannya harus mengikuti aturan yang pasti. Terkadang jawaban terbaik adalah jawaban yang sudah diperiksa dan disimpan.

Pembuat permintaan membuat pilihan tersebut berdasarkan kebutuhan pekerjaan. Ini mungkin menggunakan model, menggabungkan beberapa metode terbatas, menggunakan kembali pekerjaan yang diperiksa, atau tidak membuat panggilan model sama sekali. Itu sebabnya ini bukan proxy yang hanya meneruskan permintaan ke layanan lain.

## Model online berbayar

Layanan model bahasa komersial membantu membangun proyek ini. Mereka mendukung penelitian, pengkodean, penulisan, dan ulasan.

Mereka juga kehilangan instruksi sebelumnya, mempersingkat percakapan, menebak penyebab, mengubur jawaban singkat dalam pengisi, dan melaporkan pekerjaan sebagai selesai sebelum memeriksanya. Memperbaiki kegagalan tersebut membutuhkan lebih banyak tunjangan yang dibayar dan lebih banyak waktu manusiawi.

Batasan mereka yang lebih dalam bukanlah pertanda buruk. Model yang terlatih tidak dapat membangun kembali sejarah lengkap pekerjaan manusia yang mengajarkannya. Itu mempertahankan pola sambil kehilangan tautan yang dapat diandalkan ke setiap penulis, tujuan, audiens, perselisihan, koreksi, dan sudut pandang yang hilang.

Pengetahuan luas itu masih bermanfaat. Ini seharusnya tidak menjadi satu-satunya tempat di mana sejarah seseorang berada.

Untuk permintaan online,Robot Brain mencatat model mana yang digunakan, apa yang diterima, apa yang dikembalikan, berapa biaya layanan, pemeriksaan apa yang dijalankan, dan apakah hasilnya disimpan. Latar belakang yang tidak didukung tetap merupakan saran model dan bukan fakta.

## Model lokal tidak dilatih pada orangnya

Instalasi saat ini berjalan kecilQwenmodel bahasa melaluivLLMpada perangkat keras lokal.Qwenadalah salah satu kontributor yang dapat diganti, bukan proyek itu sendiri.

Ia tidak belajar dengan melatih percakapan, pekerjaan, atau kehidupan seseorang. Pelatihan akan menggabungkan sejarah itu menjadi sebuah model dan melemahkan jalan kembali ke kata-kata dan peristiwa aslinya.

Alih-alih,Qwenmenerima materi yang dipilih untuk satu pekerjaan setelah percakapan berakhir. Metode lokal lainnya telah meneliti bahasa, pernyataan, hubungan, penalaran, waktu, pengalaman manusia, dan nilai-nilai dalam pertukaran.Qwenmenambahkan latar belakang luas yang tidak dimiliki oleh metode-metode tersebut. Hal ini memudahkan untuk menjelaskan apa yang terjadi dan mengapa.

Qwentidak mengungkapkan pemikiran tersembunyi, pelatihan, atau alasan pribadi asisten online. Kontribusi berguna asisten online sudah ada dalam percakapan yang disimpan. Latar belakang pengetahuan umum tidak hanya dimiliki oleh asisten tersebut, sehingga model lain yang sesuai dapat membantu menghubungkan bagian-bagian rekaman.

ItuQwenbacaan disimpan dengan nama model dan tanggal. Itu tetap terpisah dari percakapan dan dapat diperbaiki atau diganti nanti. Permintaan tersebut tidak harus meninggalkan perangkat keras lokal.

## Pencarian bukanlah penjelasan

Pencarian dapat menemukan bagian-bagian dengan kata atau subjek terkait. Ia tidak dapat memutuskan mengapa suatu peristiwa penting, apakah suatu tindakan menyebabkan tindakan lain, atau apa maksud seseorang.

Kesimpulan tersebut memerlukan bukti, sejarah, dan ruang untuk koreksi.

## Biaya termasuk waktu orang tersebut

Harga dan kecepatan bukan satu-satunya biaya. Jawaban yang murah menjadi mahal ketika seseorang menghabiskan waktu berjam-jam untuk menemukan kesalahannya, menjelaskan kembali sejarahnya, dan memperbaiki hasilnya.

Oleh karena itu, pembuat permintaan mempertimbangkan biaya layanan, waktu tunggu, percobaan ulang, penggunaan energi, dan pemeriksaan manusia. Model yang lebih kecil, metode lokal yang tetap, atau hasil yang disimpan dapat menciptakan nilai lebih ketika pekerjaannya lebih mudah untuk diperiksa.

## Sumber tetap dapat diidentifikasi

Catatan asli, salinan teks, tanggapan model, penelitian publik, kutipan, dan ulasan selanjutnya tetap menjadi hal yang berbeda.

Jika diketahui dan diizinkan, catatan tersebut menyimpan pencipta, tujuan, penonton, tanggal, bahasa, bukti, ketidaksepakatan, hak, dan koreksi selanjutnya. Ketersediaan dan kredit publik tidak dengan sendirinya memberikan izin untuk mendistribusikan kembali materi yang dilindungi.

Repositori ini mencakup dokumentasi publik dan ilustrasi yang dibuat proyek. Ini meninggalkan catatan pribadi, kata sandi, rincian akses, rahasia penyedia, dan materi luar yang belum dibersihkan untuk dirilis.
