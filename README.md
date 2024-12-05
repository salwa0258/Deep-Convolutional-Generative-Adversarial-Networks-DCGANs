<h1 align="center"> Creating anime characters using Deep Convolutional Generative Adversarial Networks (DCGANs) and Keras </h1>
<p align="center"> Penjelasan tentang bagaimana cara menciptakan anime menggunakan Deep Convolutional Generative Adversarial Networks (DCGANs) dan Keras. Metode yan digunakan dalam pembuatan anime ini menggunakan metode  yang menggabungkan Generative Adversarial Networks (GANs) dan Convolutional Neural Networks (CNNs) agar dapat menghasilkan gambar anime yang realistis. </p>

<div align="center">

<img src="https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54">
<img src="https://img.shields.io/badge/Keras-FF0000?style=for-the-badge&logo=keras&logoColor=white">
<img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white">
<img src="https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=Kaggle&logoColor=white">
<img src="https://img.shields.io/badge/Colab-F9AB00?style=for-the-badge&logo=googlecolab&color=525252">
<img src="https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white">

</div>
========================================================================

## Deskripsi
**Generative Adversarial Networks (GAN)**
Generative Adversarial Networks (GAN) merupakan model generatif yang mengubah sampel acak dari satu distribusi menjadi distribusi lain. Dalam proyek ini dijelaskan juga bagaimana caranya GANs bekerja. GANs terdiri dari dua jaringan yaitu generator dan discriminator. Generator bertugas untuk membuat data baru, sedangkan discriminator bertugas untuk membedakan antara data nyata dan data yang dihasilkan oleh generator.
**Deep Convolutional Generative Adversarial Networks (DCGANs)**
Deep Convolutional Generative Adversarial Networks (DCGANs) merupakan pengembangan dari GANs yang menggunakan  CNN untuk meningkatkan kualitas gambar yang akan dihasilkan.

## Libraries
Beberapa libraries yang digunakan dalam proyek ini adalah :
    1. TensorFlow
    2. Keras
    3. NumPy
    4. Matplotlib
    5. Pandas

## Optimizer
Optimizer yang digunakan pada proyek ini menggunakan Optimizer Adam yang digunakan untuk mengupdate parameter Generator dan Discriminator selama pelatihan.

## Dataset
Dataset dari proyek ini diambil dari kaggle, yang mana pada dataset tersebut memiliki 63.632 wajah anime yang berkualitas tinggi. Karena terlalu banyak dataset, dalam proyek ini hanya menggunakan 20.000 gambar dari sampel acal pada dataset dan dataset baru tersebut disebut dengan cartoon_20000.

## Hasil
Hasil dari menjalankan proyek ini adalah, kita dapat menghasilkan karakter anime yang unik dan menarik. Dan untuk menghasilkan gambar yang lebih realistis dibanding sebelumnya kita dapat mengubah epoch dari 100 menjadi 150.

## Kesimpulan
Untuk menghasilkan karakter anime yang bervariatif kita dapat menggunakan DCGANs untuk membuat hal tersebut. Dengan menggunakan DCGANs, model yang dihasilkan maampu mempelajari pola dan fitur dari dataset gambar anime dan menghasilkan gambar-gambar baru yang menyerupai karakter anime asli. Dengan model yang terlatih dengan baik, proses pembuatan karakter anime dapat menjadi lebih efisien dan menghasilkan karakter yang unik dan berkualitas tinggi.

