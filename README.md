# 01-mppl

## A. Metode Klasik

    Beberapa metode dasar (klasik) diantaranya seperti :
1. Model Waterfall  

    Model Waterfall merupakan salah satu model untuk perencanaan dari sebuah Perangkat Lunak. Model Waterfall adalah salah satu model klasik yang bersifat sistematis. 

    Kelebihan metode ini yaitu :
    - Merupakan model pengembangan paling handal dan paling lama digunakan.
    - Cocok untuk sistem software yang bersifat generik.
    - Pengerjaan projek sistem akan terjadwal dengan baik dan mudah dikontrol.

    Kekurangan metode ini yaitu :
    - Persyaratan sistem harus digambarkan dengan jelas.
    - Rincian proses harus benar-benar jelas dan tidak boleh berubah ubah.
    - Sulit untuk mengadaptasi jika terjadi perubahan spesifikasi pada suatu tahapan pengembangan.

2. Model Spiral

    Model spiral / spiral model adalah model pengembangan software dimana proses digambarkan sebagai spiral. Setiap loop akan mewakili satu fase dari proses pembuatan / perancangan software. Loop paling dalam berfokus pada kelayakan dari sistem, loop selanjutnya tentang definisi dari kebutuhan, loop berikutnya berkaitan dengan desain sistem dan seterusnya.

    Kelebihan metode ini yaitu :
    - Setiap tahap pengerjaan dibuat prototyping sehingga kekurangan dan apa yang diharapkan oleh client dapat diperjelas dan juga dapat menjadi acuan untuk client dalam mencari kekurangan kebutuhan.
    - Lebih cocok untuk pengembangan sistem dan perangkat lunak skala besar.
    - Dapat disesuaikan agar perangkat lunak bisa dipakai selama hidup perangkat lunak komputer.
    - Pengembang dan pemakai dapat lebih mudah memahami dan bereaksi terhadap resiko setiap tingkat evolusi karena perangkat lunak terus bekerja selama proses.
    - Menggunakan prototipe sebagai mekanisme pengurangan resiko dan pada setiap keadaan di dalam evolusi produk.
    - Tetap mengikuti langkah-langkah dalam siklus kehidupan klasik dan memasukkannya ke dalam kerangka kerja iteratif.
    - Membutuhkan pertimbangan langsung terhadap resiko teknis sehingga mengurangi resiko sebelum menjadi permasalahan yang serius.

    Kekurangan metode ini yaitu :
    - Banyak konsumen (Client) tidak percaya bahwa pendekatan secara evolusioner dapat dikontrol oleh kedua pihak.
    - Model spiral mempunyai resiko yang harus dipertimbangkan ulang oleh konsumen dan developer.
    - Memerlukan tenaga ahli untuk memperkirakan resiko, dan harus mengandalkannya supaya sukses.
    - Belum terbukti apakah metode ini cukup efisien karena usianya yang relatif baru.
    - Memerlukan penaksiran resiko yang masuk akal dan akan menjadi masalah yang serius jika resiko mayor tidak ditemukan dan diatur.
    - Butuh waktu lama untuk menerapkan paradigma ini menuju kepastian yang absolute.

3. Model Incremental

    Proses pengerjaan perangkat lunak menggunakan model ini akan dilakukan perbagian sehingga bagian selanjutnya akan dikerjakan setelah bagian awal telah selesai dan selanjutnya sampai menghasilkan perangkat lunak yang lengkap dengan semua fungsi yang diperlukan dan pengerjaan perangkat lunak berakhir. Sebelum pengerjaan perangkat lunak akan dilakukan perancangan arsitektur software sebagai kerangka dalam pengerjaan perbagian.

    Kelebihan metode ini yaitu :
    - Resiko yang rendah pada pengembangan sistem.
    - Mengutamakan fungsi-fungsi pada sistem perangkat lunak sehingga kemudahan pemakaian sistem yang paling di utamakan.
    - Tahap awal adalah dasar dari pembuatan tahap berikutnya (dikerjakan secara terurut).
    - Cocok digunakan bila pembuat software tidak banyak/kekurangan pembuat
    - Mampu mengakomodasi perubahan kebutuhan customer.
    - Mengurangi trauma karena perubahan sistem. Klien dibiasakan perlahan-lahan menggunakan produknya bagian per bagian.
    - Memaksimalkan pengembalian modal investasi konsumen.

    Kekurangan metode ini yaitu :
    - Hanya akan berhasil jika tidak ada staffing untuk penerapan secara menyeluruh.
    - Penambahan staf dilakukan jika hasil incremental akan dikembangkan lebih lanjut.
    - Hanya cocok untuk proyek dengan skala kecil.
    - kemungkinan tiap bagian tidak dapat diintegrasikan.


