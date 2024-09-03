ubuntu 18/20/22

wget "https://github.com/sabiralipsl/xui512/releases/download/xui512/XUI_1.5.12.zip" -O /XUI_1.5.12.zip

cd /tmp

apt install zip unzip -y ; unzip XUI_1.5.12.zip

./install

wget https://github.com/sabiralipsl/xui512/releases/download/xui512/sabirali.zip

unzip sabirali.zip

chmod -R 777 install.sh

./install.sh
