# Instal-VS-Code-di-linux

//Pertama, perbarui indeks paket dan instal dependensi dengan mengetik:
sudo apt update
sudo apt install software-properties-common apt-transport-https wget

//lalu ketik keys dibawah ini :
wget -q https://packages.microsoft.com/keys/microsoft.asc -O- | sudo apt-key add -

//aktifkan repository dengan code dibawah ini :
sudo add-apt-repository "deb [arch=amd64] https://packages.microsoft.com/repos/vscode stable main"

//setelah repository berhasil dijalankan, sekarang menginstal visual studio code :
sudo apt update
sudo apt install code

//Selesai, coba search di menu : Visual Studio Code

//Cara Uninstal Visual Studio Code, dengan mengetik code berikut :
sudo apt purge code
