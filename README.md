# CAPSTONE-2_New-York-City-TLC-Trip-Record
![Screenshot 2024-08-02 125715](https://github.com/user-attachments/assets/b310298c-6741-44f6-a24d-efbb816d8a4f)

## LATAR BELAKANG
New York City Taxi and Limousine Commission (NYC TLC) merupakan lembaga pemerintah yang bertanggung jawab atas regulasi dan pengawasan industri taksi di Kota New York. Tanggung jawab utama lembaga ini meliputi perlindungan keselamatan publik dan hak-hak konsumen, penerbitan dan pengaturan lisensi, penetapan dan penegakan tarif taksi, serta pembatasan tarif sewa taksi.

Dalam rangka meningkatkan layanan taksi di NYC, Wakil Komisaris Perizinan dan Standar yang bertugas menganalisis tren, kendala, dan peluang untuk perbaikan membutuhkan bantuan. Beliau bertujuan untuk meningkatkan kinerja taksi baik pada hari kerja maupun hari libur. NYC TLC menyediakan dataset tentang riwayat perjalanan taksi di New York City mulai dari 1 Januari 2023 hingga 31 Januari 2023, yang dapat digunakan sebagai dasar untuk memberikan rekomendasi perbaikan.

Sebagai seorang data analyst, saya akan menganalisis pola kebutuhan konsumen dalam pemesanan taksi dengan menganalisis permasalahan berikut:

1. Analisis Trend Jarak Perjalanan, Jumlah Perjalanan, dan Tarif Taksi
2. Pola Kebutuhan Layanan Taksi pada Tiap Wilayah
3. Preferensi Konsumen dalam Memesan Taksi

Dengan pemahaman yang lebih baik atas tren perjalanan dan pola kebutuhan layanan taksi, NYC TLC diharapkan dapat meningkatkan pengalaman perjalanan masyarakat. Saya melakukan data cleaning dan melakukan exploratory data analysis untuk membantu permasalahan NYC TLC.

## INSIGHT
1. Penumpang taksi NYC memiliki pola mingguan sepanjang 1 Januari 2023 hingga 31 Januari 2023 dimana hari Selasa memiliki jumlah pemesanan taksi terbanyak dibandingkan hari lainnya. Waktu terpadat pemesanan taksi terjadi pada rentan waktu 3 sore hingga 6 sore.
2. Penumpang taksi NYC memiliki pola mingguan sepanjang 1 Januari 2023 hingga 31 Januari 2023 dimana hari weekend memiliki rata - rata jarak berpergian terjauh dan berpuncak pada hari minggu dibandingkan hari lainnya. Penumpang taksi memiliki kencendrungan melakukan berpergian jarak jauh pada jam 2 subuh hingga jam 5 pagi.
3. Penumpang taksi cendrung lebih banyak pada jam 6 pagi hingga 8 malam pada hari kerja, sedangkan untuk hari libur penumpang taksi lebih banyak pada jam 10 pagi hingga 3 subuh.
4. Terdapat 3 borough dengan permintaan taksi terbanyak yaitu Manhattan, Queens, dan Brooklyn.
5. Zona East Harlem North, East Harlem South, Central Harlem, Forest Hills, dan Elmhurst adalah zona dengan pickup terbanyak pada hari libur. Sedangkan zona Central Harlem, East harlem North, Central Harlem North, Upper East Side North, dan East Harlem South adalah zona dengan drop off terbanyak pada hari libur.
6. Zona East Harlem North, East Harlem South, Morningside Heights, Forest Hills, dan Central Harlem adalah zona dengan pickup terbanyak pada hari Kerja. Sedangkan zona East Harlem South, East harlem North, Upper East Side North, Central Harlem dan Upper West Side North adalah zona dengan drop off terbanyak pada hari kerja.
7. Zona East Harlem North adalah zona dengan lokasi pickup terpadat pada 10 rute perjalanan terpopuler baik weekday dan weekend
8. Secara proporsi, penumpang lebih cendrung melakukan perjalanan lebih jauh pada hari libur dibanding hari kerja.

## KESIMPULAN DAN REKOMENDASI
1. **Optimalkan Layanan pada Hari Tertentu**: Mengingat hari Selasa memiliki jumlah pemesanan taksi terbanyak, NYC TLC dapat mengoptimalkan layanan pada hari tersebut dengan menambah jumlah armada atau mengatur jadwal penjadwalan yang lebih efisien untuk memenuhi permintaan.
2. **Meningkatkan Keamanan Penumpang dan Supir Untuk Perjalanan Panjang dan di Waktu Malam**: Dengan adanya kecenderungan penumpang untuk melakukan perjalanan jarak jauh pada jam 2 subuh hingga 5 pagi serta kecendrungan penumpang untuk memilih taksi lebih larut malam pada hari libur, NYC TLC dapat meningkatkan keamanan penumpang dan supir dengan menghimbau supir taksi untuk memeriksa kebersihan dan kondisi mobil yang akan digunakan. Selain itu, NYC TLC dapat meningkatkan keamanan penumpang dengan menambahkan alat pecalak di tiap mobil taksi.
3. **Peningkatan Layanan di Borough-borough Tertentu**: Mengingat permintaan yang tinggi di Brooklyn, Manhattan, dan Queens, fokuskan upaya untuk meningkatkan layanan di wilayah-wilayah ini dengan menambah armada atau meningkatkan kehadiran taksi. Selain itu saya juga merekomendasikan untuk meningkatkan ketersediaan taksi di zona East Harlem North dikarenakan zona tersebut adalah titik pickup terbanyak baik di hari libur maupun hari kerja.
4. **Peningkatan Layanan di Jam Tertentu**: Pada hari kerja, penumpang lebih banyak pada waktu pagi (jam 6) hingga malam (jam 10). Sedangkan pada hari libur, penumpang lebih banyak pada waktu lebih siang yaitu jam 10 hingga subuh (jam 2). Maksimalkan waktu tersebut dengan menyediakan armada yang cukup.
## DASHBOARD
[View the NYC TLC Master Dashboard on Tableau](https://public.tableau.com/app/profile/yogga.prastya.wijaya/viz/Capstone2Yogga/NYCTLCMASTERDASHBOARD?publish=yes)
