# Definisi Variabel dalam C++

- cout: cout adalah objek dari kelas ostream. Digunakan untuk menampilkan output pada layar.
- cin: cin adalah objek dari kelas istream. Digunakan untuk mengambil input dari keyboard.
- printf: printf adalah fungsi yang digunakan untuk menampilkan output pada layar.
- endl: endl adalah manipulator yang digunakan untuk memasukkan baris baru pada output.
- return: return adalah kata kunci yang digunakan untuk mengembalikan nilai dari sebuah fungsi.

<br>

# Jenis Data dalam C++

- string: String adalah tipe data yang digunakan untuk merepresentasikan teks atau urutan karakter (Nama, Kalimat, dst.)
- int: int adalah jenis data yang digunakan untuk menyimpan nilai integer. (1, 2, 3, dst.)
- float: float adalah jenis data yang digunakan untuk menyimpan nilai floating point. (kurang presisi dibandingkan double)
- double: double adalah jenis data yang digunakan untuk menyimpan nilai floating point. (lebih presisi dibandingkan float)
- char: char adalah jenis data yang digunakan untuk menyimpan nilai karakter. (a, b, c, dst.)
- bool: bool adalah jenis data yang digunakan untuk menyimpan nilai boolean. (benar atau salah)
- void: void adalah jenis data yang digunakan untuk mendefinisikan fungsi yang tidak mengembalikan nilai apapun.
<br>

# Contoh Program C++

Output: Hello World!

```cpp
#include <iostream>
using namespace std;

int main()
{
    cout << "Hello World!";
    return 0;
}
```

Output: Masukkan sebuah angka dan tampilkan

```cpp
#include <iostream>
using namespace std;

int main()
{
    int num;
    cout << "Masukkan sebuah angka: ";
    cin >> num;
    cout << "Anda memasukkan " << num;
    return 0;
}
```

Output: Masukkan dua angka dan tampilkan hasil penjumlahannya

```cpp
#include <iostream>
using namespace std;

int main()
{
    int num1, num2, sum;
    cout << "Masukkan dua angka: ";
    cin >> num1 >> num2;
    sum = num1 + num2;
    cout << "Hasil penjumlahan = " << sum;
    return 0;
}
```

Output: Output ketika pengguna memasukkan "Y" atau "y"

```cpp
#include <iostream>

using namespace std;

int main(){
    char answer;
    cout << "Apakah Anda menyukai C++? (y/n): ";
    cin >> answer;
    if(answer == 'y' || answer == 'Y'){
        cout << "Anda menyukai C++" << endl;
        return 0;
    }else{
        cout << "Anda tidak menyukai C++" << endl;
        return 0;
    }
}
```
 > Catatan: Operator "||" digunakan untuk memeriksa apakah salah satu dari kondisi tersebut benar.

<br>

# Kode Keluaran Umum dalam C++

0: Eksekusi berhasil <br>
1: Eksekusi gagal <br>
2: Syntax tidak valid
<br>dst...

# Kesalahan Umum dalam C++

> Kasus: Kode keluaran 2 <br>
Solusi: Periksa sintaks dari program, pastikan setiap baris diakhiri dengan ";" dan setiap pernyataan ditulis dengan benar.

> Kasus: Izin ditolak <br>
Solusi: Pastikan tidak ada program lain dengan nama yang sama di direktori yang sama yang sedang berjalan. Jika ada,
