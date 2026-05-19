# Proyecto IOT

Este repositorio contiene el código fuente y la configuración necesaria para el proyecto.

## Configuración inicial

Antes de compilar y subir el código a la placa, es necesario configurar las credenciales de tu red WiFi local. 

Para hacerlo, abre el archivo principal `.cpp` y modifica las siguientes variables con los datos de tu red:

```cpp
const char* ssid = "TU_WIFI";
const char* password = "TU_PASSWORD";
