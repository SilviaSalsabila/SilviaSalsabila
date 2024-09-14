MENJUMLAHKAN DUA BUAH BILANGAN
a = int(input("Masukkan bilangan a: "))
b = int(input("Masukkan bilangan b: "))
jumlah = a + b
print("Jumlah", a, "+", b, "adalah: ", jumlah)
MENGHITUNG LUAS LINGKARAN
import math 
r = float(input("Masukkan jari jari lingkaran: ")) 
luas = math.pi * r ** 2
print(f"Luas lingkaran dengan jari jari {r} adalah {luas:.2f}")
MENDETEKSI BILANGAN GANJIL ATAU GENAP
angka = int(input("Masukkan angka: "))
if angka % 2 == 0:
    print(f"{angka} adalah bilangan genap. ")
else : 
    print(f"{angka} adalah bilangan ganjil. ")
