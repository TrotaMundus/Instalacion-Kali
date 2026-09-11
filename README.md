<h1>Instalación de Kali Linux</h1>

<p>
  <strong>
    <a href="https://www.youtube.com/watch?v=HaS0Frl8n40">
      Hacking Ético #01 | Instalación de Kali Linux desde 0
    </a>
  </strong>
</p>

<a href="https://www.youtube.com/watch?v=HaS0Frl8n40">
  <img
    src="https://img.youtube.com/vi/HaS0Frl8n40/maxresdefault.jpg"
    alt="Hacking Ético #01 | Instalación de Kali Linux desde 0"
    width="800"
  />
</a>

<section id="Benevenida">
  <h2 style="display: inline-block; border-bottom: 2px solid #ffffff; padding-bottom: 5px;">Bienvenidos a este proyecto</h2>
  <p>
    Este proyecto está pensado para
    <strong>DUMMIES o personas que están comenzando desde cero</strong>,
    por lo que inicialmente las explicaciones serán detalladas y paso a paso.
  </p>

  <p>
    A medida que avances de proyecto en proyecto,
    <strong>el nivel de dificultad irá aumentando progresivamente</strong>.
    La idea es que cada ejercicio te prepare para el siguiente.
  </p>

  <p>
    No te preocupes si al principio todo parece muy explicado;
    <strong>poco a poco iremos subiendo el nivel</strong>.
  </p>

  <p>
    <strong>Inicialmente, comenzaremos con lo más básico. ¡Vamos a ello!</strong>
  </p>
</section>

<section id="Programas">
  <h2 style="display: inline-block; border-bottom: 2px solid #ffffff; padding-bottom: 5px;">Programas necesarios</h2>

  <p>
    Antes de comenzar con la creación de nuestra máquina virtual,
    necesitaremos descargar e instalar los siguientes programas:
  </p>

  <ul>
    <li>
      <strong>
        <a href="https://winrar.es/descargas">
      WinRAR:
        </a>
      </strong>
      programa que utilizaremos para descomprimir el archivo descargado de Kali Linux.
    </li>
     <li>
      <strong>
        <a href="https://www.virtualbox.org/wiki/Downloads">
      VirtualBox:
        </a>
      </strong>
      Entorno que nos permitirá crear y ejecutar nuestra máquina virtual.
    </li>
    <li>
      <strong>
        <a href="https://www.kali.org/get-kali/#kali-platforms">
      Kali Linux:
        </a>
      </strong>
      Sistema operativo
    </li>
  </ul>
</section>

<section id="instalacion-winrar">
  <h2 style="display: inline-block; border-bottom: 2px solid #ffffff; padding-bottom: 5px;">Instalación de WinRAR</h2>

  <p>
    En este paso descargaremos e instalaremos
    <strong>WinRAR</strong>, una herramienta que utilizaremos para
    descomprimir los archivos de Kali Linux.
  </p>

  <h3>1. Descargar WinRAR</h3>

  <p>
    Abrimos nuestro navegador web y nos dirigimos al sitio oficial de WinRAR
    para descargar el instalador correspondiente a nuestro sistema operativo.
  </p>

  <img
    src="https://i.imgur.com/iWDn1th.png"
    alt="Página oficial de descarga de WinRAR"
    width="800"
  />

  <h3>2. Abrir la carpeta de descargas</h3>

  <p>
    Una vez finalizada la descarga, abrimos el Explorador de archivos de
    Windows y nos dirigimos a la carpeta <strong>Descargas</strong>.
  </p>
  <p>
    Localizamos el archivo de instalación de WinRAR, hacemos clic derecho
    sobre él y seleccionamos <strong>Ejecutar como administrador</strong>.
  </p>

  <img
    src="https://i.imgur.com/IS7ctb0.png"
    alt="Carpeta Descargas con el instalador de WinRAR"
    width="800"
  />

  <h3>3. Instalar WinRAR</h3>

  <p>
    En la ventana de instalación, revisamos la ubicación de destino y
    seleccionamos <strong>Instalar</strong>.
  </p>

  <img
    src="https://i.imgur.com/02ZY7gU.png"
    alt="Ventana de instalación de WinRAR"
    width="800"
  />

  <h3>4. Finalizar la instalación</h3>

  <p>
    Antes de finalizar el proceso seleccionamos todas la opcones que muestra la imagen y por ultimo,esperamos a que finalice el proceso. Seleccionamos<strong>Aceptar</strong> para finalizar.
  </p>

  <img
    src="https://i.imgur.com/NIahjFj.png"
    alt="Ventana de configuración final de WinRAR"
    width="800"
  />

  <p>
    <strong>¡Listo!</strong> Ya tenemos WinRAR instalado y preparado para
    descomprimir los archivos que utilizaremos en la instalación de Kali Linux.
  </p>
