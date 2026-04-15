# Servicios de red implementados

En la red de la oficina pequeña se han configurado varios servicios esenciales para garantizar el correcto funcionamiento de los equipos y la comunicación interna.

## 1. Servicio DHCP

El router actúa como servidor DHCP para asignar direcciones IP automáticamente a los equipos de la red.

### Funciones del DHCP:
- Asignación automática de IP a los PCs y al portátil.
- Configuración automática de máscara, gateway y DNS.
- Evita conflictos de direcciones IP.
- Facilita la administración de la red.

## 2. Servicio de impresión en red

La impresora tiene una dirección IP fija (192.168.10.3) para que todos los equipos puedan acceder a ella sin problemas.

### Ventajas:
- Todos los empleados pueden imprimir desde cualquier PC.
- No es necesario conectar la impresora por USB a un equipo concreto.

## 3. Servidor de archivos

El servidor (192.168.10.2) permite almacenar documentos compartidos entre los empleados.

### Funciones:
- Almacenamiento centralizado.
- Copias de seguridad internas.
- Acceso rápido a documentos comunes.

## 4. Conectividad WiFi

El punto de acceso WiFi proporciona conexión inalámbrica al portátil y a otros dispositivos.

### Configuración:
- SSID: OFICINA_WIFI
- Seguridad: WPA2-PSK
- Contraseña: oficina1234
- IP del AP: 192.168.10.50

## 5. Acceso a Internet

El router actúa como puerta de enlace (gateway) para todos los dispositivos de la red.

### Funciones:
- Permite la salida a Internet.
- Gestiona el tráfico entre la red interna y externa.

## 6. Comunicación interna

Todos los dispositivos pueden comunicarse entre sí gracias a:
- La topología en estrella.
- El switch central.
- El direccionamiento IP organizado.

Esto permite compartir archivos, imprimir, acceder al servidor y trabajar en red sin interrupciones.
