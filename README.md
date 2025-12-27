# SafeMemo (Python)
SafeMemo adalah program sederhana yang dibuat untuk mengamankan catatan pribadi menggunakan enkripsi simetris AES. Catatan dienkripsi sebelum disimpan ke dalam file sehingga tidak dapat dibaca langsung. Kunci enkripsi dihasilkan dari password pengguna menggunakan PBKDF2 agar lebih aman dan tidak disimpan langsung di dalam program.


## Daftar Isi
- Fitur
- Arsitektur Keamanan
- Cara Download & Install
- Cara Menjalankan Program
- Struktur Project
- Standar Keamanan

## Fitur

### Fitur Keamanan
- AES Encryption (Fernet)
- PBKDF2 Key Derivation (100.000 iterasi)
- Kunci Dinamis berbasis password
- Salt acak untuk setiap enkripsi
- Proteksi dari brute-force sederhana

### Mode Penggunaan
- Enkripsi catatan teks
- Dekripsi catatan terenkripsi
- Penyimpanan file `.enc`

