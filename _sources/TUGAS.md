# TUGAS
# Pengantar Web Mining

Penambangan web adalah proses mencari dan mengekstrak informasi dari internet dengan menggunakan berbagai teknik data mining. Informasi yang diperoleh dapat membantu perusahaan dalam pengambilan keputusan secara lebih efektif. Berdasarkan tugas utama yang dilakukan selama proses penambangan, web mining dapat dibagi menjadi tiga kategori utama: Web Structure Mining, Web Content Mining, dan Web Usage Mining.
1. Web Structure Mining : Web structure mining berfokus pada penemuan informasi yang berguna dari hyperlink atau tautan, yang mencerminkan struktur suatu situs web. Contohnya, dari pola tautan kita bisa menemukan halaman web yang penting, yang menjadi dasar teknologi pada mesin pencari. Selain itu, struktur link juga bisa membantu mengidentifikasi komunitas dalam media sosial. Teknik ini tidak dapat dilakukan dengan data mining tradisional, karena data tabel biasa tidak memiliki struktur tautan seperti ini.
2. Web Content Mining : Web content mining bertujuan untuk mengekstrak informasi atau pengetahuan yang berguna dari isi halaman web. Misalnya, kita dapat secara otomatis mengklasifikasikan dan mengelompokkan halaman web berdasarkan topiknya. Tugas ini serupa dengan data mining konvensional, tetapi memungkinkan kita untuk menambang data spesifik di situs web, seperti deskripsi produk, postingan forum, atau ulasan konsumen, untuk berbagai tujuan. Hal ini tidak tersedia dalam data mining tradisional.
3. Web Usage Mining : Data penggunaan situs web biasanya dikumpulkan dari Web Server dan Server Aplikasi sebagai sumber utama. Data ini berupa log, yang tercatat setiap kali pengguna berinteraksi dengan halaman web. Berdasarkan sumbernya, log dapat dibagi menjadi tiga jenis: sisi server, sisi klien/pengguna, dan sisi proxy. Selain itu, terdapat sumber data tambahan, seperti cookies, data demografis, dan informasi lain yang relevan.

## Definisi
Penambangan web adalah penggunaan teknik data mining untuk menemukan dan mengekstrak informasi dari layanan web secara otomatis (Etzioni, 1996; CACM 39). Tujuannya adalah untuk menemukan pola atau pengetahuan yang berguna dari struktur hyperlink web, isi halaman web, serta perilaku pengguna (Bing Liu, 2007, Web Data Mining).

## Tantangan Pemrosesan Data Web
- Web memiliki ukuran yang sangat besar.
- Data tersedia dalam berbagai format, seperti HTML, XML, dan teks.
- Beberapa tantangan utama dalam pemrosesan data web meliputi:
    - Ukuran web yang sangat besar sehingga sulit diproses seluruhnya.
    - Kompleksitas struktur web yang tinggi.
    - Dinamika web yang cepat berubah.
    - Tidak adanya domain spesifik yang jelas karena web bersifat umum.
    - Web mencakup beragam konten dan jenis data.

## Penambangan Isi Web (Content Mining)

1. Proses Pengambilan Informasi dari Dokumen Web
Proses ini bertujuan untuk mendapatkan informasi yang bermanfaat dari berbagai dokumen di web. Pendekatannya menitikberatkan pada isi halaman web, antara lain:
    - Teks (Text Mining): mencakup artikel, deskripsi produk, maupun komentar pengguna.
    - Gambar (Image Mining): mencakup foto, ilustrasi, atau grafis lainnya.
    - Audio (Audio Mining): meliputi rekaman suara, musik, atau klip audio lainnya.
    - Video (Video Mining): mencakup video streaming, cuplikan, atau konten multimedia.
    - Data Terstruktur: informasi dalam bentuk tabel, daftar, atau format yang terorganisir lainnya.

2. Contoh Penerapan Text Mining
Text mining dapat digunakan untuk berbagai tujuan praktis, seperti:
    - Ekstraksi Informasi: mengambil fakta atau data penting dari teks.
    - Pemodelan Topik (Topic Modelling): mengidentifikasi tema utama dalam kumpulan dokumen.
    - Ringkasan Dokumen: membuat versi singkat dari teks panjang.
    - Klasifikasi Dokumen: termasuk analisis sentimen atau penilaian opini.
    - Pengelompokan Dokumen: membagi dokumen ke dalam kelompok berdasarkan kemiripan, misalnya untuk sistem rekomendasi.
    - Ekstraksi Kata Kunci: menemukan istilah atau frasa penting dalam teks.

# Klasifikasi Dokumen
## Tujuan Klasifikasi
Proses klasifikasi bertujuan agar dokumen atau gambar yang sebelumnya belum pernah diolah dapat ditempatkan ke dalam kategori yang sesuai dengan tingkat akurasi setinggi mungkin.

## Contoh Penerapan
Beberapa bidang yang memanfaatkan klasifikasi antara lain:
- Pengelompokan Berita: menempatkan artikel ke kategori topik tertentu.
- Pengelompokan Produk: mengklasifikasikan produk berdasarkan jenis atau kategori.
- Deteksi Spam: mengenali pesan atau konten yang bersifat spam.

## Metode Klasifikasi yang Umum Digunakan
Beberapa teknik populer dalam klasifikasi meliputi:
- Naive Bayes
- Support Vector Machines (SVM)
- Jaringan Saraf Tiruan (Deep Neural Networks)
- Transformers

# Pengelompokan Konten (Content Clustering)
## Tujuan Pengelompokan (Clustering)
Diberikan sekumpulan dokumen beserta ukuran kesamaan antar dokumen, tujuan clustering adalah membentuk kelompok sedemikian rupa sehingga:
- Dokumen di dalam satu kelompok memiliki kemiripan yang tinggi.
- Dokumen di kelompok yang berbeda memiliki kemiripan yang rendah.

## Contoh Penerapan
Beberapa aplikasi clustering antara lain:
- Pengelompokan Hasil Pencarian: menyusun hasil search engine agar dokumen sejenis berada dalam satu kelompok.
- Penemuan Topik (Topic Discovery): menemukan tema atau topik tersembunyi dalam kumpulan dokumen.

## Teknik dan Metode yang Digunakan

- Algoritma Clustering: K-Means, Pengelompokan Hierarkis (Hierarchical Clustering), S-BERT.
- Ukuran Kesamaan (Similarity Measures): Cosine Similarity, Jaccard, atau kesamaan berdasarkan embedding (Similarity of Embeddings).


This is just a simple starter to get you started.
You can learn a lot more at [jupyterbook.org](https://jupyterbook.org).
