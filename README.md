# Connection_Monitoring
Realizar un monitoreo de las conexiones de red establecidas por procesos y obtener detalles tanto sobre los procesos locales como sobre las ubicaciones geográficas asociadas a las direcciones IP remotas.

Requisitos:
- Tener Python
- Instalar librerias psutil y ip2geotools

Usos y Funcionalidades:

- psutil: Es una biblioteca que proporciona una interfaz para acceder a información sobre el sistema operativo y los recursos del sistema. Permite a los desarrolladores obtener información sobre el uso de la CPU, memoria, red, discos y otros recursos del sistema.
- Algunas funciones comunes de **`psutil`** incluyen la obtención de estadísticas de uso de CPU, memoria y disco, la obtención de información sobre procesos en ejecución y la monitorización de la red.


- ip2geotools: Es una biblioteca que proporciona funcionalidades relacionadas con la geolocalización de direcciones IP. Permite obtener información sobre la ubicación geográfica asociada a una dirección IP, como el país, la región, la ciudad, las coordenadas geográficas, etc.
- Esta biblioteca es útil cuando se desea realizar análisis de datos basados en la ubicación geográfica de las direcciones IP. Puede ser utilizada para determinar la ubicación aproximada de una dirección IP en un mapa.

Comandos para instalar librerias en Windows:
pip install psutil
pip install ip2geotools

En caso de tener problemas con la instalacion de ip2geotools probar lo siguiente:
- Instalar Microsoft Visual C++ Build Tools (Si no lo has hecho):
- Instalar wheel (rueda) de typed-ast precompilada: pip install typed-ast-<versión>-cp<versión de Python>-cp<versión de Pythonm>-win_amd64.whl
- Verificar la configuración de Python: Asegúrate de que estás utilizando una versión de Python compatible con la versión de typed-ast que estás intentando instalar
