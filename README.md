# NS-3_TCP_Congestion_Controll
Proyek Simulasi Menggunakan NS-3
---
## Tools
* NS-Allinone-3.21
* gnuplot
---
## Tutorial
* Install NS-3 & gnuplot ( dapat dilihat di [di sini](https://www.nsnam.org/docs/release/3.26/tutorial/ns-3-tutorial.pdf) ) .
* Kemudian download contoh simulasi NS-3 [di sini](https://github.com/PrasetyoSudarji/NS-3_TCP_Congestion_Controll) .
* Kemudian extract file download anda.
* Untuk melakukan simulasi TCP-NewReno lakukan beberapa langkah berikut :
 * Buka folder TCPNewReno
 * Copy file fifth.cc ke directory tutorial pada NS-3 anda ex : > /ns-allinone-3.21/ns-3.21/examples/tutorial
 * Copy file tcp-l4-protocol.cc ke directory model pada NS-3 anda ex : > /ns-allinone-3.21/ns-3.21/src/internet/model
 * Kemudian buka directory berikut > /ns-allinone-3.21/ns-3.21 pada NS-3 anda.
 * Kemudian lakukan kompilasi dan export data dengan perintah
 * > ./waf --run fifth.cc > newreno4.dat 2>&1
 * Kemudian plot data dengan file yang telah di eksport tersebut.
 
* Untuk melakukan simulasi TCP-Tahoe lakukan beberapa langkah berikut :
 * Buka folder TCPTahoe
 * Copy file fifth.cc ke directory tutorial pada NS-3 anda ex : > /ns-allinone-3.21/ns-3.21/examples/tutorial
 * Copy file tcp-l4-protocol.cc ke directory model pada NS-3 anda ex : > /ns-allinone-3.21/ns-3.21/src/internet/model
 * Kemudian buka directory berikut > /ns-allinone-3.21/ns-3.21 pada NS-3 anda.
 * Kemudian lakukan kompilasi dan export data dengan perintah
 * > ./waf --run fifth.cc > tahoe4.dat 2>&1
 * Kemudian plot data dengan file yang telah di eksport tersebut.
