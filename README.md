# 🚗 **Sistem Manajemen Kendaraan di Bengkel** 🏍️

## 📉 Deskripsi
Sistem ini dibuat menggunakan **Java** dengan menerapkan konsep **Object-Oriented Programming (OOP)**. Program ini memungkinkan pengelolaan kendaraan dalam sebuah bengkel, mencatat informasi kendaraan, serta melakukan servis dengan fitur **method overloading dan overriding**.

## 🔄 Fitur Utama
✅ **Inheritance**: `Mobil` dan `Motor` merupakan subclass dari `Kendaraan`.
✅ **Method Overriding**: Setiap kendaraan memiliki cara sendiri untuk menampilkan informasi.
✅ **Method Overloading**: Servis kendaraan bisa dilakukan dengan atau tanpa parameter jenis servis.
✅ **Encapsulation**: Data kendaraan tersimpan dalam atribut privat.

---

## 🔨 **Struktur Kelas**

### 👉 **1. Class Kendaraan (Super Class)**
- Menyimpan informasi dasar kendaraan: **nama pemilik, nomor plat, jenis kendaraan**.
- Memiliki method `tampilkanInfo()` untuk menampilkan data kendaraan.
- Memiliki **overloaded method** `serviceKendaraan()`.

### 👉 **2. Class Mobil (Subclass dari Kendaraan)**
- Menambahkan atribut **jumlah pintu**.
- Meng-override `tampilkanInfo()` untuk menampilkan informasi tambahan.

### 👉 **3. Class Motor (Subclass dari Kendaraan)**
- Menambahkan atribut **memiliki box penyimpanan**.
- Meng-override `tampilkanInfo()` untuk menampilkan informasi tambahan.

### 👉 **4. Main Class**
- Membuat objek `Mobil` dan `Motor` dengan data masing-masing.
- Memanggil method `tampilkanInfo()`.
- Menjalankan method `serviceKendaraan()` untuk menunjukkan overloading.

---

## 📷 **Contoh Output**
```bash
=== Informasi Mobil ===
Nama Pemilik  : Andi
Nomor Plat    : B 1234 XYZ
Jenis Kendaraan : Mobil
Jumlah Pintu  : 4

=== Informasi Motor ===
Nama Pemilik  : Budi
Nomor Plat    : D 5678 ABC
Jenis Kendaraan : Motor
Memiliki Box  : Ya

Servis kendaraan sedang dilakukan.
Servis jenis Tune Up sedang dilakukan.
```

---

## 🚀 **Cara Menjalankan Program**  

1️⃣ **Clone Repository Ini**  
```sh
git clone https://github.com/username/repository.git
cd repository
```

2️⃣ **Kompilasi Program**  
```sh
javac Main.java
```

3️⃣ **Jalankan Program**  
```sh
java Main
```

---

## 🎡 **Teknologi yang Digunakan**  
- **Java** (JDK 8 ke atas)  
- **OOP Principles**  

## 💪 **Kontribusi**  
Jika ingin menambahkan fitur baru, silakan buat **pull request** atau **laporkan issue** pada repository ini.  

💡 **Selamat Coding! 🚀**
