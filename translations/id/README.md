> Bahasa Indonesia: Terjemahan dengan bantuan mesin dari sumber bahasa Inggris resmi. Koreksi dalam bahasa asli dipersilakan. [Bahasa inggris](../../README.md) | [Semua bahasa](../README.md)

# Simpan catatannya. Ganti modelnya.

![Catatan seseorang tetap berada di satu tempat sementara bagian kerja yang terpisah menangani pekerjaan terbatas.](../../illustrations/specialist-assembly-line-vs-giant-chatbot.png)

Robot Brain adalah perangkat lunak untuk melestarikan sejarah dan makna di balik pekerjaan manusia yang telah berlangsung lama. Ini bukan model bahasa, chatbot, atau layanan yang meneruskan setiap pertanyaan ke model.

Model bahasa besar dapat meneliti, menulis, menjelaskan, dan membantu memecahkan masalah sulit. Layanan berbayar yang dibangun di sekitar mereka masih merupakan ruang kerja sementara. Mereka dapat mempersingkat percakapan yang panjang, kehilangan instruksi sebelumnya, memisahkan kesimpulan dari bukti, dan terus menulis seolah-olah sejarah yang hilang masih ada. Seseorang kemudian menghabiskan lebih banyak waktu dan penggunaan berbayar untuk membangun kembali konteks yang telah disediakan.

Perangkat lunak ini mengubah tempat nilai abadi berada. Percakapan, dokumen, keputusan, upaya yang gagal, koreksi, dan pertanyaan yang belum terjawab dari orang tersebut tetap disimpan dalam catatan yang dikontrol oleh orang tersebut. Program lokal dapat memeriksa catatan tersebut. Model bahasa dapat membantu pekerjaan yang dipilih, namun kontribusinya kembali ke catatan sebagai pekerjaan bertanggal dan dapat ditinjau. Model tersebut kemudian dapat diganti tanpa membawa serta sejarahnya.

[Baca dokumentasi ini dalam bahasa lain.](../README.md)

## Perbedaan dalam satu pandangan

| Layanan model bahasa komersial | Robot Brain |
|---|---|
| Menghasilkan jawaban dari materi yang sedang dalam tampilan kerjanya. | Menyimpan sumber lengkap dan sejarah di sekitarnya. |
| Mungkin mempersingkat atau menghilangkan percakapan sebelumnya seiring bertambahnya pekerjaan. | Menyimpan percakapan di luar setiap model sehingga dapat digunakan kembali. |
| Memadukan pengetahuan yang dipelajari dari banyak sumber tanpa jalur lengkap kembali ke masing-masing sumber dan keadaannya. | Menyimpan setiap sumber yang diketahui, temuan selanjutnya, koreksi, dan ketidaksepakatan sebagai catatan terpisah. |
| Dapat menulis, mencari, merencanakan, dan menilai jawabannya sendiri dalam satu pertukaran. | Memberikan penyimpanan, pencarian, analisis, penulisan, pengecekan, dan persetujuan pada bagian-bagian terpisah dengan kewenangan terbatas. |
| Mengontrol model, aturan layanan, batas penggunaan, dan perubahan produk. | Meninggalkan catatan abadi di bawah kendali orang tersebut. |
| Dibayar untuk upaya yang gagal dan pertukaran korektif serta pekerjaan yang bermanfaat. | Menyimpan kegagalan dan koreksi sehingga pelajarannya tidak perlu dibeli lagi. |

Robot Brain dapat memanggil model bahasa lokal atau online. Itu tidak mengubahnya menjadi model proxy. Ia dapat menyimpan, mencari, membandingkan, mengatur, dan membangun kembali pekerjaan sebelumnya tanpa memanggil model yang mengambil bagian dalam percakapan aslinya. Ketika suatu model berguna, permintaan tersebut merupakan salah satu langkah dalam proses yang lebih besar yang ada secara independen dari model tersebut.

## Mengapa ini dibangun

