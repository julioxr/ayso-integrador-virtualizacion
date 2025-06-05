# Trabajo Integrador Final – Virtualización

**Materia:** Arquitectura y Sistemas Operativos  
**Tema:** Virtualización con VirtualBox y desarrollo en Python  
**Integrantes:** Cristian Emmanuel Rivero Corradi - Julio Cesar Roja
**Fecha:** 01/06/2025

---

## Objetivo del Proyecto

El objetivo de este trabajo es comprender y aplicar el concepto de virtualización mediante el uso de VirtualBox. Se busca instalar y configurar una máquina virtual con un sistema operativo Linux, y dentro de ella ejecutar un programa en Python desarrollado por el equipo.

---

## Contenidos Abordados

- Virtualización y entornos aislados (sandbox)
- Instalación y configuración de VirtualBox
- Instalación de Linux Mint en VM
- Uso de la terminal de Linux
- Programación básica en Python (listas, bucles, entradas/salidas)

---

## Requisitos Técnicos

- VirtualBox instalado (versión compatible con el host)
- Imagen ISO de Linux Mint XFCE (64 bits)
- Python 3 dentro de la máquina virtual

---

## Descripción del Caso Práctico

1. Instalación de VirtualBox en el sistema anfitrión (host).
2. Creación de una máquina virtual con 6 GB de RAM y 25 GB de disco virtual.
3. Instalación de Linux Mint XFCE como sistema operativo invitado (guest).
4. Desarrollo de un script en Python que:
   - Solicita 3 notas al usuario.
   - Calcula el promedio.
   - Muestra el resultado por pantalla.

---

## Estructura del Repositorio

- integrador_final.pdf – Informe técnico del trabajo realizado.
- script_notas.py – Código fuente del programa en Python.
- README.md – Este archivo.
- Link a video: [Trabajo Práctico Integrador - AySO](https://www.youtube.com/watch?v=2p4KHzjzH5o)

---

## Instrucciones para ejecutar el script

1. Abrir la terminal dentro de la máquina virtual.
2. Navegar al directorio donde se encuentra el archivo `script_notas.py`.
3. Ejecutar el siguiente comando:

   ```bash
   python3 script_notas.py

## Recursos utilizados
- [VirtualBox](https://www.virtualbox.org/)
- [Linux Mint](https://linuxmint.com/)
- [Python](https://www.python.org/)

## Resultados esperados
- Entorno virtual completamente funcional.
- Script en Python ejecutado exitosamente dentro de la VM.
- Informe técnico con evidencias del proceso.
- Video explicativo demostrando autoría y comprensión.
