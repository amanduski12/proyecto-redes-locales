# Pruebas de conectividad

A continuación se muestran las pruebas realizadas para comprobar el correcto funcionamiento de la red de la oficina pequeña.

## 1. Comprobación de configuración IP (ipconfig)

En cada PC se ejecutó el comando:

ipconfig
Resultados esperados:
- Dirección IP dentro del rango DHCP (192.168.10.x)
- Máscara: 255.255.255.0
- Gateway: 192.168.10.1

## 2. Prueba de conexión con el router (gateway)

ping 192.168.10.1
Resultado esperado:
- Respuestas exitosas (Reply from…)

## 3. Prueba de conexión con el servidor

ping 192.168.10.2
Resultado esperado:
- Respuestas exitosas

## 4. Prueba de conexión con la impresora

ping 192.168.10.3
Resultado esperado:
- Respuestas exitosas

## 5. Prueba de conexión entre PCs

Ejemplo:

ping 192.168.10.12
Resultado esperado:
- Comunicación correcta entre equipos

## 6. Prueba de conexión del portátil por WiFi

En el portátil se verificó:

- Conexión a la red OFICINA_WIFI
- Obtención de IP por DHCP
- Ping al router, servidor e impresora

## 7. Prueba de acceso a Internet simulado

ping www.google.com
Resultado esperado:
- Resolución DNS correcta
- Respuestas simuladas por Packet Tracer

---

Estas pruebas confirman que:
- El DHCP funciona correctamente
- Todos los dispositivos se comunican entre sí
- La impresora y el servidor son accesibles
- El WiFi está operativo
