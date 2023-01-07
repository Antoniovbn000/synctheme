SyncTheme
Free and fast theme for pterodactyl panel 1.x

Install tutorial:

👋, Welcome to SyncTheme documentation!
Here you can find all the information you need to get started with SyncTheme.

Enter this commands in root diretory of your server to perform clean installation!

1. Download and extract all files to /var/www/pterodactyl

git clone https://github.com/Antoniovbn000/synctheme.git

apt install -y unzip

cd synctheme && unrar e SYNC.rar && cp -r * /var/www/pterodactyl

2. Install all depencies

curl -sL https://deb.nodesource.com/setup_16.x | sudo -E bash -

apt install -y nodejs

3. Install packages required for theme to work!

npm i -g yarn

cd /var/www/pterodactyl && yarn install

yarn add @mui/material @emotion/react @emotion/styled

yarn add @mui/material @mui/styled-engine-sc styled-components

yarn add @mui/icons-material

yarn add @mui/joy @emotion/react @emotion/styled

4. Build the panel

yarn && yarn build:production

💥Once your theme is installed, refresh the page💥

💥If you need help or have errors/bugs dm AntonioVbn#7699 on discord!💥
