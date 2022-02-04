# Membangun-Web-Berbasis-SPA-dengan-Mudah-Menggunakan-VueJS
Kalkulator dengan Vuejs
# Mempersiapkan Tools
Sebelum kita dapat membuat aplikasi VueJS kita, langkah awal yang harus kita lakukan adalah mempersiapkan tools. Ada dua cara yang dapat kamu gunakan, menggunakan code editor online atau memasang tools di komputer masing-masing.
#
Untuk tips kali ini, cara yang akan kita gunakan yaitu menggunakan code editor online untuk memudahkan teman-teman membuat aplikasi. Code Editor yang akan kita gunakan yaitu CodeSandbox.
![image](https://user-images.githubusercontent.com/92959023/152517673-fc25e124-f3f7-459b-a751-130b85ccde3a.png)
# Memasang Framework VueJS
Untuk dapat memasang framework VueJS di CodeSandbox, kalian dapat membuat Sandbox dengan menekan tombol Create Sandbox yang terletak di pojok kanan atas.
![image](https://user-images.githubusercontent.com/92959023/152518321-6c6a3294-3bee-4c1e-b052-0c3663892719.png)
Setelah itu, maka akan muncul halaman welcome. Kalian dapat klik tombol Create Sandbox untuk melanjutkan dan memilih framework Vue.
![image](https://user-images.githubusercontent.com/92959023/152528540-9a2ca2da-259b-4a0e-995c-8b3b162f6cf4.png)
Jika sudah, maka halaman Code Editor yang sudah terpasang VueJS dapat kamu gunakan. Yay!
![image](https://user-images.githubusercontent.com/92959023/152528602-14d470bc-755f-4b4e-8b8d-36db9dce691f.png)
# Memahami Struktur Project
Dalam aplikasi VueJS, ada beberapa aturan dasar yang perlu kamu pahami, salah satunya adalah struktur direktori dari project VueJS.

Struktur folder ini merupakan pondasi dasar dari aplikasi kalian, dan dapat dikustomisasi tergantung dari kebutuhan kalian.


Komponen utama dari sebuah aplikasi VueJS adalah file *main.js* yang berisi inisialisasi aplikasi. Secara default, aplikasi VueJS berada di file *App.vue*
![image](https://user-images.githubusercontent.com/92959023/152531791-d9a9d0d2-66af-42da-a930-43017f59ab0a.png)
#
Pada file *App.vue,* terdapat kode aplikasi kita yang dapat kita gunakan dalam membuat aplikasi. Setiap file Vue akan memiliki 3 struktur utama, yaitu *template, script,* dan *style.*
![image](https://user-images.githubusercontent.com/92959023/152542479-15c7fd35-6792-4d60-a38c-dd55b4700b6c.png)
Aplikasi yang kita buat pun dapat kita bagi lagi ke file yang berbeda dengan menggunakan *components.* Hal ini akan sangat membantu kalian terlebih jika kalian membuat aplikasi kompleks yang membutuhkan kode yang banyak, tentunya components ini akan membantu kalian.

Contoh component yang dapat kamu gunakan pada project ini yaitu component *HelloWorld*
![image](https://user-images.githubusercontent.com/92959023/152542988-efc7fff7-cb80-4088-81e4-beb81774e323.png)
# Membuat Kalkulator Sederhana
Tentunya teman-teman ingin tahu bagaimana cara membuat aplikasi pada VueJS. Pada kali ini kita akan mencoba membuat kalkulator sederhana, yang akan menghitung angka dari variable yang sudah kita tentukan sebelumnya.

Berikut dibawah ini merupakan aplikasi yang akan kita buat.
![image](https://user-images.githubusercontent.com/92959023/152543168-8ce19ffa-9e5b-4065-80ac-ddc6a9307392.png)
Pertama-tama, kalian dapat membuat components baru dengan membuat file baru pada folder *components,* lalu kalian beri nama *Calculator.vue*
![image](https://user-images.githubusercontent.com/92959023/152544452-c209abc5-68d8-4ab1-b88f-2bca222e305f.png)

Lalu, pada file *App.vue,* ubah kode *HelloWorld* dan ganti menjadi *Calculator,* karena kita tidak membutuhkan component *HelloWorld.* Sebagai contoh lengkapnya, kalian dapat mereferensikan foto dibawah ini.
![image](https://user-images.githubusercontent.com/92959023/152544700-36a3ef73-a3eb-4b74-b0c8-5ebd62965e76.png)
