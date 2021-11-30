# KLASIFIKASI PENYAKIT TANAMAN DENGAN CNN

## Deskripsi Dataset
Dalam pembuatan project ini, dataset yang kami gunakan merupakan dataset yang berupa daun padi yang didapatkan dari situs [kaggle.com](http://www.kaggle.com) yang berjudul [Rice Leaf Diseases Dataset](http://www.kaggle.com/vbookshelf/rice-leaf-diseases). Dataset ini berisi 120 gambar padi dan terdapat 3 kategori, yaitu Bacterial Leaf Blight, Brown Spot, dan Leaf Smut yang masing-masing terdapat 120 gambar bertipe .jpg

## Jurnal Referensi
Jurnal referensi yang digunakan dalam pembuatan project ini berjudul [Rice Leaf Diseases Prediction Using Deep Neural Networks with Transfer Learning](http://www.doi.org/10.1016/j.envres.2021.111275). Krishnamoorthy N., L.V. Narasimha Prasad, C.S. Pavan Kumar, Bharat Subedi, Haftom Baraki Abraha, Sathishkumar V.E.

## Author
Kontributor dalam pengerjaan project ini adalah
1. M. Aji Purnama Wibowo [ajipurnama25@gmail.com](http://www.gmail.com)
2. Auliya Tara SL [auliyatara11@gmail.com](http://www.gmail.com)

![photo1638312448](https://user-images.githubusercontent.com/92361807/144141138-2cbcaa01-4219-40e2-95a2-31ce729131e0.jpeg)

### Pre-Processing
Pre processing yang digunakan dalam project ini yaitu ekstrak file, split data, pemberian data augmentasi menggunakan image generator

![photo1638312474](https://user-images.githubusercontent.com/92361807/144141177-b5e4113e-e7a1-46f3-8fa9-5b3c9bbef335.jpeg)

### Modeling
Modeling yang digunakan dalam project ini adalah model augmentasi, MaxPooling2D, AveragePooling2D, Hyperparameter, GlobalAveragePooling2D, Flatten,BatchNormalization, Dropout
