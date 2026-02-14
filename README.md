# Checkpoint-1-AVD
Ahmad Afif Al Ghifary, NIM 2509116002, Sistem Informasi A' 2025


#**Peringkat Universitas Dunia**

#**Import Library**
[](https://colab.research.google.com/drive/1X9gwXegynSTry_rirwmgmez3taMzLYrB#scrollTo=LZ2sKiyGWllL&line=1&uniqifier=1)

#Dataset
[](https://www.kaggle.com/datasets/mylesoneill/world-university-rankings)

#**Business Understanding**
##Business Objective
Tujuan analisis ini adalah untuk memahami faktor-faktor penentu peringkat pada perguruan tinggi. Data mencakup kualitas riset, reputasi akademik, jumlah mahasiswa dan pengajar asing, dan keberhasilan lulusan

##Assessment Situation
Dataset ini memiliki potensi strategis yang tinggi dengan memanfaatkan 3 sumber data utama (THE, ARWU, dan CWUR), namun menghadapi tantangan teknis berupa beberapa data yang hilang. Meskipun terdapat tantangan, antisipasi melalui pembersihan data yang ketat akan memastikan hasil analisis yang akurat.

##Analytic Goals
1. Mengembangkan skema pencocokan sumber untuk menyatukan data-data universitas yang hilang atau berebda penulisan antar sumber terkait (THE, ARWU, CWUR) untuk membangun suatu database yang berkualitas dan konsisten

2. Melakukan penanganan pada data yang hilang dengan cara menerapkan teknik statistik untuk mengisi skor yang hilang pada tahun tertentu sehingga data historis universitas tetap dapat dianalisis tanpa terputus.

3. Mengidentifikasi variabel mana yang memiliki korelasi terkuat terhadap kenaikan peringkat di setiap platform

##Project Plan
1. Integrasi data. berupa pembersihan data, penanganan nilai yang hilang, dan sinkronisasi nama universitas antar dataset. timeline: pekan 1

2. Standarisasi skor dari berbagai lembaga pemeringkat agar bisa dibandingkan secara objektif dengan cara menyamakan skala atau rentang nilai. timwline: pekan 2

3. menganalisis dengan cara visualisasi perkembangan peringkat dan pemetaan performa. timeline: pekan 3

4. Melakukan pemodelan statistik dengan cara mengidentifikasi indikator yang paling berpengaruh terhadap kenaikan peringkat melalui analisis korelasi. timeline: timeline: pekan 4-5, memakan waktu 2 pekan karena proses pengelompokan, validasi serta pengujian model.

5. Penyusunan laporan dasbor interaktif dan rekomendasi. timeline: pekan 6.

    penyusunan dasbor interaktif ini memungkinkan pihak kampus melihat posisi kampus mereka dengan pesaing global lainnya. rekomendasi berfungsi untuk menyarankan universitas agar lebih fokus meningkatkan kualitas riset internasional jika data menunjukkan bahwa sektor tersebut memiliki bobot yang besar terhadap faktor peringkat kampus
