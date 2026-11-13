# Proyecto - Puesta en servicio de equipos informáticos

* **Ciclo:** 1.º ASIR
* **Módulos principales:** Implantación de Sistemas Operativos y Fundamentos de Hardware
* **Organización:** Equipos de 4 alumnos
* **Metodología:** Aprendizaje basado en retos

---

## 1. Situación de partida

Formáis parte del departamento técnico de una empresa especializada en mantenimiento y recuperación de equipos informáticos.

La empresa ha recibido cuatro encargos de diferentes clientes. Cada uno presenta necesidades y características distintas.

Vuestro equipo deberá resolver los cuatro casos. No podéis elegir solamente uno ni repartir los casos de manera que cada integrante conozca únicamente el suyo.

Todos los miembros deberán participar en las actividades y ser capaces de explicar las soluciones aplicadas.

---

## 2. Casos prácticos obligatorios

### CASO A — Recuperación de un ordenador antiguo
Una asociación necesita recuperar un ordenador con recursos limitados para navegar por Internet y realizar tareas de ofimática.

**Hardware disponible:**
* 1 vCPU.
* 2 GiB de RAM.
* Disco de 20 GiB.
* BIOS heredado.
* Adaptador de red virtual.

**Trabajo solicitado:** Investigar y seleccionar un sistema operativo compatible, instalarlo, configurar las aplicaciones necesarias y evaluar su funcionamiento.

---

### CASO B — Instalación de Windows 11
Una empresa necesita preparar un equipo con Windows 11, pero la configuración inicial no cumple todos los requisitos.

**Hardware inicial:**
* 2 vCPU.
* 4 GiB de RAM.
* Disco de 80 GiB.
* Firmware UEFI.
* TPM virtual desactivado.

**Trabajo solicitado:** Consultar los requisitos oficiales, identificar los problemas de compatibilidad y modificar justificadamente la configuración para conseguir una instalación admitida y funcional. Si existen incompatibilidades que no se pueden resolver, deberán documentarse.

---

### CASO C — Instalación de un servidor
Una pequeña empresa necesita un sistema operativo para prestar servicios internos en el futuro.

**Hardware disponible:**
* 2 vCPU.
* 2 GiB de RAM.
* Disco de 25 GiB.
* Adaptador de red virtual.

**Trabajo solicitado:** Comparar soluciones, seleccionar un sistema operativo de servidor adecuado, instalarlo sin entorno gráfico si no es necesario y verificar su funcionamiento.

---

### CASO D — Diagnóstico y reparación de un servidor
Una empresa ha detectado varias incidencias en su servidor Ubuntu Server. El operario de mantenimiento ha registrado los siguientes avisos:

* **Incidencia D1. Fallo durante el arranque:** Tras una parada de mantenimiento, el operario intenta encender el servidor, pero Ubuntu no consigue completar el arranque y muestra una pantalla solicitando una intervención de mantenimiento.
* **Incidencia D2. Fallo de acceso remoto:** El administrador informa de que no puede conectarse al servidor mediante SSH desde su equipo de trabajo, aunque anteriormente utilizaba este método para administrarlo.
* **Incidencia D3. Problemas de almacenamiento:** El operario informa de que el servidor muestra advertencias relacionadas con la falta de espacio disponible. Algunas operaciones se ejecutan con dificultad y teme que el sistema deje de funcionar correctamente.
* **Incidencia D4. Problemas de acceso a archivos:** El personal de la empresa comunica que no puede consultar ni modificar el archivo de inventario de equipos situado en `/srv/empresa/inventario.csv`, aunque anteriormente podía trabajar con él sin problemas.

**Trabajo solicitado:**
Para cada incidencia deberéis:
1. Diagnosticar el problema e identificar su causa.
2. Documentar las comprobaciones realizadas y sus resultados.
3. Reparar la avería justificando la solución aplicada.
4. Verificar que el sistema vuelve a funcionar correctamente.

