# Rumus Logic untuk Mengganti Setiap Awal Kata dengan Huruf Kapital di Excel

## Deskripsi

Rumus ini digunakan untuk mengganti setiap awal kata dengan huruf kapital dalam teks yang terdapat di sel Excel.

## Rumus
```=LEFT(A1,1)&UPPER(MID(A1,2,LEN(A1)-1))

Misalkan kita memiliki teks "belajar excel" di sel A1. Untuk mengubah setiap awal kata dengan huruf kapital, kita dapat menggunakan rumus berikut:

```=LEFT(A1,1)&UPPER(MID(A1,2,LEN(A1)-1))


## Petunjuk Cara Penggunaan

Untuk menggunakan rumus tersebut, ikuti langkah-langkah berikut:

1. Masukkan teks yang ingin diubah ke dalam sel Excel.
2. Masukkan rumus tersebut ke dalam sel lain.
3. Tekan **Enter**.

## Hasil

Hasilnya adalah teks dengan setiap awal kata diganti dengan huruf kapital.

## Tips

* Untuk mengganti semua kata dengan huruf kapital, kita dapat menggunakan rumus berikut:

```=UPPER(A1)


* Untuk mengganti semua kata dengan huruf kecil, kita dapat menggunakan rumus berikut:

```=LOWER(A1)

