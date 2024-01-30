

login: groups@plwdesign.online
senha: admin

## CHECAR PROPAGAÇÃO DO DOMÍNIO ##

https://dnschecker.org/

## COPIAR A PASTA PARA ROOT E RODAR OS COMANDOS ABAIXO ##

sudo chmod +x ./groups_shell_2/groups
cd ./groups_shell_2
sudo ./groups

===================================================

## APÓS A INSTALAÇÃO

## INSTALAR O CHROME (CASO VOCÊ RECEBA ERRO NA HORA DE COLAR A SENHA DO deployplw / RECEBA ERRO NO QRCODE) ##
sudo su deployplw
cd ~
sudo apt install -y ./google-chrome-stable_current_amd64.deb
pm2 restart 0


## ATIVAR FIREWALL ##

sudo ufw enable
y
enter

===================================================
