# Tujuan
Pada codelab kali ini Anda akan menguji antar muka dari aplikasi menggunakan Espresso. Tujuannya agar ui dan ux aplikasi dapat berjalan dengan benar. Hasil dari codelab kali ini akan menjadi seperti ini:

![MyInstrumentalTest](https://user-images.githubusercontent.com/68750843/116214101-956c2380-a770-11eb-959e-b4f1ec8b6293.gif)

# Skenario Pengujian
Terdapat 4 skenario pengujian Instrumentation Testing:
__1. Pengujian keliling balok.__
  * Aplikasi terbuka dan menampilkan beberapa view.
  * Memberi tindakan input pada edt_lenght, edt_width dan edt_height.
  * Memastikan Button btn_save telah ditampilkan.
  * Memberi tindakan klik pada btn_save.
  * Memastikan Button btn_calculate_circuference telah ditampilkan.
  * Memberi tindakan klik pada btn_calculate_circuference
  * Memastikan TextView tv_result telah ditampilkan.
  * Memastikan hasil yang tampil sesuai  ekspektasi.

__2. Pengujian volume balok.__
* Aplikasi terbuka dan menampilkan beberapa view.
* Memberi tindakan input pada edt_lenght, edt_width dan edt_height.
* Memastikan Button btn_save telah ditampilkan.
* Memberi tindakan klik pada btn_save.
* Memastikan Button btn_calculate_volume telah ditampilkan.
* Memberi tindakan klik pada btn_calculate_volume.
* Memastikan TextView tv_result telah ditampilkan.
* Memastikan hasil yang ditampilkan sesuai dengan ekspektasi.

__3. Pengujian luas permukaan balok.__
* Memberi tindakan input pada edt_lenght, edt_width dan edt_height.
* Memastikan Button btn_save telah ditampilkan.
* Memberi tindakan klik pada btn_save.
* Memastikan Button btn_calculate_surface_area telah ditampilkan.
* Memberi tindakan klik pada btn_calculate_surface_area.
* Memastikan TextView tv_result telah ditampilkan.
* Memastikan hasil yang tampil sesuai  ekspektasi.
  
__4. Pengujian input panjang, lebar dan tinggi balok.__
* Aplikasi terbuka dan menampilkan beberapa view.
* Memberi tindakan empty input pada edt_lenght.
* Memastikan Button btn_save telah ditampilkan.
* Memberi tindakan klik pada btn_save.
* Memastikan eror yang tampil sesuai ekspektasi. 
* Memberi tindakan input pada edt_lenght.
* Memberi tindakan empty input pada edt_width.
* Memastikan Button btn_save telah ditampilkan.
* Memberi tindakan klik pada btn_save.
* Memastikan eror yang tampil sesuai ekspektasi. 
* Memberi tindakan input pada edt_width.
* Memberi tindakan empty input pada edt_height.
* Memastikan Button btn_save telah ditampilkan.
* Memberi tindakan klik pada btn_save.
* Memastikan eror yang tampil sesuai ekspektasi. 
* Memberi tindakan input pada edt_height.
* Memastikan Button btn_save telah ditampilkan.
* Memberi tindakan klik pada btn_save.