Model-model serba guna berbayar terkuat yang tersedia selama pengembangan mampu melakukan pekerjaan jangka panjang namun tidak dapat diandalkan.

Kegagalan yang tercatat termasuk instruksi yang hilang, bukti yang hilang, koneksi yang ditemukan, klaim penyelesaian yang terlalu dini, perubahan yang tidak diinginkan, dan kerusakan pada file kerja. Memperbaiki kegagalan tersebut membutuhkan lebih banyak permintaan, lebih banyak pengujian, lebih banyak tunjangan yang dibayarkan, dan lebih banyak waktu dan energi orang tersebut. Layanan tidak secara otomatis mengembalikan penggunaan yang dihabiskan untuk pekerjaan yang tidak dapat digunakan atau pertukaran yang diperlukan untuk memperbaikinya.

Masalahnya lebih besar daripada jawaban buruk mana pun. Generator teks sementara diminta untuk berfungsi sebagai memori, sejarawan, peneliti, penulis, pemeriksa, dan juri akhir. Pergantian model tidak mengubah tatanan tersebut.

Robot Brain dibangun dengan pengaturan yang berbeda: simpan catatan manusia terlebih dahulu, biarkan beberapa bagian yang dapat diganti berkontribusi padanya, dan memerlukan bukti di luar model pembangkitan sebelum pekerjaan penting diterima.

## Apa yang tidak bisa dipertahankan oleh model yang terlatih

Model bahasa besar mempelajari pola dari kumpulan besar karya manusia. Pola-pola tersebut membuat model berguna, namun model tersebut bukanlah pustaka dari karya lengkap yang membentuknya.

Di dalam model ini, pengaruh dari buku, artikel, percakapan, terjemahan, komunitas, label, dan umpan balik manusia digabungkan menjadi satu. Model tersebut biasanya tidak dapat menunjukkan sumber mana yang membentuk suatu kalimat tertentu. Ia tidak dapat memulihkan tujuan, pembaca, bukti, ketidaksepakatan, koreksi di kemudian hari, atau sudut pandang yang hilang dari setiap penulis.

Hal ini berarti hilangnya makna meskipun karya aslinya masih ada di tempat lain. Model ini mempertahankan beberapa kegunaan dari pekerjaan sambil membuang jalur yang dapat diandalkan untuk kembali ke lingkungan manusia.

Masalah yang sama muncul selama penggunaan biasa. Jawaban akhir mungkin bertahan setelah percakapan yang memberikan makna dipersingkat. Kesimpulannya tetap ada, namun upaya yang gagal, ketidakpastian, dan alasan di baliknya hilang dari pandangan kerja model.

Proyek ini tidak menjawab permasalahan tersebut dengan melatih model lain dalam kehidupan seseorang. Riwayat pribadi tetap dapat dibaca dan dilacak alih-alih digabungkan ke dalam model terlatih lainnya. Model bekerja dengan rekaman yang dipilih; mereka tidak menjadi catatan.

## Apa yang dilakukan setiap bagian

Perangkat lunak yang berfungsi memisahkan pekerjaan yang sering dibuat oleh layanan obrolan tampak seperti satu aktivitas:

