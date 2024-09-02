ubuntu 18/20/22

wget "https://github.com/sabiralipsl/xuiwork/releases/download/xui/XUI_1.5.5.zip" -O /XUI_1.5.5.zip

cd /tmp

apt install zip unzip -y ; unzip XUI_1.5.5.zip

./install

wget https://github.com/sabiralipsl/xuiwork/releases/download/xui/sabirali.zip

unzip sabirali.zip

chmod -R 777 install.sh

./install.sh
