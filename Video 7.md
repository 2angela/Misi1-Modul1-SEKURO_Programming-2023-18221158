# ***Rangkuman Video 7***
# ***Git dan GitHub***

<p>&nbsp;<p>

## ***Git Merge Conflict***

Conflict saat melakukan Git Merge terjadi karena dua branch mengerjakan baris yang sama dalam satu repo. Resolve Git Merge Conflict dilakukan secara manual dengan memilih script mana yang dipilih dari antara semua branch yang membuat terjadinya conflict.

<p>&nbsp;<p>

1. Sebagai contoh, dilakukan commit pada file mahasiswa di branch baru yang bernama dev.

![Screenshot_27](https://i.ibb.co/P4FYHFz/Picture27.jpg)\
![Screenshot_28](https://i.ibb.co/F3r5Crh/Picture28.jpg)\
![Screenshot_29](https://i.ibb.co/L9h214S/Picture29.jpg)

<p>&nbsp;<p>

2. Setelah itu, dilakukan juga commit pada branch master.

![Screenshot_30](https://i.ibb.co/x2fwSNC/Picture30.jpg)\
![Screenshot_31](https://i.ibb.co/mhqWdCp/Picture31.jpg)

<p>&nbsp;<p>

3. Ketika dilakukan merge branch dev ke branch master, akan terjadi merge conflict. Secara otomatis, code editor akan menampilkan conflict yang ada seperti gambar di bawah.

![Screenshot_32](https://i.ibb.co/J7dQWBG/Picture32.jpg)\
![Screenshot_33](https://i.ibb.co/TwHmHHJ/Picture33.jpg)

<p>&nbsp;<p>

4. Resolve dapat dilakukan dengan menghapus bagian kode yang tidak diinginkan di dua kotak yang disorot. Bagian lain seperti tanda panah, tulisan "HEAD" dan simbol-simbol lainnya yang tidak termasuk kode juga dapat dihapus.

![Screenshot_34](https://i.ibb.co/HtpxkNZ/Picture34.jpg)\
![Screenshot_35](https://i.ibb.co/0DSdqXm/Picture35.jpg)

<p>&nbsp;<p>

5. Setelah save file di code editor, commit dapat langsung dilakukan tanpa memasukkan command git merge lagi.

![Screenshot_36](https://i.ibb.co/FqzXPG6/Picture36.jpg)

<p>&nbsp;<p>

6. Branch dev dapat dihapus apabila tidak lagi diperlukan.

![Screenshot_37](https://i.ibb.co/3f2Synv/Picture37.jpg)

<p>&nbsp;<p>


## ***Memulai Branch dari Suatu Commit***

Checkout ke commit dapat dilakukan dengan command\
**"git checkout [*7 karakter pertama dari hash commit*]"**\
Branch baru dapat dimulai dari commit tersebut, misal branch test. Agar HEAD mengarah ke branch tersebut, lakukan checkout ke branch test.

![Screenshot_38](https://i.ibb.co/M70Pgbw/Picture38.jpg)
