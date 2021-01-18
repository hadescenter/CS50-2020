# CS50-2020
- Link Pembelajaran
    - https://cs50.harvard.edu/x/2021/weeks/8/
    - https://www.youtube.com/watch?v=5g0x2xv3aHU

# Kuliah 8
## Internet

- **Internet** 
    - Adalah jaringan dari jaringan komputer yang saling berkomunikasi dengan satu sama lain, yang menyediakan infrastruktur untuk mengirim 0 dan 1. Di atas fondasi itu, kami dapa membangun aplikasi yang mengirim dan menerima data.
- **Router**  
    - Adalah komputer khusus, denga CPU dan memori,yang tujuanya adalah untuk menyampaikan dat amelalu Kabel atau teknologi nirkabel,antara perangkat lain di internet.
- **Protokol** 
    - Adalah seperangkat konvensi standar,seperti jabat tangan fisik,yang telah disepakati dunia untuk berkomunikasi dengan komputer.Misalnya,ada pola not dan satu, atau pesan tertentu,yang harus digunakan komputer untuk memberi tahun router ke mana ia ingin mengirim data.
- **TCP/IP**
    - Adalah dua protokol untuk mengirim data antara dua komputer.Di dunia nyata,kita mungkin menulis alamat di amplop untuk mengirim surat kepada seseorang,bersama dengan alamat kita sendiri sebagai balasan surat.Versi digital amplop,atau pesan dengan alamat dari dan ke,disebut **paket**.
- **IP**
    - Adalah singkatan dari Internet Protokol,protokol yang didukung oleh perangkat lunak komputer modern,yang mencakup cara standar komputer untuk saling berhubungan.**Alamat IP** adalah **alamat** unik untuk komputer yang terhubung ke internet,sehingga paket yang dikirim dari satu komputer ke komputer lainnya akan diteruskan melalui router hingga mencapai tujuanya.
        - Router memiliki,dalam memorinya,tabel yang memetakan alamat IP ke kabel yang masing-masing terhubung ke router lain,sehingga meraka tahu ke mana harus meneruskan paket.Ternyata ada protokol untuk router untuk berkomunkasi dan mencari tahu jalur ini juga.
- **DNS**
    - Domain Name System, adalah teknologi lain yang menerjemahkan nama domain seperti google.com menjadi alamat IP.DNS umumnya disediakan sebagai layanan oleh penyedia layanan internet terdekat, atau ISP **(Internet Service Provider)**.
- **TCP**
    - Transmission Control Protocol,adalah satu protokol terakhir yang memunkinkan satu server,pada alamat IP yang sama,untuk menyediakan beberapa layanan melalui penggunaan **nomor port**, bilangan bulat kecil ditambahkan ke alamat IP.Misalnya,HTTP,HTTPS,email,dan bahkan Zoom memiliki nomor port sendiri untuk digunakan program tersebut untuk berkomunikasi melalu jaringan
    - TCP juga menyediakan mekanisme untuk mengirim ulang paket jika suatu paket hilang dan tidak diterima. Ternyata, di internet ada beberapa jalur pengiriman sebuah paket karena banyak sekali router yang saling berhubungan. Jadi browser web, membuat permintaan untuk kucing, mungkin melihat paketnya dikirim melalui satu jalur router, dan server yang merespons mungkin melihat paket responsnya dikirim melalui jalur lain.
        - Data dalam jumlah besar, seperti gambar, akan dipecah menjadi beberapa bagian yang lebih kecil sehingga semua paket memiliki ukuran yang sama. Dengan cara ini, router di sepanjang internet dapat mengirim paket semua orang dengan lebih adil dan mudah. Netralitas bersih mengacu pada gagasan bahwa router publik ini memperlakukan paket secara sama, sebagai lawan dari mengizinkan paket dari perusahaan tertentu atau jenis tertentu untuk diprioritaskan.
        - Ketika ada beberapa paket untuk satu respon, TCP juga akan menentukan bahwa masing-masing paket diberi label, seperti "1 dari 2" atau "2 dari 2", sehingga mereka dapat digabungkan atau dikirim kembali sesuai kebutuhan.
- Dengan semua teknologi dan protokol ini, kami dapat mengirim data dari satu komputer ke komputer lain, dan dapat mengabstraksi internet, untuk membangun aplikasi di atas.
