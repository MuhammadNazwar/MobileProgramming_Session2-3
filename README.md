# Mobile Application Development
Repository ini merupakan dokumentasi hasil pengerjaan praktikum **Pengembangan Aplikasi Mobile** yang mencakup implementasi teknologi WebView menggunakan dua pendekatan berbeda, yaitu MIT App Inventor dan React Native dengan arsitektur Fabric.

## Daftar Isi
- [Session 2 - Prototype WebView MIT App Inventor](#session-2---prototype-webview-mit-app-inventor)
- [Session 3 - WebView Implementation React Native Fabric](#session-3---webview-implementation-react-native-fabric)

---

# Session 2 - Prototype WebView MIT App Inventor
## 1. Identitas Mahasiswa
**Kelompok AndTop**
1. Rois Abdul Fatah - 41155050240006
2. Yovi Nurwijaya Kusumah - 41155050240025
3. Muhammad Nazwar Abdillah Putra - 41155050240029

## 2. Deskripsi Proyek
<p align="justify">
Prototype WebView MIT App Inventor merupakan proyek pengembangan aplikasi mobile sederhana yang memanfaatkan komponen WebView untuk menampilkan halaman website secara langsung di dalam aplikasi Android. Proyek ini dibuat menggunakan MIT App Inventor dengan tujuan memahami dasar pengembangan aplikasi mobile, khususnya penerapan WebView sebagai media untuk mengakses konten website tanpa harus membuka browser secara terpisah.
</p>
<p align="justify">
Aplikasi ini dikembangkan untuk menampilkan website kampus atau website berita teknologi melalui perangkat mobile. Selain itu, aplikasi dilengkapi dengan tombol navigasi seperti Home atau Refresh untuk mempermudah pengguna dalam mengakses dan memuat ulang halaman website. Hasil akhir pengembangan berupa file proyek MIT App Inventor (.aia) dan aplikasi Android (.apk).
</p>

## 3. Fitur Utama
- **WebView:** Menampilkan halaman website secara langsung di dalam aplikasi Android.
- **Navigasi Website:** Mempermudah pengguna dalam mengakses halaman website.
- **Home / Refresh:** Menyediakan navigasi kembali ke halaman utama atau memuat ulang halaman website.
- **Aplikasi Android:** Hasil pengembangan dapat dijalankan pada perangkat Android melalui file APK.

## 4. Teknologi yang Digunakan
| Teknologi | Kegunaan |
|---|---|
| MIT App Inventor | Platform pengembangan aplikasi mobile |
| WebView | Menampilkan halaman website di dalam aplikasi |
| Android | Platform untuk menjalankan aplikasi |
| GitHub | Pengelolaan dan penyimpanan repository |

## 5. Cara Instalasi dan Menjalankan Aplikasi
**A. Menggunakan file proyek (.aia)**
1. Buka website [MIT App Inventor](https://ai2.appinventor.mit.edu/).
2. Login menggunakan akun MIT App Inventor.
3. Pilih menu **Projects**.
4. Pilih **Import project (.aia) from my computer**.
5. Pilih file `UnlaNews.aia`.
6. Setelah berhasil diimpor, proyek dapat dibuka dan dikembangkan melalui MIT App Inventor.

**B. Menggunakan aplikasi (.apk)**
1. Unduh file `UnlaNew.apk` dari repository.
2. Pindahkan file APK ke perangkat Android.
3. Buka file APK dan izinkan instalasi dari sumber yang tidak dikenal apabila diperlukan.
4. Selesaikan proses instalasi.
5. Jalankan aplikasi untuk melihat implementasi WebView.

## 6. Repository
| Nama File | Keterangan |
|---|---|
| `UnlaNews.aia` | File sumber proyek MIT App Inventor |
| `UnlaNew.apk` | File aplikasi Android yang siap diinstal |

## 7. Dokumentasi dan Demo
**Tampilan MIT App Inventor**

<img width="310" height="605" alt="MIT App Inventor" src="https://github.com/user-attachments/assets/495a1367-f071-49eb-9173-f72603107649" />

**Tampilan Aplikasi Mobile**

<img width="331" height="609" alt="Mobile Application" src="https://github.com/user-attachments/assets/0073bb31-1909-44ec-afb7-6151c29967b9" />

---

# Session 3 - WebView Implementation React Native Fabric
## 1. Identitas Mahasiswa
**Muhammad Nazwar Abdillah Putra**
41155050240029

## 2. Deskripsi Proyek
<p align="justify">
WebView Implementation React Native Fabric merupakan proyek implementasi komponen WebView pada aplikasi mobile berbasis React Native dengan memanfaatkan arsitektur Fabric atau New Architecture. Pengembangan aplikasi menggunakan package react-native-webview untuk menampilkan halaman website eksternal secara langsung di dalam aplikasi mobile.
</p>
<p align="justify">
Proyek ini bertujuan untuk memahami penerapan WebView menggunakan React Native modern serta mengenal arsitektur Fabric yang merupakan bagian dari New Architecture React Native. Implementasi ini juga menjadi pengembangan dari proyek sebelumnya yang menggunakan MIT App Inventor, dengan pendekatan pengembangan aplikasi berbasis kode menggunakan React Native dan TypeScript.
</p>

## 3. Fitur Utama
- **WebView Integration:** Mengintegrasikan komponen WebView ke dalam aplikasi React Native.
- **Website Rendering:** Menampilkan halaman website eksternal secara langsung melalui aplikasi mobile.
- **React Native Fabric:** Menggunakan arsitektur Fabric atau New Architecture sebagai pendekatan rendering aplikasi.
- **Cross-Platform Framework:** Memanfaatkan React Native untuk pengembangan aplikasi mobile.

## 4. Teknologi yang Digunakan
| Teknologi | Kegunaan |
|---|---|
| React Native | Framework pengembangan aplikasi mobile |
| TypeScript | Bahasa pemrograman untuk penulisan kode aplikasi |
| react-native-webview | Package untuk menampilkan halaman website |
| Fabric | Arsitektur rendering pada React Native New Architecture |
| Android | Platform untuk menjalankan aplikasi |

## 5. Cara Instalasi dan Menjalankan Aplikasi
**Persyaratan:**
- Node.js dan npm.
- React Native development environment.
- Android Studio dan Android SDK.
- Emulator Android atau perangkat Android.

**Langkah-langkah:**
1. Clone repository dari GitHub.
   ```bash
   git clone <URL_REPOSITORY>
   ```
2. Masuk ke direktori proyek.
   ```bash
   cd <NAMA_FOLDER_PROYEK>
   ```
3. Instal seluruh dependency proyek.
   ```bash
   npm install
   ```
4. Pastikan package `react-native-webview` sudah terpasang.
   ```bash
   npm install react-native-webview
   ```
5. Pastikan konfigurasi New Architecture atau Fabric telah diaktifkan pada proyek React Native.
6. Jalankan aplikasi pada emulator atau perangkat Android.
   ```bash
   npx react-native run-android
   ```
7. Setelah proses build selesai, aplikasi akan dijalankan dan menampilkan halaman website melalui komponen WebView.

## 6. Repository
| Nama File | Keterangan |
|---|---|
| `App.tsx` | File utama yang berisi implementasi komponen WebView menggunakan React Native dan TypeScript |

## 7. Dokumentasi dan Demo
**Tampilan Aplikasi Mobile**

<img width="312" height="623" alt="React Native WebView" src="https://github.com/user-attachments/assets/64ffdc42-d014-403f-8768-6d8793837623" />

---

## Kesimpulan
<p align="justify">
Melalui kedua sesi praktikum ini, implementasi WebView dipelajari menggunakan dua pendekatan pengembangan aplikasi mobile yang berbeda. Pada Session 2, pengembangan dilakukan menggunakan MIT App Inventor dengan pendekatan visual programming, sedangkan pada Session 3, pengembangan dilakukan menggunakan React Native dengan pendekatan pemrograman berbasis kode dan arsitektur Fabric.
</p>
<p align="justify">
Kedua proyek ini memberikan pemahaman mengenai penggunaan komponen WebView untuk mengintegrasikan halaman website ke dalam aplikasi mobile, sekaligus memperkenalkan berbagai teknologi dan pendekatan dalam pengembangan aplikasi Android modern.
</p>
