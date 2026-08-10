# Creación del USB multiboot con Ventoy

## Introducción

Para crear el Kit de Emergencia IT se utilizó una memoria USB de **32 GB**, preparada como dispositivo multiboot mediante **Ventoy**.

Ventoy permite almacenar varias imágenes ISO en un mismo dispositivo USB y seleccionar el entorno que se desea iniciar desde un menú durante el arranque del equipo.

---

## Objetivo

Preparar una memoria USB que permita:

- Arrancar diferentes herramientas y sistemas Live.
- Mantener varias imágenes ISO en un único dispositivo.
- Incorporar herramientas portátiles de soporte técnico.
- Almacenar documentación, drivers y scripts.
- Facilitar la actualización del kit sin tener que crear nuevamente el USB para cada ISO.

---

## Entorno utilizado

- **Equipo:** PC con Windows 11.
- **Dispositivo:** memoria USB de 32 GB.
- **Herramienta multiboot:** Ventoy.

---

## Preparación del USB

La instalación de Ventoy se realizó desde Windows 11.

Antes de comenzar se comprobó que la memoria USB seleccionada fuera la correcta, ya que el proceso de instalación de Ventoy modifica la estructura del dispositivo y puede eliminar los datos existentes.

El procedimiento realizado fue:

1. Descargar Ventoy.
2. Conectar la memoria USB de 32 GB al equipo.
3. Ejecutar la herramienta de instalación de Ventoy.
4. Seleccionar la memoria USB correspondiente.
5. Realizar la instalación de Ventoy en el dispositivo.
6. Comprobar que el USB fuera reconocido correctamente después de finalizar el proceso.

---

## Incorporación de las imágenes ISO

Una vez instalado Ventoy, se creó una carpeta destinada a almacenar los diferentes entornos de arranque.

La estructura utilizada fue:

    ISO/
    ├── Clonezilla Live
    ├── GParted Live
    ├── HBCD_PE
    ├── Rescuezilla
    ├── Ubuntu Live
    └── WinPE11

Las imágenes ISO se copiaron al dispositivo para que Ventoy pudiera detectarlas y mostrarlas desde su menú de arranque.

---

## Organización adicional

Además de las imágenes ISO, el dispositivo contiene el **Kit de Emergencia IT**, formado por herramientas portátiles, documentación, drivers y scripts.

La organización separada de las imágenes de arranque y las herramientas de soporte permite utilizar el USB tanto como dispositivo multiboot como repositorio portátil de utilidades técnicas.

---

## Comprobación

Después de preparar el dispositivo se realizaron pruebas de arranque para verificar que Ventoy reconociera las imágenes ISO almacenadas.

Al iniciar un equipo desde el USB, Ventoy muestra un menú desde el que se puede seleccionar el entorno que se desea ejecutar.

Esto permite utilizar diferentes herramientas de diagnóstico y recuperación sin necesidad de disponer de un USB independiente para cada sistema.

---

## Resultado

Se obtuvo un USB multiboot de **32 GB** preparado para tareas de soporte y recuperación.

Ventoy permite centralizar diferentes entornos de arranque en un único dispositivo y facilita la incorporación o sustitución de imágenes ISO a medida que evoluciona el Kit de Emergencia IT.
