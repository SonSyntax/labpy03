# labpy03
NAMA : MOHAMAD SONY HIDAYATULLAH
NIM : 312410290
KELAS : TI 24 A 4
MATKUL : BAHASA PEMROGRAMAN

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



