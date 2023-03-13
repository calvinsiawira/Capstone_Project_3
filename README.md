# Capstone_Project_3

Capstone project 3

## Context and Background

California adalah sebuah negara bagian di Amerika Serikat bagian barat. Dengan jumlah penduduk lebih dari 39,2 juta jiwa dan total area sekitar 163.696 mil persegi (423.970 km2), California merupakan negara bagian Amerika Serikat yang terpadat berdasarkan kepadatan penduduk dan terbesar ketiga berdasarkan wilayah. Perekonomian California, dengan produk domestik bruto (PDB) sebesar US$3,4 triliun pada 2021 menjadikannya sebagai ekonomi sub-nasional terbesar di dunia. California juga merupakan rumah bagi beberapa perusahaan terbesar di dunia berdasarkan kapitalisasi pasar dan tempat tinggal orang terkaya di dunia.

Perekonomian yang maju menjadikan California sebagai salah satu kota dengan market properti yang paling mahal dan kompetitif di Amerika Serikat. Pertumbuhan jumlah masyarakat (baik lokal maupun expats), luas tanah yang terbatas, dan permintaan yang tinggi membuat harga rumah di California meroket. Harga rumah di California sangat tinggi dan sulit dijangkau bagi sebagian besar penduduk. Banyak orang yang ingin membeli rumah, tetapi sulit menemukan yang terjangkau dan kualitasnya baik. Hal ini membuat banyak orang berpotensi tidak memiliki tempat tinggal yang layak.

Dengan meningkatnya popularitas dan demand terhadap properti di California dalam setidaknya satu dekade terakhir, pemilik rumah dapat menaikkan harga jual rumah secara berlebihan dan sering kali melebihi value rumah tersebut. Lebih parahnya, ini menciptakan domino effect kepada pemilik properti lainnya. Akibatnya, terjadi inflasi yang tinggi di sektor properti di wilayah California. 

Salah satu tantangan terbesar bagi pemerintah adalah bagaimana pemerintah dapat mencegah 'housing bubble' seperti yang terjadi pada tahun 2008 dengan cara mengedukasi masyarakat mengenai value rumah dan membuat kebijakan (jika diperlukan) mengenai pengaturan harga rumah di wilayah California. Ketidakstabilan pada harga rumah dapat memperlebar kesenjangan sosial masyarakat, yang artinya adanya perbedaan jarak ekonomi antara satu kelompok dengan kolompok lainnya. Yang sudah mempunyai properti akan semakin sejahtera, dan yang belum memiliki properti akan menjadi lebih kesulitan dalam memperoleh sebuah properti. Oleh karena itu, **sangatlah penting untuk pemerintah dapat mengedukasi masyarakat dan membuat kebijakan yang mengatur harga properti secara adil, akurat dan kompetitif sesuai dengan value rumah tersebut**

## Goals

Berdasarkan permasalahan tersebut, saya sebagai data analyst yang bekerja di divisi data pada pemerintahan, bekerja sama dengan menteri perekonomian dan menteri sosial, ingin membuat sebuah 'tool' yang dapat **mengevaluasi value sebuah rumah di California secara objektif**. Insights yang dihasilkan dari prediction tool ini diharapkan dapat dijadikan pedoman untuk aksi pemerintah ke depannya, baik dalam penentuan kebijakan pengendalian harga rumah, pengedukasian masyarakat tentang sektor perumahan, maupun meningkatkan akses informasi mengenai perumahan yang terjangkau untuk masyarakat.

Dengan terjaganya kesejahteraan masyarakat dan perekonomian di wilayah California, ini dapat meningkatkan stabilitas ekonomi Amerika Serikat secara keseluruhan. 

## Analytic Approach

Kita perlu menganalisis data untuk dapat menemukan pola dari fitur-fitur yang ada, yang membedakan satu properti dengan yang lainnya. 
Selanjutnya, kita akan membangun suatu model regresi yang akan membantu pemerintah dalam membuat kebijakan yang mengatur rentang harga properti yang wajar.

## Metric Evaluation

Evaluasi metrik yang akan digunakan adalah RMSE, MAE, dan MAPE, di mana RMSE adalah nilai rataan akar kuadrat dari error, MAE adalah rataan nilai absolut dari error, sedangkan MAPE adalah rataan persentase error yang dihasilkan oleh model regresi. Semakin kecil nilai RMSE, MAE, dan MAPE yang dihasilkan, berarti model semakin akurat dalam memprediksi harga properti sesuai dengan limitasi fitur yang digunakan. 

Selain itu, kita juga bisa menggunakan nilai R-squared atau adj. R-squared jika model yang nanti terpilih sebagai final model adalah model linear. Nilai R-squared digunakan untuk mengetahui seberapa baik model dapat merepresentasikan varians keseluruhan data. Semakin mendekati 1, maka semakin fit pula modelnya terhadap data observasi. Namun, metrik ini tidak valid untuk model non-linear.

## Data Description
Dataset yang digunakan adalah public dataset dari kaggle dengan nama "California Housing Price". Dataset yang digunakan adalah "housing.csv", yang mengandung lebih dari 14000 data mengenai rumah di California di tahun 1990



