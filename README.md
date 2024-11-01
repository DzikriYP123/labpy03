# TUGAS PRAKTIKUM 3

Nama : Dzikri Yanuar Pamungkas

Nim  : 352311124

Kelas  : IE.23.C12

# LATIHAN 1

intruksi perintah : 

1. Tampilkan nilai n bilangan acak yang lebih kecil dari 0.5
2. nilai n diisi saat run time
3. menggunakan while atau for
4. menggunakan fungsi random


## Screenshoot Hasil Program yang dibuat

![ss latihan 1](https://github.com/user-attachments/assets/be2f565a-3fb6-49d6-a4e6-24f1fa9daf3a)


## Algoritma dan penjelasan

1. pertama kita buat program terlebih dahulu menggunakan Idle
2. saat membuat program, yang pertama kita buat sistem input terlebih dahulu agar kita bisa menginput suatu bilangan saat di runtime dengan rumus n = int(input("Masukkan jumlah bilangan acak yang ingin ditampilkan: "))
3. selanjutnya kita nisialisasi variabel untuk menghitung jumlah bilangan yang telah ditampilkan dengan rumus count = 0
4. selanjutnya kita akan Menggunakan while untuk terus menghasilkan bilangan acak sampai mencapai n, dengan rumus while count < n:
5. selanjutya kita akan menghasilkan bilangan acak dengan a = random()
6. selanjutnya Memeriksa apakah bilangan acak kurang dari 0.5, rumus:
    if a < 0.5:
        count += 1  # Menambah hitungan bilangan yang ditampilkan
        print(f"Data ke : {count} => {a}")  # Menampilkan bilangan acak dengan format yang diinginkan

7. selesai

# LATIHAN 2

Intruksi : Buat program untuk menampilkan bilangan terbesar dari n buah data yang diinputkan.
Masukkan angka 0 untuk berhenti.

## Screenshot Hasil Dari Program yang dibuat

![ss latihan 2](https://github.com/user-attachments/assets/b88a48cf-f574-4bcb-a170-65fa2b471d7b)

## Algoritma dan penjelasan

1. pertama kita buat program terlebih dahulu menggunakan Idle
2. kita buat Inisialisasi variabel untuk menyimpan bilangan terbesar dengan rumus max_number = None
3. selanjutnya kita buat while true : Mengambil input dari pengguna, Memeriksa apakah pengguna memasukkan 0, Memperbarui bilangan terbesar jika diperlukan
4. selanjutnya kita akan menamplkan bilangan terbesarnya dengan rumus,
        if max_number is not None:
            print("Bilangan terbesar adalah:", max_number)
        else:
          print("Tidak ada angka yang dimasukkan.")
5. selesai


# PROGRAM 1
Intruksi : Seorang pengusaha menginvestasikan uangnya untuk memulai usahanya dengan
modal awal 100 juta, pada bulan pertama dan kedua belum mendapatkan laba. pada
bulan ketiga baru mulai mendapatkan laba sebesar 1% dan pada bulan ke 5,
pendapatan meningkat 5%, selanjutnya pada bulan ke 8 mengalami penurunan
keuntungan sebesar 2%, sehingga laba menjadi 3%. Hitung total keuntungan selama 8
bulan berjalan usahanya.

## Screenshot Hasil Dari Program yang dibuat

![ss program 1](https://github.com/user-attachments/assets/e56cb3da-31d2-418f-b500-bd49d5cf4d54)

## Algoritma dan penjelasan

1. pertama kita buat program terlebih dahulu menggunakan Idle
2. buat print modal awal, rumus :modal_awal = 100_000_000
3. kita buat nisialisasi list untuk menyimpan laba setiap bulan dengan menggunakan statement for, in, If, elif
4. menghitung total laba dengan rumus SUM
5. menampilkan hasil dengan rumus For 1 in
6. selesai
   















