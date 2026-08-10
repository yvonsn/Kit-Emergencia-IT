# Herramientas IT

## Introducción

El Kit de Emergencia IT incluye una colección de herramientas destinadas a tareas habituales de soporte técnico, diagnóstico, mantenimiento y recuperación.

Las aplicaciones están organizadas por categorías para facilitar su localización durante una intervención.

La estructura principal utilizada es:

    APPS/
    ├── Diagnostico/
    ├── Disco/
    ├── Recuperacion/
    ├── Red/
    ├── Seguridad/
    ├── Sistema/
    ├── Sysinternals/
    └── Utilidades/

---

## Diagnóstico

Esta sección contiene herramientas destinadas a obtener información sobre el hardware y analizar posibles problemas del sistema.

| Herramienta | Función |
|---|---|
| BlueScreenView | Análisis de información relacionada con pantallazos azules de Windows |
| CPU-Z | Información sobre procesador, memoria y placa base |
| CrystalDiskInfo | Consulta del estado SMART y salud de unidades de almacenamiento |
| GPU-Z | Información sobre la tarjeta gráfica |
| HWiNFO64 | Información detallada y monitorización del hardware |
| WhoCrashed | Análisis de fallos y archivos de volcado de Windows |

Estas herramientas permiten realizar una primera evaluación del equipo antes de aplicar cambios o reparaciones.

---

## Disco

Contiene utilidades relacionadas con el diagnóstico, análisis y administración de dispositivos de almacenamiento.

| Herramienta | Función |
|---|---|
| DiskGenius | Gestión de discos, particiones y determinadas tareas de recuperación |
| HDDScan | Diagnóstico de dispositivos de almacenamiento |
| Rufus | Creación de dispositivos USB arrancables |
| Victoria | Diagnóstico y comprobación de unidades de almacenamiento |
| WizTree | Análisis del espacio utilizado en disco |

Esta categoría permite comprobar el estado de los discos, analizar su utilización y realizar diferentes tareas de mantenimiento.

---

# Recuperación

Las herramientas de recuperación se encuentran divididas en varias categorías según su finalidad.

## Backup

### FreeFileSync

Herramienta utilizada para sincronización y copia de archivos y carpetas.

### Hasleo Backup

Permite realizar tareas de copia de seguridad y restauración.

---

## Clonado

### HDD Raw Copy Tool

Utilidad destinada a realizar copias y clonados de dispositivos de almacenamiento a bajo nivel.

Puede utilizarse cuando es necesario crear una copia de un dispositivo antes de realizar determinadas operaciones de recuperación o mantenimiento.

---

## Recuperación de datos

| Herramienta | Función |
|---|---|
| Recuva | Recuperación de archivos eliminados |
| DiskGenius | Gestión de particiones y determinadas tareas de recuperación |
| TestDisk | Recuperación y análisis de particiones y estructuras de disco |

Estas herramientas proporcionan diferentes alternativas dependiendo del tipo de problema encontrado.

Siempre que sea posible, las operaciones de recuperación deben realizarse evitando escribir nuevos datos sobre el dispositivo afectado.

---

## Recuperación de credenciales

El kit incorpora utilidades destinadas a recuperar información almacenada localmente en sistemas propios o sobre los que se dispone de autorización.

Entre ellas se encuentran:

- WebBrowserPassView.
- WirelessKeyView.

Estas herramientas se incluyen únicamente para tareas legítimas de recuperación y soporte técnico autorizado.

---

# Sistema

Esta categoría contiene herramientas destinadas al mantenimiento y administración de Windows.

## Arranque

### Hasleo EasyUEFI

Permite consultar y administrar determinadas configuraciones de arranque UEFI.

Puede resultar útil durante el diagnóstico de problemas relacionados con el arranque del sistema.

---

## Limpieza

### BleachBit

Herramienta destinada a eliminar archivos innecesarios y realizar tareas básicas de limpieza del sistema.

---

## Windows

| Herramienta | Función |
|---|---|
| Everything | Búsqueda rápida de archivos y carpetas |
| ShowKeyPlus | Consulta de información relacionada con licencias de Windows |
| TreeSize | Análisis del espacio ocupado en unidades y carpetas |

---

# Red

Las herramientas de red están organizadas según el tipo de diagnóstico que permiten realizar.

## Administración remota

### PuTTY

Cliente utilizado para realizar conexiones remotas mediante protocolos como SSH.

---

## Análisis de conexiones y tráfico

### TCPView

Permite visualizar conexiones TCP y UDP activas en un sistema Windows.

### Wireshark

Herramienta de análisis de tráfico de red que permite capturar e inspeccionar paquetes.

---

## Diagnóstico de rutas

### WinMTR

Combina funciones similares a `ping` y `traceroute`, permitiendo analizar la ruta seguida por las comunicaciones y detectar posibles problemas de conectividad.

---

## Escaneo de red

El kit incluye:

- Advanced IP Scanner.
- Angry IP Scanner.

Estas herramientas permiten identificar dispositivos y direcciones activas dentro de redes sobre las que se dispone de autorización.

---

# Seguridad

Esta sección contiene herramientas destinadas al análisis y comprobación de seguridad del sistema:

- Emsisoft.
- GlassWire.
- Malwarebytes.

Permiten complementar las tareas de diagnóstico cuando existe sospecha de software no deseado, malware o actividad de red que requiere revisión.

---

# Sysinternals

El kit incorpora **Sysinternals Suite**, conjunto de herramientas de Microsoft orientadas a la administración, diagnóstico y resolución de problemas en sistemas Windows.

Estas utilidades permiten analizar con mayor detalle procesos, servicios, conexiones y diferentes componentes internos del sistema operativo.

---

# Utilidades

También se incluyen herramientas auxiliares que pueden resultar necesarias durante una intervención técnica.

| Categoría | Herramienta | Uso |
|---|---|---|
| Compresión | 7-Zip | Compresión y descompresión de archivos |
| Hash | HashTool64 | Cálculo y comprobación de hashes |
| PDF | SumatraPDF | Visualización ligera de documentos PDF |
| Texto | Notepad++ | Edición de archivos de texto, configuración y código |

---

## Criterio de organización

Las aplicaciones se clasificaron según su función para reducir el tiempo necesario para localizar una herramienta durante una intervención.

La organización permite comenzar por herramientas de diagnóstico y seleccionar posteriormente las utilidades de disco, recuperación, sistema, red o seguridad según el problema detectado.

---

## Uso responsable

Las herramientas incluidas en el Kit de Emergencia IT están destinadas a tareas de aprendizaje, mantenimiento y soporte técnico.

Las utilidades relacionadas con recuperación de información, credenciales, administración remota, análisis de tráfico o escaneo de redes deben utilizarse exclusivamente en:

- Equipos propios.
- Sistemas bajo responsabilidad del técnico.
- Equipos o redes para los que exista autorización.

---

## Resultado

La organización por categorías proporciona un entorno de trabajo portátil desde el que se pueden abordar diferentes incidencias sin necesidad de localizar y descargar cada herramienta durante una intervención.

El conjunto complementa los entornos de arranque disponibles mediante Ventoy y convierte el USB en una herramienta de apoyo para tareas habituales de soporte IT.
