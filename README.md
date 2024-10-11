# OUILookup: Herramienta para Consulta de Fabricantes de Direcciones MAC

Este informe se ha de implementar una herramienta basada en línea de comandos para consultar el fabricante de una tarjeta de red dada su dirección MAC. La aplicación se llamará OUILookup y se desarrollará en Python. La base de datos a utilizar será cualquier API REST pública que permita obtener los fabricantes de tarjetas de red a partir de una MAC determinada.tiene como objetivo Implementar una herramienta basada en línea de comandos llamada "OUILookup" en Python.

OUILookup es una herramienta de línea de comandos desarrollada en Python que permite consultar el fabricante de una tarjeta de red a partir de su dirección MAC, o bien, identificar los fabricantes de los dispositivos disponibles en la red local mediante la tabla ARP.

## Características

- Consulta el fabricante de una tarjeta de red mediante su dirección MAC.
- Identifica los fabricantes de dispositivos conectados en la red local usando la tabla ARP.
- Consulta una lista predefinida de direcciones MAC a través del parámetro `--detect`.

## Requisitos del Sistema

- Python 3.x
- Librería `requests` (instalable con `pip install requests`)

## Instalación

1. Clona el repositorio o descarga el archivo `OUILookup.py`.
2. Asegúrate de tener instalada la librería `requests` ejecutando:
   ```bash
   pip install requests
python3 OUILookup.py --mac <mac>    # Consulta una dirección MAC específica
python3 OUILookup.py --arp          # Consulta los fabricantes en la tabla ARP
python3 OUILookup.py --detect       # Consulta las direcciones MAC predefinidas en el script
python3 OUILookup.py --help         # Muestra este mensaje de ayuda

## Ejemplos

![Comando help](C:\Users\rodri\--help)

![Comando MAC especifica ](C:\Users\rodri\--mac)

## Integrantes del Grupo

-   Rodrigo Armijo Velasquez - rodrigo.armijov@alumnos.uv.cl
-   Gladys Carvacho Mondaca - gladys.carvacho@alumnos.uv.cl
## Licencia

Este proyecto se distribuye bajo la Licencia MIT. Puedes usarlo y modificarlo libremente.

## Contribuciones
