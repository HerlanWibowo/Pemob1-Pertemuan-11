# Pemob1-Pertemuan-11
## Nama : Herlan Wibowo
## NIM : 312210324
## Kelas : TI 22 A3
### Membuat Layout dengan Grid Layout untuk project yang telah dibuat
    Penjelasan:
    - Saya membuat layout dengan Grid Layout dan ImageView sebagai icon untuk tampilan activity.
    - Mengatur baris grid dengan sintaks "android:rowCount=2".
    - Mengatur kolom grid dengan sintaks "android:columnCountt=3".
    - Pada bagian setiap ImageView Saya menambahkan "android:onClick" agar dapat berpindah activity dan aplikasi.
    - Untuk logo maupun text pada ImageView saya menggunakan Image Assets
![GridCode](/image/GridActivity.png)
### Output
![GridOutput](/image/Grid%20Output.png)

### Menambahkan Explicit Intent untuk Maps
Saya menambahkan baris kode ini pada <b>grid_activity.xml</b>
```
 public void showMap(View view) {
        String uri = "http://maps.google.com/";
        Intent intent = new Intent(android.content.Intent.ACTION_VIEW, Uri.parse(uri));
        intent.setClassName("com.google.android.apps.maps", "com.google.android.maps.MapsActivity");
        startActivity(intent);
    }
```
### MainActivity Source Code
![MainActivity](/image/MainActivity.png)
### Output
![Maps](/image/Maps%20Ouput.png)
## Source Code Java Untuk Setiap Activity ada pada folder app>src>main>java
## Source Code Layout untuk setiap activity ada pada folder app>src>res>layout
# Terima Kasih!