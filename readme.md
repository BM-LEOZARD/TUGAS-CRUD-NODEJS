# CRUD NodeJS
Teknologi :
- nodeJS
- MongoDB
- Local Nodemon (npm start)

Fitur :
1.  Saat berhasil login akan muncul tulisan selamat datang  sesuai dengan nama dari si  user. Di terminal vscode juga akan menampilkan hasil jika si admin berhasil login atau tidak. Pesan pertama, jika admin salah memasukkan username atau password akan ada dua pesan, yaitu "Mencoba masuk dengan { username: 'adminnn', password: 'admin123' }" dan "Username atau Password salah { username: 'adminnn', password: 'admin123' }". Pesan kedua, jika admin benar memasukkan username dan password akan ada dua pesan juga, yaitu "Mencoba masuk dengan { username: 'admin', password: 'admin123' }" dan "Berhasil login: admin". Untuk username dan password diambil dari collection user.
2.  Data yang muncul di halaman tabel /data-siswa hanya akan menampilkan No, Nama, NISN, NIK, dan NOKK. Di halaman tabel /data-siswa juga terdapat dua tombol button, tombol detail dan delete sama-sama mengambil value dari nisn.
3. Di halaman tambah data terdapat inputan untuk nama, jenis kelamin, NISN, NIK, NOKK, tempat tanggal lahir, tingkat kelas saat ini, rombel/jurusan, terdaftar sebagai, dan tanggal masuk. Di halaman tambah data siswa juga terdapat dua tombol button, kedua tombol button tersebut mengarah ke halaman /data-siswa. Bedanya saat data sudah diisi dan tidak di simpan, maka data tersebut tidak akan masuk dan flash tidak akan muncul.
4. NISN, NIK, dan NOKK  sudah di setting  untuk nominal  yang ditetapkan. Contohnya  untuk NISN harus 10 nominal angka, sementara NIK dan NOKK  harus 16 nominal angka. Begitu pula dengan tgl_masuk yang sudah di validasi.
5. Untuk tingkat dan rombel sudah diatur, jika ingin memilih tingkat X maka untuk rombel hanya akan menampilkan PPLG 1 dan PPLG 2, sementara jika memilih tingkat XI dan XII maka untuk rombel hanya akan menampilkan RPL 1 dan RPL 2.
6. Di halaman detail data akan ditampilkan secara lengkap. Di dalam halaman detail juga terdapat dua tombol button, button edit akan mengambil value dari nisn, sementara button kembali akan kembali ke halaman /data-siswa.
7. Di halaman edit data akan ditampilkan data sebelumnya, dan hanya bisa tingkat,
rombel, tgl_masuk dan terdaftar. Untuk tingkat dan rombel sudah diatur sama seperti fitur pada no ke 2. Di halaman edit data juga terdapat dua tombol button, button update berguna saat data berhasil di edit dan akan menampilkan flash saat kembali ke halaman /data-siswa secara otomatis. Sementara tombol button kembali akan kembali ke halaman detail.
8. Saat melakukan logout, di terminal vscode terdapat pesan bahwa "Anda telah logout: Admin".
9. (!Note) Di file demo-hasil terutama pada gambar tambah-data-benar.png dan data-siswa-sesudah.png tidak ada flash karena susah untuk menangkap gambar karena flash telah diatur 3 detik, jadi setelah tiga detik flash akan hilang secara otomatis.