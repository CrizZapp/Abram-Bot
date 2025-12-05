# Instalación (Termux)

## 1. Actualizar paquetes
pkg upgrade -y && pkg update -y

## 2. Instalar dependencias necesarias
pkg install git -y
pkg install nodejs-lts -y
pkg install ffmpeg -y
pkg install wget -y
pkg install tesseract -y

## 3. Dar permisos de almacenamiento
termux-setup-storage

## 4. Clonar el repositorio
cd /sdcard
git clone https://github.com/CrizZapp/Abram-Bot

## 5. Descomprimir el ZIP 
Contraseña del ZIP: CrisZapp

## 6. Entrar a la carpeta del bot
cd CrisBot-Base

## 7. Instalar módulos
npm install

## 8. Iniciar el bot
node index
