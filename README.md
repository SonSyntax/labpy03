# labpy03
<p>NAMA : MOHAMAD SONY HIDAYATULLAH</p>
<p>NIM : 312410290</p>
<p>KELAS : TI 24 A 4</p>
<p>MATKUL : BAHASA PEMROGRAMAN</p>

## LATIHAN 1

```Python
from random import random

N = int(input("Masukkan nilai N: "))

i = 1
while i <= N:
    r = random()
    print(f"data ke: {i} => {r}")
    i += 1
````
### Membangkitkan Nilai Random() Memasukan Nilai N dan Menggunakan While

```Python
from random import random
````
kode program ini untuk memanggil fungsi `random()` yang terletak pada library python itu sendiri

```Python
N = int(input("Masukkan nilai N: "))
````
Memasukan inputan N

```Python
i = 1
while i <= N:
    r = random()
    print(f"data ke: {i} => {r}")
````

Kode ini menggunakan perulangan dengan fungsi `while` yang dimana mengprogram Variable i lebih dari N (i = 1), dan akan proses ke fungsi random() yang dibugkus oleh variable (r), Cetak "data ke {i} yang dimana (i) itu 1, => ke variable (r) yaitu `random()` .

```Python
 i += 1
````
kenapa dikasih proses ke program i += 1 yaitu akan menambahkan menjadi 2, karna di program itu index 1 = 0, Jika 0 < N maka output yang keluar tanpa batas.

## LATIHAN 2

![labpy03 2](https://github.com/user-attachments/assets/bd834ab8-03d4-404a-92c0-511c27fa27d3)

```Pythonlaba = 0
laba = 0
total_laba = 0

for bulan in range(1, 9):
    if bulan in [1, 2]:
        laba = 0
    elif bulan in [3, 4]:
        laba = 10000000.0
    elif bulan in [5, 6, 7]:
        laba = 5000000.0
    elif bulan in [8]:
        laba = 20000000.0
    print(f"laba bulan ke- {bulan} sebesar: {laba}")
    
    total_laba += laba
print(f"Total laba adalah: {total_laba}")
````

### Hitung total selama 8 bulan berjalan usahanya

```python
laba = 0
total_laba = 0
````
Variable yang dimasukan dengan angka 0

```Python
for bulan in range(1, 9):
````

fungsi `for` sama saja dengan `while` yaitu for perulangan yang bisa diketahui tanpa menggunakan struktur kondisi

untuk `(1, 9)` akan melakukan perulangan dari 1-9 kalau di bahasa program index yaitu 0-8

```Python
if bulan in [1, 2]:
        laba = 0
````

Jika bulan didalam 1 dan 2 maka laba 0

```Python
elif bulan in [3, 4]:
        laba = 10000000.0
````

dan jika bulan didalam 3 dan 4 maka laba 10000000.0

```Python
elif bulan in [5, 6, 7]:
        laba = 5000000.0
````

dan jika bulan didalam 5, 6, dan 7, maka laba 5000000.0

```Python
elif bulan in [8]:
        laba = 20000000.0
    print(f"laba bulan ke- {bulan} sebesar: {laba}")
````

dan jika bulan didalam 8 maka laba dan akan mencetak perulangan 1-8 sesuai program range yang digunakan

```Python
 total_laba += laba
print(f"Total laba adalah: {total_laba}")
````

dan Memproses akan menghitung semua hasil data yang di kumpulkan 

## LATIHAN 3

![labpy03 3](https://github.com/user-attachments/assets/68c68069-caa4-4855-9912-8b5add354b29)

```Python

````
