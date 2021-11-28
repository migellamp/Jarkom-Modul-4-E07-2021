# Jarkom-Modul-4-E07-2021
Laporan Resmi Jaringan Komputer Modul 4 - E07

Anggota Kelompok:

- M Fikri Sunandar 05111940000135

- Migel Aulia Mandiri Putra 05111940000194

- Rizaldi Nur Rahman N 05111940000201


## Topologi
![alt text](https://github.com/migellamp/Jarkom-Modul-4-E07-2021/blob/main/images/topologi.jpg) <br />

## Perhitungan VLSM
Menentukan jumlah subnet dan pembagiannya dari topologi diatas
![alt text](https://github.com/migellamp/Jarkom-Modul-4-E07-2021/blob/main/images/subnet.jpg) <br />

## A. Metode VLSM
Langkah 1 - Tentukan jumlah alamat IP yang dibutuhkan oleh tiap subnet dan lakukan labelling netmask berdasarkan jumlah IP yang dibutuhkan.
| Subnet | Kebutuhan IP | Length |
| :---   |    :---:     |  ---:  |
|   A1   |    701    |  /22  |
|   A2   |    1001    |  /22  |
|   A3   |    2    |  /30  |
|   A4   |    2    |  /30  |
|   A5   |    101    |  /25  |
|   A6   |    2021   |  /21  |
|   A7   |    521    |  /22  |
|   A8   |    2   |  /30  |
|   A9   |    502   |  /23  |
|   A10   |    13    |  /28  |
|   A11  |   2   |  /30  |
|   A12   |    252    |  /24  |
|   A13   |    721    |  /22  |
|   Total  |    5841    |  /19 |

Langkah 2 - Diurutkan dengan Length Terpendek
| Subnet | Kebutuhan IP | Length |
| :---   |    :---:     |  ---:  |
|   A6   |    2021    |  /21  |
|   A1   |    701    |  /22  |
|   A2   |    1001    |  /22  |
|   A7   |    521    |  /22  |
|   A13   |    721    |  /2  |
|   A9  |    502   |  /23  |
|   A12   |    252    |  /24  |
|   A5  |    101   |  /25  |
|   A10   |    13   |  /28  |
|   A3   |    2    |  /30  |
|   A4  |   2   |  /30  |
|   A8   |    2    |  /30  |
|   A11   |    2    |  /30  |
|   Total  |    5841    |  /19 |

Langkah 3 - Lakukan subnetting dengan menggunakan pohon tersebut untuk pembagian IP sesuai dengan kebutuhan masing-masing subnet yang ada.
![alt text](https://github.com/migellamp/Jarkom-Modul-4-E07-2021/blob/main/images/tree.jpg) <br />
