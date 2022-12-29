# Jobsheet11

JARINGAN SENSOR NIRKABEL MENGGUNAKAN ESP-NOW

 ALAT DAN BAHAN
1) ESP32
2) Breadboard
3) Kabel jumper
4) Resistor 10K Ohm


LANGKAH PERCOBAAN

A. Memperoleh MAC Address ESP32 Receiver
    Dalam percobaan dan program ini kami mendapatkan MAC adrress pada ESP32 yang kami gunakan.
    
B. ESP-NOW One-Way Point-to-Point Communication
    1. Hasil dari program sender
       
    
![b 1](https://user-images.githubusercontent.com/121172074/209970768-751c138f-4682-4ece-ac6d-a83ea3799e59.png)
 
 
    2. Hasil dari receiver
    
    
    ![b 2](https://user-images.githubusercontent.com/121172074/209970925-370cadd3-f711-4311-9a14-39136b8445e5.png)



C. One-Way, One-to-Many Communication 
   a. Mengirim Pesan yang Sama Ke Beberapa Board ESP32
      Pada percobaan ini terdapat satu master sebagaii sender dan beberapa receiver, serta ada beberapa percobaan seperti mematikan salah satu receiver dan menambah secara bertahap receiver ke dalam jaringan
   b. Mengirim Pesan yang Berbeda Ke Beberapa Board ESP32
      Membuat program agar sender bisa mengirim pesan yang berbeda kepada 3 receiver
      
      
D.One-Way, Many-to-One Communication
    Di dalam mode ini, Receiver harus dapat mengidentifikasi setiap MAC Address unik dari Sender. Namun, untuk dapat membaca MAC Address yang berbeda cukup rumit dan butuh sedikit trik. Sehingga, untuk membuatnya lebih mudah, masing-masing Sender akan diberikan ID unik, agar Receiver dapat lebih mudah mengidentifikasi Sender.


 E. Two-Way Communication 
    