1. **Penjaga sumber menyimpan apa yang terjadi.** Penjaga sumber menyimpan percakapan, dokumen, gambar, atau materi lainnya tanpa menggantinya dengan ringkasan.
2. **Salinan yang dapat dicari membuat sumber lebih mudah ditemukan.** Teks, deskripsi, dan indeks yang disalin mengarah kembali ke sumber yang tidak diubah dan dapat dibuat ulang.
3. **Pembaca lokal yang terfokus memeriksa fitur-fitur tertentu.** Metode terpisah melihat bahasa, pernyataan, hubungan, penalaran, waktu, pengalaman manusia, dan nilai-nilai. Masing-masing hanya melaporkan temuannya sendiri dan bagian di belakangnya.
4. **Catatan sejarah membuat perubahan tetap terlihat.** Temuan baru, koreksi, ketidaksepakatan, upaya yang gagal, dan pertanyaan terbuka ditambahkan tanpa menulis ulang peristiwa sebelumnya.
5. **Pembuat permintaan mengumpulkan hal-hal yang dibutuhkan suatu pekerjaan.** Alat ini memilih sumber dan temuan yang relevan, serta mencatat hal-hal yang disertakan atau tidak disertakan.
6. **Model bahasa mungkin hanya memberikan bantuan terbatas.** Model lokal dapat memberikan latar belakang yang luas. Model online dapat membantu penelitian atau penulisan yang sulit. Respons mana pun tetap merupakan kontribusi bertanggal yang dapat diperiksa, ditolak, atau diganti.
7. **Pemeriksaan terpisah membandingkan hasilnya dengan permintaan dan bukti.** Model yang menulis jawaban tidak dapat menyatakan karyanya diterima.
8. **Layar memungkinkan seseorang menggunakan perangkat lunak.** TermasukLibreChatgarpu adalah salah satu layar tersebut. Menggantinya tidak menggantikan catatan atau bagian kerja lainnya.

Tidak ada satu pun bagian yang dihadirkan sebagai asisten yang maha tahu. Keterbatasan pekerjaan mereka membuat setiap bagian dapat diganti.

## Membuat percakapan yang sudah selesai bermanfaat kembali

Percakapan yang lengkap berisi permintaan orang tersebut, balasan sebenarnya dari model bahasa, upaya yang dilakukan, kegagalan, koreksi, dan titik di mana pertukaran berakhir. Pesan-pesan tersebut mempertahankan kontribusi model asli tanpa mengharuskan model tersebut menjelaskan dirinya sendiri nanti.

Pembaca lokal yang terfokus memeriksa pertukaran yang disimpan dari beberapa sudut. Mereka dapat menemukan pola dan hubungan yang detail tanpa bergantung pada pengetahuan dunia yang luas. Temuan terpisah mereka tetap terhubung dengan bagian sebenarnya dari percakapan tersebut.

Temuan-temuan tersebut mungkin masih memerlukan latar belakang pengetahuan biasa sebelum dapat memberikan penjelasan yang jelas. Untuk langkah terbatas itu, kecilQwenmodel dijalankan secara lokalvLLM. Ini menambahkan ikhtisar bertanggal yang membantu menghubungkan temuan-temuan terperinci dan menjelaskan apa yang dicapai oleh pertukaran tersebut.

Qwentidak memulihkan pemikiran tersembunyi atau riwayat pelatihan model online. Ini memberikan latar belakang pengetahuan luas yang tidak unik pada model aslinya. Kontribusi berguna dari model asli sudah terpelihara dalam kata-kata yang dihasilkannya.

ItuQwenikhtisar disimpan di samping sumber dan temuan sebelumnya. Itu bisa diperbaiki atau diganti. Percakapan asli dan analisis lokal yang terperinci tetap tidak berubah.

## Apa yang berhasil sekarang

Implementasi saat ini dapat menyimpan percakapan yang telah selesai, memeriksanya melalui metode lokal yang terpisah, menambahkan bacaan pengetahuan umum lokal, dan mengumpulkan setiap kontribusi yang disimpan ke dalam catatan yang dapat dibuat kembali nanti.

Ia juga dapat menyiapkan permintaan terbatas untuk model online ketika bantuan dari luar berguna. Layanan itu hanya menerima materi yang dipilih. Jawabannya kembali ke catatan lokal, di mana pemeriksaan dan persetujuan manusia-bukan model-yang menentukan apa yang disimpan.

Inilah pencapaian utamanya: pekerjaan yang tadinya bergantung pada satu percakapan sementara dapat tetap berguna setelah layar obrolan, model, dan penyedianya hilang.

## Baca penjelasan selengkapnya

