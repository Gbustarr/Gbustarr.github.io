---
layout: post
title: "Como instalar Python y no morir en el intento"
---

# Bienvenid@s
## Python 101, Descarga e instalación.

Sabemos que al comenzar a realizar cualquier cosa por primera vez puede ser confuso e incluso
frustrante, motivo por el cual, cree esta pequeña guia sobre la instalación de python mediante pasos detallados para que al final puedas comenzar a escribir tus lineas de código lo mas rápido posible.

Sin mas preambulos, a comenzar!

### Requisitos previos

Esta guia esta enfocada principalmente para el sistema Windows pero tambien se describirán algunos pasos que puedan ser diferentes en otros sistemas distros de Linux como por ejemplo, en Ubuntu 20.04.

Para instalar Python, necesitas:

1.	Computadora con sistema Windows (o Ubuntu).
2.	Conexion a internet (Recomendable).
3.	Espacio entre 200 a 300 Mb.

### Paso 0: Descargar Python

Para descargar Python, te puedes dirigir a la pagina oficial de Python haciendo click [Aqui](https://www.python.org/ "Sitio oficial de Python") o buscarlo con tu buscador preferido. Como gustes, no problemo.

![Pagina principal de Python](/assets/python/images/Python_Main_Page.png "Pagina oficial de Python")
*Figura 1 : Pagina principal de Python*

Al interior del sitio encontraras una pestaña llamada "Downloads". Coloca el mouse sobre el y aparecerá un menu desplegable. Haz click en "Windows". 
![Pagina principal de Python, Descargas](/assets/python/images/Python_download.png "Descargas")
*Figura 2 : Menu desplegable*

Ya al interior de la nueva pagina, notarás que debajo de "Python Relases for Windows" hay 2 enlaces. Haz click en el que dice 'Latest Python 3 Release'.
![Pagina descargas Windows](/assets/python/images/Python_download_page.png "Pagina de descargas de Python para Windows")
*Figura 3 : Pagina de descargas de python para Windows* 

Luego, baja hasta el final de la pagina hasta que encuentres un apartado llamado "Files" y selecciona el archivo "Windows installer". Aqui debes decidir si utilizar la version para 32 o 64 bits.
![32 o 64 Bits](/assets/python/images/Python_32_64_bits.png "Descargar 32 o 64 bits")
*Figura 4 : Tabla de descargas*

**¿32 o 64 bits?**
Si no sabes que versión utilizar, despliega el menu de abajo.
<details>
<summary>Que version elegir</summary>
<br>
Las versiones 32 y 64 bits hacen referencia al tipo de arquitectura del procesador en que se basó la construccion del archivo. Es decir, la version de 32 bits sirve para computadoras de 32 bits (Tambien para 64 bits) y la version de 64 bits para computadoras de 64 bits (No sirve para 32 bits).
<br>
<br>
Basicamente si tienes un computador de 64 bits, no tendrias porque preocuparte mucho, pero sacrificarias algunas caracteristicas al no utilizar la version correcta. Cosa que no queremos cierto?
<br>
<br>
Para conocer la arquitectura de tu computadora debes:

<ul>	
	<li>Buscar "Acerca de mi pc" en el buscador de Windows e identificar en la informacion que te entrega que tipo de arquitectura es tu computadora</li>
	<li>Para Ubuntu, debes abrir una terminal (Ctrl+alt+t) y escribir 'lscpu' sin las comillas.</li>
</ul>
</details>


### Paso 1: Instalar Python
#### Windows

Ya que tenemos el archivo necesario para instalar Python, solo debemos iniciar el instalador que es bastante estandar. 

![Instalador Python](https://docs.python.org/es/3/_images/win_installer.png "Instalador Python")
*Figura 5 : Instalador de Python, imagen de Python Docs*

Debes tener especial cuidado en habilitar la casilla 'Add Python X.x to PATH' (Las "X" puede cambiar según la versión que instales) que esta en la parte inferior una vez que inicias el instalador, en caso contrario, se te dificultará ejecutar Python por consola mas adelante cuando desarrolles mas proyectos.

Solo debes darle siguiente, siguiente, siguiente, sig... ya me entiendes.

y listo, ya tienes Python en su ultima versión (y PIP) instalado en tu computadora. Facil no?
<details>
<summary>PIP?</summary>
<br>
PIP (Package Installer for Python), es un gestor que te ayudará a instalar, actualizar y/o borrar paquetes desde una terminal. Este software se instala junto a Python y facilita mucho la administración de las librerias que necesites a medida que avanzas en cualquier proyecto.
<br>
<br>
Que necesitas instalar una libreria que te permita manipular imagenes? Lo puedes instalar con PIP. O talvez una libreria que te permita utilizar sonido o video en tu codigo?, solo debes buscar una libreria que satisfaga tus necesidades y mediante PIP instalarlo.

</details>
<br>
#### Ubuntu

Generalmente, Python ya viene instalado en Ubuntu. Puedes verificar su instalación al escribir: 
>python3 --version

en un terminal (Ctrl+alt+t) y deberia salir algo como esto:
>Python 3.8.10


## Comentarios finales

Como se pudo observar, la instalación y habilitación de Python para escribir codigo en una computadora es bastante estandar y sin contratiempos.
En los siguientes posts sobre Python abarcare sobre la creación de un pequeño programa escrito en Python y como ejecutarlo.

Nos vemos!





