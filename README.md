# Gauge Echart

I. Jenis : Gauge Echart

II. Option : 

### **TITLE**
1.  Title : Text (string) -> untuk membuat judul.
2.  Title : textStyle (number) fontSize -> untuk mengubah ukuran text.
3.  Title : textStyle (string) color -> untuk mengubah warna.
4.  Title : textStyle (string) fontFamily -> mengubah jenis font.
5.  Title : textStyle (string) fontWeight bold-> membuat judul menjadi tebal.
6.  Title : textStyle (number) fontStyle italic-> untuk membuat gaya teks menjadi miring.
7.  Title : textBaseline (string) -> mengatur posisi teks secara vertical (top,middle,bottom).
8.  Title : link (string) -> untuk memindahkan halaman dari judul.
9.  Title : Target (string) blank -> untuk membuka halaman lain di tab baru.
           •	Target (string) self -> untuk membuka halamanlain pada tab yang sama.
10. Title : textAlign (string) -> menentukan letak teks (center,right,left).
 	
### **TOOLTIP**
1. Tooltip : formatter (string, function) -> Formatter dari layer floating tooltip yang mendukung template string dan fungsi callback.
 	
### **TOOLBOX**
1.  Toolbox: itemSize (number) -> menentukan ukuran ikon toolbox (default=15).
2.  Toolbox: itemGap (number) -> jarak antara masing-masing legend, jarak horizontal dalam tata letak horizontal, dan jarak vertical dalam tata letak vertical (default=10).
3.  Toolbox : feature (object) -> Item konfigurasi untuk setiap alat.
4.  Toolbox : feature (object) ; restore (object) -> untuk mengembalikan item konfigurasi.
5.  Toolbox : feature (object) ; saveAsImage (Object) -> untuk menyimpan gambar.
6.  Toolbox : iconStyle (object) : normal (object) : color (color) : untuk mengubah warna ikon.
7.  Toolbox : iconStyle (object) : normal (object) : borderColor (color) : mengubah warna area pinggir pada objek.
9.  Toolbox : iconStyle (object) : normal (object) : borderWidth (number) : menentukan ketebalan border pada ikon (default=1). 
10. Toolbox : iconStyle (object) : normal (object) : borderType (string) : untuk menentukan jenis border pada ikon (default=solid) (dashed,dotted,solid).
11. Toolbox : iconStyle (object) : normal (object) : shadowBlur (number) : mengatur blur pada bayangan. 
12.	Toolbox : iconStyle (object) : normal (object) : shadowColor (color) : mengatur warna bayangan. 
13.	Toolbox : iconStyle (object) : normal (object) : shadowOffsetX (number) : mengatur posisi bayangan horizontal (default=0). 
14. Toolbox : iconStyle (object) : normal (object) : shadowOffsetY (number) : mengatur posisi bayangan vertical (default=0). 
15.	Toolbox : iconStyle (object) : normal (object) : opacity (number) : mendukung nilai dari 0 sampai 1, dan komponen tidak akan ditarik saat diatur ke 0. 
16. Toolbox : iconStyle (object) : normal (object) : textPosition (string) : mengatur posisi teks. 
17. Toolbox : iconStyle (object) : normal (object) : textAlign (string) : mengatur align teks. 
18.	Toolbox : iconStyle (object) : emphasis (object) : color (color) : mengatur warna saat mouse melayang di atas ikon. 
19. Toolbox : iconStyle (object) : emphasis (object) : borderColor (color) : mengubah warna area pinggir pada objek. 
20. Toolbox : iconStyle (object) : emphasis (object) : shadowBlur (number) : membuat bayangan objek menjadi blur. 
21.	Toolbox : iconStyle (object) : emphasis (object) : shadowColor (color) : mengubah warna bayangan objek. 
22.	Toolbox : iconStyle (object) : emphasis (object) : shadowOffsetX (number) : jarak bayangan horizontal. 
23. Toolbox : iconStyle (object) : emphasis (object) : shadowOffsetY (number) : jarak bayangan vertikal.

### **SERIES**
1.  Series : name (string) -> Nama seri yang digunakan untuk menampilkan tooltip.
2.	Series : min (number) -> Nilai data minimum yang dipetakan ke minAngle.
3. 	Series : max ( number) -> Nilai data maksimum yang dipetakan ke minAngle.
4. 	Series : radius (number, setring) -> Jari-jari grafik gauge. Bisa jadi nilai persentase yang lebih kecil dari container setengah lebar dan setengah tinggi, juga bisa menjadi nilai absolut. 
5. 	Series : detail (object) -> Detail tentang gauge chart yang digunakan untuk menampilkan data.
