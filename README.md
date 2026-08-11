# 🧰 Kit de Emergencia IT

Proyecto personal orientado a la creación de un **USB multiboot para soporte técnico, diagnóstico, mantenimiento y recuperación de equipos**.

El dispositivo utiliza **Ventoy** como sistema de arranque y combina diferentes entornos Live con herramientas portátiles, documentación técnica, drivers y scripts de soporte.

## 🎯 Objetivo

El objetivo del proyecto es disponer de un kit portátil que permita afrontar tareas habituales de soporte IT desde un único dispositivo USB:

* Diagnóstico de hardware y sistemas.
* Gestión y análisis de discos.
* Recuperación de datos.
* Clonado y copias de seguridad.
* Diagnóstico de red.
* Análisis y mantenimiento de Windows.
* Arranque mediante entornos Live.
* Acceso a drivers y documentación técnica.
* Ejecución de scripts para tareas frecuentes de soporte.

## 💾 Sistema multiboot

El USB fue preparado utilizando **Ventoy**, permitiendo almacenar diferentes imágenes ISO y seleccionarlas desde un menú durante el arranque del equipo.

Actualmente incluye:

| Entorno           | Finalidad                                          |
| ----------------- | -------------------------------------------------- |
| Clonezilla Live   | Clonado y creación/restauración de imágenes        |
| GParted Live      | Gestión de particiones                             |
| Hiren's BootCD PE | Diagnóstico y recuperación en entorno Windows PE   |
| Rescuezilla       | Copias, clonación y restauración                   |
| Ubuntu Live       | Diagnóstico y recuperación mediante Linux          |
| WinPE11           | Mantenimiento y recuperación en entorno Windows PE |

## 🛠️ Organización del Kit

Las herramientas están clasificadas por función para facilitar su localización durante una intervención técnica.

Las principales categorías son:

* Aplicaciones de diagnóstico.
* Herramientas de disco.
* Backup, clonado y recuperación de datos.
* Herramientas de sistema.
* Diagnóstico y análisis de red.
* Seguridad.
* Sysinternals.
* Utilidades.
* Drivers.
* Documentación técnica.
* Scripts de soporte.

## 🖥️ Interfaz local

El USB incorpora una interfaz desarrollada mediante `index.html` que permite acceder visualmente a las principales secciones del kit:

**Aplicaciones · Documentación · Drivers · Scripts · ISO**

La interfaz está diseñada para agilizar la localización de recursos durante las tareas de soporte técnico.


## 📂 Documentación

La documentación completa del proyecto se encuentra organizada en los siguientes apartados:

| Nº | Documento | Descripción |
|---|---|---|
| 01 | [Introducción](docs/01-Introduccion.md) | Objetivo, diseño y alcance del Kit de Emergencia IT |
| 02 | [Creación del USB con Ventoy](docs/02-Creacion-USB-Ventoy.md) | Preparación del USB multiboot y organización inicial |
| 03 | [Entornos de arranque e ISO](docs/03-Entornos-Arranque-ISO.md) | Clonezilla, GParted, Hiren's BootCD PE, Rescuezilla, Ubuntu Live y WinPE11 |
| 04 | [Herramientas IT](docs/04-Herramientas-IT.md) | Herramientas de diagnóstico, disco, recuperación, sistema, red y seguridad |
| 05 | [Documentación y drivers](docs/05-Documentacion-Drivers.md) | Guías rápidas de consulta y herramientas para controladores |
| 06 | [Scripts de soporte](docs/06-Scripts.md) | Scripts Batch para diagnóstico y mantenimiento |
| 07 | Pruebas | Validación del USB, Ventoy y entornos de arranque *(pendiente)* |
| 08 | [Conclusiones](docs/08-Conclusiones.md) | Resultados, aprendizajes y posibles mejoras |

## 📜 Scripts

El kit incluye scripts propios para realizar tareas frecuentes de soporte:

* Información del equipo.
* Información de red.
* Prueba de conectividad mediante ping.
* Limpieza de archivos temporales.
* Comprobación de integridad de Windows.

Los scripts se incluyen en este repositorio para documentar su funcionamiento y facilitar su mantenimiento.

## 🔒 Uso responsable

Las herramientas de diagnóstico, recuperación y administración incluidas en el kit están destinadas a utilizarse exclusivamente sobre **equipos propios o sistemas para los que se disponga de autorización**.

## 🚧 Estado del proyecto

**En desarrollo.**

El USB se encuentra operativo y el proyecto está actualmente en fase de documentación, pruebas y mejora de la organización de las herramientas.

## 👩‍💻 Autora

**Yvón Salas**

Técnica en Administración de Sistemas Informáticos
Soporte técnico · Microinformática · Administración de sistemas
