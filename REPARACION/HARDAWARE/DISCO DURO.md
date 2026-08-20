# FALLOS COMUNES Y SUS SOLUCIONES
## PROGRAMAS
- [CrystalDiskInfo](https://crystalmark.info/en/software/crystaldiskinfo/)

<details>
    <summary>FALLOS MECÁNICOS</summary>

## SÍNTOMAS   
- Daños en los platos o en el cabezal de lectura y escritura. 
- Emite ruidos como chasquidos, clics o zumbidos.
- **Bloqueos del sistema:** El ordenador se congela al intentar abrir carpetas o arrancar.
- El equipo no reconoce la unidad ni en el sistema operativo ni en la BIOS.

## CAUSAS PRINCIPALES
- **Degaste Natural:** uso prolongado de los componentes móviles con los años.
- **Golpes o caídas:** impactos físicos directos que desplazan las piezas internas.
- **Sobretensión:** picos de corriente eléctrica que quemas o dañan el motor o la placa.

## SOLUCIÓN
- **No usar programas de reparación:** empeoran el daño al forzar el lector.
- **Sala blanca:** extraer los platos magnéticos.
    
</details>

<details>
    <summary>SECTORES DEFECTUOSOS</summary>
    
Zonas dañadas del disco que no permiten leer ni escribir información de forma correcta. Prioridad: sacar los archivos del Disco Duro

## SÍTOMAS
- **S.M.A.R.T.:** indica que el sistema de autocontrol de tu unidad detectó un fallo físico grave o un desgaste extremo.
- **Señales:** Si el ordenador va muy lento, se bloquea o escuchas ruidos extraños (clics repetitivos), el disco tiene un daño grave.

## SOLUCIÓN
- **Comando CHKDSK:** Abre el símbolo del sistema como administrador y escribe ```chkdsk C: /f /r (cambiando la letra C por la de tu unidad)```. Windows buscará los sectores malos, intentará rescatar los datos y los marcará como inutilizables.
- **Herramienta nativa:** Ve a Este equipo, haz clic derecho en el disco, entra en Propiedades, pestaña Herramientas y pulsa en Comprobar.
- **Clona o reinstala:** buscar software especializado
</details>

<details>
    <summary>SOBRECALENTAMIENTO</summary>

## SÍNTOMA
- El disco duro supera los 50-60º(HDD) 70º(SSD)
- El ordenador se congela o va muy lento al leer archivos grandes.
- El sistema operativo se apaga solo de repente.
- Ruidos extraños (clics o zumbidos) en discos mecánicos.

## CAUSAS 
- Polvo acumulado que bloquea la salida de aire del ordenador.
- Falta de ventilación general en la torre o portátiles apoyados en superficies blandas.
- Uso continuo e intenso sin disipadores térmicos (muy común en SSD M.2).
- Fallo mecánico interno (fricción o desgaste de piezas).

## SOLUCIÓN
- Usa aire comprimido en los ventiladores y rejillas del equipo.
- **Añade refrigeración:** Instala un disipador o almohadilla térmica si usas un SSD M.2.
- **Revisa el estado:** Mide la salud y grados de la unidad con programas gratuitos como _CrystalDiskInfo_ para verificar si el daño es crítico.
- **Haz copia de seguridad:** Rescata tus archivos importantes de inmediato antes de que la unidad falle por completo.

</details>

<details>
    <summary>FALLOS LÓGICOS O DE SOFTWARE</summary>

## SÍNTOMA
- El equipo va muy lento al abrir carpetas.
- Aparecen pantallas azules o errores de lectura (como errores CRC).
- Faltan archivos o particiones enteras.
- El disco pide ser formateado al conectarlo.

## CAUSAS
- Apagados bruscos del ordenador por cortes de luz.
- Virus o programas maliciosos que borran datos.
- Borrado accidental de archivos o particiones.
- Fallos durante una actualización del sistema operativo.
- Daños en la tabla de particiones o el sector de arranque (MBR o GPT).

## SOLUCIÓN
- Ejecutar el comando de reparación ```chkdsk``` en Windows para corregir errores lógicos del sistema de archivos.
- Usar herramientas de diagnóstico como _CrystalDiskInfo_ para comprobar el estado de salud de la unidad.
- Recuperar archivos borrados con programas especializados si no se han sobrescrito los datos.
- Formatear la unidad si la corrupción de datos es total y no se necesitan recuperar los archivos.

</details>

<details>
    <summary>FALLOS ELECTRÓNICOS</summary>

## SÍNTOMAS
- El ordenador no reconoce ni detecta el disco duro.
- El disco no gira o no se siente vibración al encenderlo.
- Olor a quemado o marcas visibles de daño en la placa inferior (PCB).
- El sistema se congela al intentar acceder a la unidad.

## CAUSAS
- Subidas bruscas de la red eléctrica o tormentas.
- **Fuente de energía mala:** Un voltaje incorrecto o inestable enviado desde la fuente del PC.
- **Cortocircuitos:** Acumulación de polvo o contacto con electricidad estática.
- **Calor excesivo:** Temperaturas altas continuas que desgastan los microcomponentes.

</details>
