# untuk diperhatikan untuk membuat web server sederhana ini menggunakan NodeJS Web Server dan NginX dan dikonfigurasi dengan 
# reverse proxy server bertujuan untuk akses port 80 yang ada Nginx request di teruskan ke web server
# setelah itu menggunakan rate limit akses di NGINX untuk meningkatkan keamanan pada web server

# - Mengubah port NGINX dari 80 ke 3000 (bukan port web server Node.js).
# - Mengubah konfigurasi rate limit menjadi 6 request per menit alias 1 request setiap 10 detik.

# Tools
- WSL Linux Ubuntu
- Node.JS Web Server (V.14.15.4)
- NVM Tools
- NginX
- Source Code Sederhana

# Konfigurasi Nginx 
copy paste semua konfigurasi pada Nginx 

setelah itu restart NginX dengan SystemCtl restart Nginx.service

Jalankan NVM 

# npm install
dan jalankan dengan perintah 

# npm run start
