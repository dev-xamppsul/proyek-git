## Judul
selamat datang di proyek testing git


## Deskripsi
folder git ini isinya latihan tentang git

### jawaban soal

### Bagian A
1 folder sudah dibuat dengan nama proyek-git
2 sudah di init
3 output yang muncul bersisi informasi tentang file pada readme.md yang belum di track/dimasukan kedalam stage area
4 identitas git saya berupa user.email && user.name
5 file readme.md telah dibuat dengan judul dan deskripsi
6 file readme.md masih diluar stage area/diluar track stage area

### Bagian B
1. file readme.md sudah ditambahakan ke stage area
2. sebelum readme.md dimasukan kedalam stage area,file readme.md berada di luar track dari stage area tersebut dan yang diluar track/untrack bukan hanya sekedar file readme.md melainkan ada 2 folder yaitu bagian-a dan bagian-b masih dalam keadaan untrack atau diluar dari stage area
3. comit pertama sudah dilakukan dengan pesan komit "initial commit"
4. riwayat commit ditampilkan via git log
5. index html sudah dibuat dengan menggunakan perintah touch index.html dan mengisi file html.

```bash
================================================
6. pada saat di stage readme mendapatkan perubahan berupa perpindahan posisi file dari luar folder BAGIAN-A ke dalam folder BAGIAN-A
================================================
```
7. log ditampilkan per baris commit menggunakan perintah git log

### Bagian C
1. git branch fitur-navbar
2. git checkout fitur-navbar
3. menambahkan elemen navbar di index.html dan git commit -m "isi pesannya"
4. git branch fitur-footer
5. git switch fitur-footer
6. git branch -a
7. git switch master && git merge fitur-navbar

### Bagian D
1. repository telah dibuat: proyek-git
2. git remote add <name> <url>
3. git remote -v
4. git push <remote> master
5. git push <remote> fitur-footer
6. melakukan commit melalui remote repository dan pull di local untuk melihat riwayat komit di local setelah pull dari remote
