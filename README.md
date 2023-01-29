# HackTheBox OpenVPN Connect

```
Simple script en BASH con un setup en python para conectarte automáticamente a tu VPN de HackTheBox al escribir "hackthebox" en la terminal
```

# Setup

> **Clonar el repositorio**

```sh
 git clone https://github.com/franafp/hackthebox-openvpn-autoconnect.git
 ```
 
> **Instalar Dependencias**

```sh
sudo apt install openvpn
sudo apt install python3
```
 > **Abrir la ruta**
 
 ```sh
 cd hackthebox-openvpn-autoconnect
 ```
 
 > **Configurar la ruta de tu archivo .ovpn**
 
 ```bash
 #!/usr/bin/bash
 
 sudo openpvn [ruta]
 ```
 
 > **Auto Install**
 
 ```bash
 sudo python3 setup.py
 ```
 
 # Dependencias
 
 > **Instalar Dependencias Obligatorias**
 ```
 sudo apt install python3
 sudo apt install openvpn
 ```
 
 # Ejecutar
 
``` 
Ahora simplemente debes escribit en tu terminal `hackthebox` y ya estaras conectado a tu VPN de HackTheBox, disfruta
```

```sh
hackthebox
```
