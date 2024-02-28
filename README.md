# Pengolahan_citra1
![image](https://github.com/heyytayo963/Pengolahan_citra1/blob/main/IMG_20240228_164556.jpg)

# Penjelasan
```
import numpy as np
import cv2 as cv
```
Baris ini berfungsi untuk menginstal paket python yaitu numpy dan cv2
```
npArray = np.ones((5,6))
```
Pada baris ini berfungsi membuat array variabel ukuran 5x6 dengan nilai 1
```
print(npArray)
```
Bagian ini  mencetak variabel npArray
```
print(npArray.dtype)
```
Menampilkan tipe data dari array "npArray" yang beripe int64 artinya interger dengan 64 bit
```
print(f"Nomor dari array baris = {npArray.shape[0]}")
print(f"Nomor dari array kolom = {npArray.shape[1]}")
```
Mencetak jumlah baris dan kolom dalam array "npArray"
