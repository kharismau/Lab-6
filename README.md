# Program Daftar Nilai Mahasiswa
Program ini bertujuan untuk mengelola data nilai mahasiswa dengan tampilan perintah sebagai berikut : 

![Screenshot 2024-12-04 201943](https://github.com/user-attachments/assets/0a91b1b3-4079-4417-b40e-b184cdae0c98)

![Screenshot 2024-12-04 201957](https://github.com/user-attachments/assets/4b32767a-fb3d-4e9d-bf8d-ce200f5c0698)

![Screenshot 2024-12-04 202011](https://github.com/user-attachments/assets/dabcc080-61cf-4f8a-9c3d-bd382034fb1d)

## Fungsi Utama

1. **Tambah Data**  
   Menambahkan data mahasiswa berupa nama dan nilai.

2. **Tampilkan Data**  
   Menampilkan semua data mahasiswa dalam bentuk daftar.

3. **Hapus Data**  
   Menghapus data mahasiswa berdasarkan nama.

4. **Ubah Data**  
   Mengubah nilai mahasiswa berdasarkan nama.

5. **Keluar**  
   Mengakhiri program.

## Struktur Data
Data mahasiswa disimpan dalam dictionary data_mahasiswa, di mana Nama adalah kunci, dan nilai lainnya (nama, tugas, UTS, UAS) disimpan dalam dictionary sebagai nilai.

### Dictionary `data_mahasiswa`
- **Kunci**: Nama mahasiswa.
- **Nilai**: Dictionary yang berisi:
  - `nama`: Nama mahasiswa.
  - `nilai_tugas`: Nilai tugas.
  - `nilai_uts`: Nilai UTS.
  - `nilai_uas`: Nilai UAS.

## Tampilan Program

![Screenshot 2024-12-04 201918](https://github.com/user-attachments/assets/5911c9fc-a676-42ad-b7b5-a92299ca5945)

![Screenshot 2024-12-04 201928](https://github.com/user-attachments/assets/59f341b4-b64a-48b1-bdbc-b2fafc0b95ac)


## Alur Program

1. Start : Titik awal program
2. Program akan menampilkan menu pilihan kepada pengguna:
   - Tambah data : Dengan memilih nomer 1
   - Tampilkan data : Dengan memilih nomer 2
   - Hapus data : Dengan memilih nomer 3
   - Ubah data : Dengan memilih nomer 4
   - Keluar : Dengan memilih nomer 5
3. Pengguna memilih opsi sesuai kebutuhan dengan memasukkan angka (1-5).
4. Program akan menjalankan fungsi berdasarkan pilihan pengguna
5. Meminta input tambahan (jika diperlukan).
6. Menampilkan hasil sesuai fungsi yang dipilih.
7. Program akan terus berjalan hingga pengguna memilih opsi "Keluar".
8. Jika pengguna memilih 5 (Keluar):
9. Tampilkan pesan bahwa program selesai dan keluar dari loop.
10. End: Titik akhir program.

## Flowchart

![Screenshot 2024-12-04 195321](https://github.com/user-attachments/assets/4fb8e3b1-6f5a-4abd-996a-d214afcc7b9e)
