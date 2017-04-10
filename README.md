# NS-3_TCP_Congestion_Controll
Proyek Simulasi Menggunakan NS-3

#Tools
* NS-Allinone-3.21
* gnuplot

#Tutorial
* Install NS-3 & gnuplot ( dapat dilihat di https://www.nsnam.org/docs/release/3.26/tutorial/ns-3-tutorial.pdf )
* Kemudian untuk melakukan simulasi TCP-NewReno lakukan beberapa langkah berikut :
* * Copy file fifth.cc ke directory /ns-allinone-3.21/ns-3.21/examples/tutorial
* * Copy file tcp-l4-protocol.cc ke directory /ns-allinone-3.21/ns-3.21/src/internet/model
* * Kemudian buka directory /ns-allinone-3.21/ns-3.21
* * Kemudian lakukan kompilasi dan export data dengan perintah
* * > ./waf --run fifth.cc > newreno4.dat 2>&1
