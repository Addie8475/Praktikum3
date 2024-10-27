# Praktikum3
**Menentukan bilangan terbesar dari 3 bilangan**

Flowchart :

![Screenshot_27](https://github.com/user-attachments/assets/da17e788-fc53-4a98-a90e-ee0a6867a6f7)

Kode Python :

![Screenshot_6](https://github.com/user-attachments/assets/b7c7ccd4-4b98-4495-8d34-0bbb9a9ed9c9)

Input dan Output

![Screenshot_6 - Copy](https://github.com/user-attachments/assets/acad19e5-2e53-410a-9b91-e36928dbd365)

Penjelasan :
1. Program meminta untuk memasukkan tiga bilangan, yaitu A, B, dan C.
- Fungsi **input()** digunakan untuk menerima input dalam bentuk string.
- Fungsi **float()** mengonversi input tersebut menjadi bilangan desimal. Jika hanya ingin bekerja dengan bilangan bulat, bisa juga menggantinya dengan int() jika untuk bilangan bulat.
2. Logika if-elif-else :
**If** :
Jika bilangan A lebih besar dari B dan lebih besar dari C, maka program akan mencetak bahwa A adalah bilangan terbesar.
**Elif** :
Jika kondisi pertama salah (artinya A bukan yang terbesar), maka program akan mengecek apakah B lebih besar dari C. Jika ya, B akan dicetak sebagai bilangan terbesar.
**Else** :
Jika tidak ada dari 2 kondisi sebelumnya yang terpenuhi, program akan mencetak bahwa C adalah bilangan terbesar.


**Menentukan bilangan terbesar dari N bilangan** 

Flowchart :

![p0](https://github.com/user-attachments/assets/3abdf689-1d78-4229-bf2e-7a4dd6d2eb2b)

Kode Python :

![p1](https://github.com/user-attachments/assets/368eb8e0-21fc-4b6a-91f1-c7cdf99d379f)

Input dan Output :

![p2](https://github.com/user-attachments/assets/22fdc3f0-c430-47f5-8a04-7940bd7d0660)

Penjelasan
1. **max_value**: Diset ke **-∞** agar setiap bilangan yang diinput lebih besar dari nilai awal ini dan memastikan bilangan pertama yang dimasukkan akan langsung menjadi kandidat terbesar.
2. **count**: Untuk menghitung jumlah bilangan yang diinput, tidak termasuk angka 0.
3. **while True**: Yaitu  loop tak terbatas yang akan terus berjalan sampai ada perintah break.
4. **input()**: Meminta untuk memasukkan bilangan. Input diubah menjadi float agar bisa menerima bilangan bulat atau desimal.
5. Program akan keluar dari loop dengan perintah break jika memasukkan angka 0 sebagai penanda berhenti.
6. Setiap kali memasukkan bilangan, program mengecek apakah bilangan tersebut lebih besar dari **max_value**. Jika ya, **max_value** diperbarui dengan bilangan tersebut.
7. Setiap kali bilangan valid dimasukkan (bukan 0), count bertambah 1.
8. Jika sesuatu yang dimasukkan bukan angka, seperti huruf, program akan menangkap **error** dengan except dan meminta input ulang.

