BAB I
PENDAHULUAN

1.1	Latar Belakang
Pada saat ini video streaming banyak diterapkan pada dunia Internet. Tetapi untuk pengadaan video streaming di Internet tidak mudah. Selain membutuhkan biaya space, domain, dll, dibutuhkan pula jaringan Internet yang mempunyai bandwidth yang besar pula. Melihat permasalahan diatas, jadi ada beberapa hal yang perlu dipertimbangkan dalam pembuatan program, antara lain kemudahan pemasangan, penggunaan, dan kompatibilitas terhadap sistem operasi yang digunakan
DILo (Digital Innovation Lounge) Bandung adalah sebuah creative camp yang dikembangkan oleh MIKTI yang bekerja sama dengan telkom, sebagai pusat interaksi peminat dan pelaku industri kreatif digital di kota Bandung yang bertujuan menciptakan bibit-bibit Digital Preneur yang selanjutnya siap masuk ke industri (Creative Center). Didalam Creative Camp, komunitas kreatif digital akan diberikan pemahaman mengenai arah yang sebaiknya dilalui untuk masuk ke industri kreatif digital, termasuk arah sektor industri yang potensial untuk dijalani. DILo sendiri berencana membuat studio bioskop sendiri yang menayangkan film – film yang khusus ada di bioskop dengan melalui media streaming. Untuk mendapatkan film – film tersebut DILo bekerja sama dengan para produser pembuat film untuk mengupload film tersebut ke cloud server berbasis web yang telah disediakan oleh DILo itu sendiri. Tetapi sebelumnya, user yang ada di DILo harus membeli film tersebut agar film – film itu dapat di tayangkan secara streaming di bioskop DILo itu sendiri dengan media streaming menggunakan device android. Dikarenakan human resource di PT DILo Bandung sedikit, dan juga pada proses pembuatannya sangat memprioritaskan pekerja dan client, dikarenakan akan selalu terjadi perubahan. 
Metodologi yang tepat untuk menangani masalah diatas adalah Metodologi Scrum. Scrum merupakan sebuah kerangka kerja untuk mengembangkan sebuah produk yang kompleks, di mana visi dari Scrum adalah produk yang bernilai tinggi secara kreativitas maupun produktivitas. Scrum juga mendukung akan ukuran tim yang kecil dan juga dapat menerima berbagai perubahan yang mungkin akan muncul pada proses pengembangan aplikasi.

1.2	Identifikasi Masalah
Identifikasi masalah yang timbul pada aplikasi indie home cinema adalah sebagai berikut :
1.	Metode SCRUM dibutuhkan untuk menyelesaikan aplikasi ini.
2.	Belum tersedia blue print dari android untuk membeli film dan streaming film di android.

1.3	Tujuan dan Manfaat
Tujuan
Adapun tujuan dari pembuatan aplikasi indie home cinema adalah sebagai berikut:
1.	Menggunakan metode SCRUM dapat mempermudah menampilkan seluruh aktivitas aplikasi.
2.	Menentukan dan merancang blue print android untuk menampung film yang telah dibeli oleh user dan user bias streaming film tersebut.

Manfaat
Manfaat yang dapat diperoleh dari pembuatan aplikasi indie home cinema ini yaitu :
Bagi peneliti : 
1	Menerapkan ilmu-ilmu yang diperoleh selama kuliah.
2	Mengetahui kondisi sebenarnya yang terjadi di dunia kerja.
3	Sebagai pengalaman kerja peneliti.
4	Menambah wawasan peneliti tentang penerapan media streaming di android device.


Bagi perusahaan : 
1	Penelitian ini dapat dijadikan sebagai referensi dalam perancangan sistem di perusahaan.
2	Memudahkan dalam memperluas proses bisnis dari aplikasi ini. 
Bagi Politeknik Pos Indonesia : 
1	Mengetahui kemampuan mahasiswa dalam menguasai teori yang telah diperoleh selama kuliah 
2	Laporan hasil penelitian ini dapat dijadikan sebagai referensi bagi mahasiswa lainnya yang ingin mengangkat topik mengenai media streaming.

1.4	Ruang Lingkup
Ruang lingkup yang akan dibahas peneliti adalah:
1.	Analisis sistem ini hanya melingkupi login user, memilih dan membeli film dari server cloud, dan streaming film dari server cloud menggunakan android device. 
2.	Semua aktifitas di atas dilakukan dengan android device yaitu HP android.
3.	Tools yang digunakan adalah Android Studio.

