1. Mencari Bilangan Terbesar Dari 3 Bilangan
   Dari program ini kita akan mencari bilangan terbesar dari 3 bilangan

# Flowchart 
![Flowchart](Flowchart1.png)

# Kode Program
```
a = int(input("Masukkan bilangan A: "))
b = int(input("Masukkan bilangan B: "))
c = int(input("Masukkan bilangan C: "))

if a > b:
    if a > c:
        print("A adalah terbesar")
        terbesar = a
    else:
        print("C adalah terbesar")
        terbesar = c
else:
    if b > c:
        print("B adalah terbesar")
        terbesar = b
    else:
        print("C adalah terbesar")
        terbesar = c

print(f"Bilangan terbesar adalah: {terbesar}")
```
# Penjelasan
Program ini menjelaskan bilangan terbesar dari 3 bilangan yang di input oleh user dengan cara:
- inputkan bilangan A, B, C
setelah masukan bilangan kemudian, cek bilangan mana yg memiliki nilai terbesar
- A > B?
  if yes (bilangan terbesar adalah A)
  kemudian A > C
  if yes bilangan terbesar adalah A
  If no (bilangan terbesar adalah c)
  
- B > A?
  if yes (bilangan terbesar adalah B)
  kemudian B > C
  if yes bi;amgan terbesar adalah B
  if no (bilangan terbesar adalah C)

# Hasil Codingan Mencari Bilangan Terbesar 
```
Masukkan bilangan A: 20
Masukkan bilangan B: 87 
Masukkan bilangan C: 59
B adalah terbesar
Bilangan terbesar adalah: 87
```

2. Mencari Bilangan Terbesar Dari N Bilangan
   Dalam kasus ini kita akan mencari bilangan dengan nilai terbesar dengan menggunakan konsep " Do While "

# FlowChart
![Flowchart](Flowchart2.png)

# Code Program
````
a = 0
bilangan = int(input("Masukkan bilangan: "))
while bilangan != 0:
    if bilangan > a:
        a = bilangan
    bilangan = int(input("Masukkan bilangan: "))
    
print(f"Bilangan terbesar {a}") 
````
# Penjelasan Program 
program ini kita akan mencari bilangan terbesar dengan konsep "Do While". Dengan do while ini program akan terus mengulang/looping sampai user menginput angka 0 jika user belom memasukan angka 0 maka user akan terus memasukan bilangan dan akan berhenti jika user memasukan angka 0. Kemudian program akan menentukan bilangan dengan nilai terbesar kemudian program akan menampilkan bilangan tersebut.

# Hasil Codingan Terbesar Dari N Bilangan 
```
Masukkan bilangan: 45
Masukkan bilangan: 58
Masukkan bilangan: 36
Masukkan bilangan: 25
Masukkan bilangan: 78
Masukkan bilangan: -53
Masukkan bilangan: -85
Masukkan bilangan: -1
Masukkan bilangan: 57
Masukkan bilangan: 0
Bilangan terbesar 78
```









