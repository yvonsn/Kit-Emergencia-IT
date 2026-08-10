# Scripts de soporte

## Introducción

El Kit de Emergencia IT incorpora una pequeña colección de scripts Batch (`.bat`) creados para agilizar tareas habituales de diagnóstico y mantenimiento en equipos Windows.

Los scripts permiten ejecutar rápidamente comandos utilizados con frecuencia durante una intervención técnica.

---

## Scripts disponibles

| Script | Función |
|---|---|
| `info_equipo.bat` | Muestra información general del sistema mediante `systeminfo` |
| `ip_red.bat` | Muestra la configuración completa de red mediante `ipconfig /all` |
| `ping_test.bat` | Realiza una prueba rápida de conectividad IP |
| `limpieza_temporales.bat` | Elimina archivos temporales del usuario |
| `integridad_windows.bat` | Comprueba y repara archivos protegidos de Windows mediante SFC |

---

## info_equipo.bat

Obtiene información general sobre el equipo y el sistema operativo.

    @echo off
    systeminfo
    pause

El comando `systeminfo` permite consultar información como la versión de Windows, nombre del equipo, memoria y otros datos del sistema.

---

## ip_red.bat

Muestra información detallada sobre la configuración de los adaptadores de red.

    @echo off
    ipconfig /all
    pause

Permite consultar direcciones IP, puerta de enlace, servidores DNS, DHCP y otra información útil para el diagnóstico de red.

---

## ping_test.bat

Realiza una comprobación básica de conectividad utilizando una dirección IP externa.

    @echo off
    ping 8.8.8.8
    pause

Al utilizar directamente una dirección IP, la prueba permite comprobar la conectividad sin depender inicialmente de la resolución DNS.

---

## limpieza_temporales.bat

Realiza una limpieza básica de los archivos temporales del usuario.

    @echo off
    del /q /f /s %TEMP%\*
    pause

Algunos archivos pueden encontrarse en uso y no ser eliminados durante la ejecución.

---

## integridad_windows.bat

Ejecuta el Comprobador de archivos de sistema de Windows.

    @echo off
    sfc /scannow
    pause

`sfc /scannow` comprueba la integridad de los archivos protegidos del sistema e intenta reparar los archivos dañados detectados.

Este script debe ejecutarse con permisos de administrador.

---

## Objetivo

Estos scripts no pretenden sustituir herramientas de administración más avanzadas. Su finalidad es proporcionar accesos rápidos a comandos utilizados habitualmente durante tareas básicas de soporte.

Además, su incorporación permite ampliar progresivamente el Kit de Emergencia IT mediante nuevas automatizaciones.

---

## Resultado

La incorporación de scripts permite ejecutar de forma rápida y repetible determinadas tareas de diagnóstico y mantenimiento desde el propio USB.
