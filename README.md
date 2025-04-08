# NGINX-in-Mac
NGINX Installation on Mac



# Homebrew Installation (Optional)

/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

# 1. Open Terminal
# 2. Install NGNIX

brew install nginx

<img width="567" alt="Screenshot 2025-04-08 at 5 35 38 PM" src="https://github.com/user-attachments/assets/fac103a8-6c7c-4d5d-b8ce-0455ae0f5161" />

# 3. Start/Stop the NGNIX Service

brew services start nginx
brew services stop nginx

<img width="713" alt="Screenshot 2025-04-08 at 5 36 30 PM" src="https://github.com/user-attachments/assets/b43477a7-264a-4869-8414-3bcbcc8fa8be" />


# 4. Check Installation

Trough Terminal
curl http://127.0.0.1:8080 

<img width="703" alt="Screenshot 2025-04-08 at 5 37 23 PM" src="https://github.com/user-attachments/assets/80855da0-61ec-46e3-be25-36d17255e868" />


Trough browser

<img width="781" alt="Screenshot 2025-04-08 at 5 37 42 PM" src="https://github.com/user-attachments/assets/105cd2a7-b842-41ad-ad7f-0f448612f4d6" />


# 5. Check Configuration and Index files:

cat /usr/local/etc/nginx/nginx.conf
 
<img width="665" alt="Screenshot 2025-04-08 at 5 38 48 PM" src="https://github.com/user-attachments/assets/a7720fb6-956a-4cfa-b9ac-428ff6a5affa" />

cat /usr/local/opt/nginx/html/index.html

 
