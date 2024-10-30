# AplikasiPenghitungKata
 
## Identitas 
Nama: Ayu Atut Khofifah

NPM: 2210010553

## Penjelasan Program

### Deskripsi Program
Aplikasi ini adalah alat bantu untuk menghitung jumlah kata dan karakter dalam sebuah teks. Pengguna memasukkan teks ke dalam area input, kemudian menekan tombol "Hitung" untuk mendapatkan hasil berupa jumlah kata dan karakter yang ditampilkan pada beberapa label. Program ini dirancang menggunakan elemen-elemen GUI Java Swing seperti `JFrame`, `JPanel`, `JLabel`, `JTextArea`, `JScrollPane`, dan `JButton` untuk memastikan antarmuka yang ramah pengguna.

### Komponen GUI
1. **JFrame** - Merupakan frame utama yang menjadi wadah bagi semua komponen GUI.
2. **JPanel** - Digunakan untuk mengorganisir tata letak komponen di dalam JFrame.
3. **JLabel** - Menampilkan informasi seperti hasil jumlah kata dan karakter.
4. **JTextArea** - Area teks tempat pengguna memasukkan input yang akan dihitung.
5. **JScrollPane** - Melapisi JTextArea untuk memungkinkan pengguna menggulir teks jika melebihi tampilan.
6. **JButton** - Tombol yang memicu proses perhitungan.

### Logika Program
Program ini memanfaatkan manipulasi string dan ekspresi reguler untuk menghitung jumlah kata dan karakter. String yang dimasukkan oleh pengguna dipecah menjadi komponen-komponen yang kemudian dihitung berdasarkan logika tertentu.

### Events
1. **ActionListener** - Diimplementasikan pada tombol "Hitung" untuk memproses perhitungan jumlah kata dan karakter saat tombol ditekan.
2. **DocumentListener** - Ditambahkan pada JTextArea untuk menghitung kata dan karakter secara real-time setiap kali ada perubahan teks.

### Variasi Fitur
1. **Menghitung Jumlah Kalimat dan Paragraf** - Fitur tambahan ini memungkinkan aplikasi untuk menghitung tidak hanya kata dan karakter tetapi juga jumlah kalimat dan paragraf.
2. **Pencarian Kata Tertentu** - Aplikasi menyediakan fungsi untuk mencari kata tertentu di dalam teks dan menampilkan jumlah kemunculannya.
3. **Penyimpanan Hasil ke File** - Pengguna dapat menyimpan teks yang dimasukkan beserta hasil perhitungannya ke dalam file untuk dokumentasi atau keperluan lain.

### Kesimpulan
Dengan menggunakan komponen GUI Java Swing yang sederhana namun fungsional, aplikasi ini memberikan kemudahan dalam menghitung berbagai elemen teks yang dibutuhkan oleh pengguna. Penggunaan Event Listeners juga memperkaya interaktivitas aplikasi, membuatnya lebih dinamis dan responsif.

## Keunggulan Program

1. **Antarmuka Simpel dan Mudah Dipakai**  
   Aplikasi ini tampil dengan desain yang sederhana pakai komponen GUI dari Java Swing, jadi orang gampang paham cara pakainya tanpa harus belajar banyak. Tinggal ketik teks, klik tombol, dan hasilnya langsung kelihatan.

2. **Hitung Otomatis Secara Real-Time**  
   Dengan adanya fitur `DocumentListener` di JTextArea, aplikasi ini bisa langsung menghitung kata dan karakter begitu kamu mengetik atau mengedit teks. Jadi, kamu nggak perlu klik apa-apa buat lihat hasilnya—semuanya otomatis muncul secara real-time.

3. **Fitur Hitung yang Lengkap**  
   Aplikasi ini nggak cuma ngitung kata dan karakter, tapi bisa juga dikembangkan buat hitung jumlah kalimat dan paragraf. Fitur ini cocok buat yang butuh data teks yang lebih lengkap.

4. **Bisa Cari Kata Tertentu**  
   Fitur pencarian kata di aplikasi ini bikin kamu gampang nemuin kata tertentu dalam teks. Ini bermanfaat banget buat yang suka analisis teks, misalnya buat riset atau nyunting dokumen.

5. **Hasil Bisa Disimpan ke File**  
   Kamu bisa simpan teks dan hasil perhitungannya langsung ke file. Jadi kalau butuh data itu di lain waktu, tinggal buka filenya aja, nggak perlu ngulang perhitungan.

6. **Cepat dan Ringan**  
   Aplikasi ini pakai Java Swing yang ringan, jadi kerjanya cepat dan nggak bikin komputer berat. Ini bikin aplikasi tetap lancar bahkan di komputer dengan spek standar.

7. **Mudah Dikembangin Lagi**  
   Karena programnya dibuat modular pakai Java Swing, kamu atau developer lain gampang kalau mau tambahin fitur atau ubah-ubah sedikit sesuai kebutuhan.

8. **Hasil Akurat dengan Ekspresi Reguler**  
   Dengan bantuan ekspresi reguler, aplikasi ini bisa menghitung kata, karakter, dan bagian lain kayak kalimat atau paragraf dengan lebih akurat. Jadi, teks apa pun yang kamu masukkan, aplikasinya tetap bisa bekerja dengan baik.

Secara keseluruhan, aplikasi ini simpel tapi fungsional banget buat hitung-hitung kata dan karakter. Cocok buat yang butuh bantuan analisis teks ringan!

## Ini dia Screenshot Programnya

**1.** ![ss an AplikasiPenghitungKata](https://github.com/user-attachments/assets/a13d0fce-9522-4a4b-8162-3ebcf6e08fa8)


**2.** ![ss an AplikasiPenghitungKata2](https://github.com/user-attachments/assets/0b36b319-3799-437f-8f9a-25e08e7f6025)


**3.** ![ss an AplikasiPenghitungKata3](https://github.com/user-attachments/assets/d7d6f216-b148-4f57-b2f0-eb1d52b9e459)


**4.** ![ss an AplikasiPenghitungKata4](https://github.com/user-attachments/assets/9e7e026a-7ab5-45c6-bad7-7d629080b906)


**5.** ![ss an AplikasiPenghitungKata5](https://github.com/user-attachments/assets/50ceb67a-c83a-485b-863d-a6e0068da7c8)




