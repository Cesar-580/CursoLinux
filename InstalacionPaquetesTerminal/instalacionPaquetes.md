# Instalación de paquetes

Para la instalación de paquetes se usa:

´´´
sudo apt install "paquete"
´´´

´´´
sudo apt install nodejs
´´´

Para desinstalar paquetes se usa:

´´´
sudo apt remove"paquete"
´´´

´´´
sudo apt remove nodejs
´´´

Para instalar nvm(Manejador de versiones de nodejs)

Primero instalamos curl

´´´
sudo apt install curl
´´´

´´´
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash
´´´

Finalmente, para instalar la última version usamos

´´´
nvm install --lts
´´´