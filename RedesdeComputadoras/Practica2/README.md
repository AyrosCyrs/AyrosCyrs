# Práctica 02 - Servidor de almacenamiento en la nube (OMV)

Materia: Redes de Computadoras — Facultad de Ciencias, UNAM

**Práctica realizada en equipo.** Créditos a mis compañeros de equipo:
- Blancas Peralta Alejandro
- Dromundo Escobedo Antonio Sebastian
- Giron Jimenez Emmanuel

## Objetivo

Configurar un servidor de almacenamiento en la nube propio, usando Open Media Vault (OMV), con acceso compartido para Windows (Samba) y Linux (NFS), y accesible remotamente mediante una VPN (ZeroTier).

## Qué se hizo

1. Instalación de OMV 7 en una máquina virtual (VirtualBox y VMware)
2. Configuración de almacenamiento compartido con **Samba** (para clientes Windows) y **NFS** (para clientes Linux)
3. Configuración de usuarios y permisos de acceso a las carpetas compartidas
4. Instalación y configuración de **ZeroTier** para acceder al servidor desde fuera de la red local, como una VPN
5. Conexión y prueba desde múltiples dispositivos y sistemas operativos de todo el equipo

## Retos encontrados
- Problemas de memoria RAM al correr las máquinas virtuales
- Configuración del modo "bridge" de red, distinta entre Windows y Linux
- La configuración de NFS fue más compleja que la de Samba, tanto en el servidor como en el cliente

## Aprendizajes
Samba y NFS resuelven el mismo problema (compartir archivos en red) de forma distinta según el sistema operativo. ZeroTier permitió entender de forma práctica cómo funciona una VPN, y lo útil que es tener un servidor propio accesible de forma remota, sin depender de servicios como Google Drive o Dropbox.

## Evidencia

Ver capturas del proceso en la carpeta [`capturas/`](./capturas).