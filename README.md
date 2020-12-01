# UTS_Semester1
## Profil
| Variable | Isi |
| -------- | --- |
| **Nama** | Reza Riyaldi Irawan |
| **NIM** | 312010284 |
| **Kelas** | TI.20.A.2 |
| **Mata Kuliah** | Bahasa Pemrograman |

Konsep program : 
1. Membuat program untuk menampilkan bilangan terbesar dari n buah data yang diinputkan.
2. Ketika memasukan angka 0 program akan berhenti.

Program Sederhana Untuk Menampilkan bilangan Terbesar dari n buah data yang dimasukkan

![hasil](https://github.com/RezaRiyaldi/UTS_Semester1/blob/main/hasil.PNG)

Penjelasan program

1. Membuat header `print(40*"=")` untuk menampilkan "=" sebanyak 40, begitupun yang `print(5*"=")` untuk menampilkan "=" sebanyak 5
```python
print(40*"=")
print(5*"=","Menentukan bilangan terbesar", 5*"=")
print(40*"=")
```
2. Deklarasi variable
```python
max = 0
```
3. Untuk perulangan hingga waktu yang tidak di tentukan atau selamanya
```pyhton
while True: 
```
4. Untuk menentukan jumlah input yang diinginkan dan dikonversi ke dalam bilangan bulat (integer) yang dimasukan ke variable `a`
```python
 a = int(input("Masukan bilangan : "))
```
5. Jika max kurang dari a maka max = a maka variable max = a atau nilai yang diinputkan
```pyhton
if max < a:
max = a
```
6. Jika a = 0 maka program akan berhenti dengan syarat break yang terpenuhi
```python
if a == 0: 
break 
```
7.  Menampilkan Bilangan Terbesar
```python
print ("Bilangan Terbesar Adalah : ", max) 
```
Program yang saya buat bisa dilihat di [Source Code](https://github.com/RezaRiyaldi/UTS_Semester1/blob/main/uts.py)
