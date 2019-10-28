# Program sederhana untuk menentukan bilangan terbesar

## coding
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

### penjelasan
1. Pertama kita harus menginput bilangan pertama sampai bilangan ketiga. Codingnya :
- a=int(input("Bilangan A = "))
- b=int(input("Bilangan B = "))
- c=int(input("Bilangan C = "))
2. Selanjutnya kita menggunakan logika if dan Logika AND. Codingnya :
- if a>b and a>c:
- print (a, "Adalah Bilangan terbesar")
- elif b>a and b>c:
- print (b, "Adalah Bilangan terbesar")
- elif c>b and c>b:
- print (c, "Adalah Bilangan terbesar")
- Penjelasannya : Jika a lebih dari b dan a lebih dari c, maka output bilangan a, kalau bilangan a bukan bilangan terbesar maka lanjut ke bilangan b, jika b lebih dari a dan b lebih dari c maka bilangan b Adalah Bilangan terbesar, kalau a dan b bukan bilangan terbesar maka bilangan c Adalah bilangan yang terbesar.
![Untitled](https://user-images.githubusercontent.com/56240221/67644048-a7d58900-f950-11e9-9890-8e907be311f3.jpg)
#### output
![Untitled1](https://user-images.githubusercontent.com/56240221/67644105-e9feca80-f950-11e9-85a8-131b7a34e3b8.jpg)
- =====================================
- PROGRAM MENENTUKAN BILANGAN TERBESAR
- =====================================
- Masukkan 3 Bilangan yang diinginkan!
- Bilangan A = 10
- Bilangan B = 40
- Bilangan C = 30
- =====================================
- 40 Adalah Bilangan terbesar
- =====================================
- Process finished with exit code 0
