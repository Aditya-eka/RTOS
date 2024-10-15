# RTOS 1
Program ini bekerja dengan menginisialisasi berbagai perangkat keras seperti ADC, I2C, UART, dan GPIO, lalu menggunakan FreeRTOS untuk mengelola beberapa task yang berjalan secara paralel. ADC membaca data analog yang kemudian ditampilkan pada layar OLED SSD1306 melalui komunikasi I2C dan juga dikirimkan ke terminal melalui UART. Program ini memantau tombol fisik untuk interaksi pengguna, dan menampilkan respons di terminal saat tombol ditekan. Dengan FreeRTOS, setiap task seperti pembacaan ADC, pembaruan OLED, komunikasi UART, dan pemantauan tombol diatur agar berjalan secara efisien dan terkoordinasi.


![WhatsApp Image 2024-10-13 at 01 00 01](https://github.com/user-attachments/assets/0722af74-8c75-44a9-a340-69dea9fb4cbe)


https://github.com/user-attachments/assets/08b86a16-27be-4be4-8dae-cd6412362cd1

