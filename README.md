#latihan 1
TUTORIAL MEMBUAT FILE  README.md
BAGIAN MEMBUAT REPOSIORY LOKAL
1.	Download Git Bash https://git-scm.com/downloads Download sesuai OS masing-masing

![image](https://user-images.githubusercontent.com/56445770/67139886-4c840680-f27f-11e9-856f-4c1ac59ab2d5.png)


2.	Setelah download dan di install, langkah selanjutnya buka aplikasi Git Bash yang tadi sudah di download

![image](https://user-images.githubusercontent.com/56445770/67139923-a8e72600-f27f-11e9-818c-179712bc7131.png)

3.	Lalu Git Bash akan terbuka 

![image](https://user-images.githubusercontent.com/56445770/67139976-172be880-f280-11e9-8c9a-3ad946e385d0.png)


4.	Lalu untuk membuat folder yg bernama latihan1 ketik perintah mkdir latihan1

5.	Lalu akan muncul folder bernama latihan1

![image](https://user-images.githubusercontent.com/56445770/67139996-52c6b280-f280-11e9-87c0-7e49acbafa5a.png)


6.	Setelah itu kembali kedalam aplikasi Git Bash lalu ketik cd latihan1 untuk masuk kedalam direktori tersebut 

![image](https://user-images.githubusercontent.com/56445770/67140026-87d30500-f280-11e9-8f03-2ab87a62e6c2.png)


7.	Jalankan perintah git init, untuk membuat repository local

![image](https://user-images.githubusercontent.com/56445770/67140036-a6390080-f280-11e9-8c61-3af7339e06b9.png)


8.	Jika berhasil maka akan muncul direktori hidden .git

![image](https://user-images.githubusercontent.com/56445770/67140046-c1a40b80-f280-11e9-8b67-056030070925.png)


9.	Selanjutnya untuk membuat file README.md lalu d isikian dengan text latihan 1 dengan menjalankan perintah $  echo “#latihan 1” >> README.md

![image](https://user-images.githubusercontent.com/56445770/67140058-e5ffe800-f280-11e9-919b-833e2423fe0e.png)

10.	Jika berhasil maka akan muncul file README.md di dalam folder latihan1 yang pertama kali di buat di awal

![image](https://user-images.githubusercontent.com/56445770/67140073-092a9780-f281-11e9-83be-7095ee27810e.png)


BAGIAN MEMBUAT REPOSIORY SERVER
1.	Buatlah repisiory di Github.com, dengan nama latihan 1, lalu klik create repository

![image](https://user-images.githubusercontent.com/56445770/67140089-28c1c000-f281-11e9-8f7d-1bdf0e2e9596.png)

2.	setelah itu kembali ke Git Bash dengan mengetik perintah git remote add origin [url]

![image](https://user-images.githubusercontent.com/56445770/67140101-5149ba00-f281-11e9-9bec-8556a4d49919.png)

3.	untuk menaruh file README.md yang tadi sudah di buat, dengan cara mengetik perintah git push -u origin master
 
![image](https://user-images.githubusercontent.com/56445770/67140133-9a9a0980-f281-11e9-9c7a-436a932f0160.png)

4.ketik perintah git add -A
 
 ![image](https://user-images.githubusercontent.com/56445770/67140161-d339e300-f281-11e9-81aa-f6c174c0542c.png)

5.	lalu ketik perintah git commit –m “initial commit”

![image](https://user-images.githubusercontent.com/56445770/67140169-f4023880-f281-11e9-9397-8cdc8eeaabae.png)

6.	lalu ketik lagi perintah git push –u origin master 
	
![image](https://user-images.githubusercontent.com/56445770/67140185-2318aa00-f282-11e9-96f5-07b8a7a87c4c.png)

7.	jika berhasil akan seperti gambar di bawah, dan file README.md sudah berada di reposiory latihan 1 di Github.com yang tadi di buat

![image](https://user-images.githubusercontent.com/56445770/67140194-4cd1d100-f282-11e9-96a5-a7bd4e9bad7f.png)