1.5	Penelitian Sebelumnya
A. Made Krisnanda (2014) Implementasi Metodologi SCRUM dalam  Pembangunan Situs Harga Komoditas
B.  Fiqi Rathomy (2007) Analisa Perbandingan Kinerja Layanan Video Streaming pada Jaringan IP dan Jaringan MPLS
Pada penelitian yang dikutip dari “Made Krisnanda (2014)” yang menyatakan bahwa metodologi SCRUM membuktikan bahwa dari hari ke hari proyek pengembangan sistem makin memerlukan fleksitabilitas yang tinggi untuk dapat memenuhi kepuasan pelanggan.
Pada penelitian yang dikutip dari “Fiqi Rathomy (2007)” yang menyatakan bahwa hasil pengujian jaringan IP terdapat packet loss tanpa bebas sebesar 0.15 % dan juga pada pengukuran delay, transmisi video pada jaringan MPLS memiliki delay lebih besar daripada jaringan.
Jadi, kesimpulan dari kedua penelitian tersebut disimpulkan bahwa metodologi SCRUM ini cocok untuk membangun sebuah sistem yang didalamnya memerlukan fleksitabilitas tinggi karena banyaknya permintaan perubahan dari klien. Dan untuk media streaming, peneliti menggunakan protocol UDP dalam mengirimkan data. Dikarenakan dari hasil penelitian yang dikutip dari peneliti sebelumnya lebih baik menggunakan protocol UDP karena beban packet loss nya lebih sedikit daripada menggunakan protocol lainnya. 

1.6	Sistematika Penulisan
Sistematika penulisan laporan pembuatan Analisis dan Perancangan Aplikasi Android Indie Home Cinema Dengan Menggunakan Metode SCRUM (Studi Kasus : PT DILo Bandung) ini sebagai berikut :
BAB I 	PENDAHULUAN
Pembahasannya meliputi latar belakang, identifikasi masalah, tujuan, ruang lingkup, penelitian sebelumnya, sistematika penulisan. Pada bagian ini akan membantu pembaca dalam menganalisa latar belakang dan mengindentifikasi masalah dari sistem dan tujuan dari dibuatnya Analisis dan Perancangan Aplikasi Android Indie Home Cinema Dengan Menggunakan Metode SCRUM (Studi Kasus : PT DILo Bandung)
BAB II	LANDASAN TEORI
Pembahasannya meliputi uraian dan sumber tentang penjelasan mengenai Analisis dan Perancangan Aplikasi Android Indie Home Cinema Dengan Menggunakan Metode SCRUM (Studi Kasus : PT DILo Bandung) yang akan dibuat dari sistem tersebut dan membantu proses berjalannya sistem.
BAB III	ANALISIS ORGANISASI PERUSAHAAN
Gambaran Umum Perusahaan adalah  Bagian ini menceritakan secara umum produk/jasa yang dihasilkan. Sejarah Perusahaan  berisi uraian asal-usul berdirinya perusahaan. Struktur Organisasi Perusahaan memuat struktur organisasi perusahaan secara menyeluruh dan struktur organisasi turunannya (per bagian). Job Description memuat uraian tentang tugas pokok masing-masing bagian dari semua bagian dalam Struktur Organisasi Perusahaan.
BAB IV	METODOLOGI PENELITIAN
Menjelaskan mengenai metodologi yang digunakan pada Analisis dan Perancangan Aplikasi Android Indie Home Cinema Dengan Menggunakan Metode SCRUM (Studi Kasus : PT DILo Bandung)
BAB V        ANALISIS DAN PERANCANGAN SISTEM
Pembahasan yang disajikan meliputi struktur menu yang membahas tentang penjelasan dari setiap menu dan sub menu aplikasi ini. Gambar dari suatu rancangan menjelaskan proses aplikasi manajemen data ini dari awal sampai akhir.
BAB VI        PENGKAJIAN dan EVALUASI
Pengkajian dan Evaluasi, menjelaskan implementasi , pengujian , serta hasil pengujian dari methodology yang diterapkan pada aplikasi .
BAB VII        KESIMPULAN dan SARAN
Pada bab ini berisikan pencapaian tujuan dari rancangan yang dibuat, serta saran yang konstruktif yang berdasarkan atas kesimpulan dari hasil aplikasi yang telah dibuat.

