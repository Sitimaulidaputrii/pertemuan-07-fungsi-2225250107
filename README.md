# Pertemuan 7 Fungsi Python

Nama: Siti Maulida Putri Irawan
NIM: 2225250107
Kelas: 3A

## Tujuan

Membuat program utilitas matematika dengan beberapa fungsi untuk menghitung luas bangun datar, jumlah bilangan, dan faktorial. Program ini juga melatih penggunaan parameter, return, serta percabangan untuk menjalankan operasi sesuai pilihan pengguna.

## Cara Menjalankan

Program praktik dapat dijalankan melalui Terminal VS Code dengan perintah:
```bash
python praktik/utilitas_matematika.py
```

untuk menjalankan program latihan:
```bash
python latihan/01_salam.py
```

untuk menjalankan yang lainnya, gunakan perintah sesuai dengan nama berkasnya.

## Struktur Fungsi

| Nama Fungsi | Parameter | Kegunaan |
| --- | --- | --- |
| luas_persegi_panjang | p dan l | Menghitung luas persegi panjang dan mengembalikan hasilnya menggunakan return. |
| luas_segitiga | a dan t | Menghitung luas segitiga dan mengembalikan hasilnya menggunakan return. |
| jumlah_n | n | menjumlahkan bilangan dari 1 sampai n menggunakan perulangan, kemudian mengembalikan hasilnya. |
| faktorial | n | Menghitung faktorial suatu bilangan menggunakan perulangan, kemudian mengembalikan hasilnya. |
| tampilkan_menu | - | Menampilkan empat pilihan operasi matematika kepada pengguna. |

## Hasil Pengujian

| Pengujian | Input | Hasil yang Diharapkan | Hasil Aktual | Status |
| --- | --- | --- | --- | --- |
| Luas persegi panjang | p=8, l=5 | 40 | 40.0 | Berhasil |
| Luas segitiga | a=10, t=6 | 30 | 30.0 | Berhasil |
| Jumlah bilangan | n=10 | 55 | 55 | Berhasil |
| Faktorial | n=5 | 120 | 120 | Berhasil |
| Faktorial | n=0 | 1 | 1 | Berhasil |

## Refleksi

Pada pertemuan 7, saya belajar memahami penggunaan fungsi dalam Python, terutama cara menggunakan parameter dan return. Saya memahami bahwa fungsi dapat digunakan untuk memisahkan setiap perhitungan agar program lebih teratur. Salah satu hal yang saya pelajari adalah perbedaan antara return dan print. return digunakan untuk memberikan hasil perhitungan agar dapat digunakan kembali oleh bagian program lain, sedangkan print digunakan untuk menampilkan hasil ke layar. Dari praktik ini, saya jadi lebih memahami cara membuat program yang setiap bagiannya memiliki tugas masing-masing.

## Sumber
Python Software Foundation. The Python Tutorial
Materi pertemuan 07 Algoritma dan Pemrograman: Fungsi, Parameter, Return Value, dan Scope dalam Python di VS Code dan Pengumpulan melalui GitHub