- [Mengapa model bahasa besar tidak dapat mempertahankan keseluruhan cerita](01-Why-Large-Language-Models-Cannot-Preserve-the-Full-Story.md)
- [Apa yang dilakukan setiap bagian-dan apa yang tidak dikontrol oleh model mana pun](02-A-Lasting-Record-Outside-the-Model.md)
- [Pertahankan koreksinya tanpa menghapus kesalahannya](03-How-Knowledge-Changes-Without-Erasing-History.md)
- [Ikuti klaim kembali ke bukti](04-How-Every-Claim-Can-Be-Checked.md)
- [Bangun dokumen sebelum menulis prosa](05-How-Evidence-Becomes-a-Finished-Document.md)
- [Jelaskan kebenaran yang sama kepada pembaca yang berbeda](06-One-Meaning-Different-Readers.md)
- [Simpan riwayat pribadi di bawah kendali orang tersebut](07-Privacy-and-Control-Stay-With-People.md)
- [Apa yang dilakukan implementasi saat ini](08-What-Works-Today.md)
- [Mengapa desainnya mengambil dari banyak bidang](09-How-Research-Strengthens-the-System.md)
- [Membantu tanpa menyerahkan catatan pribadi](11-Contribute-Without-Giving-Up-Control.md)
- [Kata-kata yang digunakan di seluruh dokumen ini](12-A-Short-Guide-to-Key-Terms.md)
- [Ikuti satu permintaan melalui bagian yang berfungsi](13-The-Parts-Running-Today.md)
- [Gunakan model bahasa untuk pekerjaan, bukan sebagai memori](15-Why-a-Language-Model-Is-a-Replaceable-Tool.md)
- [Kegagalan yang terjadi pada layanan model bahasa berbayar-dan upaya perlindungan yang dihasilkannya](16-What-Commercial-Language-Model-Services-Got-Wrong.md)
- [Pelajaran yang mengubah desain](17-How-Language-Models-Lose-Meaning-and-How-to-Preserve-It.md)
- [Catatan penggunaan publik, kredit, dan privasi](18-Use-Attribution-and-Limits.md)
- [Bagaimana percakapan yang selesai menjadi pengetahuan yang bertahan lama](19-What-the-System-Accomplishes.md)
- [Apa yang terjadi selanjutnya](20-Where-the-System-Goes-Next.md)

## Kredit, sumber, dan hak

- [Apa yang membantu membentuk pekerjaan ini](10-What-Helped-Shape-This-Work.md)
- [Penelitian di balik desain](14-Sources-Behind-the-Design.md)
- [Sumber, lisensi, dan pemeriksaan rilis publik](../../SOURCES-LICENSES-AND-PRIVACY.md)

## Lisensi

Tulisan asli, diagram, dan ilustrasi proyek tersedia di bawah organisasi[Lisensi Internasional Creative Commons Atribusi 4.0](../../LICENSE.md), kecuali dokumen menyatakan ketentuan yang berbeda. Materi yang dibuat oleh orang lain mempunyai hak dan ketentuannya sendiri.

## Kemandirian dan privasi

Ini adalah proyek pribadi independen yang dikembangkan berdasarkan waktu pribadi, peralatan, akun, dan layanan berbayar. Tidak ada majikan yang berpartisipasi di dalamnya. Menyebutkan seseorang, pemberi kerja, lembaga, penyedia model, kelompok penelitian, aturan bersama, atau proyek luar tidak berarti partisipasi, persetujuan, kemitraan, atau dukungan.

Rilis publik tidak termasuk catatan pribadi, rincian identitas, kata sandi, informasi koneksi pribadi, informasi pemberi kerja, dan instruksi untuk menghubungi layanan swasta. Deskripsi kegagalan model terbatas pada rekaman perilaku dan dampaknya; mereka tidak mengklaim penyebab atau motif yang dirahasiakan. Dokumen tersebut bukanlah nasihat profesional atau janji hasil.

![Jalur dari memori yang dikontrol oleh penyedia layanan menuju catatan yang tetap ada pada orang-orang yang berkepentingan.](../../illustrations/open-door-human-future.png)
