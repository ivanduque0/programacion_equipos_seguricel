# programacion_equipos_seguricel

# Configurar IDE de arduino para Programar esp8266 y esp32

1 Descargue el IDE de arduino en el siguiente link:
https://www.arduino.cc/en/software

2 Luego de haber instalado el IDE ejecutelo, vaya a "archivo" y haga click en "preferencias". 
Al lado de donde dice "Gestor de URLs Adicionales de Tarjetas", pegue lo siguiente:

https://dl.espressif.com/dl/package_esp32_index.json,http://arduino.esp8266.com/stable/package_esp8266com_index.json

por ultimo haga click en "OK"

3 Dirijase a "Herramientas", luego a "Placa" y seleccione "Gestor de tarjetas". Se abrira una nueva pestaña, arriba del todo en la pestaña primero escriba "esp8266".
Le aparecera un solo resultado en la busqueda, abajo del todo del unico resultado seleccione la version "2.7.0" y luego haga click en "instalar", esto empezara a descargar las librerias necesarias para programar el esp8266. espere a que el proceso termine y no cierre la pestaña, luego pase al siguiente paso.

4 Ahora arriba del todo de la pestaña donde habia escrito "esp8266", borre eso que escribio y ahora escriba "esp32". Tambien le aparecera un solo resultado en la busqueda, abajo del todo de ese resultado seleccione la version "2.0.6" y haga click en "instalar". Espere a que el proceso termine y al finalizar cierre la pestaña.

5 Para instalar arduionoJson dirijase a "Herramientas" y seleccione "gestionar librerias". Se abrira una nueva pestaña, arriba del todo en la pestaña primero escriba "arduinoJson", instale la version 6.21.2 de la primera opcion.

6 Para instalar NTPClient dirijase a "Herramientas" y seleccione "gestionar librerias". Se abrira una nueva pestaña, arriba del todo en la pestaña primero escriba "ntpclient", instale la version 2.2.1 de la primera opcion.

# Programar placas 8266

1 Introduzca en un puerto usb el dispositivo con el esp8266 instalado

2 Abra el IDE de Arduino, arriba del todo seleccione "Herramientas", luego a "Placa", luego donde dice "ESP8266 Boards", y por ultimo seleccione el que dice "Generic ESP8266 Module"

3 Ahora vuelva a seleccionar "Herramientas", luego "Puerto" y seleccione el que le aparezca.

4 En el navegador de su preferencia ingrese el siguiente link:
https://github.com/ivanduque0/Modulos_wifi/tree/main/aperturas_esp01

5 Se debe seleccionar el codigo que corresponda con las funciones que se requiere en el contrato, al darle click a alguno de los que aparecen le deberia aparecer varias lineas de codigo de programacion, copie todo el codigo y peguelo en el IDE de arduino previamente abierto.

6 Haga las modificaciones correspondientes en cuanto a la IP del dispositivo en la red, las credenciales de la red wifi, el acceso asignado,etc.

7 Una vez que haya hecho los ajustes correspondientes, en el IDE de arduino dirijase arriba a la izquierda del todo y dele click al circulo que tiene una flecha apuntando hacia la derecha, ese boton se usa para subir el codigo. Espere hasta que se suba el codigo por completo.


# Programar placas esp32

NOTA: asegurese que se tienen los drivers del esp32, en el caso de los esp32 devkit v4 el driver se consigue en https://www.wch.cn/downloads/CH343SER_ZIP.html

1 Introduzca en un puerto usb el dispositivo con el esp8266 instalado

2 Abra el IDE de Arduino, arriba del todo seleccione "Herramientas", luego a "Placa", luego donde dice "ESP32 Arduino", y por ultimo seleccione el que dice "ESP32 Dev Module"

3 Ahora vuelva a seleccionar "Herramientas", luego "Puerto" y seleccione el que le aparezca.

4 En el navegador de su preferencia ingrese el siguiente link:
https://github.com/ivanduque0/Modulos_wifi/blob/main/esp32_bluetooth/esp32_bluetooth_full.ino

5 Le deberia aparecer varias lineas de codigo de programacion al abrir el link, copie todo el codigo y peguelo en el IDE de arduino previamente abierto.

6 Haga las modificaciones correspondientes en cuanto a la IP del dispositivo en la red, las credenciales de la red wifi, el acceso asignado,etc.

7 Una vez que haya hecho los ajustes correspondientes, en el IDE de arduino dirijase arriba a la izquierda del todo y dele click al circulo que tiene una flecha apuntando hacia la derecha, ese boton se usa para subir el codigo. Espere hasta que se suba el codigo por completo.

