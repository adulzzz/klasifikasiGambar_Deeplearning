Pada proyek ini saya menggunakan dataset Intel Image Classification yang terdiri dari 6 kelas, yaitu buildings, forest, glacier, mountain, sea, dan street.
Model dibangun menggunakan Convolutional Neural Network (CNN) dengan beberapa layer Conv2D, MaxPooling2D, BatchNormalization, Dropout, dan Dense. Untuk membantu proses training, saya juga menggunakan callback EarlyStopping, ReduceLROnPlateau, dan ModelCheckpoint.
Selain melakukan evaluasi menggunakan accuracy dan loss, saya juga menambahkan classification report, confusion matrix, serta melakukan pengujian prediksi pada gambar baru.
Model yang telah dilatih kemudian dikonversi ke format SavedModel, TensorFlow Lite (TFLite), dan TensorFlow.js sesuai dengan kriteria submission.
Saya menyadari masih banyak hal yang dapat ditingkatkan pada proyek ini, sehingga saya sangat terbuka terhadap masukan dan saran dari reviewer sebagai bahan pembelajaran ke depannya.
Terima kasih.