</section>

<section id="instalacion-kali-linux">
  <h2 style="display: inline-block; border-bottom: 2px solid #ffffff; padding-bottom: 5px;">Instalación de Kali Linux</h2>

  <p>
    En esta sección descargaremos Kali Linux, prepararemos sus archivos
    y lo incorporaremos a VirtualBox para crear nuestro entorno de
    prácticas de ciberseguridad.
  </p>

  <h3>1. Descargar Kali Linux</h3>

  <p>
    Abrimos nuestro navegador web y accedemos al sitio oficial de Kali Linux.
    seleccionamos la opción <strong>Maquinas virtuales</strong> "NO seleccionamos imagenes del instalador" y buscamos la versión compatible con <strong>VirtualBox</strong>.
  </p>

  <img
    src="https://i.imgur.com/dlAPoXD.png"
    alt="Página oficial de descarga de Kali Linux para máquinas virtuales"
    width="800"
  />

  <p>
    Descargamos el archivo correspondiente a virtualbox y esperamos a que finalice
    el proceso.
  </p>

  <img
    src="https://i.imgur.com/yB2yDHs.png"
    alt="Página oficial de descarga de Kali Linux para máquinas virtuales"
    width="800"
  />

  <h3>2. Descomprimir los archivos de Kali Linux</h3>

  <p>
    Una vez finalizada la descarga, abrimos la carpeta
    <strong>Descargas</strong> y localizamos el archivo comprimido de Kali Linux.
  </p>

  <p>
    Hacemos clic derecho sobre el archivo, seleccionamos
    <strong>WinRAR</strong> y elegimos la opción
    <strong>Extraer aquí</strong> o <strong>Extraer en...</strong>,
    según dónde deseemos guardar los archivos.
  </p>

  <p>
    Esperamos a que finalice la extracción. Al terminar, tendremos disponible
    la carpeta con los archivos de la máquina virtual.
  </p>

  <img
    src="https://i.imgur.com/ezQWrSP.png"
    alt="Extracción de los archivos comprimidos de Kali Linux con WinRAR"
    width="800"
  />

  <h3>3. Añadir Kali Linux a VirtualBox</h3>

  <p>
    Abrimos <strong>VirtualBox</strong> y seleccionamos el botón
    <strong>Añadir</strong>. Luego nos dirigimos a la carpeta donde
    descomprimimos Kali Linux y seleccionamos el archivo de la máquina virtual,
    normalmente con extensión <strong>.vbox</strong>.
  </p>

  <p>
    Confirmamos la selección para incorporar la máquina virtual a VirtualBox.
  </p>

  <img
    src="https://i.imgur.com/kOmnGkU.png"
    alt="Selección del archivo de la máquina virtual de Kali Linux en VirtualBox"
    width="800"
  />
  <p>
    Abrimos <strong>Continuación</strong> y replicaremos las configuraciones que estan en las siguientes imagenes.
  </p>

  <img
    src="https://i.imgur.com/IeHy9gs.png"
    alt="Selección del archivo de la máquina virtual de Kali Linux en VirtualBox"
    width="800"
  />
  <img
    src="https://i.imgur.com/zrjE1z7.png"
    alt="Selección del archivo de la máquina virtual de Kali Linux en VirtualBox"
    width="800"
  />
  <p>
    Las demas secciones, como : pantalla, almacenamiento, audio, las dejaremos por defecto. 
  </p>

  <h3>4. Iniciar Kali Linux</h3>

  <p>
    Seleccionamos la máquina virtual de Kali Linux y hacemos clic en
    <strong>Iniciar</strong>.
  </p>

  <p>
    Cuando aparezca el menú de arranque, seleccionamos con la tecla
    <strong>Enter</strong> la opción:
  </p>

  <pre><code>Kali GNU/Linux</code></pre>

  <img
    src="https://i.imgur.com/hRBVs14.png"
    alt="Inicio de Kali Linux y pantalla de acceso al sistema"
    width="800"
  />
 
  <p>
    Una vez cargado el sistema, ingresamos las credenciales de acceso:
  </p>

  <ul>
    <li><strong>Usuario:</strong> kali</li>
    <li><strong>Contraseña:</strong> kali</li>
  </ul>

  <img
    src="https://i.imgur.com/sZ50szc.png"
    alt="Inicio de Kali Linux y pantalla de acceso al sistema"
    width="800"
  />
  
  <p>
    <strong>¡Listo!</strong> Ya tenemos Kali Linux incorporado a VirtualBox
    y preparado para continuar con los siguientes proyectos del curso.
  </p>
</section>

<section>
  <h2>Continuación del curso</h2>

  <p>
    <strong>
      <a href="URL_REPOSITORIO_VIDEO_2">
        Video 2 - Actualización de Kali Linux
      </a>
    </strong>
  </p>
</section>
