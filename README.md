# NGINX-in-Mac
NGINX Installation on Mac





 NGNIX Installation trough hombrew (Optional)
1. Open Terminal
2. Install NGNIX

brew install nginx
3. Start/Stop the NGNIX Service



brew services start nginx

brew services stop nginx

4. Check Installation

Trough Terminal
curl http://127.0.0.1:8080 

Trough browser


5. Check Configuration and Index files:

 cat /usr/local/etc/nginx/nginx.conf


 cat /usr/local/opt/nginx/html/index.html

 
