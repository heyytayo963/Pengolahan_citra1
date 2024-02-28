# Pengolahan_citra1
![image](https://github.com/heyytayo963/Pengolahan_citra1/blob/main/IMG_20240228_164556.jpg)

# Penjelasan
```
import numpy as np
import cv2 as cv
```
Baris ini berfungsi untuk menginstal paket python yaitu numpy dan cv2

1. Membuat Array NumPy:
```
npArray = np.zeros((5, 6))
```
Membuat array NumPy dengan ukuran 5x6 yang diisi dengan nilai nol.

2. Menampilkan Array:
```
print(npArray)
```
Menampilkan isi dari array NumPy yang telah dibuat.

3. Menampilkan Tipe Data Array:
```
print(npArray.dtype)
```
Menampilkan tipe data elemen dalam array NumPy. Dalam hal ini, akan menampilkan float64 karena secara default NumPy membuat array dengan tipe data float.

4. Menampilkan Bentuk Array:
```
print(npArray.shape)
```
Menampilkan bentuk (shape) array NumPy. Dalam hal ini, (5, 6) menunjukkan array 2D dengan 5 baris dan 6 kolom.

5. Menampilkan Jumlah Baris dan Kolom:
```
print("Nomor dari array baris = {}".format(npArray.shape[0]))
print("Nomor dari array kolom = {}".format(npArray.shape[1]))
```
Menampilkan jumlah baris dan kolom dari array NumPy.

6. Mengganti Tipe Data Array:
```
npArray = np.zeros((5, 6), dtype=np.uint8)
```
Mengganti tipe data elemen array NumPy menjadi uint8 (unsigned 8-bit integer).

7. Menampilkan Bentuk Array Setelah Perubahan:
```
print(npArray.shape)
```
Menampilkan bentuk array setelah perubahan tipe data. Dalam hal ini, (5, 6) menunjukkan array 2D dengan 5 baris dan 6 kolom, tetapi dengan tipe data
