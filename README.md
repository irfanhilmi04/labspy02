#Program sederhana untuk menentukan bilangan terbesar
##coding
1. print("--------------------------------------------")
2. print("MEMBUAT PROGRAM MENENTUKAN BILANGAN TERBESAR")
3. print("--------------------------------------------")
4. a = int(input("masukan bilangan A: ")
5. b = int(input("masukan bilangan B: ")
6. c = int(input("masukan bilangan c: ")
7. if a>b and a>c:
8. print(a, "adalah angka terbesar")
9. elif b>a and b>c:
10. print(b, "adalah angka terbesar")
11. elif c>a and c>b:
12. print(c, "adalah angka terbesar")

###penjelasan
1. Pertama kita harus menginput bilangan pertama sampai bilangan ketiga. Codingnya :
a=int(input(‘Bilangan 1 = ‘))
b=int(input(‘Bilangan 2 = ‘))
c=int(input(‘Bilangan 3 = ‘))
2. Selanjutnya kita menggunakan logika if dan Logika AND. Codingnya :
if a>b and a>c:
print (a, ‘Adalah Bilangan terbesar’)
elif b>a and b>c:
print (b, ‘Adalah Bilangan terbesar’)
else:
print (c, ‘Adalah Bilangan terbesar’)
Penjelasannya : Jika a lebih dari b dan a lebih dari c, maka output bilangan a, kalau bilangan a bukan bilangan terbesar maka lanjut ke bilangan b, jika b lebih dari a dan b lebih dari c maka bilangan b Adalah Bilangan terbesar, kalau a dan b bukan bilangan terbesar maka bilangan c Adalah bilangan yang terbesar.
####output
=====================================
PROGRAM MENENTUKAN BILANGAN TERBESAR
=====================================
Masukkan 3 Bilangan yang diinginkan!
Bilangan 1 = 10
Bilangan 2 = 30
Bilangan 3 = 20
=====================================
30 Adalah Bilangan terbesar
=====================================
Process finished with exit code 0
