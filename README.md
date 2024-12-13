Nama : Kristian Perdamaian Pasaribu
kelas : IE.23.C12

FLOWCHART

![Diagram Tanpa Judul drawio (7)](https://github.com/user-attachments/assets/b9936b68-e614-4558-aff0-dd078785894c)

CODING PROGRAM

![code1](https://github.com/user-attachments/assets/5b90ce6e-a44e-4fd9-8790-978725a2c00c)
![code 2](https://github.com/user-attachments/assets/bc5a5f9b-4f1f-4130-be9f-b5e9675f88b6)

HASIL PROGRAM

![122](https://github.com/user-attachments/assets/b808bd32-40e9-4870-83c1-58829c74ebe4)
![1222](https://github.com/user-attachments/assets/1d64be6e-db61-4190-b5ca-202ea632c249)

PENJELASANNYA

1. Kelas Daftar Nilai Mahasiswa
Kelas ini digunakan untuk mengelola data mahasiswa. Terdapat beberapa method utama dalam kelas ini:
a. __init__
•	Method ini adalah constructor yang digunakan untuk menginisialisasi atribut data_mahasiswa, yang berupa list kosong untuk menyimpan data mahasiswa
b. tambah (self, nim, nama, nilai)
•	Method ini menambahkan data mahasiswa ke dalam list data_mahasiswa.
•	Parameter:
o	nim: Nomor Induk Mahasiswa.
o	nama: Nama mahasiswa.
o	nilai: Nilai mahasiswa.
•	Data disimpan dalam bentuk dictionary ({"nim": nim, "nama": nama, "nilai": nilai})
c. tampilkan (self)
•	Method ini menampilkan semua data mahasiswa yang ada dalam list data_mahasiswa
•	Jika daftar kosong, akan mencetak pesan bahwa tidak ada data mahasiswa
d. hapus (self, nim)
•	Method ini menghapus data mahasiswa berdasarkan nim
•	Jika ditemukan, data dihapus dari list, dan jika tidak ditemukan, akan mencetak pesan bahwa NIM tersebut tidak ada
e. ubah (self, nim, nilai_baru)
•	Method ini mengubah nilai mahasiswa berdasarkan nim
•	Jika ditemukan, nilai mahasiswa diperbarui dengan nilai_baru, dan jika tidak ditemukan, akan mencetak pesan bahwa NIM tersebut tidak ada
2. Fungsi main()
Fungsi ini adalah antarmuka utama yang digunakan untuk berinteraksi dengan pengguna. Fitur yang ada meliputi:
a. Menu Interaktif
Menu yang mencakup 5 pilihan:
1.	Tambah Data: Meminta input NIM, nama, dan nilai untuk ditambahkan
2.	Tampilkan Data: Menampilkan semua data mahasiswa
3.	Hapus Data: Meminta input NIM mahasiswa untuk dihapus
4.	Ubah Data: Meminta input NIM dan nilai baru untuk memperbarui data
5.	Keluar: Mengakhiri program
b. Logika Pilihan
Setiap pilihan akan memanggil method yang sesuai dari objek DaftarNilaiMahasiswa untuk menjalankan tugas
3. Alur Kerja Program
1.	Mulai Program: Membuat objek DaftarNilaiMahasiswa
2.	Pilih Menu: Program terus berjalan hingga pengguna memilih opsi "Keluar".
3.	Proses Tambah, Hapus, Ubah, atau Tampilkan Data: Menjalankan operasi sesuai dengan input pengguna
