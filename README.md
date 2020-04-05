# ## **Setup Bastillion - Untuk manage dan audit SSH**

System yang saya gunakan adalah **Ubuntu Server 18.04**

### **Tentang Bastillion**
Bastillion generate public/private SSH key sendiri saat startup. Key diletakan di authorized_key dari system yang terdaftar. Bastillion memungkinkan untuk berbagi perintah dan mengunggah file ke beberapa sistem secara bersamaan.

Sistem administrator tambahan dapat ditambahkan dan sesi terminalnya dan riwayatnya diaudit. Selain itu, Bastillion dapat mengelola, mendistribusikan, dan menonaktifkan kunci publik yang telah diatur dalam aplikasi. Manajemen kunci diaktifkan secara default untuk mencegah kunci publik yang tidak dikelola dan menegakkan praktik terbaik.

## **Kasus dalam konfigurasi ini:**
Saya ingin mengistall bastillion server di **Ubuntu Server 18.04**, dengan tujuan membuat ssh gateway. Konfigurasi ini ada 3 langkah;
1. Install Bastilliion
2. Membuat Bastillion menjadi Startup Service
3. Menambahkan SSL Certificate Trusted pada Bastillion

Pada langkah Menambahkan SSL Trusted sebenarnya cukup mudah, tapi saya ada sedikit kendala saat konfigurasinya, saya beli SSL ini di ..... . Setelah membeli SSL, kita dapat file, nah file tersebut kita gabungkan. (seperti yang tertulis di file .txt di atas). Pada langkah membuat keystore, kita isi Identitas seperti yang ada di file certficate yang telah digabungkan, (misal seperti Common Name, State, Locality, dll.). 

Untuk dokumentasi lengkapnya, silahkan kunjungi website https://www.bastillion.io/

## **Terimakasih**