4. Model Evolusi

    Model evolusi adalah sebuah model yang berulang-ulang. Model ini memiliki karakteristik yang memungkinkan para programmer mengembangkan perangkat lunaknya menjadi semakin lengkap di tiap versinya. Model ini diterapkan karena persyaratan (requierement) sering berubah sehingga hasil akhir dari sebuah produk tidak akan realistis, dimana edisi komplit dari produk tersebut mustahil dikeluarkan dikarenakan deadline market yang begitu ketat. Oleh karena itu lebih baik mengeluarkan versi limited untuk memperkenalkannya terlebih dahulu dan programmer dapat membuat model dari sebuah design untuk mengakomodasikan produk, yang secara bertahap akan diselesaikan dari waktu ke waktu.
    
    Kelebihan metode ini yaitu :
    - Meningkatkan kemampuan memimpin dan mengatur sesuatu dengan pengembangan diri.
    - Menciptakan suasana yang sadar akan kualitas suatu produk.
    - Fungsi inti dari quality control dalam perusahaan besar pada tingkat lokakarya.
    - Meningkatkan kebersamaan untuk mencapai suatu hasil dan semangat kerja karyawan.
    - Meningkatkan kualitas dengan biaya efektif.
    - Membebaskan manajemen.

    Kekurangan metode ini yaitu :
    - Intensitas pekerjaan meningkat karena masalah akan lebih banyak dari pada yang diperkirakan.
    - Manajemen perlu berkomitmen untuk sistem yang berkualitas, jika sebuah solusi dari sebuah masalah tidak dapat diterapkan maka itu bisa membuat frustasi para pekerja.
    - Dapat memiliki efek negatif pada hubungan industrial.
    - Dapat fokus pada masalah duniawi.

5. Model Prototype
    
    Prototype merupakan salah satu metode pengembangan perangat lunak yang banyak digunakan. Dengan metode prototyping ini pengembang dan pelanggan dapat saling berinteraksi selama proses pembuatan sistem. Prototyping dimulai dengan pengumpulan kebutuhan, mendefinisikan objektif keseluruhan dari software, mengidentifikasikan segala kebutuhan, kemudian dilakukan perangcangan kilat yang difokuskan pada penyajian aspek yang diperlukan.

    Kelebihan metode ini yaitu :
    - Prototype melibatkan user dalam analisa dan desain.
    - Punya kemampuan menangkap requirement secara konkret daripada secara abstrak.
    - Untuk digunakan secara standalone.
    - Digunakan untuk memperluas SDLC.
    - Mempersingkat waktu pengembangan Sistem Informasi

    Kekurangan metode ini yaitu :
    - Proses analisis dan perancangan terlalu singkat.
    - Mengesampingkan alternatif pemecahan masalah.
    - Bisanya kurang fleksible dalam menghadapi perubahan.
    - Prototype yang dihasilkan tidak selamanya mudah dirubah


6. Model V / V-Model

    Bisa dikatakan model ini merupakan perluasan dari model waterfall. Disebut sebagai perluasan karena tahap-tahapnya mirip dengan yang terdapat dalam model waterfall. Jika dalam model waterfall proses dijalankan secara linear, maka dalam model V proses dilakukan bercabang. Dalam model V ini digambarkan hubungan antara tahap pengembangan software dengan tahap pengujiannya.

    Kelebihan metode ini yaitu :
    - V Model sangat fleksibel. V Model mendukung project tailoring dan penambahan dan pengurangan method dantool secara dinamik. Akibatnya sangat mudah untuk melakukan tailoring pada V Model agar sesuai dengan suatu proyek tertentu dan sangat mudah untuk menambahkan method dan tool baru atau menghilangkan method dan tool yang dianggap sudah obsolete.
    - V Model dikembangkan dan di-maintain oleh publik. Userdari V Model berpartisipasi dalam change control boardyang memproses semua change request terhadap V Model.

    Kekurangan metode ini yaitu :
    - V Model adalah model yang project oriented sehingga hanya bisa digunakan sekali dalam suatu proyek.
    - V Model terlalu fleksibel dalam arti ada beberapa activity dalam V Model yang digambarkan terlalu abstrak sehingga tidak bisa diketahui dengan jelas apa yang termasuk dalamactivity tersebut dan apa yang tidak.


