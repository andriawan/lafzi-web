# Lafzi Web Interface

Repositori ini berisi antarmuka Lafzi dalam bentuk web seperti pada http://lafzi.apps.cs.ipb.ac.id. 
Web interface ini mengimplementasikan proses pencarian (online) sesuai bagian kiri pada diagram berikut:

![Flowchart](https://raw.githubusercontent.com/lafzi/lafzi-indexer/master/docs/flowchart.png)

Indeks yang digunakan untuk pencarian dibangun dengan script pada repository [lafzi-indexer](https://github.com/lafzi/lafzi-indexer).

Menjalankan
---

1. Clone atau download repository ini ke folder web server (htdocs atau /var/www/html)
2. Aktifkan module `mbstring` pada PHP dengan command `sudo apt-get install phpX.Y-mbstring` (sesuaikan `X.Y` dengan versi PHP yang terinstal)
3. Langsung kunjungi di browser

Tidak ada setup khusus karena aplikasi ini tidak menggunakan database. 
Disarankan menggunakan sistem operasi Linux karena sistem cache mengandalkan command di Linux.

Lisensi
---

GPL (GNU General Public License) v3. Anda bebas menggunakan, memodifikasi, dan mendistribusikan software ini dengan syarat tetap menjadikannya *open-source*.
