Sensor DHT11 adalah salah satu sensor yang dapat mengukur dua parameter lingkungan sekaligus, yakni suhu dan kelembaban udara (humidity). 

Dalam sensor ini terdapat sebuah thermistor tipe NTC (Negative Temperature Coefficient) untuk mengukur suhu, sebuah sensor kelembaban tipe resisitif dan sebuah mikrokontroller 8-bit.

Mengolah kedua sensor tersebut dan mengirim hasilnya ke pin output dengan format single-wire bi-directional (kabel tunggal dua arah).

Adapun kelebihan dari module sensor ini dibanding module sensor lainnya yaitu dalam segi kualitas pembacaan data sensing yang lebih responsif dengan memliki kecepatan dalam hal sensing objek suhu dan kelembaban, dan data yang terbaca tidak mudah terinterverensi.


[CASE]

Sebuah kandang dipasang sebuah sensor DHT11 yang digunakan untuk mengetahui perubahan suhu pada kandang dan pada akhirnya data suhu dapat terinterface dengan pengguna melalui serangkaian alat serta aplikasi pendukung.

Sensor akan mendeteksi sebuah perintah yang sudah di program pada alat :

•	Jika suhu/temperature pada ruangan meningkat atau berada di derajat >=30, maka pendingin akan otomatis menyala dan akan muncul laporan "pendingin menyala"

•	Jika suhu/temperature pada ruangan menurun atau berada di derajat <=25, maka pemanas akan otomatis menyala dan akan muncul laporan "pemanas menyala"

•	Jika suhu berada di derajat 26-29 akan dinyatakan sebagai "suhu normal"

•	Jika suhu none maka akan dinyatakan dengan "suhu tidak terdeteksi"