7. Model Rapid Application Development (RAD)  
    
    Rapid Aplication Development (RAD) adalah sebuah model proses perkembanganperangkat lunak sekuensial linier yang menekankan siklus perkembangan yang sangat pendek (kira-kira 60 sampai 90 hari). Model RAD ini merupakan sebuah adaptasi “kecepatan tinggi” dari model sekuensial linier dimana perkembangan cepat dicapai dengan menggunakan pendekatan konstruksi berbasis komponen.

    Kelebihan metode ini yaitu :
    - Lebih efektif dari Pengembangan Model waterfall/sequential linear dalam menghasilkan sistem yang memenuhi kebutuhan langsung dari pelanggan.
    - Cocok untuk proyek yang memerlukan waktu yang singkat.
    Model RAD mengikuti tahap pengembangan sistem seperti pada umumnya, tetapi mempunyai kemampuan untuk menggunakan kembali komponen yang ada sehingga pengembang tidak perlu membuatnya dari awal lagi sehingga waktu pengembangan menjadi lebih singkat dan efisien.

    Kekurangan metode ini yaitu :
    - Model RAD menuntut pengembangan dan pelanggan memiliki komitmen di dalam aktivitas rapid-fire yang diperlukan untuk melengkapi sebuah sistem, di dalam kerangka waktu yang sangat diperpendek. Jika komitmen tersebut tidak ada, proyek RAD akan gagal.
    - Tidak semua aplikasi sesuai untuk RAD, bila system tidak dapat dimodulkan dengan teratur, pembangunan komponen penting pada RAD akan menjadi sangat bermasalah.
    - RAD tidak cocok digunakan untuk sistem yang mempunyai resiko teknik yang tinggi.
    - Membutuhkan Tenaga kerja yang banyak untuk menyelesaikan sebuah proyek dalam skala besar.
    - Jika ada perubahan di tengah-tengah pengerjaan maka harus membuat kontrak baru antara pengembang dan pelanggan.

## B. Metode Agile

1. Adaptive Software Development (ASD) 

    Merupakan suatu model pengembangan perangkat lunak yang tergolong dalam agile development methods yang diusulkan oleh Jim Highsmith. Adaptive Software Development (ASD) menekankan pada pengorganisasian tim secara mandiri, kolaborasi antar-perseorangan, dan terus belajar, baik secara individu maupun secara tim, Adaptive Software Development (ASD) menggunakan tools yang disebut dengan time-boxing, time-boxing merupakan aktifitas yang menentukan jangka waktu tertentu yang dialokasikan untuk menyelesaikan berbagai macam tugas. Apabila waktu yang telah ditentukan selesai, maka pembangunan sistem akan dilanjutkan ke tugas berikutnya, dengan harapan bahwa sebagian besar dari critical work telah berhasil diselesaikan sebelum waktu keseluruhan tugas berakhir.

    kelebihan metode ini yaitu :
    - Menambah produktivitas tim
    - Menambah kualitas software
    - Menambah kepuasan klien
    - Menghemat biaya
    - Mengurangi resiko kegagalan implementasi software dari segi non-teknis
    
    Kekurangan metode ini yaitu :
    - Metode ini tidak akan berjalan dengan baik jika komitmen tim tersebut kurang
    - Metode ini tidak cocok dengan skala tim  yang lebih dari 20 orang.
    - Perkiraan waktu rilis dan harga perangkat lunak sulit ditentukan. tergantung dari kesulitan pengerjaannya.

