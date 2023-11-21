npm install -g http-server
cd C:\PWA
npm install
http-server

# (Optional) Install mkcert and create a local SSL certificate
mkcert -install
mkcert localhost

# Start http-server with HTTPS (after creating the SSL certificate)
http-server -S -C localhost.pem -K localhost-key.pem


git config --global user.name "zduvenage"
git config --global user.email "zduvenge@gmail.com"

http://192.168.1.105:8080