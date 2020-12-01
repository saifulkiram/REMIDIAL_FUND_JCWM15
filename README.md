# Purwadhika
Sebelum anda mengerjakan soal ujian, pastikan anda memiliki akun **GitHub** dan ***software git*** sudah terinstall dilaptop. Anda dapat memastikan bahwa **git** sudah terinstall dilaptop anda dengan menjalankan perintah berikut ini diterminal atau ***cmd*** : ``` git --version ```. Jika muncul *versi git* maka komputer anda sudah terinstal *git*.

Soal ujian dapat anda temukan didalam repositori ini atau anda dapat melihatnya melalui *[link](https://github.com/alee0510/JCWM15_FUND_EXAM/blob/master/soal_ujian_JCWM_FUND.pdf)* berikut ini :

Sebelum mengerjakan ujian, bacalah dengan seksama aturan serta panduan dalam mengerjakan soal-soal ujian berikut ini.

## Term & Condition
- ujian akan dilaksanakan selama 3 jam 20 menit
    - 10 menit untuk *setup*
    - 3 jam mengerjakan soal
    - 10 menit *pull request*
- selama mengerjakan ujian, siswa wajib **men-share seluruh screen** di **zoom** (khusus untuk kelas online) sampai ujian selesai
- dilarang bekerjasama dalam mengerjakan soal ujian
- dilarang memberikan jawaban atau meminta jawaban dari teman atau pihak lain
- jika ada pertanyaan mengenai ujian dan soal, langsung tanyakan kepada operasional selaku pengawas ujian atau *lecturer* yang mengawasi
- siswa boleh membuka *website* dan referensi lainnya selama ujian sesuai ketentuan yang berlaku
- jawaban soal akan dikumpulkan di dalam repositori ini dengan sistem ***pull request*** dan siswa wajib mengirim ***link*** dari ***Forked Repositoy*** ke alamat email berikut ini :<br>

to : operational_jkt@purwadhika.com <br>
subject : JCWM15-JKT-UJIAN_FUNDAMENTAL_REMED

## Exam Guide
- sebelum mengerjakan soal, lakukan ***Fork*** untuk repositori ini
    ![guide_1](./assets/guide_01.jpg)

- kemudian *clone* repositori hasil *Forked* ke komputer kalian dengan cara *copy link forked respository* anda
    ![guide_2](./assets/guide_02.jpg)

- buka terminal atau *cmd* dengan mengarah pada folder tempat anda akan menyimpan hasil *clone* dari repositori yang sudah anda *forked*, kemudian jalankan perintah ```git clone``` dan *paste link forked repository* anda

    ``` C:\data\alee> git clone http://github.com/alee/...```

- pindah ke direktori folder hasil ```git clone``` dengan cara

    ``` C:\data\alee> cd nama-forked-repository ``` 

- lalu buatlah sebuah *branch* baru tempat anda akan mengerjakan soal ujian

    ``` C:\data\alee\ujian> git checkout -b NAMA-JCWM15 ```

- bukalah *code editor* anda atau *vscode* : 

    ``` C:\data\alee\ujian> code . ```

- pastikan anda berada di-*branch* yang baru anda buat dengan cara lihat dipojok kiri bawah *vscode* dan anda akan melihat nama *branch* yang baru anda buat atau anda bisa menggunakan perintah : ``` git branch ``` di terminal atau cmd untuk melihat semua daftar *branch* yang ada di folder *project* anda, *branch* yang dipakai saat ini ditandai dengan warna hijau dan *nama-*branch*
- buatlah sebuah folder dengan nama : NAMA-ANDA-PROGRAM, e.x. ALEE-JCWM15 <br>
    ![guide_3](./assets/guide_03.jpg)

- kerjakanlah semua soal ujian didalam folder tersebut

> **NOTE** : <br>
> - jangan hapus file .gitignore dan file lainnya hasil dari clone baik di-*branch* master atau di *branch* baru tempat anda mengerjakan soal
> - jangan lakukan perubahan apapun di file .gitignore dan file *original* dari repositori ini

## Pull Request Guide
- sebelum anda melakukan *pull request* ke repositori pusat (respositori awal), **PASTIKAN!** bahwa semua file yang anda buat disimpan didalam satu folder (NAMA-ANDA-PROGRAM)
- simpan perubahan yang terjadi di *git* dengan cara : ```git add nama-file``` atau ```git add .``` untuk menyimpan semua perubahan yang terjadi sekaligus
- kemudian lakukan ```commit``` : ```git commit -m "masukan pesan commit"```, e.x. "alee : ujian fundamental JCWM15"
- *push branch* baru tempat anda mengerjakan soal : ``` git push origin nama-branch ```
- buka GitHub anda dan lihat repositori hasil *forked* anda. **PASTIKAN!** bahwa *branch* yang anda *push* sudah ada di GitHub
- jika sudah ada, maka akan ada *warning* untuk melakukan ```compare & pull request``` <br>
    ![guide_4](./assets/guide_04.jpg)

- lakukan *pull request* dan pastikan bahwa
    1. **HEAD repository** berasal dari repositori kalian dan **branch** berasal dari *branch* tempat anda mengerjakan soal, **BASE respository** menuju repositori asal dan *branch* **master**
    2. beri informasi *pull request* berupa : nama-program-EXAM_FUNDAMENTAL
    <br>e.x. : alee-JCWM15-EXAM_FUNDAMENTAL
    
    ![guide_5](./assets/guide_05.jpg)

- jika *pull request* berhasil dan tidak terjadi konflik maka akan muncul info berikut ini
    ![gudie_6]()

## Selamat Mengerjakan Ujian ☺