2. SCRUM

    SCRUM adalah kerangka kerja di mana orang dapat mengatasi masalah adaptif yang kompleks, sementara secara produktif dan kreatif memberikan produk dengan nilai setinggi mungkin. SCRUM merupakan salah satu metode rekayasa perangkat lunak dengan menggunakan prinsip-prinsip pendekatan AGILE, yang bertumpu pada kekuatan kolaborasi tim, incremental product dan proses iterasi untuk mewujudkan hasil akhir. 

    Kelebihan metode ini yaitu :
    - Hemat waktu dan biaya (dalam hal ini uang).
    - Dapat mengontrol dan memonitoring aktivitas peningkatan dan penurunan beban pekerjaan yang bisa terjadi kapan saja.
    - Masalah yang timbul dapat di identifikasi dengan baik pada pertemuan harian dan oleh karena itu setiap masalah dapat di selesaikan dengan cepat.
    - Dapat dengan mudah untuk mengirim produk berkualitas sesuai dengan waktunya.
    - Dapat bekerja dengan berbagai teknologi dan bahasa pemrograman. 

    Kekurangan metode ini yaitu :
    - SCRUM bisa menjadi salah satu penyebab utama terjadinya scope creep, kecuali ada tanggal akhir tertentu. Stakeholder proyek atau manajemen akan terus menuntut fungsi dan fitur baru untuk disampaikan.
    - Setiap tugas harus didefinisikan dengan baik, karena hal ini dapat mempengaruhi perkiraan biaya dan waktu pengerjaan proyek. Jika tidak didefinisikan dengan baik maka semua hal tersebut tidak akan akurat. Dalam kasus seperti ini, biasanya tugas dapat tersebar di beberapa sprint.
    - Jika anggota tim Anda tidak berkomitmen dengan baik, maka proyek Anda tidak akan selesai atau bahkan bisa gagal.
    - Metode SCRUM ini hanya membutuhkan anggota tim yang sudah berpengalaman, jika tim Anda berisi orang-orang yang masih pemula maka proyek tidak dapat selesai sesuai dengan waktunya.
    - SCRUM dapat bekerja dengan baik jika seorang Scrum Master dapat mempercayai tim yang mereka kelola. Jika Scrum Master terlalu mengontrol secara ketat, hal ini dapat menyebabkan tim menjadi tertekan dan stress, sehingga mengakibatkan demoralisasi dan kegagalan dari proyek tersebut.
    - Jika sering terjadi pergantian anggota tim saat pengembangan proyek berlangsung, hal ini dapat menyebabkan efek yang kurang baik bagi perkembangan proyek tersebut, proyek akan semakin lama selesai dari waktunya.

3. Dynamic System Development Method (DSDM)

    Dynamic System Development Method (DSDM) merupakan salah satu metode Agile dan pengembangan tahap lanjut dari metode Rapid Application Development (RAD) yang dikembangkan pada tahun 1990 oleh sekelompok vendor SI dan para ahli di Inggris. Metode ini mengutamakan keterlibatan pengguna secara berkesinambungan dengan pendekatan incremental dan iterative.

    Dynamic System Development Method (DSDM) berupaya mengatasi penyebab-penyebab kegagalan proyek seperti melebihi anggaran, terlambat dari jadwal, kurangnya keterlibatan pengguna dan lemahnya komitmen dari pemimpin.

    Kelebihan metode ini yaitu :
    - Menyajikan kerangka kerja (framework) untuk membangun dan memelihara sistem dalam waktu yang terbatas melalui penggunaan prototyping yang incremental dalam lingkungan yang terkondisikan.
    - Membangun software dengan cepat.
    - DSDM dapat dikombinasikan dengan XP menghasilkan kombinasi model proses yang mengikuti DSDM dan praktek yang sejalan dengan XP.
    
    Kekurangan metode ini yaitu :
    - Setiap iterasi bergantung pada prototype sebelumya.
    - Menentukan scope dari suatu prototype proyek tidak pernah selesai.
    - Dokumentasi sering kali tidak lengkap karena fokus pada pembuatan prototype.
    - Isu-isu mengenai sistem backup dan recovery, system performance dan system security kurang/tidak diperhatikan dan sering terlupakan.

[Referensi Meteode Klasik](https://siniajacom.blogspot.com/2017/10/model-pengembangan-perangkat-lunak.html)

[Referensi Meteode Agile ASD](https://projectperangkatlunakb.blogspot.com/2019/09/adaptive-software-development-asd.html)

[Referensi Meteode Agile scrum](https://rachmat.id/articles/kelebihan-dan-kekurangan-scrum)

[Referensi Meteode Agile DSDM](https://projectperangkatlunakb.blogspot.com/2019/09/dynamic-systemdevelopment-method-dsdm.htmll)
