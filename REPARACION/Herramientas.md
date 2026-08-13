# WINDOWS
- [Técnico](https://www.tiktok.com/@scpc_informatica)
  
## PANTALLA CONGELADA
    WINDOWS + CTRL + SHIFHT + B -- LA PANTALLA PARDADEARA Y ESCUCHARAS UN SONIDO Y SE REINICIARA EL CONTROLADOR GRÁFICO

## UTILES DE WINDOWS + R
    Windows + R + %LocalAppData%\NVIDIA -- eliminar archivos caché
    Windows + R + shell:appsfolfer -- permite gestionar tus apps mas rápido
    Windows + R + perfmon /report -- después de 60s + Monitor de rendimiento + Informes + Sistema + System Diagnostics -- ves el diagnostico de tu sistema

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

## COMANDOS RÁPIDOS DE SEGURIDAD Y REPARACIÓN
    Windows + L -- Bloquea la Pantalla
    Windows + Flecha IDZ/DER -- divide la pantalla en dos
    Windows + D -- te coloca en escritorio
    Windoes + V -- accede rapido al listado de cosas que has copiado
    Windows + CTRL + D -- Abre un escritorio virtual
    Windows + Shift + T -- Reabre la ultima pestaña que has cerrado

## FALLO EN LA CONEXION DE USB EN PC
- [Fallos USB](https://www.tiktok.com/@scpc_informatica/video/7646501352406961411)
  
        1º Opcion cmd(administrador) + control /name Microsoft.AutoPlay + abre una ventana + resstablecer todos los valores predeterminados + USB + Elegir una opcion(pref Abrir carpeta para ver archivos) + guardar
        2º Opcion Windiws R + regedit(ejecutar como administrador) + Equipo\HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Policies\Explorer + Pinchas en NoDriveTypeAutoRun + valor ! 91 en Hexadecimal o valor ! 145 en Decimal + aceptar-- ahi estara el problema y colocaremos esos valores

## REPARAR GRÁFICA
    Windows + S + cmd como administrador + WMIC DISKDRIVE GET STATUS -- revisa el estado de la gráfica
