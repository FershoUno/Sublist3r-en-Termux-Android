# Sublist3r-en-Termux-Android
Sublist3r, es una herramienta diseñada para enumerar los subdominios de las paginas web a utilizando diferentes motores de búsquedas como Google, Bing entre otros, aparte de utilizar motores de búsquedas mas conocidos, también recopila subdominios utilizando Netcraft, VirusTotal, DNSdumpster entre otros.
Sublist3r cuenta con una opción llamado "BRUTEFORCE" que usa un modulo "subbrute" con el fin de encontrar subdominios utilizando fuerza bruta.

# Instalación Sublist3r en Termux
~~~
git clone https://github.com/FershoUno/Sublist3r-en-Termux-Android

cd Sublist3r-en-Termux-Android

chmod +x Sublist3r-installer

./Sublist3r-installer
~~~

# Ejemplos de uso

__enumerar un dominio__  

    $ sublist3r -d example.com

__enumerar un dominio con puerto especifico__  

    $ sublist3r -d example.com -p 22  

__enumerar un dominio con varios puertos__  

    $ subist3r -d example.com -p 21,22,80,443,8080,9050

__guardar resultados de enumeración del dominio en un fichero__  

    $ sublister -d example.com -o results-dominio

__Ver todas las opciones de sublist3r__

    $ sublist3r --help


>Nota.- Solo utilizarlo con fines academicos.
