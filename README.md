
## Deteksi Bentuk Gambar Menggunakan Contour
Countor, terjadinya pada piksel terhadap intensitasnya yang berhubungan dengan titik-titik terhadap citra gambar yang digunakan.

Ini projek skrip pemrograman pada bahasa python terhadap library OpenCV, dimana sebuah citra gambar akan dideteksi bentuk gambar menggunakan Contour.

Penjelasan Penyelesaian Contour di Skrip:

- Konversi citra menjadi citra biner. Hal ini dapat dilakukan dengan menggunakan teknik thresholding atau edge detection.

- Menemukan kontur pada gambar biner menggunakan fungsi cv2.findContours(). Fungsi ini mengambil gambar biner sebagai masukan dan mengembalikan daftar contour.

-  Menggambar kontur pada gambar asli menggunakan fungsi cv2.drawContours(). Fungsi ini mengambil gambar asli, daftar kontur, indeks kontur yang akan digambar, dan warna serta ketebalan contour sebagai masukan.

Berikut alur penjelasan skrip tersebut:

- Import Library menggunakan OpenCV
  
Dimana pemrosesan gambar akan dilakukan dengan OpenCV.

- Membuka Gambar
  
Dimana gambar diproses dengan nama file "objek_Anugrah AK._202131037.jpg".

- Konversi Gambar ke Grayscale
  
Menjadi nilai keabuan ketika setiap piksel dari nilai intensitas warna pada citra pada file "objek_Anugrah AK._202131037.jpg".

- Ambang Batas Gambar
  
Suatu citra mengdasar pada terang gelap, dimana background dan objek didalam citra gambar yang terpisah pada file "objek_Anugrah AK._202131037.jpg". Ini akan membantu menemukan contour didalam citra gambar.

- Menemukan Contour
  
Ketika sudah melakukan ambang batas gambar dan konversi gambar ke grayscale, untuk melakukan penemuan contour bisa dilakukan dari file "objek_Anugrah AK._202131037.jpg".

- Gambar Contour
  
Lalu, ketika selesai melakukan penemuan contour, konversi gambar ke grayscale dan juga melakukan pada ambang batas gambar, maka pada piksel terhadap intensitasnya yang berhubungan dengan titik-titik, akan melakukan gambaran contour pada citra gambar dari file "objek_Anugrah AK._202131037.jpg".

- Menampilkan Gambar
    
Hasil akhir dari proses citra asli ke penemuan contour. Citra asli yang berasal dari file dengan nama "objek_Anugrah AK._202131037.jpg".

## Dokumentasi

[Citra Gambar yang Digunakan](https://postimg.cc/BtVmzSwZ)

[Bukti Bagian ke-1 Pengambilan Citra Gambar](https://postimg.cc/189sYrdZ)

[Bukti Bagian ke-2 Pengambilan Citra Gambar](https://postimg.cc/CB4W83FB)

[Hasil Contour dari Citra Gambar yang Digunakan](https://postimg.cc/Snz3d2Sp)
## Authors

- Anugrah AK. [@aanggaanugrahhakk](https://github.com/aanggaanugrahhakk)


## Indentitas Authors

Nama: Anugrah AK.

NIM: 202131037

Kelas: B
