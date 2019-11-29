# Sublist3r-en-Termux-Android

Nucleo Linux UAGRM   
Enlaces de los Grupos   

Facebook: https://www.facebook.com/groups/nucleolinux/

Facebook: https://www.facebook.com/groups/nucleolinux.uagrm 

Telegram: https://t.me/nucleolinux_uagrm                     

GitHub  : https://github.com/nucleolinux-uagrm               


# Instalación Sublist3r en Termux

git clone https://github.com/FershoUno/Sublist3r-en-Termux-Android

cd Sublist3r-en-Termux-Android

chmod +x Sublist3r-installer

./Sublist3r-installer

#

Sublist3r, es una herramienta diseñada para enumerar los subdominios de las paginas web a utilizando diferentes motores de busquedas como Google, Bing entre otros, aparte de utilizar motores de busquedas mas conocidos, tambien recopila subdominios utilizando Netcraft, VirusTotal, DNSdumpster entre otros.
Sublist3r cuenta con una opción llamado "BRUTEFORCE" que usa un modulo "subbrute" con el fin de encontrar subdominios utilizando fuerza bruta.


Ejemplos de uso

# enumerar un dominio

$ sublist3r -d dominio.com

# enumerar un dominio con puerto especifico
$ sublist3r -d dominio.com -p 22

# enumerar un dominio con varios puertos
$ subist3r -d dominio -p 21,22,80,443,8080,9050

# guardar resultados de enumeración del dominio en un fichero
$ sublister -d dominio.com -o results-dominio

# Ver todas las opciones de sublist3r 
$ sublist3r --help





Nota.- ejecutar sublist3r como cualquier comando
