# Servidor-Escolar-Linux-TRL5
“Repositorio oficial del prototipo TRL5 del servidor escolar basado en Linux para la Institución Educativa Jorge Eliécer Gaitán. Incluye documentación del proyecto, arquitectura, pruebas simuladas y enlace al prototipo en Figma.”
README – Servidor Escolar Basado en Linux (Prototipo TRL5)

Proyecto de Grado – Ingeniería de Sistemas – UNAD

Descripción del proyecto

Este repositorio documenta el desarrollo del prototipo TRL5 de un servidor escolar basado en Linux para la Institución Educativa Jorge Eliécer Gaitán (Aguachica – Cesar).
El sistema integra servicios esenciales para la gestión académica y administrativa, tales como:

Autenticación centralizada

Almacenamiento de archivos

Administración de red local

Servicios de seguridad y respaldo

Interfaz de gestión vía web

El prototipo se valida en un entorno simulado siguiendo la metodología CDIO (Concebir, Diseñar, Implementar y Operar), conforme a los lineamientos de la UNAD para proyectos tecnológicos.

Objetivo general

Diseñar y documentar un prototipo funcional (TRL5) de un servidor escolar basado en Linux que permita la administración centralizada de usuarios, recursos y servicios de red en la institución educativa.

Justificación

La institución presenta fallas de conectividad, ausencia de un sistema unificado para usuarios y archivos, baja eficiencia de red y dependencia del software propietario.
El prototipo demuestra que es viable implementar una solución basada en software libre, económica, sostenible y alineada con las necesidades reales de la comunidad educativa.

Integrantes

Joaquín Rafael Vides Beleño – Estudiante de Ingeniería de Sistemas – UNAD

Dayanna Marcela Campuzano Opdemboth – Estudiante de Ingeniería de Sistemas – UNAD

Tutor: (Agregar nombre del tutor)

Enlace al prototipo en Figma

🔗 (https://www.figma.com/proto/2c98QVzg3t6dYrCDnEFPpo/Prototypo-SST?node-id=28-101&t=MyTkmyLswp0h6N2z-0&scaling=scale-down&content-scaling=fixed&page-id=0%3A1&starting-point-node-id=136%3A321)

Arquitectura del sistema (simulada – TRL5)

Servidor principal (Ubuntu Server / Debian):

Autenticación: OpenLDAP

Archivos compartidos: Samba

Asignación IP: DHCP Server

Dominio interno: Bind9 (gaitan.local)

Firewall: UFW / iptables

Backups: cron + rsync

Administración: Webmin o Cockpit

Parámetros técnicos simulados:

Hostname: server-gaitan

Dominio: gaitan.local

IP del servidor: 192.168.10.1

Red interna: 192.168.10.0/24

Implementación TRL5 (simulada)

La implementación se estructura en cuatro componentes:

1. Preparación del entorno

Definición del sistema operativo, red interna, dominio institucional y roles del servidor.

2. Instalación conceptual de servicios

Documentación de configuraciones simuladas para:

LDAP

Samba

DHCP

DNS

Firewall

Tareas de respaldo

3. Evidencias del prototipo

Incluye diagramas, estructuras de carpetas, ejemplos de archivos de configuración y vistas representativas del sistema utilizando prototipos de interfaz.

4. Validación operativa

Pruebas simuladas que comprueban:

Autenticación de usuarios

Acceso a carpetas compartidas

Asignación automática de IP

Resolución DNS interna

Reglas del firewall

Funcionamiento del backup

Tecnologías utilizadas

Debian GNU/Linux / Ubuntu Server

OpenLDAP

Samba

ISC DHCP

Bind9

UFW / iptables

Cron + rsync

Webmin / Cockpit

Figma (prototipo funcional del sistema – TRL5)

GitHub (gestión documental y repositorio académico)

Explicación del nivel TRL5

El nivel TRL5 indica que el proyecto presenta un prototipo validado en entorno simulado, donde se demuestra:

Arquitectura técnica

Funcionamiento conceptual de los servicios

Flujo de usuarios

Cumplimiento de requerimientos

Realización de pruebas simuladas

Documentación completa del modelo

El sistema está listo para evolucionar hacia TRL6, que corresponderá a pruebas en entorno real.

Contacto

📧 Correo institucional: jrvidesb@unadvirtual.edu.co
