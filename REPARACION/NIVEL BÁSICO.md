## EJECUCION DE PROGRAMAS NATIVOS 

<details>
    <summary>NATIVOS WINDOWS</summary>

Windows SFC: Analiza los archivos protegidos del sistema operativo para detectar errores, daños o modificaciones, y los repara reemplazándolos por copias sanas.

```
CMD - EJECUTAR COMO ADMINISTRADOR
sfc / scannow -- PRESIONA ENTER
REALIZA EL ANALISIS, EN CASO DE SER MAS PROFUNDO EL DAÑO HACER ESTO:
DISM.exe /Online /Cleanup-image /Restorehealth -- VUELVE A EJECUTAR SFC
```
Windows DISM: repara archivos dañados del sistema operativo, preparar imágenes de instalación y solucionar fallos graves.
```
CMD - EJECUTAR COMO ADMINISTRADOR
DISM /Online /Cleanup-Image /RestoreHealth -- EJECUTA ESTE COMANDO
REINICIA

DISM /Online /Cleanup-Image /ScanHealth -- COMPROBAR DAÑOS SIN REPARAR 
DISM /Online /Cleanup-Image /CheckHealth -- VER SI HAY DAÑOS DETECTADOS
 
```

CHKDSK: Analiza el disco duro en busca de sectores defectuosos y errores lógicos.
```
CMD - EJECUTAR COMO ADMINISTRADOR
chkdsk -- Revisa la unidad principal (C:) solo para mostrar si hay errores, sin reparar nada.
chkdsk /f -- Revisa el disco y repara los errores que encuentra
chkdsk /r -- Busca sectores dañados en el disco e intenta recuperar la información que aún sirve.
chkdsk C: /f /r /x -- Analiza a fondo la unidad C:, repara errores, busca partes malas del disco y desmonta la unidad si hace falta.
HARA EL PROCESO DESPUES DE REINICIAR EL PC
```

Solucionadores de problemas: Apartado dentro de la configuración de Windows para arreglar fallos de red, audio o Windows Update.
    
</details>

## EJECUCIÓN DE PROGRAMAS EXTERNOS

<details>
    <summary>INFO DE HARDAWARE</summary>

