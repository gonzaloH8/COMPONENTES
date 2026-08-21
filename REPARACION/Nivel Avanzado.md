# WINDOWS
- [Técnico](https://www.tiktok.com/@scpc_informatica)
  
## PANTALLA CONGELADA
    WINDOWS + CTRL + SHIFHT + B -- LA PANTALLA PARDADEARA Y ESCUCHARAS UN SONIDO Y SE REINICIARA EL CONTROLADOR GRÁFICO

## UTILES DE WINDOWS + R
    Windows + R + %LocalAppData%\NVIDIA -- eliminar archivos caché
    Windows + R + shell:appsfolfer -- permite gestionar tus apps mas rápido
    Windows + R + perfmon /report -- después de 60s + Monitor de rendimiento + Informes + Sistema + System Diagnostics -- ves el diagnostico de tu sistema
    Windows + R + sysdm.cpl + Opciones Avanzadas + Ajustar para obtener el mejor rendimiento + Seleccionas las tres ultimas + Aplicas y aceptas + Reinicio -- mejora el rendimiento

## APAGADO REAL
    Windows + Sifth + ESC -- compruebas el rendimiento del PC
    Panel de Control + Opciones de Energia + Elegir el comportamiento de los botones de inicio/apagado + Desactivar la opcion de inicio rápido

## BLOQUEO DINÁMICO
    Barra de Tareas + Bloqueo dinámico + Activar + agregar mediante bluetooth el móvil al PC -- permite bloquear el PC cuando tu móvil se aleja del PC

## ENTRAR SIN CONTRASEÑA  A TU USUARIO DE WINDOWS
    BOTON DE REINICIO + SIFHT + SOLUCIONAR PROBLEMAS + OPCIONES AVANZADAS + SIMBOLO DEL SISTEMA + REGEDIT + 
    HKEY_LOCAL_MACHINE + ARCHIVO + CARGAR SUBARBOL + ESTE EQUIPO + DISCO DURO PRINCIPAL + SYSTEM32 + CONFIG + SYSTEM + INGRESAMOS UNA PALABRA(PRUEBA) + 
    LOCALIZAMOS LA CARPETA (PRUEBA) EN REGEDIT + SETUP + CMDLINE + INGRESAMOS CMD.EXE + SETUPTYPE + 2 + SELECCIONAMOS LA CARPETA (PRUEBA) + ARCHIVO + DESCARGAR SUBARBOL +
    CERRAMOS TODO Y REINICIAMOS + SE ABRE EL CDM + NET USER WINDOWS CONTRASEÑA + INGRESAMOS LA NUEVA CONTRASEÑA -- 

## APLICACIONES UTILES PC
    GEEK Permite borrar toda la info de una aplicación sin dejar rastro
    EVERYTHING Permite buscar cualquier tipo de archivo
    Wizztree -- Encuentra archivos y carpetas gigantes y libera espacio
    QickLook -- Previsualiza cualquier archivo pulsando solo la tecla ESPACIO. Mira imagenes, videos y documentos sin tener que abrirlos
    LocalSend -- Envia archivos entre tu PC y móvil sin cables ni cuentas. Tansferir directamente por Wi-Fi sin subirlos a la nube
    EarTrumpet -- Controla el volumen de cada APP por separado
    PowerToys -- añade funciones como atajos, ventanas, búsqueda, etc
    UniGetUI -- Instala y actualiza programas desde una sola APP
    WinDirStat -- Te lista todos los archivos por tamaño
    Mouzi -- ordena los archivos descargados sengún las reglas que implantes

## COMANDOS RÁPIDOS DE SEGURIDAD Y REPARACIÓN
    Windows + L -- Bloquea la Pantalla
    Windows + Flecha IDZ/DER -- divide la pantalla en dos
    Windows + D -- te coloca en escritorio
    Windoes + V -- accede rapido al listado de cosas que has copiado
    Windows + CTRL + D -- Abre un escritorio virtual
    Windows + Shift + T -- Reabre la ultima pestaña que has cerrado

## FALLO EN LA CONEXION DE USB EN PC
- [Fallos USB](https://www.tiktok.com/@scpc_informatica/video/7646501352406961411)
  
        1º Opción CMD(administrador) + control /name Microsoft.AutoPlay + abre una ventana + restablecer todos los valores predeterminados + USB + Elegir una opción(pref Abrir carpeta para ver archivos) + guardar
        2º Opción Windows R + regedit(ejecutar como administrador) + Equipo\HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Policies\Explorer + Pinchas en NoDriveTypeAutoRun + valor ! 91 en Hexadecimal o valor ! 145 en Decimal + aceptar-- ahi estara el problema y colocaremos esos valores

## REPARAR GRÁFICA
    Windows + S + CMD (Administrador) + WMIC DISKDRIVE GET STATUS -- revisa el estado de la gráfica

## SABER SI ALGUIEN ENTRO EN EL PC Y QUE VIO
- [Infiltración](https://www.tiktok.com/@donpaquito.tv/video/7646875681799933206)

      Inicio + Visor de Eventos + Ejecutar como administrador + Registro de Windows + Seguridad + Click Derecho + Filtrar Registro Actual + Se abre una ventana + <Todos lo id de Eventos> bórralo + Escribe en su lugar 4624 + te listara todos las operaciones 
      Inicio + Visor de Eventos + Ejecutar como administrador + Registro de Windows + Seguridad + Click Derecho + Filtrar Registro Actual + Se abre una ventana + <Todos lo id de Eventos> bórralo + Escribe en su lugar 4625 -- Marcará los intentos fallidos

## QUITAR LA NUBE DE MICROSOFT ONDRIVE
- [OnDrive](https://www.tiktok.com/@fran_winter/video/7670689063438912775)

      Escritorio + Propiedades -- podemos ver si OneDrive esta usurpando el escritorio
      Click en OneDrive + Opciones + Configuración + Administrar copias de Seguridad + Desactivamos todas + Salta un mensaje - detener la copia de seguridad e indicar guardar en mi PC








    
