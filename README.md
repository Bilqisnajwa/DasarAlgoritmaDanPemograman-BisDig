# DasarAlgoritmaDanPemograman-BisDig
**Manfaat Penggunaan Fungsi**
Penggunaan fungsi dalam pemrograman memiliki beberapa manfaat signifikan:
 * Modularitas: Fungsi memungkinkan Anda memecah program yang kompleks menjadi bagian-bagian yang lebih kecil dan terkelola. Setiap fungsi bertanggung jawab atas tugas tertentu, sehingga kode menjadi lebih terstruktur dan mudah dipahami.
 * Reusabilitas (Penggunaan Kembali): Setelah sebuah fungsi dibuat, Anda dapat menggunakannya berkali-kali dalam program yang sama atau bahkan dalam program yang berbeda tanpa perlu menulis ulang kode yang sama. Ini menghemat waktu dan usaha.
 * Mengurangi Redundansi: Dengan menggunakan fungsi, Anda menghindari penulisan blok kode yang sama berulang kali. Jika ada logika yang perlu digunakan di beberapa tempat, cukup panggil fungsinya.
 * Meningkatkan Keterbacaan: Kode yang menggunakan fungsi cenderung lebih mudah dibaca dan dipahami karena alur program menjadi lebih jelas. Pembaca dapat fokus pada apa yang dilakukan oleh setiap fungsi tanpa harus memahami detail implementasinya sekaligus.
 * Memudahkan Pemeliharaan: Ketika ada perubahan atau perbaikan yang diperlukan pada bagian tertentu dari logika program, Anda hanya perlu memodifikasi fungsi yang relevan. Ini mempermudah proses pemeliharaan dan mengurangi risiko mempengaruhi bagian kode lainnya.


   **Bagaimana Rekursi Bekerja dalam Menghitung Faktorial**
Rekursi adalah teknik pemrograman di mana sebuah fungsi memanggil dirinya sendiri di dalam definisinya. Dalam konteks perhitungan faktorial, rekursi bekerja berdasarkan definisi matematis faktorial:
 * n\! = n \\times (n-1)\! untuk n \> 0
 * 0\! = 1
Proses rekursif untuk menghitung faktorial suatu bilangan n akan berjalan sebagai berikut:
 * Base Case (Kasus Dasar): Fungsi akan memiliki kondisi berhenti, yang disebut base case. Untuk faktorial, kasus dasarnya adalah ketika bilangan yang dihitung adalah 0, di mana hasilnya adalah 1. Kasus dasar ini penting untuk mencegah fungsi memanggil dirinya sendiri secara tak terbatas (infinite recursion).
 * Recursive Step (Langkah Rekursif): Jika bilangan yang dihitung bukan merupakan base case, fungsi akan mengembalikan hasil perkalian bilangan tersebut dengan faktorial dari bilangan yang lebih kecil (n-1). Di sinilah fungsi memanggil dirinya sendiri dengan argumen yang berbeda.
Contoh perhitungan faktorial 4 menggunakan rekursi:
4\! = 4 \\times 3\!
3\! = 3 \\times 2\!
2\! = 2 \\times 1\!
1\! = 1 \\times 0\!
0\! = 1 (base case)
Kemudian, hasil dari base case akan dikembalikan ke pemanggilan sebelumnya:
1\! = 1 \\times 1 = 1
2\! = 2 \\times 1 = 2
3\! = 3 \\times 2 = 6
4\! = 4 \\times 6 = 24



**Penjelasan Penggunaan Perulangan dan List:**
*List (sebagai pengganti Array):*
Dalam Python, kita menggunakan list untuk menyimpan sekumpulan data. Dalam kasus ini, kita akan menggunakan sebuah list untuk menyimpan nilai-nilai dari 5 siswa.
List memungkinkan kita untuk menyimpan banyak nilai di dalam satu variabel, dan setiap nilai dapat diakses menggunakan indeks (posisi)nya. Indeks dalam Python dimulai dari 0.
Perulangan (for loop):

Perulangan sangat berguna ketika kita perlu melakukan tindakan yang sama berulang kali. Dalam kasus ini, kita perlu meminta input nilai dari 5 siswa.
Kita dapat menggunakan perulangan for untuk mengulang proses input sebanyak 5 kali. Setiap kali perulangan berjalan, kita akan meminta input nilai untuk satu siswa dan menambahkannya ke dalam list nila



**Penjelasan Penggunaan Struktur Kontrol Percabangan:**
Struktur kontrol percabangan (seperti if, elif, else) memungkinkan program untuk mengambil keputusan berdasarkan kondisi tertentu. Dalam kasus diskon e-commerce ini, kita perlu memeriksa apakah total belanja pelanggan memenuhi syarat untuk mendapatkan diskon (yaitu, di atas Rp500.000).

Logika percabangannya adalah sebagai berikut:

Kondisi: Periksa apakah total belanja pelanggan lebih besar dari Rp500.000.
Jika kondisi benar (True): Berikan diskon sebesar 10% dari total belanja. Hitung total pembayaran setelah diskon.
Jika kondisi salah (False): Tidak ada diskon yang diberikan. Total pembayaran sama dengan total belanja awal.