- [**CPU-Z**](https://www.cpuid.com/) Muestra el modelo exacto de tu procesador, placa base, memoria RAM (velocidad y tipo) y tarjeta gráfica de forma muy ligera.
- [**GPU-Z**](https://www.techpowerup.com/download/gpu-z/) Detalla los datos clave de tu gráfica como memoria VRAM, tipo de chip, velocidad y temperatura actual.
- [**HWiNFO**](https://www.hwinfo.com/download/) Ofrece una lista profunda de cada componente de tu PC junto con el monitoreo completo de voltajes y calor.
- [**Speccy**](https://www.ccleaner.com/es-es/speccy/download?srsltid=AfmBOornRyEuGW-u238zBBOMAxLQU8ZJLYoO978lPyDwpHywdYUZqYwu) Crea un resumen visual y ordenado de todo el equipo (disco duro, audio, sistema operativo y hardware).

- **Información del sistema:** Presiona las teclas ```Win + R```, escribe ```msinfo32``` y pulsa ```Enter``` para ver datos detallados de tu equipo. 
- **Herramienta DirectX:** Presiona ```Win + R```, escribe ```dxdiag``` y presiona ```Enter``` para revisar la pantalla, tarjeta de vídeo y memoria.

</details>

<details>
    <summary>PROGRAMAS EXTERNOS</summary>

- [**CrystalDiskInfo**](https://crystalmark.info/en/software/crystaldiskinfo/) supervisa la salud, la temperatura y el rendimiento de los discos duros (HDD) y unidades de estado sólido (SSD o NVMe).
- [**Windows Repair Toolbox**](https://windows-repair-toolbox.com/) Un excelente panel portátil y gratuito que reúne las mejores utilidades de terceros para desinfectar, reparar y comprobar el hardware del equipo.
- [**Tweaking.com (Windows Repair)**](https://www.tweaking.com/) Soluciona problemas avanzados comunes como permisos de registro, errores de Windows Update y daños en el firewall.
- [**Microsoft PC Manager**](https://microsoft-pc-manager.uptodown.com/windows) La herramienta oficial de optimización ligera de Microsoft para limpiar basura y acelerar el rendimiento.

</details>

<details>
    <summary>ANTIVIRUS</summary>

- [**Microsoft defender**](https://learn.microsoft.com/en-us/defender-endpoint/configure-microsoft-defender-antivirus-features) revisa archivos, programas, amenazas ocultas del disco duro.
- [**Malwarebytes**](https://www.malwarebytes.com/es/?x-clickref=1011lDtATyAW&gad_source=1) excelente programa de seguridad, muy eficaz para encontrar y borrar virus ocultos, troyanos y programas espías. La versión gratuita los virus que ya han entrado y premium previene de virus futuros.
- [**AdwCleaner**](https://www.malwarebytes.com/es/adwcleaner) escanea el registro de Windows, los navegadores y los archivos del sistema para detectar y eliminar publicidad molesta (adware), barras de herramientas indeseadas y programas potencialmente no deseados (PUP).

</details>

## ACTUACIONES

<details>
    <summary>EL PC NO ENCIENDE</summary>

- **Cables sueltos:** Revisa que el enchufe, la regleta y el cable de corriente estén bien conectados. 
- **Memoria RAM floja:** Abre la torre, saca los módulos de RAM, limpia los contactos con una goma de borrar y vuelve a encajarlos.
- **Fuente de alimentación dañada:** Si no hace ningún ruido ni enciende ningún led, cambia la fuente o prueba en otro enchufe.
- **Sin señal en el monitor:** Asegúrate de que el cable HDMI o DisplayPort esté conectado a la tarjeta gráfica y no a la placa base.
    
</details>

<details>
    <summary>El PC VA MUY LENTO</summary>

- **Disco lleno:** Libera espacio borrando archivos grandes o pasando datos a un disco externo. Si usas un disco duro mecánico antiguo, cámbialo por un SSD.
- **Demasiados programas al iniciar:** Abre el Administrador de tareas ```(CTRL + SHIFT + ESC)```, ve a la pestaña de Aplicaciones de inicio y desactiva lo que no necesites.
- **Falta de memoria:** Si la RAM está al 100%, cierra pestañas del navegador o añade más memoria física al equipo.

</details>

<details>
    <summary>PANTALLAZOS AZULES O REINICIOS REPENTINOS</summary>

- **Controladores (drivers) malos:** Desinstala el último controlador instalado o vuelve a una versión anterior desde el Modo seguro.
- **RAM inestable:** Si añadiste memoria nueva o hiciste overclock, restablece los valores por defecto en la BIOS.
- **Sistema corrupto:** Abre la consola de comandos como administrador y escribe ```sfc /scannow``` para reparar archivos dañados de Windows.

</details>

<details>
    <summary>SOBRECALENTAMIENTOS Y APAGONES</summary>

- **Acumulación de polvo:** Limpia los ventiladores y el disipador del procesador con aire comprimido.
- **Pasta térmica seca:** Desmonta el disipador de la CPU, limpia la pasta vieja y aplica una capa de pasta térmica nueva.

</details>

<details>
    <summary>PRESENCIA DE VIRUS O MALWARE</summary>

- **Publicidad molesta o archivos bloqueados:** Pasa un análisis completo con un antivirus actualizado o utiliza herramientas como Windows Defender para limpiar el sistema.
- **Restauración de fábrica:** Si el daño persiste, haz una copia de seguridad de tus archivos importantes y formatea el equipo.

</details>

<details>
    <summary>SOBRECALENTAMIENTOS Y APAGONES</summary>

- **Acumulación de polvo:** Limpia los ventiladores y el disipador del procesador con aire comprimido.
- **Pasta térmica seca:** Desmonta el disipador de la CPU, limpia la pasta vieja y aplica una capa de pasta térmica nueva.

</details>

## NUMERACION DE ERRORES

<details>
    <summary>ERRORES 400-500</summary>

- [**Errores**](https://vicentferrer.com/errores-en-http/)

- **400(Bad Request):** en la peticion, el servidor no puede procesar la solicitud.
  - caracteres incorrectors en la URL
  - Cookies con errores(borralas)
  - DNS antiguos
  - Archivos demasiado grandes
- **401(Unauthorized):** nos informa de que la peticion http no ha sido ejecutada porque debemos iniciar una sesion
  - 401.1: error de inicio de sesion
  - 401.2: por error de configuracion del servidor
  - 401.3: fallo por ACL
  - 401.4: Auth Filtro
  - 401.5: Auth APP ISAPI CGI
- **403 Forbidden:** la autentificacion no es posible, no tenemos permisos y esta prohibido acceder al recurso solicitado.
- **404 Not Found:** el servidor no ha podido encontrar la pagina solicitada(contenido borrado, enlace incorrecto o defectuoso). Search Console
- **500 Internal Server Error:** por fallo en la programacion o aplicacion web.
  - Otros nombre: 500 Internal Server Error
  - HTTP 500 -Internal Server Error
  - Temporary Error(500)
  - HTTP 500 Internal Error
  - 500 Error
  - HTTP Error 500
  - 500. That's an error
Para saber mas revisar el log de errores de Apache, /error_log.
Si nuestro hosting utiliza Cpanel, tiene una seccion para los errores
    - Error de Permisos: error 500
    - Demasido tiempo de Espera: en caso de que el script de php dependa de recursos y el tiempo de ejecucion lo limite.
    - Fallo en el .htaccess: en este archivo, puede haberse tocado algo
    - Fallo por limite de memoria: el archivo php.ini o wp-config(wordpress) estan limitados de memoria, habra que aumentarla.
- **502 Bad Gateway:** error en la comunicacion del servidor web y algunos servidores que actuan por proxy
  - Firewall bloqueando la solicitud: o se ha activado alguna regla por error
  - Fallo en el servidor Proxy: como no puede conectarse al servidor web, nos devuelve un error
  - Fallo en un cluster, o CDN(sobrecarga)
  - Estamos recibiendo un DDOS

</details>






















