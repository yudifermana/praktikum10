# praktikum10

Nama : Yudi Fermana 

Nim : 312210321

Kelas: TI.22.A3

Latihan 1

![212907829-eee1256b-4119-403b-be52-6d0677092e49](https://user-images.githubusercontent.com/115516653/213088754-94b26e14-6cfe-4e4c-8904-8f4eaa4deca1.png)


Penjelasan Latihan 1

  Untuk menghitung jumlah karakter, gunakan fungsi len(). python

# Menghitung jumlah karakternya

print(len(txt))

  Cara mengambil satu karakter pada string yaitu dengan menggunakan kurung siku [ ] dan deklarasi nomor di dalam kurung siku dengan urutan ARRAY dan menggunakan titik dua lalu masukan nomor ARRAY selanjutnya.

*Untuk mengambil karakter terakhir, gunakan *index [-1]. Sedangkan untuk mengambil karakter *index ke-2 sampai ke-4, gunakan index [2:5]. python

# Mengambil karakter terakhir

print(txt[-1])


# Mengambil karakter index ke-2 sampai index ke-4 (llo)

print(txt[2:5])

  Jika ingin menghilangkan spasi pada string, gunakan method replace(). Method replace() mengganti semua kemunculan string lama dengan yang baru atau paling banyak kemunculan.

  Di dalam method replace, kita dapat menggunakan 2 cara, yang pertama bisa menggunakan (txt.replace(" ", "")) dan kedua dengan cara (txt.replace(txt[5], "")). python

# Menghilangkan spasi pada text tersebut (HelloWorld)

print(txt.replace(" ", ""))

  Untuk mengubah huruf menjadi besar, gunakan method upper(). Sedangkan jika ingin mengubah huruf menjadi kecil, gunakan method lower(). python

# Mengubah text menjadi huruf besar

print(txt.upper())

# Mengubah text menjadi huruf kecil

print(txt.lower())

  Untuk mengganti karakter 'H' dengan karakter 'J', gunakan method replace(). python

# Mengganti karakter H dengan karakter J

print(txt.replace("H", "J")) print()

Output Latihan 1

![212908778-e5216f2d-e4b2-4a8a-981f-7d3a836419f5](https://user-images.githubusercontent.com/115516653/213090212-7bccda86-2eab-49e8-8594-5dd63e6ce105.png)

Latihan 2

![212907978-db76ae3f-944e-486b-8433-2e2eb6dd358e](https://user-images.githubusercontent.com/115516653/213090393-4d3ac393-0380-4fac-b572-ed559ba97dab.png)

Penjelasan Latihan 2

Untuk memasukkan variable ke dalam string, tambahkan kurung kurawal {} untuk menempatkan variable sebelumnya. python umur = 24 txt = "\nHello, nama saya john, dan umur saya adalah {0} tahun\n"

print(txt.format(umur))

Output Latihan 2

![212908908-2f5574b3-6b42-4d6c-be92-a0261897288f](https://user-images.githubusercontent.com/115516653/213091121-ca445495-c194-446b-a48c-6416a0ee85d7.png)
