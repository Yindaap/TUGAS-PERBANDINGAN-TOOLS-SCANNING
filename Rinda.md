"TUGAS 4 KEAMANAN KOMPUTER"

NAMA : RINDAAMBARWATIPUTRI
NIM : 09030582226004
KLAS : TK5B


1. Nmap (via terminal)

![NMAP RNDA](https://github.com/user-attachments/assets/3679698d-c332-4d8c-ba19-c6c09e164fbb)


Nmap (Nerwork Mapper) adalah alat pemindaian sumber tebuka untuk eksplorasi jaringan dan keamanan.

Antarmuka : Command-line

Fitur utama : Dapat melakukan pemindaian port, penemuan host, penemuan sistem operasi, sidik jari layanan, serta penemuan firewall dan ids. Mendukung pembuatan skrip melalui Nmap Scripting engine (NSE), memungkinkan otomatisasi tugas-tugas tertentu. anda dapat melakukan pemindaian TCP dan UDP, serta pemindaian tersembunyi untuk menghindari deteksi. mendukung berbagai jenis pemindaian seperti pemindaian SYN, pemindaian ACK, dan pemindaian FIN.

Kelebihan : - Sangat fleksibel, terutama untuk pengguna yang sudah berpengalaman - Mampu bekerja dengan sangat baik dijaringan besar mendukung berbagai kustomisasi.

Kekurangan : - Diperlukan pengetahuan teknis yang cukup untuk menggunakan secara optimal - Kurva belajar cukup curam bagi pemula

2. Zenmap (Via Aplikasi)

![Screenshot 2024-09-16 225845](https://github.com/user-attachments/assets/7e8b4889-038b-46f5-9acf-fd953afb57ea)


Zenmap adalah versi GUI dari Nmap yang dimaksudkan untuk memudahkan pengguna menggunakan Nmap tanpa harus menguasai baris perintah

Antarmuka : Graphical User Interface (GUI)

Fitur utama : Zenmap sebenarnya hanya berfungsi sebagai frontend untuk Nmap, sehingga memiliki semua fitur Nmap. Berbagai profil pemindaian tersedia untuk memudahkan penggunaan pemula. hasil scan ditampilkan dalam visualisasi yang mudah dibaca seperti diagram dan grafik. Mendukung pembuatan dan penyimpanan sesi pemindaian untuk analisis selanjutnya.

Kelebihan : Mudah digunakan bahkan bagi pengguna yang belum familiar dengan terminal. Visualisasi yang lebih mudah dan ramah pengguna. anda dapat mengekspor hasil scan harian ke berbagai frmat seperti XML, HTML, dll

Kekurangan : Karena ini GUI, maka bisa lebih lambat dibandingkan menjalankan Nmap langsung dari terminal, khususnya pada jaringan besar. Tidak sekuat dan selengkap menggunakan Nmap melalui terminal, terutama ketika menggunakan opsi pemindaian yang rumit

3. Angry IP Scan (Via aplikasi)

![Screenshot 2024-09-16 225923](https://github.com/user-attachments/assets/233456cc-c6f2-4dc6-9bcc-8ef81e8551df)


Angry IP Scan adalah aplikasi pemindaian jaringan yang ringan dan cepat, fokus pada kemudahanan penggunaan dan kecepatan pemindaian

Antarmuka : Graphical User Interface (GUI)

Fitur utama : Pindai alamat ip dalam rentang tertentu dan periksa port yang terbuka, Menampilkan informasi dasar seperti IP, nama host dan status port. Hasil scan dapat disimpan dalam berbagai format seperti CSV, TXT, dan XML. plugin yang dapat memperluas fungsionalitas pemindaian anda.

Kelebihan : Sangat mudah digunakan bahkan untuk pemula, proses pemindaian cepat cocok untuk jaringan yang keci berjalan lintas Platform (Linux, Windows, macOS0. Ukuran aplikasi kecil dan ringan.

Kekurangan : Fungsionalitasnya terbatas di bandingkan Nmap, terutama dalam hal penemuan mendalam (penemuan sistem operasi, layanan, pemindaian kerentanan, DLL.) Tidak cocok untuk memindai jaringan yang besar dan kompleks.

Kesimpulan Perbandingan dari ketiga tersebut :

Berikut perbandingan antara Nmap (via Terminal), Zenmap (via GUI), dan Angry IP Scanner (via GUI). Nmap merupakan tool scanning yang sangat kuat dan fleksibel, ideal untuk pengguna berpengalaman karena menawarkan berbagai opsi scanning dan mendukung scripting, namun membutuhkan pemahaman teknis yang cukup tinggi. Zenmap, versi GUI dari Nmap, lebih mudah digunakan dengan visualisasi yang baik dan profil scanning yang siap pakai, meski sedikit lebih lambat dibandingkan versi terminal. Angry IP Scanner, di sisi lain, adalah tool scanning yang cepat, ringan, dan sangat sederhana, cocok untuk jaringan kecil hingga menengah, tetapi dengan fitur yang terbatas dibandingkan dua tool lainnya, terutama dalam hal deteksi OS dan layanan jaringan. Pemilihan tool bergantung pada kebutuhan pengguna serta skala jaringan yang hendak dipindai.
