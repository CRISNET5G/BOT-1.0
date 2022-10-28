# COMANDOS PARA INSTALAR NA VPS LINUX

apt update

apt upgrade

apt install git

apt install npm

curl -fsSL https://deb.nodesource.com/setup_14.x | E bash -

apt-get install -y nodejs

apt install apt-transport-https ca-certificates

apt-get install -y libgbm-dev wget unzip fontconfig locales gconf-service libasound2 libatk1.0-0 libc6 libcairo2 libcups2 libdbus-1-3 libexpat1 libfontconfig1 libgcc1 libgconf-2-4 libgdk-pixbuf2.0-0 libglib2.0-0 libgtk-3-0 libnspr4 libpango-1.0-0 libpangocairo-1.0-0 libstdc++6 libx11-6 libx11-xcb1 libxcb1 libxcomposite1 libxcursor1 libxdamage1 libxext6 libxfixes3 libxi6 libxrandr2 libxrender1 libxss1 libxtst6 ca-certificates fonts-liberation libappindicator1 libnss3 lsb-release xdg-utils

wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb
apt install ./google-chrome-stable_current_amd64.deb

git clone https://github.com/CRISNET5G/BOT-1.0.git && cd BOT-1.0

sh start.sh

Após escanear o qr code pare o bot digitando ctrl+C e faça esses comandos 

npm install -g pm2

pm2 start index.js

cd BOT-1.0 && pm2 reload index.js
