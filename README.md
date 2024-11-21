# Praktikum-6

# Program Daftar Nilai Mahasiswa
Program ini digunakan untuk mengelola data mahasiswa, menghitung nilai akhir, dan menampilkan daftar mahasiswa dalam format tabel. berikut perintah programnya :
![image](https://github.com/user-attachments/assets/155cf71e-cfde-4891-9019-c14bc04e9415)

## Fungsi `hitung_nilai_akhir`

### Tujuan

Menghitung nilai akhir mahasiswa berdasarkan nilai tugas, UTS, dan UAS.

### Parameter

- **nilai_tugas**: Nilai tugas mahasiswa (float).
- **nilai_uts**: Nilai UTS mahasiswa (float).
- **nilai_uas**: Nilai UAS mahasiswa (float).

### Rumus

Nilai akhir dihitung dengan rumus:
Akhir = (Tugas * 0.3) + (UTS * 0.35) + (UAS * 0.35)

### Return

Mengembalikan nilai akhir yang telah dihitung (float).

## Inisialisasi Data

- data_mahasiswa : Menyimpan data mahasiswa dengan NIM sebagai kunci dan informasi mahasiswa (nama, nilai tugas, UTS, UAS, dan nilai akhir) sebagai nilai.

## Input Data Mahasiswa

Menggunakan while True untuk membuat loop yang terus berulang hingga pengguna memilih untuk berhenti.
Program meminta pengguna untuk memasukkan data mahasiswa dalam format berikut:
1. **Nama**: Nama lengkap mahasiswa.
2. **NIM**: Nomor Induk Mahasiswa.
3. **Nilai Tugas**: Nilai yang diperoleh dari tugas.
4. **Nilai UTS**: Nilai yang diperoleh dari Ujian Tengah Semester.
5. **Nilai UAS**: Nilai yang diperoleh dari Ujian Akhir Semester.

Menggunakan fungsi hitung_nilai_akhir untuk menghitung nilai akhir.

## Menyimpan Data

Menyimpan data mahasiswa beserta nilai akhirnya ke dalam dictionary data_mahasiswa dengan NIM sebagai kuncinya.

## Menanyakan Tambah Data

Menanyakan kepada pengguna apakah ingin menambahkan data lagi. jika pengguna ingin berhenti, maka loop akan berakhir.

## Menampilkan Daftar Mahasiswa

Setelah pengguna memilih untuk tidak menambah data lagi, program menampilkan daftar semua mahasiswa yang telah dimasukkan dalam format tabel. Tabel mencakup:
- **No**: Nomor urut mahasiswa.
- **Nama**: Nama lengkap mahasiswa.
- **NIM**: Nomor Induk Mahasiswa.
- **Tugas**: Nilai tugas mahasiswa.
- **UTS**: Nilai Ujian Tengah Semester.
- **UAS**: Nilai Ujian Akhir Semester.
- **Akhir**: Nilai akhir yang telah dihitung.

### Contoh Output

![image](https://github.com/user-attachments/assets/6fd643dd-0f20-472b-8a2b-3393acb2fd5c)

### Flowchart

![Gambar WhatsApp 2024-11-21 pukul 22 35 39_2ae88f45](https://github.com/user-attachments/assets/e99065ad-cf76-4b56-bb19-8c22aa44e099)

