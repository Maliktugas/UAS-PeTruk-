HEADER
#include <iostream>

using namespace std;

// Implementasi fungsi untuk memasukkan data kambing
void inputDataKambing(double &berat, double &tinggi, double &panjang) {
    cout << "Masukkan berat kambing (kg): ";
    cin >> berat;

    cout << "Masukkan tinggi kambing (cm): ";
    cin >> tinggi;

    cout << "Masukkan panjang kambing (cm): ";
    cin >> panjang;
}

// Implementasi fungsi untuk menampilkan data kambing
void tampilkanDataKambing(double berat, double tinggi, double panjang) {
    cout << "Berat: " << berat << " kg\n";
    cout << "Tinggi: " << tinggi << " cm\n";
    cout << "Panjang: " << panjang << " cm\n";
}
