# ## **Setup Bastillion - Untuk manage dan audit SSH**

System yang saya gunakan adalah **Ubuntu Server 18.04**

### **Tentang Bastillion**
Bastillion generate public/private SSH key sendiri saat startup. Key diletakan di authorized_key dari system yang terdaftar. Bastillion memungkinkan untuk berbagi perintah dan mengunggah file ke beberapa sistem secara bersamaan.

Sistem administrator tambahan dapat ditambahkan dan sesi terminalnya dan riwayatnya diaudit. Selain itu, Bastillion dapat mengelola, mendistribusikan, dan menonaktifkan kunci publik yang telah diatur dalam aplikasi. Manajemen kunci diaktifkan secara default untuk mencegah kunci publik yang tidak dikelola dan menegakkan praktik terbaik.