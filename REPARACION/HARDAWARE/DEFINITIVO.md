## EJECUCION DE PROGRAMAS NATIVOS 

<details>
    <summary>NATIVOS WINDOWS</summary>

Herramientas nativas de Windows SFC y DISM: Comandos de consola integrados para buscar y reparar archivos del sistema dañados o corrompidos de la imagen de Windows.

```
CMD - EJECUTAR COMO ADMINISTRADOR
sfc / scannow -- PRESIONA ENTER
REALIZA EL ANALISIS, EN CASO DE SER MAS PROFUNDO EL DAÑO HACER ESTO:
DISM.exe /Online /Cleanup-image /Restorehealth -- VUELVE A EJECUTAR SFC
```

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

- [**CPU-Z**](https://www.cpuid.com/): Muestra el modelo exacto de tu procesador, placa base, memoria RAM (velocidad y tipo) y tarjeta gráfica de forma muy ligera.
- [**GPU-Z**](https://www.techpowerup.com/download/gpu-z/): Detalla los datos clave de tu gráfica como memoria VRAM, tipo de chip, velocidad y temperatura actual.
- [**HWiNFO**](https://www.hwinfo.com/download/): Ofrece una lista profunda de cada componente de tu PC junto con el monitoreo completo de voltajes y calor.
- [**Speccy**](https://www.ccleaner.com/es-es/speccy/download?srsltid=AfmBOornRyEuGW-u238zBBOMAxLQU8ZJLYoO978lPyDwpHywdYUZqYwu): Crea un resumen visual y ordenado de todo el equipo (disco duro, audio, sistema operativo y hardware).

- **Información del sistema:** Presiona las teclas ```Win + R```, escribe ```msinfo32``` y pulsa ```Enter``` para ver datos detallados de tu equipo. 
- **Herramienta DirectX:** Presiona ```Win + R```, escribe ```dxdiag``` y presiona ```Enter``` para revisar la pantalla, tarjeta de vídeo y memoria.

</details>

<details>
    <summary>PROGRAMAS EXTERNOS</summary>

- [**CrystalDiskInfo**](https://crystalmark.info/en/software/crystaldiskinfo/) supervisa la salud, la temperatura y el rendimiento de los discos duros (HDD) y unidades de estado sólido (SSD o NVMe)
- [**Windows Repair Toolbox**](https://windows-repair-toolbox.com/): Un excelente panel portátil y gratuito que reúne las mejores utilidades de terceros para desinfectar, reparar y comprobar el hardware del equipo.
- Tweaking.com (Windows Repair): Soluciona problemas avanzados comunes como permisos de registro, errores de Windows Update y daños en el firewall.
- FixWin: Una aplicación gratuita y muy liviana que permite corregir fallos específicos del Explorador de archivos, la interfaz o la red con un solo clic.
- Microsoft PC Manager: La herramienta oficial de optimización ligera de Microsoft para limpiar basura y acelerar el rendimiento.
- Malwarebytes / AdwCleaner: Programas esenciales orientados a eliminar virus, troyanos y software publicitario intrusivo (adware) que bloquean el buen funcionamiento del sistema.

</details>

<details>
    <summary>ANTIVIRUS</summary>

- [CrystalDiskInfo](https://crystalmark.info/en/software/crystaldiskinfo/) supervisa la salud, la temperatura y el rendimiento de los discos duros (HDD) y unidades de estado sólido (SSD o NVMe)
- [Windows Repair Toolbox](https://windows-repair-toolbox.com/): Un excelente panel portátil y gratuito que reúne las mejores utilidades de terceros para desinfectar, reparar y comprobar el hardware del equipo.
- Tweaking.com (Windows Repair): Soluciona problemas avanzados comunes como permisos de registro, errores de Windows Update y daños en el firewall.
- FixWin: Una aplicación gratuita y muy liviana que permite corregir fallos específicos del Explorador de archivos, la interfaz o la red con un solo clic.
- Microsoft PC Manager: La herramienta oficial de optimización ligera de Microsoft para limpiar basura y acelerar el rendimiento.
- Malwarebytes / AdwCleaner: Programas esenciales orientados a eliminar virus, troyanos y software publicitario intrusivo (adware) que bloquean el buen funcionamiento del sistema.

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
