# Diseño de la red

La red de la oficina pequeña está diseñada para permitir la comunicación entre todos los dispositivos, ofrecer acceso a Internet y proporcionar servicios internos como impresión y almacenamiento compartido.

## Topología general

La estructura de la red es en estrella, con un switch central que conecta todos los dispositivos:

- Router conectado al switch
- Switch conectado a:
  - 8 PCs
  - 1 servidor
  - 1 impresora en red
  - 1 punto de acceso WiFi
- El portátil se conecta mediante WiFi

## Dispositivos utilizados

- Router Cisco 1941
- Switch Cisco 2960
- Servidor (Server-PT)
- 8 PCs (PC-PT)
- 1 portátil (Laptop-PT)
- 1 impresora en red (Printer-PT)
- 1 punto de acceso WiFi (WRT300N o AP-PT)

## Conexiones

- Router (GigabitEthernet0/0) → Switch (FastEthernet0/1)
- Switch → PCs (Fa0/2 a Fa0/9)
- Switch → Servidor
- Switch → Impresora
- Switch → Punto de acceso WiFi
- Portátil → WiFi

## Diagrama de red

El diagrama se encuentra en la carpeta `/diagramas/diagrama_red.drawio`.

Representa la topología en estrella con todos los dispositivos conectados al switch central.
