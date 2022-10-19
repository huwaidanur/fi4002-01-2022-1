# 10219013
Huwaida Nur Asysyifa Mufarrida


## materi sebelumnya
+ Review bahasa python (plot grafik dsb), Osilasi Harmonik Sederhana, Pegas Osilasi Teredam, Metode Predator prey, Sebaran temperatur pada persegi, Metode Euler, Metode Runge Kutta orde 4, Monte Carlo 


## materi paling menarik
+ Monte Carlo, menarik karena konsepnya yang menebak hasil dengan banyak tembakan, aplikasinya banyak namun konsep dasarnya mudah dipahami 


## materi paling membosankan
+ Metode Runge Kutta orde 4


## materi yang sudah dipami
+ Review bahasa python (plot grafik dsb), Osilasi Harmonik Sederhana, Pegas Osilasi Teredam, Metode Predator prey, Sebaran temperatur pada persegi, Metode Euler, Metode Runge Kutta orde 4, Monte Carlo 


## materi yang belum dipahami
+ Secara umum semua materi sudah dipahami tapi belum mendalam. Seperti bagaimana menerapkan metode euler dan runge kutta kedalam kasus rangkaian rlc


## contoh program
+ Buat suatu contoh program dalam Python dan sertakan di sini dengan hasil keluarnnya.

```python
# contoh program python
import matplotlib.pyplot as plt
import random

inside = 0
n = 10000

x_inside = []
y_inside = []
x_outside = []
y_outside = []

for i in range (n):
  x = random.uniform(-5.0,5.0)
  y = random.uniform(-5.0,5.0)
  if x**2 + y**2 <= 25:
    inside +=1
    x_inside.append(x)
    y_inside.append(y)
  else:
    x_outside.append(x)
    y_outside.append(y)

pi=4*(inside/n)
print(pi)

fig,ax = plt.subplots()
ax.set_aspect('equal')
ax.scatter(x_inside, y_inside, color='g', marker='s')
ax.scatter(x_outside, y_outside, color='r', marker='s')

plt.draw()

Hasilnya adalah

![image](https://user-images.githubusercontent.com/111943398/196588526-e8c26abf-e16c-4c54-bc94-3d804476c37c.png)



## cara perkuliahan
+ Saya suka dengan cara pak dudung dan pak acep memberi kuliah namun lebih suka cara pak dudung memberi kuliah dibandingkan pak Acep, alasannya karena pak dudung lebih jelas dan lebih runtut dalam memberikan materi ditambah contoh kasus dalam kehidupan real yang dipaparkan
+ Saran saya, pertemuan rabu membahas materi dan pertemuan jumat barulah hands on dengan kasus yang diberikan, agar mahasiswa mempunyai bekal terlebih dahulu baru mencoba di laptop masing-masing. Namun boleh juga jika tiap hari pemberian materi dan hands on, jam pertama pemaparan materi dan jam kedua barulah hands on 
+ Selanjutnya, ada baiknya dosen menampilkan contoh program penyelesaian kasus yang diberikan, jadi mahasiswa tidak hanya trial and error saja tetapi juga melihat dan mempelajari program python yang ditampilkan dosen, agar lebih memahami secara mendalam algoritma dan logika pemrograman yang tepat


## topik sistem fisis
+ Pola konsumen dalam memilih produk yang akan dibeli, parameternya berupa umur, jenis kelamin konsumen,dan pekerjaan


## simulasi dan visualisasi
+ Saya sangat tertarik. Namun kadang ada rasa malas karena merasa ruwet.
+ Hal yng ingin saya simulasikan sekaligus visualisasikan yaitu aliran fluida atau kalor disekitar bahan bakar nuklir dalam silinder reaktor nuklir
