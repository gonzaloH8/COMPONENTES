<details>
    <summary>EQUIPO NO ENCIENDE</summary>

## SÍNTOMAS
- Falta de voltaje para arrancar el equipo
- No enciende

## SOLUCIÓN
- **Revisa el enchufe y el cable:** Conecta otro aparato al mismo enchufe para descartar que no tenga corriente. Prueba también con otro cable de corriente si tienes uno a mano.
- **Mira el interruptor trasero:** La parte trasera de la fuente de alimentación tiene un pequeño interruptor con los símbolos "I" y "O". Asegúrate de que está pulsado en la posición de encendido ("I").
- **Desconecta regletas:** Enchufa la torre directamente a la pared para descartar que la regleta o protector de tensión estén rotos
- **Conector principal de 24 pines:** Comprueba que el cable ancho que va de la fuente a la placa base esté bien insertado y encajado hasta el fondo.
- **Conector de la CPU:** Revisa el cable de 4 u 8 pines que alimenta el procesador, situado cerca de este en la placa base.
- **Botón de encendido (Front Panel):** Los pequeños cables que conectan el botón de la caja con la placa base a veces se sueltan. Consulta el manual de tu placa para asegurarte de que siguen en su sitio correcto.
- **La prueba del clip (Puente):** Desconecta todos los cables de la fuente de alimentación de la placa base y de los componentes. Localiza el conector grande de 24 pines y usa un pequeño clip de papel o alambre para unir el pin del cable verde con cualquier pin de cable negro (tierra).

</details>

<details>
    <summary>FALLOS EN COMPONENTES INTERNOS</summary>

## CONDENSADORES (ELECTROLÍTICOS)
- **Qué hacen:** Filtran y estabilizan la energía eléctrica.
- **Por qué fallan:** Pierden capacidad o se secan por el calor acumulado.
- **Síntomas:** Se ven hinchados, con la parte superior abierta o con líquido seco. Causan apagones repentinos, reinicios del equipo o que la fuente no logre arrancar en frío.

## TRANSITORES MOSFET Y DE COMUTACIÓN
- **Qué hacen:** Controlan el paso de la corriente a alta frecuencia en la etapa primaria.
- **Por qué fallan:** Soportan mucho estrés térmico y picos de corriente directa.
- **Síntomas:** Entran en cortocircuito directo, lo que hace saltar el fusible principal de inmediato y bloquea por completo el encendido del dispositivo.

## Fusible de Protección
- **Qué hacen:** Cortan la entrada de electricidad si hay un peligro grave de sobrecarga.
- **Por qué fallan:** Se queman al recibir un cortocircuito interno (como un diodo o un MOSFET dañado) o un pico de la red eléctrica externa.
- **Síntomas:** El filamento interior está roto o ennegrecido. La fuente queda totalmente muerta sin mostrar ningún tipo de luz o actividad.

## Puente Rectificador (Diodos)
- **Qué hacen:** Convierten la corriente alterna de la pared en corriente continua.
- **Por qué fallan:** Sobrecargas de tensión o fallos en los filtros posteriores.
- **Síntomas:** Uno o más diodos se ponen en cortocircuito, haciendo que salte el fusible de entrada o provocando olor a quemado y calor excesivo.

## Varistor y Termistor (NTC)
- **Qué hacen:** Protegen contra subidas repentinas de tensión y limitan el golpe de corriente inicial al encender.
- **Por qué fallan:** Absorben picos de voltaje muy altos.
- **Síntomas:** El varistor aparece agrietado, chamuscado o reventado. El termistor puede abrirse e interrumpir por completo el paso de la electricidad hacia el resto de los circuitos.

</details>
