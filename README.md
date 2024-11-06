#🚀 DAW2 11/2024 - Instalaciones 

## Introducción

Comandos para instalar en Linux un servidor de aplicaciones.

## Instalación de Nginx en Linux 🖥️

Para la instalación de Nginx, ejecuta en tu terminal los siguientes comandos:

```bash
sudo apt-get update
sudo apt install nodejs
node -v
npm -v
sudo apt install npm
sudo apt install nginx
```


## Instalación de Apache Tomcat de Linux 🐱‍💻

Para la instalación de Tomcat, ejecuta en tu terminal los siguientes comandos:

```bash
sudo apt-get update
sudo apt-get install openjdk-11-jdk
java -version
```

Para comprobar la disponibilidad de los paquetes Apache 📦:

```bash
sudo apt-cache search tomcat
sudo apt install tomcat9-admin

//Si da error usa:
sudo apt install tomcat10-admin
```

Comprueba los puertos Apache Tomcat 🌐:

```bash
ss -ltn
```

Añade el puerto al firewall 🔒:

```bash
sudo ufw allow from any to any port 8080 proto tcp
```
Abre el navegador y busca:

🌐 [http://127.0.0.1:8080](http://127.0.0.1:8080)
