# Plan de direccionamiento IP

Para la red de la oficina pequeña se ha definido un plan de direccionamiento sencillo y coherente, basado en una única red IPv4 privada.

## Red utilizada

- **Red:** 192.168.10.0/24
- **Máscara:** 255.255.255.0
- **Gateway (router):** 192.168.10.1

Esta red permite hasta 254 hosts, más que suficiente para una oficina pequeña.

## Asignación de direcciones IP

| Dispositivo | Dirección IP | Tipo |
|-------------|--------------|------|
| Router (LAN) | 192.168.10.1 | Estática |
| Servidor | 192.168.10.2 | Estática |
| Impresora | 192.168.10.3 | Estática |
| PCs (1–8) | 192.168.10.10 – 192.168.10.17 | DHCP |
| Portátil | Asignada por DHCP | DHCP |
| Punto de acceso WiFi | 192.168.10.50 | Estática |

## DHCP

El servidor DHCP está configurado en el router para simplificar la administración de la red.

### Configuración del pool DHCP

- **Rango asignable:** 192.168.10.20 – 192.168.10.200  
- **Direcciones excluidas:** 192.168.10.1 – 192.168.10.19  
- **DNS:** 8.8.8.8  
- **Gateway:** 192.168.10.1  

## Justificación

- Los dispositivos críticos (router, servidor, impresora, AP) usan IP fija para garantizar estabilidad.
- Los equipos de usuario utilizan DHCP para facilitar la gestión.
- El rango está organizado para evitar conflictos y mantener orden en la red.
