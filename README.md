# praktikum4


##latihan1.cpp:Mencari Angka Terbesar dari Sejumlah Bilangan yang Diinputkan Sebelum Diinputkan 0

**Alur Algoritma**
1. Mendeklarasikan  variabel **int n=0** dan **int max=0**
2. Membaca input dari keyboard cin >> n
3. Bandingkan **n > max** proses diulangi selama  nilai n tidak berjumlah 0
4. Cetak **max**

**flowchart Program**
![ing](https://raw.githubusercontent.com/SeptiZahrotunNisa/praktikum4/master/latihan1.cpp/flowchartt1.png)

**Code Program**
```c++
#include<iostream>

using namespace std;

int main()
{
    int n=0;
    int max=0;


    do {
        cout << "masukan bilangan (masukan 0 untuk berhenti : ";
        cin >> n;

        if (n > max)
            max= n;

    }while (n!= 0);
    cout << "bilangan terbesar adalah" << max;

}
```
**Hasil**
![ing](https://raw.githubusercontent.com/SeptiZahrotunNisa/praktikum4/master/latihan1.cpp/hasil1.png)

## latihan2.cpp: Program Struk Pembelanjaan

**Alur Algoritma**
1. Mendeklarasikan variabel penjelasan (x,y,barang,harga,jumlah barang,diskon,banyak barang,total,nilai N dan total belanjaan).
2. Membaca nilai **N** untuk menginput banyaknya barang dan di deskripsikan lagi dengan (x,y) untuk variabel pembanding
3. Membandingkan nilai variabel **x** dan **y**  dengan hasil x lebih kecil atau sama dengan y (x<=y) mengunakan while untuk mengulangi hasil semua intruksi yang diinputkan
4. Membaca atau cerak variabel **a** untuk barang ke-
5. Membaca atau cetak variabel **jumlah beli** dan **harga** untuk menginturksikan input harga dan barang
6. input program sesuai perintah
	```harga barang = harga*jumlah_beli;
	   total=total + harga barang;
	   total_beli += jumlah_beli;

untuk bisa menjumlahkan hasil
7. Kemudian deskripsikan variabel diskon yang mau kita taruh di program ini dengan intruksi (if-then-else)
8. Jika selesai intruksikan kembali (bayar=total-diskon)
9. Cetak semua hasil perintah diatas (jumlah barang, total harga belanja, diskon yang diberikan, harga yang harus dibayar)

**flowchart Program**
![ing](https://raw.githubusercontent.com/SeptiZahrotunNisa/praktikum4/master/latihan2.cpp/flowchart2.png)

**Code Program**
```c++
#include<iostream>
using namespace std;
int main()
{
    cout<< "Tugas Praktikum4 Soal2"<< "Program Menghitung Total Belanja"<< endl;
    cout<< "===========================================================" <<endl;
    int jumlah_beli =0,total_beli=0,x,y,a;
    long int
    harga=0,harga_barang=0,total=0,bayar=0,diskon;
    cout<< "Masukan Jumlah Barang (N) :"; cin>>y;
    x=1;

    while(x<=y)
    {
        cout<< "Barang Ke-"; cin>>a;
        cout<< "Masukan Banyaknya Barang; "; cin>>jumlah_beli;
        cout<< "Masukan Harga Barang:Rp"; cin>>harga;
        harga_barang = harga*jumlah_beli;
        total=total + harga_barang;
        total_beli += jumlah_beli;
        x++;
    }
```
**Hasil**
![ing](https://raw.githubusercontent.com/SeptiZahrotunNisa/praktikum4/master/latihan2.cpp/hasil2.png)
