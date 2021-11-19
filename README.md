# Indonesia-Named-entity-Recognition

11S18022 | Devi Wahyuni Silitonga
11S18037 | Hisar Haryanto Sinaga
11S18046 | Simson Fransisco Panjaitan
11S18058 | Leonardo Sianturi
11S18066 | Jumadi Heryanto Damanik


_Named Entity Recognition_ merupakan salah satu penerapan _Sequence Labeling_ pada _Natural Language Processing_. _Named Entity Recognition_ ini digunakan untuk mengekstraksi infotmasi seperti nama orang, nama organisasi maupun nama lokasi/tempat. 

Pada penelitian kali ini, tim Aesthetics akan membuat suatu model _NER_ yang dapat mengekstraksi informasi berupa nama orang, nama organisasi maupun nama lokasi/tempat dengan menerima inputan berupa kalimat atau teks berbahasa Indonesia.

Pada tahap pengerjaannya, tim Aesthetics menggunakan metode/pendekatan berikut untuk setiap tahapnya:

**1. Dataset**
    Dataset yang digunakan adalah dataset SINGGALANG.tsv, yang dapat diperoleh melalui https://github.com/ialfina/ner-dataset-modified-dee/tree/master/singgalang
    
**2. Text Preprocessing** 

_a. Tokenisasi_ : pemecahan kalimat menjadi kata-kata yang disebut dengan token. Tokenisasi dilakukan agar setiap kata dipisahkan menjadi data independen. Karena model _Named Entity Recognition_ yang dibangun akan memberikan label pada setiap kata, maka tokenisasi akan sangat mempermudah proses tersebut. Jika semua kata sudah terpisah, maka model dapat memberikan label pada setiap kata.

_b. Stopwords Removal_ : penghapusan kata kata yang termasuk kedalam _stop list_. Kata-kata yang termasuk kedalam _stop list_ adalah _the, a, an, so, as, of_, dll. Penggunaan _stopwords_ sering kali tidak memberikan pengaruh yang besar terhadap makna suatu kata. Karena model yang dibangun akan memberikan label pada setiap kata, maka _stopwords removal_ akan berguna, karena _stopwords_ sering kali tidak memiliki makna apabila digunakan tidak bersamaan dengan kata-kata lain. Selain itu, model yang dibangun tidaklah mendeteksi makna kata, sehingga _stopwords removal_ tidak akan mempengaruhi proses pemberian label.


**2. Feature Extraction****


**3. Model klasifikasi berdasarkan fitur yang sudah di ekstrak**


**4. Metode dan metrik untuk mengevaluasi model =>**