*Las intervenciones deberán realizarse sobre la máquina virtual proporcionada, sin reinstalar el sistema operativo y procurando conservar los datos existentes. El profesor proporcionará una máquina virtual con incidencias preparadas.*

---

## 3. Actividades comunes a los cuatro casos

Para cada caso deberéis realizar, cuando corresponda:

1. Analizar las características del hardware y las necesidades del cliente.
2. Consultar documentación técnica.
3. Justificar la selección del sistema operativo.
4. Planificar y configurar los recursos virtuales.
5. Instalar o recuperar el sistema.
6. Comprobar el funcionamiento.
7. Identificar e inventariar el software instalado.
8. Documentar las decisiones, pruebas y resultados.

Además, el equipo deberá realizar una práctica de creación y restauración de imágenes de disco sobre una de las máquinas instaladas, utilizando una herramienta apropiada, como **Clonezilla**.

Deberéis recuperar la imagen desde dos ubicaciones de almacenamiento diferentes y verificar que el sistema restaurado funciona.

---

## 4. Organización del equipo

Cada grupo estará formado por cuatro personas.

Todos los miembros deben trabajar en los cuatro casos, aunque se distribuyan las responsabilidades.

Para organizar el trabajo se utilizará **GitHub Projects**, con tareas asignadas, responsables y seguimiento de su estado.

### Reparto de responsabilidades
Se proponen cuatro funciones:

| Función | Responsabilidad |
| --- | --- |
| **Coordinación** | Organización de tareas y seguimiento de GitHub Projects. |
| **Hardware** | Análisis de recursos, configuración de VM y diagnóstico de hardware virtual. |
| **Sistemas** | Instalaciones, configuración y actualizaciones. |
| **Calidad y documentación** | Pruebas, evidencias, inventarios y documentación técnica. |

Estas funciones deberán rotar entre los integrantes durante el reto. Cada alumno tendrá que asumir diferentes responsabilidades.

---

## 5. Hitos y entregables

| Hito | Actividad | Entregable |
| :---: | --- | --- |
| **1** | Análisis y selección de sistemas para A, B y C | Fichas técnicas y comparativa |
| **2** | Instalación y verificación de A, B y C | Tres VM operativas y documentadas |
| **3** | Software, actualizaciones y rendimiento | Inventarios y pruebas comparativas |
| **4** | Imagen, restauración e incidencias del caso D | Imagen recuperable y partes de incidencia |
| **5** | Validación y documentación final | Repositorio completo y demostración técnica |

---

## 6. Entrega

Toda la documentación deberá estar disponible en el repositorio GitHub del equipo.

El repositorio contendrá un directorio para cada caso práctico y una sección con la documentación común.

Las máquinas virtuales y las imágenes de disco deberán conservarse en la ubicación que indique el profesor. **No se subirán archivos de discos virtuales completos al repositorio GitHub.**

---

## 7. Evaluación

Se evaluarán las competencias técnicas relacionadas con los RA y CE de Implantación de Sistemas Operativos y Fundamentos de Hardware.

El profesor podrá solicitar a cualquier integrante del equipo que:
* Explique las características técnicas de una máquina.
* Justifique la elección de un sistema operativo.
* Identifique las particiones y los sistemas de archivos.
* Demuestre el funcionamiento de una instalación.
* Utilice herramientas de diagnóstico.
* Explique cómo se ha recuperado un sistema.
* Resuelva una incidencia similar a las trabajadas.

La evaluación tendrá en cuenta las evidencias del trabajo en equipo y las demostraciones individuales. Todos los integrantes deberán conocer las soluciones de los cuatro casos.

---

## 8. Resultado final

El equipo deberá entregar tres máquinas virtuales instaladas y verificadas, resolver las incidencias del cuarto caso, crear y restaurar una imagen de sistema y elaborar la documentación técnica correspondiente.

El objetivo es demostrar que podéis abordar el ciclo completo de puesta en servicio de un sistema informático: análisis, selección, instalación, verificación, mantenimiento, diagnóstico y recuperación.
