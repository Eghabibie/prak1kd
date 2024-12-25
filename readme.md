README

Enkripsi dan Dekripsi Teks dengan Tkinter

Aplikasi ini adalah implementasi sederhana dari algoritma Caesar Cipher menggunakan Python dan pustaka Tkinter untuk antarmuka grafis. Aplikasi ini memungkinkan pengguna untuk:

Mengenkripsi teks (Plain Text) menjadi teks terenkripsi (Chiper Text).

Mendekripsi teks terenkripsi (Chiper Text) kembali menjadi teks asli (Plain Text).

Fitur

Input teks biasa (Plain Text).

Input nilai shift (1-25) untuk menggeser huruf dalam algoritma Caesar Cipher.

Output teks terenkripsi (Chiper Text).

Tombol untuk mengenkripsi dan mendekripsi teks.

Validasi input untuk memastikan nilai shift valid.

Antarmuka grafis sederhana dengan Tkinter.

Cara Menjalankan

Pastikan Anda memiliki Python 3.x di komputer Anda.

Simpan kode ke dalam file bernama enkripsi_tkinter.py.

Jalankan file dengan perintah berikut di terminal atau command prompt:

python enkripsi_tkinter.py

Aplikasi akan muncul dengan antarmuka grafis.

Penggunaan

Masukkan teks biasa (Plain Text) ke dalam kotak input pertama.

Masukkan nilai shift (1-25) ke dalam kotak input kedua.

Klik tombol "Encrypt" untuk mengenkripsi teks atau "Decrypt" untuk mendekripsi teks.

Hasil akan ditampilkan pada kotak input yang sesuai.

Struktur Kode

Fungsi enkripsi:

Mengenkripsi teks menggunakan algoritma Caesar Cipher.

Fungsi dekripsi:

Mendekripsi teks menggunakan algoritma Caesar Cipher.

Fungsi encrypt_text:

Mengambil input dari pengguna, memvalidasi nilai shift, dan menghasilkan teks terenkripsi.

Fungsi decrypt_text:

Mengambil input dari pengguna, memvalidasi nilai shift, dan menghasilkan teks asli.

Antarmuka Tkinter:

Menggunakan widget Tkinter seperti Label, Entry, dan Button untuk membuat antarmuka.

Validasi Input

Shift harus berupa bilangan bulat antara 1 dan 25.

Jika input tidak valid, pesan error akan ditampilkan menggunakan kotak dialog.

Tampilan

Latar belakang biru muda (#add8e6).

Teks label berwarna navy dengan font tebal.

Tombol berwarna navy dengan teks putih.

Persyaratan

Python 3.x

Catatan

Algoritma Caesar Cipher hanya memindahkan huruf alfabet dan tidak memengaruhi karakter non-alfabet.

Pastikan nilai shift berada dalam rentang 1 hingga 25 untuk hasil yang benar.

