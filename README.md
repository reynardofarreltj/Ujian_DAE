# Laporan Ujian DAE 
## (Reynardo Farrel Tjahjono / c14250124) / (Raymond Chandler Gunawan / c14250121)

---

# Korelasi pada Data Titanic🚢
Dataset yang dipakai untuk diinterpretasi dan mendapat insight adalah dataset titanic. Dataset tersebut mendeskripsikan selamat/tidak selamat, gender, umur, kelas, jumlah keluarga, harga, dan tujuan. Jumlah data pada dataset tersebut adalah 889 penumpang.

---

### Proses Pengelolahan Data di KNIME
#### 1. Data cleaning
Data dibersihkan dengan membuang data-data yang tidak diperlukan atau data yang duplikat dengan column filter, lalu missing value yang terdapat pada data dihilangkan dengan mencari nilai yang dapat menggantikannya melalui missing value. Lalu, outlire pada data dihilangkan untuk memperbaiki ketidakakuratan data.
#### 2. Data processing
Data di proses melalui berbagai metode untuk mendapatkan hasil akhir yang dapat divisualisasikan
#### 3. Data visualization
Data yang sudah diproses akan divisualisasikan dalam berbagai bentuk untuk mengintepretasikannya dan mendapat insight yang berguna.
#### Bonus
Pada workflow digunakan decision tree learner untuk memprediksi penumpang yang selamat atau tidak berdasarkan variabel-variabel yang tersedia pada data.

---

### Intepretasi dan Insight

#### 1. Umur Penumpang
Sebagian besar umur penumpang titanic berada di rentan usia 31-50 dengan jumlah 318 penumpang dan diikuti dengan rentan usia 20-30 dengan jumlah 306.
##### Insight:
Dari data tersebut dapat dilihat sebagian besar mayoritas penumpang berada di usia produktif untuk bekerja sehingga dapat ditarik kesimpulan bahwa kapal titanic adalah kapal yang membawa tenaga kerja dan pembisnis dengan tujuan untuk produktivitas dan mitgrasi.

#### 2. Umur Dengan Tingkat Keselamatan
Visualisasi dilakukan dengan heatmap dan dapat dilihat penumpang dengan rentan umur 20-50 memiliki tingkat kematian yang sangat tinggi dan penumpang selain umur tersebut memiliki tingkat kematian yang lebih rendah.
##### Insight:
Dari data tersebut dapat dilihat penumpang dengan umur yang muda lebih diprioritaskan untuk diselamatkan sehingga memiliki peluang keselamatan yang tinggi dibandingkan dengan penumpang dewasa yang memiliki peluang keselamatan rendah.

#### 3. Umur Dengan Kelas Penumpang
Sebagian besar penumpang kelas tiga terletak pada rentan umur yang muda, kelas dua terletak pada rentan umur yang dewasa, dan kelas satu terletak pada rentang umur yang tua.
##### Insight:
Dari data tersebut dapat dilihat bahwa semakin tua penumpang maka semakin besar kemungkinannya untuk terletak pada kelas yang lebih tinggi.

#### 4. Tingkat Keselamatan Dengan Kelas Penumpang
Tingkat keselamatan penumpang kelas tiga sangat rendah sedangkan tingkat keselamatan kelas dua hampir setara dan tingkat keselamatan kelas satu sangatlah tinggi.
##### Insight:
Dari data tersebut dapat dilihat bahwa semakin tinggi kelas penumpang maka tingkat selamat dari bencana titanic naik secara signifikan karena penumpang memiliki kekayaan untuk menjadikan diri mereka sebagai prioritas diselamatkan.

#### 5. Tingkat Keselamatan Dengan Gender
Jika dibandingkan penumpang yang meninggal sesuai gender adalah pria dengan 466 kematian dan 109 selamat lalu wanita dengan 81 kematian dan 233 keselamatan.
##### Insight:
Berdasarkan data tersebut dapat dilihat bahwa gender wanita lebih diprioritaskan untuk diselamatkan dibanding dengan pria sehingga memiliki tingkat keselamatan yang lebih tinggi.

#### 6. Tarif dan Kelas Penumpang
Penumpang yang membayar tinggi akan masuk ke dalam kelas 1 dan sedikit masuk kelas 2 namun penumpang yang membayar biaya menengah-tinggi sebagian besar akan masuk ke dalam kelas tiga dan jumlah penumpang yang masuk kelas dua dan satu hampir setara. Lalu penumpang yang membayar tarif menengah-rendah kebanyakan akan masuk ke dalam kelas tiga namun juga masuk ke dalam kelas dua dan penumpang yang membayar tarif rendah pasti akan masuk kelas tiga.
##### Insight:
Bedasarkan data tersebut dapat dilihat bahwa ada banyak faktor-faktor tersembunyi yang dapat mempengaruhi biaya tarif penumpang sehingga biaya per kelas tidak terlalu pasti dan masih fleksibel.

#### 7. Tarif dan Tempat Keberangkatan
Tempat keberangkatan kapal titanic terdapat 3 wilayah yaitu, Cherbourg, Southampton, dan Queenstown. Sebagian besar penumpang berangkat dari wilayah southampton membayar tarif yang rendah, lalu sebagian besar penumpang yang berangkat dari cherbourg membayar tarif yang mahal. Selain itu, sebagian besar penumpang yang berangkat dari Queenstown membayar tarif yang murah.
##### Insight:
Dari data tersebut dapat dilihat bahwa penumpang dari cherbourg rata-rata kaya, penumpang dari southampton dapat dikatakan sebagai umum karena persebaran tarif merata, dan penumpang dari Queenstown rata-rata miskin.

#### 8. Tarif dan Jumlah Berpergian
Rata-rata orang yang berdua hingga berempat akan membayar tarif yang sangat mahal dan rata-rata orang yang sendirian dan lebih dari empat akan membayar tarif yang sangat murah.
##### Insight:
Dari data tersebut dapat dilihat keluarga yang kecil atau pasangan akan membayar tarif yang mahal sedangkan penumpang yang sendirian atau membawa keluarga sangat besar akan membayar tarif yang murah.

#### 9. Umur dan Jumlah Berpergian
Semakin banyak penumpang yang berpergian bersama maka semakin rendah juga umur group penumpang tersebut.
##### Insight:
Group besar yang berpergian bersama di titanic rata-rata keluarga dengan anak-anak yang muda dalam bentuk keluarga hierarkis dan rata-rata orang yang berpergian sendiri adalah orang dewasa.

---

### Kesimpulan
Jadi dari pengelolaan dataset titanic ini dapat ditarik kesimpulan bahwa data yang tersedia berkaitan dengan perilaku manusia dan struktur sosial. Semua variabel di dalam titanic ini tidak semuanya setara dan memiliki tingkat pengaruhnya sendiri. Maka jika ditarik kesimpulan terdapat tiga variabel yang sangat berpengaruh pada tingkat keselamatan pada bencana titanic, yaitu umur sebagai prioritas, kelas sebagai akses(untuk keselamatan), dan gender untuk norma(kurang lebih sama dengan prioritas keselamatan).

### Pengunaan Insight
1. Selalu mempersiapkan untuk hal terburuk karena Titanic merupakan contoh bencana yang tidak terprediksi akan terjadi.
2. Privilege atau keuntungan akibat ekonomi itu nyata, Uang memiliki pengaruh besar terhadap persentase keselamatan penumpang karena lebih diprioritaskan.
3. Dalam mengelola data itu harus hati-hati terhadap variabel tersembunyi karena memiliki pengaruh yang sangat besar contohnya pada korelasi variabel lain yang harus dipisahkan oleh gender di titanic.
