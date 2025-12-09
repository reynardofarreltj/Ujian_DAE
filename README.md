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
Jika dibandingkan penumpang yang meninggal sesuai gender adalah pria dengan 453 kematian dan 108 selamat lalu wanita dengan 81 kematian dan 233 keselamatan.
##### Insight:
Berdasarkan data tersebut dapat dilihat bahwa gender wanita lebih diprioritaskan untuk diselamatkan dibanding dengan pria sehingga memiliki tingkat keselamatan yang lebih tinggi.

#### 6. Tarif dan Kelas Penumpang
