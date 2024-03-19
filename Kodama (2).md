
# Kodama

### LPIC-1 - Enero - Marzo 2024





   * Asistencia obligatoria mínima del 75% de horas del curso.
   * Pruebas de evaluación intermedia y final. Hay que superarlas con una nota mínima de 5 sobre 10
   * Finalización (Diplomas): 
       * Aprovechamiento (APTO/A) -> prueba final aprobada + 75% asistencia
       * Asistencia (NO APTO/A) -> 75% asistencia
#### PUE

   * El examen de **certificación LPIC1-101** no está incluido en el curso del SEPE, pero el PUE tiene la deferencia de proporcionarlo de forma gratuita si se cumple lo siguiente:
       * El alumno ha conseguido el diploma de aprovechamiento.
       * El alumno se ha unido al programa "PUE Alumni" ( [https://sepe.pue.es/pue-alumni](https://sepe.pue.es/pue-alumni) ) antes de la finalización del curso (tiene un coste de 60€ + IVA anuales). Dicho programa tiene otras ventajas, como descuentos a otras certificaciones (LPIC1-102). 
       * [https://www.pue.es/cursos/alumni](https://www.pue.es/cursos/alumni)
#### **Dudas y consultas**

   * Para consultas sobre los cursos: **sepe.bcn@pue.es**
   * Para incidencias de acceso aula virtual/entornos: [https://help.pue.es](https://help.pue.es)
   * Para consultas sobre certificaciones: [https://exam.pue.es/help/](https://exam.pue.es/help/)


## Logística

   * **Tenemos distintos materiales para el curso: **
       * Los de el Linux Professional Institute,
       * los de NetAcad (Cisco) 
       * y los que proporciona PUE.
   * Como el orden de los mismos es distinto, priorizaremos el que sigue el orden más estricto para la certificación, es decir el de la Fundación Linux. Además, el de NetAcad es autoexplicativo con Labs incluidos, así que el material de NetAcad lo dejaremos para que lo hagáis vosotros en casa y os sirva de repaso.
   * [https://github.com/ether/etherpad-lite/wiki/Sites-That-Run-Etherpad#sites-that-run-etherpad](https://github.com/ether/etherpad-lite/wiki/Sites-That-Run-Etherpad#sites-that-run-etherpad) - Otros sitios que tiene Etherpad público
### Material del curso de la Linux Professional Institute

   * [https://www.lpi.org/es/our-certifications/lpic-1-overview](https://www.lpi.org/es/our-certifications/lpic-1-overview) - LPIC-1
   * **010 - Essentials, sin certificación, este contenido se da por sabido**
       * [https://www.lpi.org/es/our-certifications/linux-essentials-overview](https://www.lpi.org/es/our-certifications/linux-essentials-overview) - Temario 010
       * [https://learning.lpi.org/pdfstore/LPI-Learning-Material-010-160-es.pdf](https://learning.lpi.org/pdfstore/LPI-Learning-Material-010-160-es.pdf) - **PDF** de 447 pág
   * **101 - Primera parte del curso**
       * [https://learning.lpi.org/es/learning-materials/101-500/](https://learning.lpi.org/es/learning-materials/101-500/) - Temario 101
       * [https://www.lpi.org/es/our-certifications/exam-101-objectives](https://www.lpi.org/es/our-certifications/exam-101-objectives) - Objetivos del **Examen 101**
       * [https://learning.lpi.org/pdfstore/LPI-Learning-Material-101-500-es.pdf](https://learning.lpi.org/pdfstore/LPI-Learning-Material-101-500-es.pdf) - **PDF** de 571 pág
   * **102 - Segunda parte del curso**
       * [https://learning.lpi.org/es/learning-materials/102-500/](https://learning.lpi.org/es/learning-materials/102-500/) - Temario 102
       * [https://www.lpi.org/es/our-certifications/exam-102-objectives](https://www.lpi.org/es/our-certifications/exam-102-objectives) - Objetivos del **Examen 102**
       * [https://learning.lpi.org/pdfstore/LPI-Learning-Material-102-500-es.pdf](https://learning.lpi.org/pdfstore/LPI-Learning-Material-102-500-es.pdf) - **PDF** de 594 pág
### NetAcad

   * Tenemos disponible, hasta el 5 de abril, acceso al material del curso, con laboratorios incluidos en la página de NetAcad (propiedad de CISCO):
       * [https://www.netacad.com/](https://www.netacad.com/)
   * El acceso al material es 24x7, podéis acceder en cualquier horario.
   * Si hacéis los exámenes dentro de la plataforma, al aprobar te dan un badge de Credly que puedes poner en linkedin
   * **Laboratorios con máquinas virtuales dentro de NetAcad**
       * El password de root es: **netlab123**
       * Para cambiar el teclado dentro de la terminal en los labs al español, con el comando
           * **-->** **loadkeys es**
       * Para escribir la** tubería "|"**, podemos hacerlo de varias formas, dependiendo del tipo de teclado físico que tengamos, y del idioma de la máquina remota:
           * **-->** **loadkeys es **, y luego pulsamos** "AltGr + <"** o también **"AltGr + 1"**
           * **-->** **loadkeys gb **, y luego pulsamos **"<" **o también** "Ç"**
           * Pulsando** "ALT + 124"** del teclado numérico
       * **IMPORTANTE**: 
           * Una vez que acabamos un laboratorio, podemos cerrar la pestaña del navegador del mismo, PERO, las máquinas virtuales guardan el estado del laboratorio durante unas horas. 
           * Esto implica que, si hacemos un laboratorio y después otro, las máquinas permanecen en el estado del laboratorio anterior, pudiendo dar problemas. Por ejemplo, si en un laboratorio ponemos el teclado en español, en el siguiente ya estará el teclado en español. 
           * Esto puede dar problemas con algunos segundos o terceros laboratorios, con lo que, a partir del segundo laboratorio, es recomendable antes de empezar, darle a **reset** a las máquinas virtuales.
   * [https://www.netacad.com/courses/os-it](https://www.netacad.com/courses/os-it) - Otros cursos de Linux. Los siguientes son gratuitos:
       * NDG Linux Unhatched (8 horas)
       * NDG Linux Essentials (70 horas) (este está en español)
### Entorno de Labs del PUE

   * [https://labs.pue.es/](https://labs.pue.es/) - Panel de control de las máquinas virtuales para los labs, a través de Guacamole.
       * **Passwords:**
           * pue** : cangetin**
           * root** : toor**
       * [https://help.pue.es](https://help.pue.es) - Soporte, en caso de problemas
   * **El horario de acceso a las máquinas es el mismo del curso**. Fuera del horario del curso no tenéis acceso a las máquinas
   * **No actualicéis las máquinas**, no es necesario, y además, como son versiones de hace unos años, tardaría demasiado y cambiaría el entorno.
   * Las máquinas se paran solas 15 minutos después de acabar el curso. Se pueden encender desde 15 minutos antes de empezar el curso.
   * Las máquinas tardan un poquito en arrancar, (en estar disponibles). Lo que es importante es que vosotros apaguéis de forma ordenadas las máquinas, por qué si no, si no responden al apagarlas, se les hace un destruir, con lo que pueden tardar luego en arrancar (tienen que chequear el FS).
### **Máquinas para practicar (Ubuntu 22.04 LTS y CentOS 7.9)**

   * **Sin instalar nada, online**
       * [https://www.onworks.net/](https://www.onworks.net/) - El password de root es: **123456**
           * [https://www.onworks.net/component/content/article?id=65750:free-centos-workstation-online](https://www.onworks.net/component/content/article?id=65750:free-centos-workstation-online) - **CentOS**
           * [https://www.onworks.net/component/content/article?id=65734:free-debian-online](https://www.onworks.net/component/content/article?id=65734:free-debian-online) - **Debian**
           * [https://www.onworks.net/component/content/article?id=587225:free-ubuntu-online-version-22](https://www.onworks.net/component/content/article?id=587225:free-ubuntu-online-version-22) - **Ubuntu 22.04**
       * [https://distrosea.com/](https://distrosea.com/) - Aquí tenemos las últimas versiones (CentOS 9 y Debian 12)
           * [https://distrosea.com/select/centosstream/](https://distrosea.com/select/centosstream/) - **CentOS**
           * [https://distrosea.com/select/debian/](https://distrosea.com/select/debian/) - **Debian**
           * [https://distrosea.com/start/ubuntu-22.04-default/](https://distrosea.com/start/ubuntu-22.04-default/) - **Ubuntu 22.04**
   * **Máquinas virtuales ya instaladas, solo descargar e importar en VirtualBOX (o VMware)**
       * [https://www.virtualbox.org/](https://www.virtualbox.org/) - **VirtualBox**, hypervisor open source gratuito para instalarlo en vuestro equipo y dentro importar las siguientes máquinas virtuales:
       * [https://www.osboxes.org/](https://www.osboxes.org/) - **OSBoxes**, repositorio con cientos de máquinas virtuales.
           * [https://www.osboxes.org/centos/](https://www.osboxes.org/centos/) - **CentOS** para **VirtualBox**
           * [https://www.osboxes.org/debian/](https://www.osboxes.org/debian/) - **Debian** para **VirtualBox**
           * [https://www.osboxes.org/ubuntu/](https://www.osboxes.org/ubuntu/) - **Ubuntu** para **VirtualBox**
           * **Credenciales por defecto:**
               * username: **osboxes**
               * password: **osboxes.org**
               * []root[] password: **osboxes.org**
#### **VPS gratis, pero hay que instalar el SSOO de forma manual**

       * [https://apuntesit.tk/tutoriales/como-obtener-2-vps-gratis-para-siempre/](https://apuntesit.tk/tutoriales/como-obtener-2-vps-gratis-para-siempre/) - Como tener dos VPS gratis de por vida en la cloud de Oracle
       * [https://aws.amazon.com/es/ec2/pricing/?loc=ft#Free\_tier]([]https://aws.amazon.com/es/ec2/pricing/?loc=ft#Free\_tier[]) - En Amazon AWS
   * **Instalarlo de forma nativa en Windows. Esta forma es la más insegura si vamos a trastear, podemos romper Windows**
       * [https://ubuntu.com/tutorials/install-ubuntu-on-wsl2-on-windows-11-with-gui-support](https://ubuntu.com/tutorials/install-ubuntu-on-wsl2-on-windows-11-with-gui-support) - WSL2


### Comandos interesantes

   * Con el comando **script <fichero>** podemos grabar lo que pasa en la terminal. 
       * Cuando queramos parar la grabación, tecleamos **exit**. 
       * Para ver la grabación, lo podemos hacer con** less -r <fichero>**
   * **grep -n**  me muestra el numero de línea de lo que encuentra. 
       * **vim -c <num\_linea>** me lleva directamente a esa línea.
   * **file** me da información acerca del formato de un fichero




## Tema Introductorio Inicial

   * [https://es.wikipedia.org/wiki/Unix](https://es.wikipedia.org/wiki/Unix) - UNIX nace oficialmente el 1 de enero de 1970
   * Mundo UNIX, dos versiones:
       * **BSD** - FreeBSD
       * **System V** - Linux.  Dentro de System V, existen dos grandes ramas, más una tercera basada en **LFS** (Linux From Scratch)
           * **Red Hat** - CentOS - Oracle - Alma Linux - Rocky Linux - Fedora
           * **Debian** - Ubuntu - Linux Mint - Kali Linux
           * [https://www.linuxfromscratch.org/](https://www.linuxfromscratch.org/) - **LFS**, para crear tu propia distribución desde cero. Esto es ya muy PRO :P
               * **ArchLinux** y derivados entran en esta categoría. Derivados más o menos conocidos: **BlackArch**, **Manjaro**, **SteamOS**, **SystemRescue**.
           * [https://es.wikipedia.org/wiki/Anexo:Distribuciones\_GNU/Linux\_de\_Espa%C3%B1a](https://es.wikipedia.org/wiki/Anexo:Distribuciones\_GNU/Linux\_de\_Espa%C3%B1a) - Distribuciones Linux en España
       * Al comando **ps** se le pueden pasar opciones en los tres formatos: BSD, System V, GNU. Ver la página del manual: **man ps**
   * [https://es.wikipedia.org/wiki/Principio\_KISS](https://es.wikipedia.org/wiki/Principio\_KISS) - **Principio KISS** - Keep IT Simple Stupid. Mantener las cosas lo más sencillo posible. En Unix, cada comando hace solo una cosa, pero lo hace muy bien.
   * [https://es.wikipedia.org/wiki/Bash](https://es.wikipedia.org/wiki/Bash) - **Bash**, shell por defecto que vamos a usar
       * [https://es.wikipedia.org/wiki/Categor%C3%ADa:Shell\_de\_Unix](https://es.wikipedia.org/wiki/Categor%C3%ADa:Shell\_de\_Unix) - Otras Shells de Unix
       * El Tabulador es mi amigo
       * Concatenación de comandos simples para hacer tareas complejas
       * Cada proceso es totalmente independiente
   * **En UNIX todo es un fichero**
   * En UNIX se distingue entre mayúsculas y minúsculas
   * En UNIX si un comando es exitoso, no muestra ningún tipo de información.




## Materia del curso

### Para dominar Linux necesitamos controlar 4 temas importantes:

   * Ayuda del sistema - **Curso 010 - Tema 2.2**
   * Gestión del software - **Tema 102**
   * Gestión de procesos - **Tema 103.5**
   * Registros del sistema (logs) - **Tema 108.2**
### Otras materias básicas:

   * SystemD - **Temas 101.3, 107.2 **(cron)** 108.2** (logs) **109.2** (red)
   * Diferencias entre tipos de comillas - **Tema 103.1**
   * globbing - **Tema 103.3**
   * Regex - **Tema 103.7**
   * vi - **Tema 103.8**
   * Permisos - **Tema 104.5**
   * Enlaces - **Tema 104.6**
   * scripting - **Tema 105.2**
   * sudo - **Tema 110.1**




### Ayuda

   * **man** -> Ayuda principal del sistema (MANual). Está dividida en páginas temáticas, siendo las más importantes la 5, la 8 y la 1.
       * **man man** -> Ayuda sobre man.
       * **man 1** -> /bin/ comandos que puede ejecutar cualquier usuario (ej. man 1 ls)
       * **man 8** -> /sbin/ comandos de root (ej. man 8 fdisk)
       * **man 5** -> **ficheros de configuración** (ej. man 5 fstab)
       * **man 7** -> ayuda genérica (ej. man 7 units)
           * **-->** ls -1 /usr/share/man/man7 | cut -d"." -f1 | sort | xargs whatis 2>/dev/null | grep '(7)' #Ver todas las páginas de ayuda de la sección 7
       * **man 2** -> llamadas al sistema
       * **man 3** -> funciones de lenguajes de programación
       * **man 4** -> dispositivos (devices)
       * **man 6** -> juegos
   * **less** -> es el paginador por defecto, se usa dentro del **man**, en el **vi** (Tema 103.8), y en otros comandos. Así que si aprendemos a utilizarlo, sabremos movernos dentro del man, del vi, etc..
       * **g** --> vamos al principio del documento.
       * **G** --> vamos al final.
       * **/texto** --> Busca **texto** dentro del documento, y me posiciona en esa línea.
           * **n** --> busca la siguiente vez que aparece **texto**, y me lleva a esa línea.
           * **N** --> busca la anterior vez que aparece **texto**, y me lleva a esa línea.
       * **h** --> Ayuda, listado de atajos de teclado
       * **q** --> Salimos
   * **mandb** -> genera una base de datos con la primera linea de todas las páginas del Manual, la linea en la que se describe cada comando
   * . Esa base de datos luego es usada por los dos comandos siguientes. En RHEL6 y anteriores el comando se llama makewhatis.
       * **whatis** -> busca palabras completas en la base de datos (ej. whatis ls). Es equivalente a **man -f**.
       * **apropos** -> busca cadenas en la base de datos (ej. apropos ls). Es equivalente a **man -k**.
   * **info** -> sistema de ayuda alternativo a man.
       * **info info** -> ayuda sobre info.
       * **pinfo** -> Una mejor alternativa a info (info coloreado, se ve todo mucho mejor)
       * **n** --> Siguiente página
       * **p** --> Página previa
       * **u** --> Vuelve al nivel padre
       * Para ir a un link, nos posicionamos en el, y pulsamos **Enter**
       * **q** --> Salida
   * **- -help** -> resumen de opciones de un comando (ej. ls - -help).
   * **updatedb** -> genera una base de datos con todos los ficheros accesibles en ese momento del sistema. Almacena el camino completo, el path completo. Por defecto no indexa ficheros en medio removibles o remotos (NFS, SAMBA). Debe ser ejecutado como root. Existe una tarea automatizada para que se actualize todas las noches (con el Cron).
       * **locate** -> busca en la base de datos la cadena especificada, incluido el path (ej. locate 7/READ).
       * Solo puedes ver lo que está en directorios a los que puedes acceder
   * **find** -> busca en tiempo real ficheros. Muy configurable, tiene muchas opciones interesantes.
   * **/usr/share/doc** -> directorio con cientos de megabytes de documentación en varios formatos.
       * **du -sh /usr/share/doc** --> Me muestra cuanto ocupa el directorio
   * **grep -R cadena /etc/*** -> buscar cadena en el contenido de todos los ficheros del directorio /etc
   * Además, hay paquetes específicos de documentación en algunos programas, que podemos encontrar con los siguientes comandos:
       * **$ yum search manual**
       * **$ yum search documentation**




### Leyenda

   * **103.1 - 4p - C1,2y4L - Trabajar desde la línea de comandos**
       * **103.1** - Sección de la documentación de LPI
       * **4p** - 4 preguntas de examen en esta sección
       * **C1,2y4** - Capítulos 1, 2 y 4 del material de NetAcad
       * El resto es el título de esa sección
       * Si tiene una **L** detrás de los capítulos, es que ese tema tiene Lab




## Examen 101, primera parte del curso, 60 preguntas



### Tema 101 - 8p - Arquitectura del Sistema

   * **101.1 - 2p - C15L - Determinar y configurar los ajustes de hardware**
       * Comandos para inspeccionar los dispositivos detectados: **lspci** y **lsusb**.
       * Comandos para administrar módulos del núcleo del sistema operativo: **lsmod** y **modprobe**.
       * Archivos especiales relacionados con los dispositivos, ya sean los archivos que se encuentran en el directorio /**dev**/ o en los pseudo-sistemas de archivos en /**proc**/ y /**sys**/.
       * [https://www.profesionalreview.com/2018/04/01/como-verificar-la-informacion-sobre-el-hardware-en-linux/](https://www.profesionalreview.com/2018/04/01/como-verificar-la-informacion-sobre-el-hardware-en-linux/) - Cómo verificar la información sobre el hardware en Linux
       * **[]architecnologia.es[]**
           * [https://architecnologia.es/lpic-1-101-1-dispositivos-de-bloques-vs-dispositivos-de-caracteres](https://architecnologia.es/lpic-1-101-1-dispositivos-de-bloques-vs-dispositivos-de-caracteres) - LPIC-1 101.1: dispositivos de bloques vs dispositivos de caracteres y más…
           * [https://architecnologia.es/lpic-1-101-1-comprendiendo-sys-udev-y-dbus](https://architecnologia.es/lpic-1-101-1-comprendiendo-sys-udev-y-dbus) - LPIC-1 101.1:  comprendiendo /sys, udev y dbus
           * [https://architecnologia.es/lpic-1-101-1-information-gathering-y-manipulacion-de-hardware](https://architecnologia.es/lpic-1-101-1-information-gathering-y-manipulacion-de-hardware) - LPIC-1 101.1: information gathering y manipulación de hardware
   * **101.2 - 3p - C16 -** **Arranque del sistema**
       * **-->** man 7 bootparam
       * Una opción muy interesante para añadir a la línea del kernel, es **nomodeset**, arranca la tarjeta gráfica en modo compatible, para evitar problemas con la misma (si por ejemplo, al arrancar linux, se ve mal la pantalla)
       * **-->** dmesg #Me permite ver todo lo que ha hecho el kernel durante el `proceso de arranque
       * **Targets (SystemD) **vs** Runlevels (Init)**
           * shutdown.target   - runlevel **0**: Halt
           * emergency.target  - Menos que el runlevel 1
           * rescue.target     - runlevel **1**: Single-User Mode
           * multi-user.target - runlevels **2** and **3**: Multi-User Mode
           * graphical.target  - runlevel **5**: Graphical Mode
           * reboot.target     - runlevel **6**: Reboot
       * **[]architecnologia.es[]**
           * [https://architecnologia.es/lpic-1-101-2-secuencia-arranque](https://architecnologia.es/lpic-1-101-2-secuencia-arranque) - LPIC-1 101.2: comprendiendo la secuencia de arranque
           * [https://architecnologia.es/lpic-1-101-systemd-sysv](https://architecnologia.es/lpic-1-101-systemd-sysv) - LPIC-1 101.2: SysV vs systemd (Lo vemos en el siguiente tema)
   * **101.3 - 3p - C18L -** **Cambiar los niveles de ejecución / objetivos de arranque y apagar o reiniciar el sistema**
       * **man 7 bootup**
       * Hacemos el **lab** 18 de NetAcad (solo viene el inicio en formato init de System V)
       * **SystemD**
           * [https://manuais.iessanclemente.net/index.php/Gesti%C3%B3n\_del\_Sistema\_con\_Systemd](https://manuais.iessanclemente.net/index.php/Gesti%C3%B3n\_del\_Sistema\_con\_Systemd) - Gestión del sistema con **SystemD**
           * [https://www.freedesktop.org/software/systemd/man/index.html](https://www.freedesktop.org/software/systemd/man/index.html) -  Páginas del manual de **SystemD**
           * [https://fedoraproject.org/wiki/Systemd/es](https://fedoraproject.org/wiki/Systemd/es) - **SystemD**
           * [https://without-systemd.org/wiki/index\_php/Arguments\_against\_systemd/](https://without-systemd.org/wiki/index\_php/Arguments\_against\_systemd/) - Argumentos contra **SystemD**
           * **Orden de preferencia de directorios**
               * **/usr/lib/systemd/system/<unit>** - Directorio original donde se instalan por defecto las units. No debemos tocar nada en este directorio, porque se machaca en cada actualización.
               * **/run/systemd/<unit>** - Si queremos cambiar algo del fichero de configuración de forma temporal, lo copiamos a esta localización y lo editamos. Pero al estar en **/run** se pierde al rebotar. Si lo quiero hacer persistente, lo meto en **/etc**
               * **/etc/systemd/system/<unit>** -  Directorio con mayor preferencia, pero puede existir o no.  Copio aquí el fichero de configuración de la unit, y de esta forma es persistente lo que yo cambie en el.
           * **Comandos**:
               * **alias servicios="systemctl --no-page --no-legend --plain -t service --state=running"**
               * **alias sockets='systemctl --no-page --no-legend --plain -t socket --state=running'**
               * **systemctl daemon-reload** - Comando para indicarle a **systemd** que hemos tocado un fichero de configuración por nuestra cuenta y que relea y aplique todos los ficheros de configuración.
       * **[]architecnologia.es[]**
           * [https://architecnologia.es/lpic-1-101-3-runlevels-boot-targets](https://architecnologia.es/lpic-1-101-3-runlevels-boot-targets) - LPIC-1 101.3: runlevels \& boot targets
           * [https://architecnologia.es/lpic-1-101-3-comandos-reboot-y-shutdown](https://architecnologia.es/lpic-1-101-3-comandos-reboot-y-shutdown) - LPIC-1 101.3: comandos reboot y shutdown


### Tema 102 - 12p - Instalación de Linux y gestión de paquetes

   * **102.1 - 2p - C19 - Diseño del esquema de particionado del disco duro duro**
       * [https://es.wikipedia.org/wiki/Filesystem\_Hierarchy\_Standard](https://es.wikipedia.org/wiki/Filesystem\_Hierarchy\_Standard) - Estándar que especifica que contenido debe ir en cada directorio en los sistemas UNIX.
       * **Swap**
           * free -h \&\& sync \&\& echo \&\& **echo 3 > /proc/sys/vm/drop\_caches** \&\& free -h # Para limpiar la caché
       * **[]architecnologia.es[]**
           * [https://architecnologia.es/lpic-1-102-1-diseno-del-espacio-de-particionamiento](https://architecnologia.es/lpic-1-102-1-diseno-del-espacio-de-particionamiento) - LPIC-1 102.1: diseño del espacio de particionamiento
           * [https://architecnologia.es/lpic-1-102-1-herramientas-y-creacion-de-particiones](https://architecnologia.es/lpic-1-102-1-herramientas-y-creacion-de-particiones) - LPIC-1 102.1: herramientas y creación de particiones
   * **102.2 - 2p - C17L - Instalar un gestor de arranque**
       * En la línea del **GRUB** que empieza por "**linux**" puedo poner algunas opciones extras:
           * **nomodeset** - para arrancar en modo gráfico a prueba de fallos gráficos (entraría en modo VGA normal, sin usar tarjetas gráficas)
           * **noacpi** - si tenemos problemas con el gestor de energía (se apaga la máquina durante el arranque), podemos desactivarlo. El sistema no podrá entrar en modo de ahorro de energía, pero por lo menos arranca.
           * **init=/bin/bash** - en vez de lanzar el systemd como proceso 1, lanza el bash. Esto implica que entramos directamente en el bash como root SIN que te pida el password de root
       * **Lab 17** de **GRUB**
       * **Límites**:
           * MBR puede gestionar hasta 4 particiones primarias y hasta 2TB de disco
           * GPT (UEFI) puede gestionar hasta 128 particiones primarias y hasta 9ZB de disco
       * **[]architecnologia.es[]**
           * [https://architecnologia.es/lpic-1-gestor-de-arranque](https://architecnologia.es/lpic-1-gestor-de-arranque) - LPIC-1 102.2: el gestor de arranque
   * **102.3 - 1p - C25L - Gestión de librerías compartidas**
       * **ldd** - comando para ver las librerías compartidas usadas por un binario dado
       * **[]architecnologia.es[]**
           * [https://architecnologia.es/lpic-1-102-3-gestion-de-bibliotecas-compartidas](https://architecnologia.es/lpic-1-102-3-gestion-de-bibliotecas-compartidas) - LPIC-1 102.3: gestión de bibliotecas compartidas
   * **102.4 - 3p - C24L - Gestión de paquetes Debian**
       * Ver Chuleta\_apt.txt
       * **/etc/apt/sources-list** - fichero con los repositorios
           * **/etc/apt/sources.list.d** - Directorio con los repositorios
       * **[]architecnologia.es[]**
           * [https://architecnologia.es/lpic-1-102-4-gestion-de-paquetes-deb](https://architecnologia.es/lpic-1-102-4-gestion-de-paquetes-deb) - LPIC-1 102.4: gestión de paquetes DEB
   * **102.5 - 3p - C24L - Gestión de paquetes RPM y YUM**
       * Hacemos el Lab24
       * Ver Chuleta\_rpm.txt
       * [https://paraisolinux.com/dkms-que-gran-invento/](https://paraisolinux.com/dkms-que-gran-invento/) - **dkms**, que gran invento
       * [https://access.redhat.com/documentation/en-us/red\_hat\_enterprise\_linux/6/html/deployment\_guide/sec-yum-transaction\_history](https://access.redhat.com/documentation/en-us/red\_hat\_enterprise\_linux/6/html/deployment\_guide/sec-yum-transaction\_history) - yum history
       * **epel, epel-release** - Repositorio de paquetes extras de Fedora para RHEL
       * **fasttrack** - Repositorio con paquetes actualizados más frecuentemente
       * **/etc/yum.repos.d** - Directorio con los repositorios
       * **--scripts** - opción que añadimos al comando rpm para ver los scripts que ejecuta un rpm al instalarlo o desinstalarlo
       * Cuando actualizo un RPM, no machaca los ficheros de configuración, los mantiene como están.
       * **laboratorio "ls" (en Red Hat)**
           * ls
           * which ls
           * rm /bin/ls # Elimino el binario
           * ls # No funciona, lo he borrado
           * dir # Si no tengo el comando ls, puedo usar dir
           * rpm -qf /bin/ls
           * yum provides /bin/ls
           * rpm -V coreutils
           * yum reinstall coreutils ~~/ yum install coreutils~~
       * **[]architecnologia.es[]**
           * [https://architecnologia.es/lpic-1-102-5-gestion-de-paquetes-rpm](https://architecnologia.es/lpic-1-102-5-gestion-de-paquetes-rpm) - LPIC-1 102.5: gestión de paquetes RPM
   * **102.6 - 1p - C26 - Linux como sistema virtualizado**
       * **Tipos de virtualización**
           * **Tipo 1**: *bare-metal hypervisor*, no necesita un SSOO, el ordenador arranca directamente con el hipervisor: **Xen**
           * **Tipo 2**: Aplicación de escritorio que me permite crear y gestionar Máquinas virtuales: **VirtualBox**
           * **KVM** puede funcionar como Tipo 1 y Tipo 2. Por ejemplo: **Proxmox** (Tipo 1)
       * **Tipos de Máquinas virtuales**
           * **Totalmente virtualizado**: La MV desconoce que está siendo virtualizada. Tiene que estar activa la virtualización por hardware en la BIOS (o UEFI). Podemos virtualizar cualquier SSOO.
           * **Paravirtualizado**: La MV sabe que está siendo virtualizada, a través de un núcleo o kernel modificado (no vale cualquier SSOO). Tiene la ventaja respecto al otro, que gestiona mejor la concurrencia de peticiones a los recursos HW.
           * **Híbrido: **Combinación que recoje lo mejor de ambos mundos: el SSOO no está modificado, con lo que podemos virtualizar cualquier sistema, pero los drivers de acceso a los recursos "externos" a la máquina, como disco, red, cpu, etc, están paravirtualizados y gestionan mejor la concurrencia a los mismos. **KVM + QEMU (VirtIO)**
       * **KVM**
           * Para ver si la máquina está virtualizada:
               * virt-what 
               * dmesg | grep virt
               * lsmod | grep kvm
           * Virtualización anidada
               * cat /sys/module/kvm\_amd/parameters/nested # Para ver los parámetros del módulo kvm\_amd, en este caso, si permite virtualización anidada
               * npt - Nested Page Tables, el flag que nos permite la virtualización anidada
           * **kernel - kvm - libvirt - virtio (Qemu) - MV** # Orden de comunicación entre componentes
           * **Qemu**
               * [https://es.wikipedia.org/wiki/QEMU](https://es.wikipedia.org/wiki/QEMU)
           * **Virtio**
               * locate virtio | grep -e ko.xz$ 
           * **libvirt**
               * cd /var/lib/libvirt/
                   * /etc/libvirt
                   * [https://libvirt.org](https://libvirt.org)
           * [https://es.wikipedia.org/wiki/Dnsmasq](https://es.wikipedia.org/wiki/Dnsmasq) - **dnsmasq** - Servicio DNS y DHCP, usado por libvirt
           * [https://www.ovirt.org/download/](https://www.ovirt.org/download/) - **oVirt** - Plataforma de virtualización, base de Red Hat Enterprise Virtualization
           * **ksm** - Kernel Shared Memory 
           * **Almacenamiento**
               * **COW** - Copy-on-write (también conocido como thin-provisioning o sparse images)
                   * Para crear un fichero de tipo **sparse**, que aparentemente ocupe 10TB pero no ocupe nada:
                       * **dd if=/dev/zero of=fichero.sparse bs=1T count=0 seek=10**
                   * [https://es.wikipedia.org/wiki/Archivo\_disperso](https://es.wikipedia.org/wiki/Archivo\_disperso) - Archivo de tipo sparse
               * **RAW** - full-provisioning
           * **Conexión gráfica a la MV**
               * **VNC** - Ineficiente, inseguro
               * **RDP** - Usado por Microsoft
               * **Spice** - Seguro, adaptativo, eficiente, tuneliza otros protocolos, como USB, sonido, etc..
           * **tuned** # Para tunear el sistema con perfiles predefinidos
               * /usr/lib/tuned # Localización de los perfiles
               * cockpit # Para gestionar un sistema via web, de forma remota
                   * systemctl enable --now cockpit.socket
                   * me conecto al puerto 9090 de esa máquina
       * **cloud-init**
           * [https://onthedock.github.io/post/181009-cloud-init/](https://onthedock.github.io/post/181009-cloud-init/) - Automatizando la personalización de máquinas virtuales con cloud-init
           * [https://access.redhat.com/documentation/es-es/red\_hat\_enterprise\_linux/8/html/configuring\_and\_managing\_cloud-init\_for\_rhel\_8/introduction-to-cloud-init\_cloud-content](https://access.redhat.com/documentation/es-es/red\_hat\_enterprise\_linux/8/html/configuring\_and\_managing\_cloud-init\_for\_rhel\_8/introduction-to-cloud-init\_cloud-content) - Introducción a cloud-init
       * **Contenedores**. Se basan en cuatro componentes principales:
           * [https://www.ionos.es/digitalguide/servidores/know-how/que-es-lxc/](https://www.ionos.es/digitalguide/servidores/know-how/que-es-lxc/) - Qué es **LXC**
               * [https://www.linuxadictos.com/incus-el-fork-de-lxd-que-busca-ofrecer-un-proyecto-comunitario-real.html](https://www.linuxadictos.com/incus-el-fork-de-lxd-que-busca-ofrecer-un-proyecto-comunitario-real.html) - **Incus**, el fork de **LXC** tras su polémica "absorción" por Canonical
           * **namespaces**
               * Nos permite separar nombres de recursos, al estar en distintos espacios de trabajo.
               * Por ejemplo, en dos Contenedores distintos podemos tener un proceso con el mismo PID, porque están en espacios separados.
               * De esta forma no tenemos que preocuparnos de como llamemos a los recursos dentro de un contenedor, no hay posibilidad de colisión.
               * El kernel nos permite nombrar recursos como PIDs, usuarios, redes, etc..
               * [https://es.wikipedia.org/wiki/Espacio\_de\_nombres](https://es.wikipedia.org/wiki/Espacio\_de\_nombres)
           * **cgroups**
               * [https://elpuig.xeill.net/Members/vcarceler/articulos/introduccion-a-los-grupos-de-control-cgroups-de-linux](https://elpuig.xeill.net/Members/vcarceler/articulos/introduccion-a-los-grupos-de-control-cgroups-de-linux) - Introducción a los grupos de control (cgroups) de Linux
           * **SELinux / AppArmor (LSM - Linux Security Models)**
               * [https://es.wikipedia.org/wiki/SELinux](https://es.wikipedia.org/wiki/SELinux)
           * **Seccomp BPF**
               * El filtrado Seccomp ofrece un medio para limitar el número de system calls que expone el kernel a un determinado proceso.
               * **Seccomp BPF** (SECure COMputing with filters) son filtros expresados como un programa BPF (Berkeley Packet Filter).
               * [https://web.archive.org/web/20201027130513/https://clibre.io/blog/por-secciones/hardening/item/405-computacion-segura-con-filtros-seccomp-bpf](https://web.archive.org/web/20201027130513/https://clibre.io/blog/por-secciones/hardening/item/405-computacion-segura-con-filtros-seccomp-bpf)
       * **Lab para instalar una MV**
           * apt install virt-manager libvirt-client # En Ubuntu
           * yum install virt-manager libvirt-client # En CentOS
           * mkdir /var/lib/libvirt/isos
           * [https://mirrors.almalinux.org/isos/x86\_64/9.2.html](https://mirrors.almalinux.org/isos/x86\_64/9.2.html) - Para bajarme la ISO
       * **Otras distros**
           * Proxmox - Plataforma de virtualización, es KVM en Debian
           * Qubes - El SO más seguro, cada proceso es virtualizado con Xen
       * [https://www.brendangregg.com/linuxperf.html](https://www.brendangregg.com/linuxperf.html) - MegaExperto en Linux de Netflix
       * **[]architecnologia.es[]**
           * [https://architecnologia.es/lpic-1-102-6-linux-como-anfitrion-virtualizacion](https://architecnologia.es/lpic-1-102-6-linux-como-anfitrion-virtualizacion) - LPIC-1 102.6: Linux como huésped (virtualización)




### Tema 103 - 26p - Comandos GNU y Unix

   * **103.1 - 4p - C1,2Ly4L** **- Trabajar desde la línea de comandos**
       * **history**
           * **!!** - se refiere al comando anteriormente introducido en la línea de comandos
               * sudo !! # truco para ejecutar con el sudo el comando anterior
           * !X** **# Cambiando la X por un número, volvemos a ejecutar el comando número X del histórico
       * Tanto el comando **which** como el comando **whereis**, me indican donde está un binario dado, pero con una diferencia fundamental: **which** solo me indica su primera aparición en el **PATH**, mientras que **whereis** me indica todas sus apariciones y las páginas del man asociadas. La opción **-a**, con el comando **which**, muestra todas las apariciones del comando dado.
       * Para ejecutar un comando y no ejecutar su alias asociado, le anteponemos el carácter "**\**":
           * **\ls**
       * **Valores especiales de algunos caracteres**
           * Las comillas **sencillas** quitan el valor especial de cualquier carácter
           * Las comillas **dobles** quitan el valor especial de todos los caracteres, EXCEPTO para  **$,** **`**, **\** y, en ciertos casos, **!**
           * La **\** quita el valor especial del siguiente carácter
       * **-->** comando=ls #Definimos el contenido de la variable **comando** a "ls"
       * **-->** echo "$comando" #Vemos el contenido de la variable **comando**
       * ls
       * 

       * **-->** echo '$comando' #Quitamos el significado especial del **$** que hay dentro
       * $comando
       * 

       * **-->** echo \$comando  #Quitamos el significado especial al siguiente carácter de la **\**, en este caso el **$**
       * $comando
       * 

       * **-->** echo `$comando` #Se desaconseja el uso de las comillas invertidas
       * mi\_fichero
       * 

       * **-->** echo $($comando) #Mejor de esta forma para ejecutar lo que hay dentro
       * mi\_fichero
       * 

       * Comandos vistos: **pwd, uname, man, type, which, history, echo, env, export, unset**
       * 🇬🇧 [https://cmdchallenge.com](https://cmdchallenge.com) - Página con desafíos para gente que empieza de cero
       * **bash** - atajos de teclado
           * **ALT+.** o **ESC+.** --> poner el ultimo parámetro del comando anterior
           * **CNTRL+r** --> búsqueda inversa en la línea de comandos
               * ENTER - lo ejecuta
               * ESC - me lo deja en la línea de comandos sin ejecutarlo
           * **CNTRL+l** --> limpiar la pantalla (hacer un **clear**)
           * [https://esgeeks.com/atajos-de-teclado-linux-bash/](https://esgeeks.com/atajos-de-teclado-linux-bash/) - Muchos más atajos
       * **[]architecnologia.es[]**
           * [https://architecnologia.es/lpic-1-103-1-trabajo-linea-de-comandos-linux](https://architecnologia.es/lpic-1-103-1-trabajo-linea-de-comandos-linux) - LPIC-1 103.1: introducción al trabajo con la línea de comandos
   * **103.2 - 2p - C3L - Procesar secuencias de texto usando filtros**
       * Comandos vistos: **cat, bzcat, xzcat, zcat, less, head, tail, wc, sort, uniq, od, nl, sed, tr, cut, paste, split, md5sum, sha256sum, sha512sum**
       * **xxd** - visor hexadecimal
       * **trucos de sed**
           * sed -n ‘/INICIO/,/FIN/p’ fichero **# Sacar el texto entre dos cadenas de texto**
           * sed -i '17 s/^/#/' <filename> **# Comenta la línea 17 de un fichero**
           * sed -n '10,20p' <filename> **# Imprime las lineas 10 a 20 de un fichero**
           * [https://www.commandlinefu.com/commands/using/sed](https://www.commandlinefu.com/commands/using/sed) - Ejemplos de trucos usando el comando sed
       * **[]architecnologia.es[]**
           * [https://architecnologia.es/lpic-1-103-2-procesar-secuencias-de-texto-usando-filtros](https://architecnologia.es/lpic-1-103-2-procesar-secuencias-de-texto-usando-filtros) - LPIC-1 103.2: procesar secuencias de texto usando filtros
   * **103.3 - 4p - C4L,5L,6Ly12L - Administración básica de archivos**
       * **ls -A** -  ver todos los ficheros y directorios ocultos, excepto el **.** y el **..**
       * **Comodines**
           * **? (signo de interrogación) **: representa **una** sola aparición de un carácter cualquiera.
           * **[] (corchetes)** - representa cualquier aparición de los caracteres encerrados entre corchetes. **PERO SOLO UNO DE ELLOS**. 
               * **[11131111114]** --> un **1** un **3** o un **4**.
               * **[0-299999]** --> un **0** un **1** un **2** o un **9**.
               * **[12-40]** --> un **0** un **1** un **2** un **3** o un **4**.
           * *** (asterisco)** - representa **cero**, **una** o **más** ocurrencias de cualquier caracter.
       * **find**
           * find . -type d -empty -delete **# Encuentra y borra directorios vacios**
           * find /proc -name "smaps" | xargs grep Swap 2>/dev/null | egrep -v "0 kB|task" **# Ver los procesos que están utilizando swap**
           * find  . -ctime -1  -printf "%a %f\n" **# Encuentra ficheros que han cambiado en las últimas 24 horas**
       * **[]architecnologia.es[]**
           * [https://architecnologia.es/lpic-1-tema-103-3-realizar-una-gestion-basica-de-los-ficheros-y-directorios](https://architecnologia.es/lpic-1-tema-103-3-realizar-una-gestion-basica-de-los-ficheros-y-directorios) - LPIC-1 Tema 103.3: realizar una gestión básica de los ficheros y directorios
   * **103.4 - 4p - C10L - Uso de secuencias de texto, tuberías y redireccionamientos**
       * **xargs** - Para pasar argumentos a través de la tubería en el lugar que nos convenga en el comando que le indiquemos, en el caso que el comando no escuche por la entrada estandar.
           * find . -iname '*.mp3' -type f -print0 | xargs -i -0 cp {} {}.backup **# Encuentra ficheros con la extensión mp3 y duplícalos con la extensión .backup**
       * set -o noclobber ; set -C **# dos formas equivalentes para indicarle al bash que no sobrescriba ficheros con el redireccionamiento ">"**
       * 2>\&1 **# Para redireccionar la salida de errores (2) a la estandar (1), mezclándose ambas en la 1, y de esa formap poder enviar la salida de errores a través de la tubería**
       * **[]architecnologia.es[]**
           * [https://architecnologia.es/lpic-1-tema-103-4-flujos-tuberias-redirecciones](https://architecnologia.es/lpic-1-tema-103-4-flujos-tuberias-redirecciones) - LPIC-1 Tema 103.4: flujos, tuberías y redirecciones
   * **103.5 - 4p - C11L - Crear, supervisar y matar procesos**
       * **-->** apt install x11-apps # Para instalar xeyes en Ubuntu / Debian
       * Guión
           * sudo yum install xeyes
           * echo hola
           * mato el xeyes
           * lanzo xeyes y mato la terminal
           * lanzo xeyes y hago cntrl-c
           * xeyes \&
           * job - pid
           * cat /proc/PID/cmdline
           * cntrl+z
           * bg 1
           * xeyes \& x4
           * jobs
           * nohup xeyes \&
           * grep -i PID /proc/PID/status
           * disown
           * kill -l
           * kill 3828
           * señales 15 y 9
           * señales 19 y 18
           * señal 1, service reload sshd
           * man 7 signal
           * xkill
           * pidof
           * killall
           * ps auxwf
           * grep [x]eyes
           * xwininfo y xprop
           * top
           * htop
           * prioridades
           * sudo yum install -y screen
       * Comandos: **fg, bg, \&, ^Z, ^C, nohup, disown, kill, xkill, killall, pkill, pidof, pgrep, top, dd, ps, pstree**
       * **-->** grep -i ppid /proc/<PID del proceso>/status # Vemos el PPID del proceso
       * **-->** xwininfo # Me da información de la ventana en la que pinche
       * **-->** watch -n 0.5 -d ls # ejecutar ls cada 0,5 segundos
       * **Listado de señales más usadas**
           * **SIGHUP (1)** - Reload, relee el fichero de configuración y aplica los cambios
           * **SIGINT (2)** - Equivale a CNTRL+C
           * **SIGKILL (9)** - Muerte incondicional
           * **SIGTERM (15) **- Muerte ordenada, termina lo que estés haciendo y muere
           * **SIGCONT (18)** - Continua un proceso parado
           * **SIGSTOP (19)** - Para el proceso
       * **top** me muestra información de consumo de recursos del sistema
           * [https://learn.microsoft.com/es-es/troubleshoot/developer/webapps/aspnetcore/practice-troubleshoot-linux/3-2-task-managers-top-htop](https://learn.microsoft.com/es-es/troubleshoot/developer/webapps/aspnetcore/practice-troubleshoot-linux/3-2-task-managers-top-htop) - Uso de **top** y **htop**
           * **e**: Cambia la visualización de la memoria entre porcentaje, kilobytes (KB) y megabytes (MB).
           * **k**: kill
           * **r**: renice
           * **-->** top -p $(pidof xeyes | tr " " ",") # Muestra top con los procesos de xeyes
           * **Consumo de CPU**, medido en porcentaje de uso de CPU:
               * **us** - procesos ejecutándose en espacio de usuario
               * **sy** - procesos ejecutándose en espacio del systema
               * **ni** - procesos con prioridad más alta de la normal (nice)
               * **id** - iddle, sin hacer nada
               * **wa** - waiting, esperando por disco o red
               * **hi** - tiempo gastado en atender interrupciones de tipo hard
               * **si** - tiempo gastado en atender interrupciones de tipo soft
               * **st** - stolen, tiempo robado por el hypervisor
           * Otros tops: **htop, powertop, bashtop **(solo Ubuntu, en CentoS se llama **btop**)**, glance, nethogs**
       * Comandos: **screen, tmux**
       * **[]architecnologia.es[]**
           * [https://architecnologia.es/lpic-1-crear-monitorizar-matar-procesos](https://architecnologia.es/lpic-1-crear-monitorizar-matar-procesos) - LPIC-1 Tema 103.5: crear, monitorizar y matar procesos
   * **103.6 - 2p - C11L - Modificar la prioridad de ejecución de los procesos**
       * Comandos: **nice, renice**
       * **[]architecnologia.es[]**
           * [https://architecnologia.es/lpic-1-tema-103-6-modificar-la-prioridad-de-procesos-en-ejecucion](https://architecnologia.es/lpic-1-tema-103-6-modificar-la-prioridad-de-procesos-en-ejecucion) - LPIC-1 Tema 103.6: modificar la prioridad de procesos en ejecución
   * **103.7 - 3p - C8L - Realizar búsquedas en archivos de texto usando expresiones regulares**
       * **regex**: Expresiones Regulares
           * 🇬🇧 [https://regexr.com/](https://regexr.com/) - Una página muy chula para comprobar una expresión regular en tiempo real.
           * 🇬🇧 [https://regex101.com/](https://regex101.com/) - Otra
           * 🇬🇧 [https://www.debuggex.com/](https://www.debuggex.com/) - Otra
       * **[]architecnologia.es[]**
           * [https://architecnologia.es/lpic-1-tema-103-7-buscar-texto-con-expresiones-regulares](https://architecnologia.es/lpic-1-tema-103-7-buscar-texto-con-expresiones-regulares) - LPIC-1 Tema 103.7: buscar texto con expresiones regulares
   * **103.8 - 3p - C9L - Edición básica de archivos - vi**
       * **export EDITOR=/usr/bin/vi** # para definir el vi como editor por defecto
       * **Para aprender vi:**
           * **LANG=es\_ES.UTF8 vimtutor** # Comando que te abre el vi en modo tutorial en español
           * [https://openvim.com/tutorial.html](https://openvim.com/tutorial.html)
           * [https://vim-adventures.com/](https://vim-adventures.com/)
       * **Configuraciones interesantes**
           * **set list** # Muestra los caracteres no visibles
           * **set number (set nu)** # Numera las líneas
       * Para modificar el comportamiento del vi de forma persistente, añadimos en el fichero** ~/.vimrc** los cambios que queramos hacer:
           * **syntax on** - Activar detección de sintaxis con colores (si instalamos el paquete vim-enhanced lo hace automáticamente)
           * **set number** - mostrar número de línea
           * **set mouse=a** - para que funcione el ratón en modo texto
           * Para cambiar el tabulador por defecto (que son 8 caracteres), lo podemos hacer con lo siguiente:
               * **set tabstop=4** - Cambia el tamaño a 4 espacios para texto en general
               * **set shiftwidth=4** - Cambia el tamaño a 4 espacios, si estás editando código en cualquier lenguaje de programación
               * **set expandtab** - Substituye el carácter de tabulador por espacios en blanco
       * **[]architecnologia.es[]**
           * [https://architecnologia.es/lpic-1-tema-103-8-edicion-basica-de-archivos](https://architecnologia.es/lpic-1-tema-103-8-edicion-basica-de-archivos) - LPIC-1 Tema 103.8: edición básica de archivos
### 

### Tema 104 - 14p - Dispositivos, sistemas de archivos Linux y el estándar de jerarquía de archivos

   * **104.1 - 2p - C20 - Creación de particiones y sistemas de archivos**
       * partprobe # Para forzar al kernel a releer la tabla de particiones, **si no se hace, se puede perder el contenido del disco entero**
       * Tipos de particiones usadas por Linux
           * 82 Linux swap / Solaris
           * 83 Linux
           * 8e Linux LVM
       * **[]architecnologia.es[]**
           * [https://architecnologia.es/lpic-1-tema-104-1-crear-particiones-y-sistemas-de-archivos](https://architecnologia.es/lpic-1-tema-104-1-crear-particiones-y-sistemas-de-archivos) - LPIC-1 Tema 104.1: crear particiones y sistemas de archivos
   * **104.2 - 2p - C22Ly23L - Mantener la integridad de los sistemas de archivos**
       * **[]architecnologia.es[]**
           * [https://architecnologia.es/lpic-1-104-2-mantener-integridad-filesystem](https://architecnologia.es/lpic-1-104-2-mantener-integridad-filesystem) - LPIC-1 Tema 104.2: mantener la integridad de los sistemas de ficheros
   * **104.3 - 3p - C21L - Controlar el montaje y desmontaje de los sistemas de archivos**
       * lsof - Se ve en el Tema 110
       * [https://access.redhat.com/documentation/es-es/red\_hat\_enterprise\_linux/8/html/managing\_file\_systems/common-mount-options\_assembly\_mounting-file-systems](https://access.redhat.com/documentation/es-es/red\_hat\_enterprise\_linux/8/html/managing\_file\_systems/common-mount-options\_assembly\_mounting-file-systems) - Opciones de montaje por defecto (defaults)
       * mount -o remount,rw /mnt/disco # Para remontar un FS que está en modo de solo lectura, en modo lectura escritura
       * [https://rm-rf.es/atime-noatime-y-relatime/](https://rm-rf.es/atime-noatime-y-relatime/) - Diferencias entre atime, noatime y relatime
       * **[]architecnologia.es[]**
           * [https://architecnologia.es/lpic-1-control-montaje-desmontaje-fs](https://architecnologia.es/lpic-1-control-montaje-desmontaje-fs) - LPIC-1 Tema 104.3: Control del montaje y desmontaje de FS
   * **~~104.4 - 0p - C24 - Cuotas de disco (no entra en el examen)~~**
   * **104.5 - 3p - C13L - Administración de los permisos y los propietarios de los archivos**
       * [https://howtoforge.es/que-es-umask-en-linux/](https://howtoforge.es/que-es-umask-en-linux/) - uso de umask
       * **[]architecnologia.es[]**
           * [https://architecnologia.es/lpic-1-gestion-permisos-propiedad-archivos-linux](https://architecnologia.es/lpic-1-gestion-permisos-propiedad-archivos-linux) - LPIC-1 Tema 104.5: Gestión de permisos y propiedad de archivos
   * **104.6 - 2p - C14L - Crear y cambiar enlaces duros y simbólicos**
       * **[]architecnologia.es[]**
           * [https://architecnologia.es/lpic-1-creacion-modificacion-enlaces-simbolicos-duros](https://architecnologia.es/lpic-1-creacion-modificacion-enlaces-simbolicos-duros) - LPIC-1 Tema 104.6: crear y modificar enlaces duros y simbólicos
   * **104.7 - 2p - C7L - Encontrar archivos de sistema y ubicar archivos en el lugar correspondiente**
       * Ver tema de ayuda
       * **[]architecnologia.es[]**
           * [https://architecnologia.es/lpic-1-fhs-sistema-archivos](https://architecnologia.es/lpic-1-fhs-sistema-archivos) - LPIC-1 Tema 104.7: jerarquía FHS y localización de ficheros y directorios




## Examen 102, segunda parte del curso, 60 preguntas



### Tema 105 - 8p - Shells y scripts

   * **105.1  - 4p - C1L - Personalizar y usar el entorno de shell**
       * **Tipos de Shell y ficheros**
           * **Shells de inicio de sesión / Sin inicio de sesión**
               * Dependiendo si el usuario accede al sistema por medio sus credenciales, como el nombre de usuario y la contraseña, o no.
               * **/etc/profile**: se ejecuta cuando **cualquier** usuario **inicia sesión**. Es general y afecta a todos los usuarios del sistema. Existe un directorio, llamado **/etc/profile.d/** en el que poner nuestros ficheros **.sh** personalizados
               * **~/.profile** (Debian) o** ~/.bash\_profile** (RH): igual al anterior, pero afecta solo a nuestro usuario o usuario actual.
                   * **~/.bash\_login**: Bash permite algunos sinónimos para **.profile** como es éste. 
                   * Si **.bash\_profile** no existe se buscará primero **.bash\_login** y si tampoco está, busca **.profile**. 
                   * Si hay varios, solo se lee el primero que encuentre.
               * **~/.bash\_logout**: es el fichero que lee Bash cuando se sale del sistema o sesión. Se pueden definir algunas tareas como eliminar ficheros temporales generados durante la sesión, registrar el tiempo de sesión del usuario, etc. Si no existe, no se ejecutará nada al salir.
           * **Shells interactivos / No interactivos**
               * Se refiere a la comunicación entre el usuario y la shell: Si interactuamos con la shell mediante el teclado y vemos la salida en la pantalla o no. No interactivo sería un script
               * **/etc/bashrc**: se ejecuta cada vez que cualquier usuario ejecuta **bash**. Es general y afecta a **todos** los usuarios del sistema.
               * **~/.bashrc **o** ~/.bash\_bashrc**: igual a /etc/bashrc pero para un usuario particular, como es el usuario actual al que pertenece. Los cambios solo afectarán a él.
       * **Distintos tipos de shells de inicio**
           * **Shell de inicio de sesión interactivo como user2**
               * **su - user2 **# Pide el password de user2
               * **sudo su - user2 **# Pide mi password, pero solo funciona si está configurado en el sudoers
           * **Shell de inicio de sesión interactivo como root**
               * **su - root ; su -**
               * **sudo su - root ; sudo su - ; sudo -i**
           * **Shell interactivo de no inicio de sesión como user2**
               * **su user2**
               * **sudo su user2 ; sudo -u user2 -s**
           * **Shell interactivo de no inicio de sesión como root**
               * **su root ; su**
               * **sudo su root ; sudo su ; sudo -s**
       * Para saber en qué tipo de shell estamos trabajando, podemos escribir **echo $0 **en la terminal y obtener la siguiente salida:
           * **-bash or -su **# Inicio de sesión interactivo
           * **bash or /bin/bash **# Sin inicio de sesión interactivo
           * **<name\_of\_script> **# Sin inicio de sesión no interactivo (scripts)
       * **echo ${PEPE}illo** # Muestra el contenido de la variable $PEPE concatenada con la cadena "illo"
       * **declare **es una función interna del **bash**, que me permite declarar funciones, y que admite las siguientes opciones:
           * **-i** para definir variables numéricas que contienen enteros
           * **-r** para definir variables readonly (lo mismo que el comando **readonly**)
           * **-x** para exportar la variable a subshells (lo mismo que **export**)
       * **Variables**
           * **LANG=es\_ES.UTF-8 cal** # Para ejecutar un comando en un idioma determinado
           * **LANG=C** # Si tenemos el idioma inglés por defecto, las horas las pone en formato AM/PM, lo cual es horrible si queremos ordenarlo por horas. El truco es cambiar el idioma a C, que aunque sigue siendo inglés, ahora si, las horas me las pone en formato 24 horas.
       * **alias**
           * Cuando se usan comillas con variables de entorno, las comillas simples hacen que la expansión sea dinámica.
               * **$ alias where?='echo $PWD'**
               * **$ where?**
               * **/home/user2**
               * **$ cd Music**
               * **$ where?**
               * **/home/user2/Music**
           * Sin embargo, con las comillas dobles la expansión se hace de forma estática en el momento de asignar el alias, y ya no cambia.
               * **$ alias where?="echo $PWD"**
               * **$ where?**
               * **/home/user2**
               * **$ cd Music**
               * **$ where?**
               * **/home/user2**
       * **Varios / Avanzado**
           * **ps auxw | grep [b]ash** # Para no ver el comando en el resultado del grep 
       * **[]architecnologia.es[]**
           * [https://architecnologia.es/lpic-1-tema-shell-scripting](https://architecnologia.es/lpic-1-tema-shell-scripting) - LPIC-1 Tema 105.1: shell y shell scripting
   * **105.2 - 4p - C2L - Personalizar y escribir scripts sencillos**
       * **renice 15 -p $$** # Truco para bajar la prioridad de un script, ejecutándolo dentro del propio script
       * **|| y \&\&**
           * **||** es el **OR** lógico
           * **\&\&** es **AND** lógico
           * **(ls /root \&>/dev/null \&\& echo "tengo permisos de root" ) || echo "no tengo permisos de root"** # si se ejecuta como root, dice que tiene permisos, y si se ejecuta como cualquier otro usuario, dice que no tiene permisos
       * **Opciones de depuración de bash**
           * **set -x** # muestra las lineas que va ejecutando
           * **set -e** # para al primer error
           * **set -n** # lee el script, pero no lo ejecutes, para buscar errores
           * **trap 'read -u1' debug** # Añade un read detrás de cada línea del script, para pausarlo y que tengas que darle a enter
               * [https://stackoverflow.com/questions/9080431/how-execute-bash-script-line-by-line](https://stackoverflow.com/questions/9080431/how-execute-bash-script-line-by-line)
           * [https://github.com/koalaman/shellcheck](https://github.com/koalaman/shellcheck) - Chequeador de scripts
           * [https://www.baeldung.com/linux/debug-bash-script](https://www.baeldung.com/linux/debug-bash-script) - Debugging a Bash Script
       * **IFS**
           * **$IFS** es la variable que define el separador entre campos (*Internal Field Separator*). Por defecto su valor es: espacio en blanco, tabulador, salto de linea.
           * El problema surge, cuando tengo nombres de ficheros que contienen espacios en blanco, ya que dentro de un script lo gestiona mal. Para resolverlo, puedo redefinir el valor de **$IFS** dentro del script. Por ejemplo, para que solo contemple como separador el salto de línea, con: 
               * **IFS=$'\n'**
           * El valor por defecto es:
               * **IFS=$' \t\n'** # o también puedo hacer: **unset IFS**
           * [https://www.baeldung.com/linux/ifs-shell-variable](https://www.baeldung.com/linux/ifs-shell-variable) - The Meaning of **IFS** in Bash Scripting
       * **Varios / Avanzado**
           * Ejecutar el script al completo como root (shebang) (no recomendado)
               * **#!/usr/bin/sudo /bin/bash**
           * [https://devhints.io/bash](https://devhints.io/bash) - Bash scripting cheatsheet
       * **[]architecnologia.es[]**
           * [https://architecnologia.es/lpic-1-tema-105-2-modificar-o-escribir-scripts-sencillos](https://architecnologia.es/lpic-1-tema-105-2-modificar-o-escribir-scripts-sencillos) - LPIC-1 Tema 105.2: Modificar o escribir scripts sencillos




### Tema 106 - 4p - Interfaces de usuario y escritorios

   * **106.1 - 2p - C3L - Instalar y configurar X11**
       * **Sistema de ventanas X - X Window**
           * Es el responsable de las operaciones gráficas básicas como dibujar los iconos, los fondos y las ventanas en las que se ejecutan las aplicaciones.
           * Es el propio **servidor** **Xorg**
           * El servidor X ejecuta el driver de video real y proporciona una interfaz a través de la cual otros programas pueden ejecutar órdenes de dibujo sin conocer qué hardware está usándose
       * **Window Manager - Gestor de ventanas**
           * Añade elementos alrededor de las ventanas, de forma que el usuario pueda cambiar el tamaño, cerrar, ocultar, mover, …
           * También controla la barra de título, la ventana en el foco y comandos y ratón que afectan a dicha ventana
           * [https://wiki.archlinux.org/title/Window\_manager\_(Espa%C3%B1ol%29](https://wiki.archlinux.org/title/Window\_manager\_(Espa%C3%B1ol%29) - Gestores de Ventanas
       * **Display Manager - Gestor de Pantalla / Administrador de pantalla**
           * Es una parte **opcional** del sistema X Window que se usa para el manejo de sesiones, ya que gestiona el registro de usuario (inicio y fin de sesión). 
           * Forma parte del cliente X.
       * **Entorno de escritorio**
           * El entorno de escritorio puede ser, desde un simple gestor de ventanas, hasta un conjunto muy completo de aplicaciones de escritorio. En realidad es lo que “ve” el usuario después de abrir la sesión.
           * En general, permiten la coordinación entre aplicaciones y ofrecen un entorno uniforme de trabajo
           * Un entorno de escritorio consta, al menos de las siguientes aplicaciones clientes X:
               * Gestor de ventanas.
               * Administrador de Vistas.
               * Barra de tareas.
               * Gestor de archivos.
               * Conjunto de aplicaciones
           * [https://es.wikipedia.org/wiki/Entorno\_de\_escritorio](https://es.wikipedia.org/wiki/Entorno\_de\_escritorio) - Entornos de escritorio libres
           * La variable **$DISPLAY**, identifica la máquina (nombre o IP) en la que se está ejecutando el servidor X y el monitor y nº de pantalla virtual. La sintaxis es: 
               * **DISPLAY**: hostname**:**display**.**screen
                   * **hostname**: hostname de la máquina. Si este campo no aparece, entonces es localhost.
                   * **display**: nº de monitor conectado al servidor (comienza en 0); 
                   * **screen**: nº de pantalla virtual (comienza en 0). Si son dos monitores actuando como uno solo unido, no aparece este parámetro. Solo aparece si cada monitor es independiente.
           * **startx** # Una vez que entras en un sistema con el entorno de texto (runlevel 3), y si el entorno gráfico está instalado pero no activo, se puede levantar con este comando
       * **[]architecnologia.es[]**
           * [https://architecnologia.es/lpic-1-tema-106-1-introduccion-a-x11](https://architecnologia.es/lpic-1-tema-106-1-introduccion-a-x11) - LPIC-1 Tema 106.1: introducción a X11
   * **106.2 - 1p - C4L - Escritorios gráficos**
       * **xdpyinfo** # Muestra información sobre el servidor X en ejecución
       * **xprop** # Para ver las propiedades de una ventana
       * **yum provides *bin*system-config*** # Buscar utilidades de configuración gráfica
       * **ssh -X 172.168.8.1 **# Conectarme por ssh a otra máquina, definiendo la variable DISPLAY para poder reenviar la ventana gráfica de la aplicación de una maquina a otra
       * **krusader, mc** --> gestores de archivos de doble panel (twin panel)
       * **zenity**
           * **zenity --warning --title=Aviso --text="🐧 al poder"** # Para interactuar gráficamente con un script
           * **zenity --entry --title=Pregunta --text="Ponga aquí su contestación"**
           * **zenity --display=:0**
           * [https://howtoforge.es/como-mostrar-dialogos-gui-en-un-script-bash-usando-zenity/](https://howtoforge.es/como-mostrar-dialogos-gui-en-un-script-bash-usando-zenity/)
       * **[]architecnologia.es[]**
           * [https://architecnologia.es/lpic-1-tema-106-2-entornos-de-escritorio](https://architecnologia.es/lpic-1-tema-106-2-entornos-de-escritorio) - LPIC-1 Tema 106.2: entornos de escritorio
   * **106.3 - 1p - C5L - Accesibilidad**
       * **Teclas adhesivas/pegajosas/persistentes (sticky keys)** - Cuando esta función se activa, las combinaciones de teclas como Ctrl + C no necesitan ser presionadas al mismo tiempo. El usuario puede pulsar primero la tecla Ctrl , soltarla y luego pulsar la tecla C. Esto está pensado para usuarios con movilidad en solo una mano, o solo un dedo.
       * **Teclas de rebote /rechazo de teclas (Bounce keys)** - Agrega un retardo entre pulsaciones, es decir, una nueva pulsación de tecla será aceptada sólo después de que haya transcurrido un tiempo determinado desde la última pulsación de la misma. Esto está pensado para usuarios con temblores en las manos.
       * **Teclas lentas (slow keys)** - Requiere que el usuario mantenga pulsada la tecla durante un tiempo determinado antes de ser aceptada. Esto también está pensado para usuarios con temblores en las manos, es posible que está activo a la vez que lo anterior.
       * **[]architecnologia.es[]**
           * [https://architecnologia.es/lpic-1-tema-106-3-accesibilidad-la-gran-olvidada](https://architecnologia.es/lpic-1-tema-106-3-accesibilidad-la-gran-olvidada) - LPIC-1 Tema 106.3: Accesibilidad, la gran olvidada…




### Tema 107 - 12p - Tareas administrativas

   * **107.1 - 5p - C6L - Administrar cuentas de usuario y de grupo y los archivos de sistema relacionados con ellas**
       * **/etc/login.defs** # Opciones por defecto al crear nuevos usuarios
       * **/etc/adduser.conf** # Opciones por defecto del comando useradd
       * **vipw; vigr** # Comandos que nos permiten editar el /etc/passwd y /etc/group, creando una copia de seguridad por defecto
       * **userdel** # La opción -r también elimina el directorio principal del usuario y todos sus contenidos
       * [https://bytelearning.blogspot.com/2016/04/fichero-nsswitchconf-que-es-y-para-que.html](https://bytelearning.blogspot.com/2016/04/fichero-nsswitchconf-que-es-y-para-que.html) - **/etc/nsswitch.conf**
       * **sssd** # servicio que gestiona las credenciales contra un servidor remoto (AD, kerberos, LDAP...)
       * **find /home -nouser** # Para encontrar ficheros y directorios que no pertenecen a ningún usuario
       * **system-config-users** # Red Hat tiene una herramienta gráfica de gestión de usuarios, que no está instalada por defecto. Tenemos que instalarla nosotros.
       * **Hashes**
           * [https://gchq.github.io/CyberChef/#recipe=MD5(%29](https://gchq.github.io/CyberChef/#recipe=MD5(%29) - CyberChef, herramienta para calcular distintos algoritmos
           * [https://crackstation.net/](https://crackstation.net/) - Busca passwords a partir de hashes almacenados en una Rainbow table
           * [https://freerainbowtables.com/](https://freerainbowtables.com/) - Para bajarte Rainbow Tables
       * **[]architecnologia.es[]**
           * [https://architecnologia.es/lpic-1-tema-107-1-administracion-de-usuarios-y-grupos](https://architecnologia.es/lpic-1-tema-107-1-administracion-de-usuarios-y-grupos) - LPIC-1 Tema 107.1: administración de usuarios y grupos
   * **107.2 - 4p - C7L - Automatizar tareas administrativas del sistema mediante la programación de trabajos**
       * [https://crontab.guru](https://crontab.guru) - Para probar el cron
       * **CUIDADO**, si especificamos tanto el día del mes, como el día de la semana, se ejecuta cuando cualquiera de los dos se cumple. En el PDF de la Fundación Linux está mal. Ej: 
           * **0 9 13 * 2 echo "cuidado con la mala suerte" **# Esto se ejecuta todos los días 13 y todos los martes del año, a las 9 en punto
           * [https://crontab.guru/cron-bug.html](https://crontab.guru/cron-bug.html) - El bug del cron con la especificación del día de la semana Y el día del mes
       * Si quiero lanzar un mensaje gráfico desde el cron, tengo que pasarle las variables **DISPLAY** y **XAUTHORITY**:
           * *** * * * * export DISPLAY=:0; export XAUTHORITY=~/.Xauthority; notify-send test**
       * **systemctl list-timers** # Para listar los "timers" de SystemD (el equivalente de cron)
       * **[]architecnologia.es[]**
           * [https://architecnologia.es/lpic-1-programacion-tareas](https://architecnologia.es/lpic-1-programacion-tareas) - LPIC-1 Tema 107.2: gestión y programación de tareas
   * **107.3 - 3p - C8L - Localización e internacionalización**
       * **localectl set-locale LANG=es\_US.UTF-8** # Para cambiar las variables locales, a través de **SystemD**
       * **locale** # Para ver las variables locales
       * **/etc/timezone** # Zona horaria por defecto del sistema
       * **/etc/localtime** # Ajuste de la zona horaria, por ejemplo, cuando cambia la hora en verano
       * **/etc/locale.conf** # Idioma por defecto
       * Ver Unicode 
       * **[]architecnologia.es[]**
           * [https://architecnologia.es/lpic-1-tema-107-3-locales](https://architecnologia.es/lpic-1-tema-107-3-locales) - LPIC-1 Tema 107.3: locales e internacionalización




### Tema 108 - 12p - Servicios esenciales del sistema

   * **108.1 - 3p - C9L - Mantener la hora del sistema**
       * rdate hora.roa.es ; LANG=C date # Ver la hora oficial de España
       * **NTP - UDP puerto 123**
           * [https://www.incibe-cert.es/blog/ntp-sntp-y-ptp-sincronizacion-tiempo-necesito](https://www.incibe-cert.es/blog/ntp-sntp-y-ptp-sincronizacion-tiempo-necesito) - Comparativa entre SNTP, NTP y PTP.
           * [https://fedoramagazine.org/secure-ntp-with-nts/](https://fedoramagazine.org/secure-ntp-with-nts/) - NTS, un NTP más seguro (en Red Hat 9 y derivados ya está soportado)
           * [https://github.com/jselvi/Delorean](https://github.com/jselvi/Delorean) - Delorean, un servidor NTP para pentesting
           * [https://www.pool.ntp.org](https://www.pool.ntp.org) - Servidores NTP accesibles en el mundo
               * [https://wiki.bandaancha.st/Lista\_de\_servidores\_NTP\_stratum\_1\_en\_Espa%C3%B1a](https://wiki.bandaancha.st/Lista\_de\_servidores\_NTP\_stratum\_1\_en\_Espa%C3%B1a) - Servidores NTP de estrato 1 en España
           * [https://web.archive.org/web/20230320215748/https://blog.guillen.io/2016/11/04/explicacion-de-la-salida-del-comando-ntpq/](https://web.archive.org/web/20230320215748/https://blog.guillen.io/2016/11/04/explicacion-de-la-salida-del-comando-ntpq/) - Explicación de la salida del comando **ntpq**
               * [https://doc.ntp.org/documentation/4.2.6-series/decode/#peer-status-word](https://doc.ntp.org/documentation/4.2.6-series/decode/#peer-status-word) - Explicación del símbolo que hay antes de cada servidor
       * **[]architecnologia.es[]**
           * [https://architecnologia.es/lpic-1-tema-108-1-hora-sistema](https://architecnologia.es/lpic-1-tema-108-1-hora-sistema) - LPIC-1 Tema 108.1: mantenimiento de la hora en el sistema 
   * **108.2 - 4p - C10L - Registros del sistema**
       * **syslog**
           * **Emergency     0     System unusable messages **
           * **Alert         1     Immediate action required messages **
           * **Critical      2     Critical condition messages **
           * **Error         3     Error condition messages **
           * **Warning       4     Warning condition messages**
           * **Notification  5     Normal but significant messages **
           * **Information   6     Informational messages **
           * **Debugging     7     Debugging messages**
       * **syslogd**
           * En **Ubuntu**, está definido que logs van a que ficheros, en el fichero de configuración:
               * **/etc/rsyslog.d/50-default.conf**
               * El fichero principal de logs en **Ubuntu** y derivados es: **/var/log/syslog**
           * En **Red Hat** la configuración de los logs de **syslogd**, está en:
               * El fichero **/etc/rsyslog.conf** y en el directorio **/etc/rsyslog.d/*.conf**
               * El fichero principal de logs en **Red Hat** y derivados es: **/var/log/messages**
           * **logrotate** me permite gestionar cuanto tiempo almaceno los logs
           * **rsyslog-doc** # paquete extra que hay que instalar para poder tener documentación en formmato html en /usr/share/doc/rsyslog*
       * **Audit**
           * [https://www.solvetic.com/tutoriales/article/4343-como-auditar-linux-auditd-tool-ausearch/](https://www.solvetic.com/tutoriales/article/4343-como-auditar-linux-auditd-tool-ausearch/) - Sistema de auditorias en Linux **Audit**
           * [https://access.redhat.com/documentation/es-es/red\_hat\_enterprise\_linux/8/html/security\_hardening/auditing-the-system\_security-hardening](https://access.redhat.com/documentation/es-es/red\_hat\_enterprise\_linux/8/html/security\_hardening/auditing-the-system\_security-hardening) - Configuración de auditd para un entorno seguro
           * 🇬🇧 [https://www.thegeekdiary.com/how-to-audit-file-access-on-linux/](https://www.thegeekdiary.com/how-to-audit-file-access-on-linux/) - Como usar **Audit**
           * 🇬🇧 [https://gist.github.com/Neo23x0/9fe88c0c5979e017a389b90fd19ddfee](https://gist.github.com/Neo23x0/9fe88c0c5979e017a389b90fd19ddfee) - Best Practice
           * 🇬🇧 [https://access.redhat.com/articles/4409591](https://access.redhat.com/articles/4409591) - Audit explicado
           * **ausearch -c ssh | tail -n 1** - Para ver el último evento sshd
       * **[]architecnologia.es[]**
           * [https://architecnologia.es/lpic-1-tema-108-2-registros-sistema](https://architecnologia.es/lpic-1-tema-108-2-registros-sistema) - LPIC-1 Tema 108.2: registros del sistema
   * **108.3 - 3p - C11L - Conceptos básicos del Agente de Transferencia de Correo**
       * [https://programmerclick.com/article/27301611221/](https://programmerclick.com/article/27301611221/) - Explicación sencilla de los **MTA**, **MDA** y **MUA**
       * **postsuper -d ALL** # para borrar la lista de correos no enviados
       * **mailq | tail -n +2 | awk 'BEGIN { RS = "" } /@Dominioabuscar/ { print $1 }' | tr -d '*!' | sudo postsuper -d -** # borrar determinados correos en cola
       * **mail -s "Asunto" <vuestro-correo> <<<"Mensaje $(curl ifconfig.io)"**
       * **[]architecnologia.es[]**
           * [https://architecnologia.es/lpic-1-tema-108-3-basico-mta](https://architecnologia.es/lpic-1-tema-108-3-basico-mta) - LPIC-1 Tema 108.3: lo básico sobre MTA
   * **108.4 - 2p - C12L - Gestión de la impresión y de las impresoras**
       * **BSD**:
           * **lpr** to print, 
           * **lpq** to view pending jobs, 
           * **lprm** to cancel a job.
       * **System** **V**:
           * **lp** to print, 
           * **lpstat** to view pending jobs, 
           * **cancel** to cancel ongoing jobs.
       * **631: ipp** - puerto del Internet Printing Protocol
       * [https://openprinting.github.io/cups/](https://openprinting.github.io/cups/) - fork de **CUPS** (2020), agregando nuevas funcionalidades, como impresión para dispositivos móviles (**IPP Everywhere**)
       * **[]architecnologia.es[]**
           * [https://architecnologia.es/lpic-1-tema-108-4-impresoras-linux](https://architecnologia.es/lpic-1-tema-108-4-impresoras-linux) - LPIC-1 Tema 108.4: gestión de impresoras e impresión en Linux 




### Tema 109 - 14p - Fundamentos de redes

   * **109.1 - 4p - C13L - Fundamentos de los protocolos de Internet**
       * **IPv4**
           * Clase A - 1-126 /8
           * Loopback internal - 127 /8 
           * Clase B - 128-191  /16
           * Clase C - 192-223   /24
           * Clase D - Multicast - 224-239
           * Clase E - experimental - 240-255
       * [https://www.iptp.net/es\_ES/iptp-tools/ip-calculator/](https://www.iptp.net/es\_ES/iptp-tools/ip-calculator/) - Calculadora de redes
       * El fichero **/etc/services**, en Windows está localizado en:
           *  *C:\Windows\System32\drivers**\etc\services***
       * [https://en.wikipedia.org/wiki/Regional\_Internet\_registry#/media/File:Regional\_Internet\_Registries\_world\_map.svg](https://en.wikipedia.org/wiki/Regional\_Internet\_registry#/media/File:Regional\_Internet\_Registries\_world\_map.svg) - Regiones de internet
       * **IPv6**
           * [https://www.google.es/ipv6/statistics.html#tab=ipv6-adoption](https://www.google.es/ipv6/statistics.html#tab=ipv6-adoption) - Estadísticas de adopción
           * [https://es.wikipedia.org/wiki/IPv6](https://es.wikipedia.org/wiki/IPv6) - **IPv6**
           * [https://es.wikipedia.org/wiki/Neighbor\_Discovery](https://es.wikipedia.org/wiki/Neighbor\_Discovery) - **Neighbor Discovery** (ND) protocolo de IPv6, equivalente al protocolo Address Resolution Protocol (ARP) en IPv4. Está integrado en ICMPv6.
           * **Tipos de IPs**
               * **Unicast** - Identifica una **única** interfaz de red. Por defecto, los 64 bits de la izquierda identifican la red, y los 64 bits de la derecha identifican la interfaz.
               * **Multicast** - Identifica un **conjunto** de interfaces de red. Un paquete enviado a una dirección de multidifusión se enviará a todas las interfaces que pertenezcan a ese grupo. Aunque es similar, no debe confundirse con el **broadcast**, no existe en el protocolo IPv6.
                   * **[ff00::/8] - [ffff::/8]**
               * **Anycast** - Esto también identifica un conjunto de interfaces en la red, pero el paquete reenviado a una dirección anycast será entregado **sólo a una dirección** de ese conjunto, no a todas.
               * **Link-Local - [fe80::/10] [febf::/10]**
                   * [https://openwebinars.net/blog/ipv6-autoconfiguracion-slaac/](https://openwebinars.net/blog/ipv6-autoconfiguracion-slaac/) - Autoconfiguración con **SLAAC**
               * **Unique Local - [fc00::/7] [fdff::/7]**
                   * [https://es.wikipedia.org/wiki/Unique\_Local\_Address](https://es.wikipedia.org/wiki/Unique\_Local\_Address) - El equivalente a las redes locales de Clase C
               * **Localhost - [::1/128]**
               * **Red - [::/128]**
       * **[]architecnologia.es[]**
           * [https://architecnologia.es/lpic-1-tema-109-1-redes](https://architecnologia.es/lpic-1-tema-109-1-redes) - LPIC-1 Tema 109.1: fundamentos de redes
   * **109.2 - 4p - C14L - Configuración de red persistente**
       * **NetworkManager** - servicio de **SystemD** para gestionar la red
           * **nmcli** # comando de NetworkManager en línea de comando para gestionarlo
           * **nmtui** # comando de NetworkManager para levantar el interfaz de usuario en modo texto
           * **nmcli connection reload** # si hemos tocado algún fichero de redes, le decimos a NM que aplique los cambios
           * **systemctl daemon-reload** # Comando para indicarle a **systemd** que hemos tocado un fichero de configuración por nuestra cuenta y que relea y aplique todos los ficheros de configuración.
           * **nmcli connection up/down** # el equivalente a los comandos **ifup** y **ifdown**
       * **Directorios con la configuración de las interfaces de red**
           * **/etc/network/interfaces/** # Sistemas basados en Debian
           * **/etc/sysconfig/network-scripts/** # Sistemas basados en Red Hat
       * 🇬🇧 [https://wiki.debian.org/NetworkInterfaceNames](https://wiki.debian.org/NetworkInterfaceNames) - Evolución de los cambios de nomenclatura de las interfaces de red
       * [https://www.linuxparty.es/enviar-articulos/29-internet/7759-ifconfig-iwconfig-netstat-y-route-han-quedado-obsoletos-en-linux.html](https://www.linuxparty.es/enviar-articulos/29-internet/7759-ifconfig-iwconfig-netstat-y-route-han-quedado-obsoletos-en-linux.html) - ifconfig, iwconfig, netstat y route han quedado **obsoletos** en Linux, ¡artículo de 2012!
           * [https://www.linuxparty.es/enviar-articulos/29-internet/10787-ejemplos-de-comandos-ip-en-linux.html](https://www.linuxparty.es/enviar-articulos/29-internet/10787-ejemplos-de-comandos-ip-en-linux.html) - Ejemplos de uso de **ip **y** ss**
               * **netstat -tulpn  -->   ss -tulpn**
               * **netstat -neopa  -->   ss -neopa**
       * [https://netplan.io/](https://netplan.io/) - **Netplan** en **Ubuntu**. Netplan lee la configuración de red de **/etc/netplan/*.yaml**  Durante el arranque, **Netplan** genera archivos de configuración específicos en **/run** que luego son importados por **NetworkManager** o **systemd-networkd** para configurar la red.
       * [https://bytelearning.blogspot.com/2016/04/fichero-nsswitchconf-que-es-y-para-que.html](https://bytelearning.blogspot.com/2016/04/fichero-nsswitchconf-que-es-y-para-que.html) - /etc/nsswitch.conf
       * [https://www.redhat.com/en/blog/rhel-9-networking-say-goodbye-ifcfg-files-and-hello-keyfiles](https://www.redhat.com/en/blog/rhel-9-networking-say-goodbye-ifcfg-files-and-hello-keyfiles) - Cambios de ficheros a partir de RHEL9
       * [https://github.com/StevenBlack/hosts](https://github.com/StevenBlack/hosts) - Fichero **/etc/hosts** que al instalarlo en nuestra máquina, nos bloquea malware y anuncios
       * **/etc/machine-info** # Este fichero se crea cuando asignamos a nuestra máquina un "pretty name"
       * **[]architecnologia.es[]**
           * [https://architecnologia.es/lpic-1-tema-109-2-configuraciones-redes](https://architecnologia.es/lpic-1-tema-109-2-configuraciones-redes) - LPIC-1 Tema 109.2: configuraciones persistentes de redes 
   * **109.3 - 4p - C15L - Resolución de problemas básicos de red**
       * [https://www.howtouselinux.com/post/ping-icmp](https://www.howtouselinux.com/post/ping-icmp) - Entendiendo el **ping**
       * **nethogs** # herramienta que muestra las conexiones de red en tiempo real
       * **apt install iptraf-ng** # Otra herramienta igual, más completa
       * [https://winmtr.uptodown.com/windows](https://winmtr.uptodown.com/windows) - WinMTR, MTR para windows (Para windows está también pathping)
           * **mtr --aslookup** # Para ver el AS por el que pasa (es lo mismo que **-z**)
       * **Crear una shell remota con netcat (nc)**
           * En la máquina que queremos que se ejecute la shell (en este caso le decimos que escuche solo en **localhost**, si queremos hacerlo desde otra máquina, cambiamos localhost por la IP de la máquina donde estamos ejecutando este comando)
               * **mkfifo pipe**
               * **nc -lv -s localhost -p 4444 <pipe | /bin/bash \&>pipe **# escucho solo en localhost
               * **nc -lv -p 4444 <pipe | /bin/bash \&>pipe** # escucho en cualquier interfaz
               * Cuando se termine la conexión borramos el fichero pipe: **rm pipe**
           * En la máquina remota ejecutamos lo siguiente, y a continuación comandos de la shell. Si es otra máquina distinta, cambiamos localhost por la IP de la máquina remota.
               * **nc localhost 4444**
           * Es mucho más cómodo con la opción -e, aunque es una opción más moderna, y no todas las versiones de nc la admiten:
               * **nc -l -e /bin/bash 4444**
               * En la maquina donde escucho por el puerto 4444, debería abrir dicho puerto en el firewall. Lo que he hecho, por comodidad, es pararlo con: **systemctl stop firewalld.service**
       * **[]architecnologia.es[]**
           * [https://architecnologia.es/lpic-1-tema-109-3-resolucion-problemas-redes](https://architecnologia.es/lpic-1-tema-109-3-resolucion-problemas-redes) - LPIC-1 Tema 109.3: resolución de problemas de redes 
   * **109.4 - 2p -  - Configuración DNS en el lado del cliente**
       * **dig**
           * [https://juncotic.com/dig-opciones-interesantes-para-consultas-dns/](https://juncotic.com/dig-opciones-interesantes-para-consultas-dns/) - Resumen de dig
           * [https://www.hostinger.es/tutoriales/comando-dig-linux](https://www.hostinger.es/tutoriales/comando-dig-linux) - Ejemplos
       * [https://bytelearning.blogspot.com/2016/04/fichero-nsswitchconf-que-es-y-para-que.html](https://bytelearning.blogspot.com/2016/04/fichero-nsswitchconf-que-es-y-para-que.html) - /etc/nsswitch.conf
           * 🇬🇧 [https://linuxsimply.com/getent-command-in-linux/](https://linuxsimply.com/getent-command-in-linux/) - Ejemplos de uso de **getent**, para  chequear el funcionamiento de nsswitch
           * **getent -s dns example.com** # Con la opción **-s** fuerzo a utilizar una fuente de datos concreta
       * **[]architecnologia.es[]**
           * [https://architecnologia.es/lpic-1-tema-109-1-configurar-cliente-dns](https://architecnologia.es/lpic-1-tema-109-1-configurar-cliente-dns) - LPIC-1 Tema 109.4: configurar el lado del cliente DNS




### Tema 110 - 10p - Seguridad

   * **110.1 - 3p - C16L - Tareas de administración de seguridad**
       * [https://rm-rf.es/linux-el-comando-lsof/](https://rm-rf.es/linux-el-comando-lsof/) - Resumen de **lsof**, un comando de linux muy potente
           * [https://www.commandlinefu.com/commands/matching/lsof/bHNvZg==/sort-by-votes](https://www.commandlinefu.com/commands/matching/lsof/bHNvZg==/sort-by-votes) - trucos con **lsof**
           * **lsof -i -P -n** # Muestra las conexiones de red. La opción **-P** no resuelve puertos. La opción **-n** no resuelve Hosts.
           * **lsof -i@ubuntu **# Ver las conexiones con una máquina en concreto
       * [https://www.linuxparty.es/35-linux/11459-aprenda-a-usar-el-comando-fuser-con-ejemplos-en-linux.html](https://www.linuxparty.es/35-linux/11459-aprenda-a-usar-el-comando-fuser-con-ejemplos-en-linux.html) - Resumen de **fuser**
       * **find**
           * **find . -perm 4000** # **Exactamente** ficheros con permisos **4000**
           * **find . -perm -4000** # Ficheros con **al menos** el permiso **u+s**
           * **find . -perm /u+s,g+s** # Ficheros con **alguno** de los permisos descritos, el **u+s** o el **g+s**
           * **find /usr/bin -perm /6000 -exec ls -l {} \; **# Ejemplo real del comando anterior
       * **nmap**
           * [https://openwebinars.net/blog/nmap-uso-basico-para-rastreo-de-puertos/](https://openwebinars.net/blog/nmap-uso-basico-para-rastreo-de-puertos/) - Tutorial bastante extenso
           * [https://nmap.org/nsedoc/scripts/](https://nmap.org/nsedoc/scripts/) - Listado de **NSE Scripts**
           * [https://nmap.org/zenmap/](https://nmap.org/zenmap/) - **Zenmap**, interfaz gráfica para **nmap**
       * **sudo**
           * 🇬🇧 [https://www.maketecheasier.com/differences-between-su-sudo-su-sudo-s-sudo-i/](https://www.maketecheasier.com/differences-between-su-sudo-su-sudo-s-sudo-i/) - Diferencias entre **Su**, **Sudo** **Su**, **Sudo** **-s **y** Sudo -i**
           * [https://www.digitalocean.com/community/tutorials/how-to-edit-the-sudoers-file-es](https://www.digitalocean.com/community/tutorials/how-to-edit-the-sudoers-file-es) - Cómo editar el archivo **sudoers**
           * [https://www.linuxtotal.com.mx/index.php?cont=info\_admon\_014](https://www.linuxtotal.com.mx/index.php?cont=info\_admon\_014) - El fichero **/etc/sudoers**
       * **ulimit**
           * [https://sysarmy.com/blog/posts/entendiendo-la-fork-bomb-de-bash/](https://sysarmy.com/blog/posts/entendiendo-la-fork-bomb-de-bash/) - **fork bomb**
       * [https://docs.oracle.com/cd/E56339\_01/html/E53835/spconcepts-60676.html](https://docs.oracle.com/cd/E56339\_01/html/E53835/spconcepts-60676.html) - Recopilación automática de datos de la actividad del sistema (**sar**)
       * **[]architecnologia.es[]**
           * [https://architecnologia.es/lpic-1-tema-110-1-tareas-seguridad](https://architecnologia.es/lpic-1-tema-110-1-tareas-seguridad) - LPIC-1 Tema 110.1: realizar tareas de seguridad básicas
   * **110.2 - 3p - C17L - Configuración de la seguridad del sistema**
       * [https://web.archive.org/web/20210101015020/https://www.redeszone.net/tutoriales/seguridad/lynis-auditoria-seguridad-linux/](https://web.archive.org/web/20210101015020/https://www.redeszone.net/tutoriales/seguridad/lynis-auditoria-seguridad-linux/) - **Lynis**, herramienta para auditar la seguridad
           * [https://cisofy.com/lynis/controls/](https://cisofy.com/lynis/controls/) - Listado de todas las posibles recomendaciones de seguridad
           * **apt install lynis** # Para instalarlo en Ubuntu
       * [https://github.com/decalage2/awesome-security-hardening](https://github.com/decalage2/awesome-security-hardening) - Recopilación de guías de seguridad
       * **PAM**
           * **Tipos de módulos**
               * **auth** (autenticación): Autentica al usuario
               * **account** (verificación): Comprueba si el usuario tiene permiso para utilizar el servicio o si el servicio esta permitido (control horario, por ejemplo).
               * **password** (actualización): Actualiza el mecanismo de autenticación.
               * **session** (sesión): Acciones que deben ejecutarse antes y/o después del acceso del usuario.
           * **Control** 
               * **sufficient**: Se enviará correcto si no existe fallo previo. Si da ok, no mira más.
               * **requisite**: Se envía fallo sin ejecutar otros módulos. Si falla, da igual el resto.
               * **required**: Para tener el ok, todos los **required** tienen que dar su ok
               * **optional**: Su respuesta solo se usa si no existe otro módulo de este servicio y tipo.
               * **include**: Incluye todas las líneas del **mismo tipo de módulo** encontradas en un fichero de configuración adicional, cuyo nombre se especifica como argumento. En cuanto un módulo falle, no sigue mirando el resto, funciona como un **requisite**.
               * **substack**: Similar a **include**, excepto que la evaluación de las acciones no hacen que PAM se salte el resto de los módulos, substack se trata como un único módulo. Funciona como un **required**, si falla, sigue comprobando todo, hasta que devuelve el no ok, para no dar pistas donde ha fallado. El **include**, si falla, sale en el momento.
           * [https://eltallerdelbit.com/configurar-pam-registrar-actividad-usuarios-terminal/](https://eltallerdelbit.com/configurar-pam-registrar-actividad-usuarios-terminal/) -  módulo PAM que literalmente es un keylogger, almacena todo lo que van tecleando los usuarios.
       * **TCPWrappers**
           * **sshd: ALL: spawn <comando>** # Para ejecutar un comando cuando se active (Red Hat)
           * **sshd: ALL: aclexec <comando>** # Para ejecutar un comando cuando se active (Ubuntu)
           * **zenity --display=:0 --warning --text Mensaje**
           * **export DISPLAY=:0; export XAUTHORITY=~/.Xauthority; notify-send test**
       * **[]architecnologia.es[]**
           * [https://architecnologia.es/lpic-1-110-2-configuracion-seguridad-anfitrion](https://architecnologia.es/lpic-1-110-2-configuracion-seguridad-anfitrion) - LPIC-1 Tema 110.2: configurar seguridad del sistema anfitrión
   * **110.3 - 4p - C18L - Protección de datos mediante cifrado**
       * **SSH**
           * **ssh-keygen -b 4096 -t rsa -a 100** # Para crear claves seguras
           * **PubkeyAuthentication yes** # Para admitir conexiones con clave publica privada
           * **ssh -i id\_rsa\_kvm\_lpic fernando@192.168.124.1  **# Especifico que clave uso
           * **apt install ssh-askpass-gnome **# La versión gráfica del agente ssh
           * **ssh-keygen -lv -f /etc/ssh/ssh\_host\_ed25519\_key.pub **# como invocar el random-art
           * [https://github.com/jtesta/ssh-audit](https://github.com/jtesta/ssh-audit) - Script para auditar los algoritmos que usa SSH, y la seguridad que da cada uno de ellos, con el objetivo de deshabilitar los más inseguros.
           * tuneles ssh, VPN poor man
       * **GPG**
           * [https://www.genbeta.com/desarrollo/manual-de-gpg-cifra-y-envia-datos-de-forma-segura](https://www.genbeta.com/desarrollo/manual-de-gpg-cifra-y-envia-datos-de-forma-segura) - Lab de uso con GPG
       * **[]architecnologia.es[]**
           * [https://architecnologia.es/lpic-1-tema-110-3-seguridad-datos-cifrado](https://architecnologia.es/lpic-1-tema-110-3-seguridad-datos-cifrado) - LPIC-1 Tema 110.3: seguridad de datos con cifrado


### 

# 21:20 - 22:00 - Lab 18 (35 min)

Regex (101)





### Varios

   * [https://pad.disroot.org/p/SystemD](https://pad.disroot.org/p/SystemD) - **SystemD**
   * [https://hacknet-os.com/](https://hacknet-os.com/) - Juego para aprender a usar la línea de comando
   * **Unicode**
       * Para poder poner caracteres unicode en bash, tenemos que hacer lo siguiente:
           * 1.- Pulsar CNTRL+SHIFT+u
           * 2.- Dejamos de pulsarlo
           * 3.- Metemos el código del carácter unicode
           * 4.- Pulsamos Enter
       * Caracteres Unicode
           * 007c - | (tubería o pipe)
           * 007e - ~ (vigudilla o tilde)
           * 1F493 - 💓 (corazón)
           * 1F427 - 🐧 (Pingüino)
       * [https://unicodeplus.com/](https://unicodeplus.com/) - Para buscar caracteres unicode
   * **Prácticas con Linux**
       * 🇬🇧 [https://www.redhat.com/en/interactive-labs/enterprise-linux](https://www.redhat.com/en/interactive-labs/enterprise-linux) - Laboratorios gratis de Red Hat para aprender. Empezar por la serie 101.
       * 🇬🇧 [https://developers.redhat.com/](https://developers.redhat.com/) - Si os creáis una cuenta gratuita de developer, tenéis acceso a gran parte de los productos de Red Hat, con actualizaciones incluidas, pero sin soporte.
       * 🇬🇧 [https://developers.redhat.com/learn/rhel](https://developers.redhat.com/learn/rhel) - Cursos
       * 🇬🇧 [https://developers.redhat.com/cheat-sheets](https://developers.redhat.com/cheat-sheets) - Chuletas de RHEL
   * 🇬🇧 [https://openela.org/](https://openela.org/) - **OpenELA**, unión entre SUSE, Oracle y Rocky Linux, para intentar heredar el mercado de CentOS
   * 🇬🇧 [https://linux.web.cern.ch/](https://linux.web.cern.ch/) - Página de Linux del CERN
   *  [https://archive.org/details/la-linea-de-comandos-de-linux/mode/1up](https://archive.org/details/la-linea-de-comandos-de-linux/mode/1up) - Libro en español, en PDF de la linea de comandos. Es antiguo, pero para la línea de comandos no nos afecta.
   * 🇬🇧 [https://github.com/debMan/cheatSheets/blob/master/lpic1-cheatsheet.md](https://github.com/debMan/cheatSheets/blob/master/lpic1-cheatsheet.md) - Chuletario de comandos usados en LPIC-1




### Horarios del curso

   * **Grupo de Lunes y Miércoles**
       * Lunes 18: **           - **
       * Miércoles 20: ** 17:50 - 22:10 <-- Examen final a primera hora**


   * **Grupo de Martes y Jueves**
       * ~~Martes 12: **    18:50 - 22:00**~~
       * Jueves 14:**     18:50 - 22:00 <-- Mirar PUE Alumni**
       * 

       * Martes 19: **          -      **
       * Jueves 21:**     17:50 - 22:00 <-- Examen final a primera hora**






### Certificación

   * La certificación **LPIC-1** consta de 2 exámenes de 90 minutos, con 60 preguntas cada uno.
       * Examen 101
       * Examen 102
   * De igual forma, la certificación **LPIC-2 **consta de 2 exámenes de 90 minutos, con 60 preguntas cada uno.
       * Examen 201
       * Examen 202
   * Hay preguntas de distintos tipos:
       * De elección de una única respuesta
       * De elección entre 2 y 3 respuestas correctas
       * De teclear un fichero de configuración o directorio, con el path completo
       * De especificar un comando o un parámetro de un comando
   * **Passing score:** 500/800 (62.5%)
   * **Su validez es de 5 años**. Cada vez que apruebas una nueva certificación, se resetea el contador
   * [https://www.lpi.org/exam-pricing/](https://www.lpi.org/exam-pricing/) - Precios oficiales, 176€ en España
   * LPIC-1 está en español, en cualquier momento podemos ver la pregunta original en inglés.
   * **Exámenes de prueba**
       * [https://www.daypo.com/buscar.php?t=lpic](https://www.daypo.com/buscar.php?t=lpic) - **Exámenes de prueba gratuitos**
       * [https://examposter.com/lpi/](https://examposter.com/lpi/) - más preguntas, aunque puede que sean antiguas
       * [https://www.examtopics.com/exams/lpi/101-500/view/](https://www.examtopics.com/exams/lpi/101-500/view/) - De pago, en inglés
       * [https://www.examcollection.com/search.html?q=LPIC\&sa=](https://www.examcollection.com/search.html?q=LPIC\&sa=) - De pago, en inglés
   * **LPIC-2**
       * LPIC-2 está en inglés
       * [https://www.daypo.com/lpic201.html](https://www.daypo.com/lpic201.html) - Preguntas del examen **201**, dos tercios de las preguntas que me salieron están aquí. Un tercio de las preguntas eran "nuevas"
       * [https://www.daypo.com/buscar.php?t=202-450](https://www.daypo.com/buscar.php?t=202-450) - Preguntas del examen **202**.
















G

M

T

Y





Detectar idiomaAfrikáansAlbanésAlemánAmháricoArabeArmenioAsamésAymaraAzeríBambaraBashkirBengalíBhojpuriBielorrusoBirmanoBosnioBúlgaroCamboyanoCanarésCatalánCebuanoChecoChichewaChino simpChino tradChuvasioCincalésColina maríaCoreanoCorsoCriollo haitianoCroataDanésDhivehiDogriEmojiEslovacoEslovenoEspañolEsperantoEstonioEuskeraEweFinlandésFrancésFrisioGaélico escocésGalésGallegoGeorgianoGriegoGujaratiHausaHawaianoHebreoHindiHmongHolandésHúngaroIgboIlocanoIndonesioInglésIrlandésIslandésItalianoJaponésJavanésKazajoKazajo (latín)KinyarwandaKirguísKonkaniKrioKurdo (Kurmanji)Kurdo (Sorani)LaoLatínLetónLingalaLituanoLuxemburguésMacedonioMaithiliMalayalamMalayoMalgacheMaltésMaoríMaratíMariMeiteilon (Manipuri)MizoMongolNepalíNoruegoOdia (Oriya)OromoPanyabíPapiamentoPastúnPersaPolacoPortugués (Brasil)QuechuaRumanoRusoSamoanoSanskritSepediSerbioSerbio (Cirílico)Serbio (Latín)SesotoShonaSindhiSomalíSuajiliSuecoSundanésTagaloTagaloTailandésTamilTártaroTayikoTeluguTigrinyaTsongaTurcoTurcomanoTwiUcranianoUdmurtoUigurUrduUzbecoUzbeko (Cirílico)VietnamitaXhosaYakutoYidisYorubaZulú



EspañolInglésAfrikáans-------- [ Todos ] --------AfrikáansAlbanésAlemánAmháricoArabeArmenioAsamésAymaraAzeríBambaraBashkirBengalíBhojpuriBielorrusoBirmanoBosnioBúlgaroCamboyanoCanarésCatalánCebuanoChecoChichewaChino simpChino tradChuvasioCincalésColina maríaCoreanoCorsoCriollo haitianoCroataDanésDhivehiDogriEmojiEslovacoEslovenoEspañolEsperantoEstonioEuskeraEweFinlandésFrancésFrisioGaélico escocésGalésGallegoGeorgianoGriegoGujaratiHausaHawaianoHebreoHindiHmongHolandésHúngaroIgboIlocanoIndonesioInglésIrlandésIslandésItalianoJaponésJavanésKazajoKazajo (latín)KinyarwandaKirguísKonkaniKrioKurdo (Kurmanji)Kurdo (Sorani)LaoLatínLetónLingalaLituanoLuxemburguésMacedonioMaithiliMalayalamMalayoMalgacheMaltésMaoríMaratíMariMeiteilon (Manipuri)MizoMongolNepalíNoruegoOdia (Oriya)OromoPanyabíPapiamentoPastúnPersaPolacoPortugués (Brasil)QuechuaRumanoRusoSamoanoSanskritSepediSerbioSerbio (Cirílico)Serbio (Latín)SesotoShonaSindhiSomalíSuajiliSuecoSundanésTagaloTagaloTailandésTamilTártaroTayikoTeluguTigrinyaTsongaTurcoTurcomanoTwiUcranianoUdmurtoUigurUrduUzbecoUzbeko (Cirílico)VietnamitaXhosaYakutoYidisYorubaZulú 



















La función de sonido está limitada a 200 caracteres





Opciones : Historia : Feedback : DonateCerrar







G

M

T

Y





Detectar idiomaAfrikáansAlbanésAlemánAmháricoArabeArmenioAsamésAymaraAzeríBambaraBashkirBengalíBhojpuriBielorrusoBirmanoBosnioBúlgaroCamboyanoCanarésCatalánCebuanoChecoChichewaChino simpChino tradChuvasioCincalésColina maríaCoreanoCorsoCriollo haitianoCroataDanésDhivehiDogriEmojiEslovacoEslovenoEspañolEsperantoEstonioEuskeraEweFinlandésFrancésFrisioGaélico escocésGalésGallegoGeorgianoGriegoGujaratiHausaHawaianoHebreoHindiHmongHolandésHúngaroIgboIlocanoIndonesioInglésIrlandésIslandésItalianoJaponésJavanésKazajoKazajo (latín)KinyarwandaKirguísKonkaniKrioKurdo (Kurmanji)Kurdo (Sorani)LaoLatínLetónLingalaLituanoLuxemburguésMacedonioMaithiliMalayalamMalayoMalgacheMaltésMaoríMaratíMariMeiteilon (Manipuri)MizoMongolNepalíNoruegoOdia (Oriya)OromoPanyabíPapiamentoPastúnPersaPolacoPortugués (Brasil)QuechuaRumanoRusoSamoanoSanskritSepediSerbioSerbio (Cirílico)Serbio (Latín)SesotoShonaSindhiSomalíSuajiliSuecoSundanésTagaloTagaloTailandésTamilTártaroTayikoTeluguTigrinyaTsongaTurcoTurcomanoTwiUcranianoUdmurtoUigurUrduUzbecoUzbeko (Cirílico)VietnamitaXhosaYakutoYidisYorubaZulú



EspañolInglésAfrikáans-------- [ Todos ] --------AfrikáansAlbanésAlemánAmháricoArabeArmenioAsamésAymaraAzeríBambaraBashkirBengalíBhojpuriBielorrusoBirmanoBosnioBúlgaroCamboyanoCanarésCatalánCebuanoChecoChichewaChino simpChino tradChuvasioCincalésColina maríaCoreanoCorsoCriollo haitianoCroataDanésDhivehiDogriEmojiEslovacoEslovenoEspañolEsperantoEstonioEuskeraEweFinlandésFrancésFrisioGaélico escocésGalésGallegoGeorgianoGriegoGujaratiHausaHawaianoHebreoHindiHmongHolandésHúngaroIgboIlocanoIndonesioInglésIrlandésIslandésItalianoJaponésJavanésKazajoKazajo (latín)KinyarwandaKirguísKonkaniKrioKurdo (Kurmanji)Kurdo (Sorani)LaoLatínLetónLingalaLituanoLuxemburguésMacedonioMaithiliMalayalamMalayoMalgacheMaltésMaoríMaratíMariMeiteilon (Manipuri)MizoMongolNepalíNoruegoOdia (Oriya)OromoPanyabíPapiamentoPastúnPersaPolacoPortugués (Brasil)QuechuaRumanoRusoSamoanoSanskritSepediSerbioSerbio (Cirílico)Serbio (Latín)SesotoShonaSindhiSomalíSuajiliSuecoSundanésTagaloTagaloTailandésTamilTártaroTayikoTeluguTigrinyaTsongaTurcoTurcomanoTwiUcranianoUdmurtoUigurUrduUzbecoUzbeko (Cirílico)VietnamitaXhosaYakutoYidisYorubaZulú 



















La función de sonido está limitada a 200 caracteres





Opciones : Historia : Feedback : DonateCerrar
