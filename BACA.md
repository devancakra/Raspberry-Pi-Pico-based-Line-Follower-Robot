[![Open Source Love](https://badges.frapsoft.com/os/v1/open-source.svg?style=flat)](https://github.com/ellerbrock/open-source-badges/)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg?logo=github&color=%23F7DF1E)](https://opensource.org/licenses/MIT)
![GitHub last commit](https://img.shields.io/github/last-commit/devancakra/Smart-Green-House-Berbasis-IoT-Mobile-Apps)
![Project](https://img.shields.io/badge/Project-Raspberry%20Pi%20Pico-light.svg?style=flat&logo=raspberrypi&logoColor=white&color=%23F7DF1E)

# Raspberry-Pi-Pico-based-Line-Follower-Robot
<strong>Proyek Tunggal Robot Pengikut Garis Berbasis Raspberry Pi Pico</strong><br><br>
Mobil robot ini menggunakan sensor inframerah untuk menentukan batas terdalam dari sebuah garis, sehingga mobil robot akan tetap bergerak mengikuti garis yang ada. Dalam prosesnya, sensor ini bekerja berdasarkan prinsip pemantulan cahaya. Led memancarkan cahaya, kemudian cahaya tersebut diterima oleh photodioda.

<br><br>

## Fitur / Kerangka Kerja / Alat
| Media | Deskripsi |
| --- | --- |
| Papan Pengembangan | Raspberry Pi Pico |
| Editor Kode | Thonny IDE |
| Bootloader | MicroPython UF2 |
| Bahasa Pemrograman | MicroPython |
| Pustaka MicroPython | machine & time |
| Aktuator | Gear Motor / Motor DC (x2) |
| Sensor | KR08200: Sensor IR Pelacakan Garis 3 Arah (x1) |
| Saklar | KCD11: Saklar Pengayun (x1) |
| Komponen Lainnya | Kabel mikro usb (x1), Kabel jumper, Baterai Li-ion 4800mAh 3.7V 18650 (x2), Tempat baterai seri 2 slot (x1), Roda robot (x2), Roda kastor (x1), Motor driver L298N (x1), Kerangka robot mobil (x1), DLL |

<br><br>

## Unduh & Instal
1. Thonny IDE

   ```
   https://thonny.org/
   ```
<br>

2. MicroPython UF2

   ```
   https://bit.ly/MicroPython_UF2
   ```
   
<br><br>

## Persyaratan Proyek
<table>
<tr>
<th width="420">Diagram Blok</th>
<th width="420">Diagram Ilustrasi</th>
</tr>
<tr>
<td><img src="https://github.com/devancakra/Raspberry-Pi-Pico-based-Line-Follower-Robot/assets/54527592/2d13dd05-7f81-45cb-9e72-9e8d3ff9a8ef" alt="Block-Diagram"></td>
<td><img src="https://github.com/devancakra/Raspberry-Pi-Pico-based-Line-Follower-Robot/assets/54527592/521bf89b-a76d-4eea-97eb-40c5e3d1d0cf" alt="Pictorial-Diagram"></td>
</tr>
</table>
<table>
<tr>
<th width="840">Pengkabelan</th>
</tr>
<tr>
<td><img src="https://github.com/devancakra/Raspberry-Pi-Pico-based-Line-Follower-Robot/assets/54527592/234b15e2-d3d6-4794-a652-f54707d60a7e" alt="Wiring"></td>
</tr>
</table>

<br><br>

## Pengaturan Bootloader MicroPython
1. ``` Unggah firmware ``` :

   • Tekan dan tahan tombol ``` BOOTSEL ``` yang ada di papan Raspberry Pi Pico sembari menyambungkan ke komputer melalui kabel mikro USB.

   • Setelah Raspberry Pi Pico dikenali oleh komputer (terhubung), maka segera lepaskan tombol ``` BOOTSEL ```.
   
   • Ketika berhasil terhubung, maka sebuah drive baru bernama ``` RPI-RP2 ``` akan terbuka.
   
   • ``` Seret -> Lepaskan ``` atau ``` Salin -> Tempelkan ``` file firmware ``` MicroPython UF2 ``` ke dalam drive ``` RPI-RP2 ```.<br><br>

2. Setelah prosesnya berhasil, maka drive ``` RPI-RP2 ``` akan otomatis tertutup.

<br><br>

## Pengaturan Thonny IDE
1. Buka ``` Thonny IDE ``` terlebih dahulu.<br><br>

2. Klik ``` Tools ``` -> lalu pilih ``` Options... ``` -> klik ``` Interpreter ```, kemudian pengaturannya ubah seperti ini :

   • ``` Interpreter ``` -> ``` MicroPython (Raspberry Pi Pico) ```.

   • ``` Port ``` -> ``` <Try to detect port automatically> ```.<br><br>

3. Jika tampilan berkas belum ada di Thonny IDE, maka silakan anda klik bagian ``` View ``` -> lalu pilih ``` Files ``` untuk menampilkannya.<br><br>

4. Kemudian cari berkas yang bernama ``` rpipico_line_follower.py ``` di komputer Anda -> lalu klik kanan pada berkas tersebut -> pilih ``` Upload to / ```.<br><br>

5. Buka berkas ``` rpipico_line_follower.py ``` yang ada di penyimpanan ``` Raspberry Pi Pico ``` -> lalu klik ``` Run current script (F5) ```.

<br><br>

## Memulai
1. Unduh dan ekstrak repositori ini.<br><br>
   
2. Pastikan anda memiliki komponen elektronik yang diperlukan.<br><br>
   
3. Pastikan komponen anda telah dirancang sesuai dengan diagram.<br><br>
    
4. Jika Anda tidak menerapkan poin 2 dan 3 untuk tujuan pengembangan proyek, tidak masalah, tetapi perlu diketahui bahwa beberapa hal perlu diubah sesuai dengan kebutuhan Anda agar sistem dapat bekerja dengan baik.<br><br>

5. Selamat menikmati [Selesai].

<br><br>

## Sorotan
Segera hadir....

<br><br>

## Penafian
Aplikasi ini dibuat dengan menyertakan sumber-sumber dari pihak ketiga. Pihak ketiga di sini adalah penyedia layanan, yang layanannya berupa pustaka, kerangka kerja, dan lain-lain. Saya ucapkan terima kasih banyak atas layanannya. Telah terbukti sangat membantu dan dapat diimplementasikan.

<br><br>

## LISENSI
LISENSI MIT - Hak Cipta (c) 2023 - Devan C. M. Wijaya, S.Kom

Dengan ini diberikan izin tanpa biaya kepada siapa pun yang mendapatkan salinan perangkat lunak ini dan file dokumentasi terkait perangkat lunak untuk menggunakannya tanpa batasan, termasuk namun tidak terbatas pada hak untuk menggunakan, menyalin, memodifikasi, menggabungkan, mempublikasikan, mendistribusikan, mensublisensikan, dan/atau menjual salinan Perangkat Lunak ini, dan mengizinkan orang yang menerima Perangkat Lunak ini untuk dilengkapi dengan persyaratan berikut:

Pemberitahuan hak cipta di atas dan pemberitahuan izin ini harus menyertai semua salinan atau bagian penting dari Perangkat Lunak.

DALAM HAL APAPUN, PENULIS ATAU PEMEGANG HAK CIPTA DI SINI TETAP MEMILIKI HAK KEPEMILIKAN PENUH. PERANGKAT LUNAK INI DISEDIAKAN SEBAGAIMANA ADANYA, TANPA JAMINAN APAPUN, BAIK TERSURAT MAUPUN TERSIRAT, OLEH KARENA ITU JIKA TERJADI KERUSAKAN, KEHILANGAN, ATAU LAINNYA YANG TIMBUL DARI PENGGUNAAN ATAU URUSAN LAIN DALAM PERANGKAT LUNAK INI, PENULIS ATAU PEMEGANG HAK CIPTA TIDAK BERTANGGUNG JAWAB, KARENA PENGGUNAAN PERANGKAT LUNAK INI TIDAK DIPAKSAKAN SAMA SEKALI, SEHINGGA RISIKO ADALAH MILIK ANDA SENDIRI.
