# labspy01
## Daftar Isi
- Latihan 1
- Latihan 2
- Latihan 3
- Latihan 4

## Latihan 1
Program sederhana untuk menampilkan bilangan terbesar

Penjelasan:
```
Untuk menginput dua variabel dengan bilangan bulat (Integer) yang akan diproses dan dimasukan kedalam variabel hasil
bil1 = int(input("Masukan Bilangan Pertama : "))
bil2 = int(input("Masukan Bilangan Kedua   : "))

hasil = 0
```
Proses:

```
Jika (if) bilangan pertama lebih besar dari bilangan kedua maka hasilnya adalah Bilangan pertama lebih besar
if (int(bil1) > bil2):
    hasil = bil1
```
Tetapi jika bilangan kedua lebih besar dari bilangan pertama maka hasilnya adalah bilangan kedua lebih besar (else)

```
else:
    hasil = bil2
```

Untuk menampilkan hasil dari dua buah bilangan yang sudah diproses diatas

```
print("Bilangan Terbesar Adalah", hasil)
```

## Latihan 2
Program Untuk Mengurutkan Data dari Bilangan Terkecil

Penjelasan:

Untuk menginput lima buah bilangan yang akan dimasukan ke list variabel data

```
a = int(input("Masukan Bilangan Ke-1: "))
b = int(input("Masukan Bilangan Ke-2: "))
c = int(input("Masukan Bilangan Ke-3: "))
d = int(input("Masukan Bilangan Ke-4: "))
```

Data akan diproses menggunakan metode sort. yaitu metode untuk mengurutkan data, baik itu dari nilai terkecil ataupun terbesar.

```
data.sort()
```

Menampilkan urutan data dari nilai terkecil

```
print("Urutan Bilangan: ", data)
e = int(input("Masukan Bilangan Ke-5: "))
data = [a,b,c,d,e]
```

## Latihan 3
Program Perulangan Bertingkat (Nested for)

Penjelasan: i (baris) j (kolom)

Untuk melakukan perulangan baris dan kolom dengan nilai 10, menggunakan nested for

```
for i in range(10):
    for j in range(10):
```

Untuk menampikan hasil dari perulangan
- Agar terlihat lebih rapih, gunakan format string rata ke kanan sebanyak 3 karakter
- Agar tidak membuat baris baru menggunakan end='' (i/baris)
- Penggunaan print() untuk membuat baris baru (j/kolom)

```
    print("%3d"%(i+j), end='')
print()
```

## Latihan 4
Program Untuk Menampilkan N Bilangan Acak yang Lebih Kecil dari 0.5

Penjelasan:

Import module random untuk membuat bilangan acak

```
from random import random
```

Untuk menginput nilai yang ingin dikonversikan kedalam bilangan bulat (Integer) yang akan di masukan kedalam variabel n

```
n = int(input("Masukan Nilai N: "))
```

Untuk pengulangan range yang diinputkan oleh variable n

```
for i in range(n):
    while True:
        n = random()
        if n < 0.5:
```

Menampilkan hasil dari n

```
print(n)
```
