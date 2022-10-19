# Permodelan-Gerak-Jatuh-Bebas-Menggunakan-Microsoft-Excel
Banyak gejala fisika yang sukar diamati dan dieksperimenkan, terutama dalam hal pengukuran yang terbatasi oleh kemampuan mata manusia (Young & Freedmann, 2008). Termasuk di dalamnya adalah fenomena gerak linier pada gerak jatuh bebas (Zollman & Fuller, 1994). Suatu benda dikatakan mengalami gerak jatuh bebas, jika benda tersebut dilepaskan dari suatu ketinggian tertentu terhadap tanah tanpa kecepatan awal. Benda yang dijatuhkan dari atas akan jatuh ke bumi karena benda tersebut mendapat percepatan gravitasi (g) yang arahnya selalu menuju ke pusat bumi (Supriyadi, 2008)
Langkah – langkah 
Pembuatan permodelan gerak jatuh bebas tanpa gesekan udara tersebut adalah sebagai berikut :
Open Software Microsoft Excel >> Memasukkan Data (berupa tabel hasil perhitungan) >> Insert >> Recommended Charts >> All Charts >> X,Y (Scatter) >> Pilih Charts >> Klik kanan (pada charts) >> Select Data >> Klik Tabel (sumbu x untuk sumbu x) >> Klik Tabel (ketinggian untuk sumbu y) >> Oke >> Double Klik (pada chart) >> Setting Format Chart Area >> Fill >> Picture or Texture Fall >> File >> Input File >> Oke >> Klik Developer Tools >> Insert >> Pilih Command Button >> Buat tombol >> Rename dan Input Caption >> Klik Design Mode >> View Code >> Isi kode >> Save >> Run (F5) atau Klik Command Button yang sudah di rename dan di panggil pada kodingan.

Keterangan : 
Kode yang digunakan pada menu developer tools ( view code ) :
Private Sub Lompat_Click()
Range("B15").Value = 0 '0
delta_t = Range("C11").Value '0,2
While Range("B15").Value < 50
Range("B15").Value = Range("B15").Value + delta_t
DoEvents
Wend
End Sub

Penggunan fitur Developer Tools pada software Microsoft Excel sangat memudahkan kita dalam mengamati fenomena gerak jatuh bebas tanpa gesekan udara tersebut. Mengoprasikannya sangat mudah, dilakukan hanya dengan menekan tombol commad button yang telah dibuat saja secara otomatis grafik modifikasi menampilkan simulasi terjadi nya gerak jatuh bebas tanpa gesekan diudara sesuai dengan konsep yang dictuskan pertama kali oleh Galileo Galilei

Vidio tutorial membuat permodelan gerak jatuh bebas menggunakan microsoft excel saya lampirkan: 
https://youtu.be/EXRCHPdFXAo
