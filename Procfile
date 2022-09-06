worker: sudo apt update -y &&
sudo apt upgrade -y &&
sudo apt install ffmpeg -y &&
sudo apt install imagemagick -y &&
sudo apt install wget -y &&
sudo apt install mc -y &&
wget -qO- https://raw.githubusercontent.com/nvm-sh/nvm/v0.38.0/install.sh | bash &&
source ~/.bashrc &&
nvm ls-remote	&&
nvm install 16.16.0	&&
npm i pm2 -g &&
pm2 start haruka.js &&
pm2 save &&
pm2 monit
