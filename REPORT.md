1. #include <iostream>
Header iostream digunakan untuk mengakses fasilitas input dan output standar seperti :
cout -> untuk menampilkan teks ke layar
cin  -> untuk menerima input dari keyboard

2. #include <string>
Header string dipakai agar kita bisa menggunakan tipe data string untuk menyimpan teks (karakter lebih dari satu kata)

Karena input nama bisa mengandung spasi seperti "Budi Ani", kita butuh tipe string agar bisa menampung kalimat lengkap

3. using namespace std;
Kode ini digunakan agar kita tidak perlu menulis std::cout, std::string, dan std::getline

4. int main() { ... }
Bagian ini adalah fungsi utama yang pertama kali dijalankan saat program dimulai

5. string nama;
Mendeklarasikan variabel bernama nama dengan tipe string untuk menyimpan inputan nama dari user

6. Menampilkan pesan ke user
cout << "Silahkan inputkan nama Anda: ";
Perintah ini mencetak teks ke layar sebagai instruksi agar user menginputkan nama

7. Mengambil input dengan getline()
getline(cin, nama);

8. Menampilkan hasil output
cout << "Hello " << nama << endl;

contoh output :
Hello Budi Ani

9. return 0;
Mengembalikan nilai 0 ke sistem operasi sebagai tanda bahwa program berjalan dengan normal tanpa error

