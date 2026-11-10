# Requisitos Oficiales de Instalación

<p align="center">
  <b>Comprueba si tu equipo cumple con las especificaciones técnicas necesarias para la instalación.</b>
</p>

---

## 💻 Especificaciones de Hardware

| Componente | Requisito Mínimo |
| :--- | :--- |
| **Procesador (CPU)** | `1 GHz` o más rápido con 2 o más núcleos, arquitectura de 64 bits (SoC compatible).<br>*(Intel Core 8.ª gen+, AMD Ryzen serie 2000+, o Qualcomm Snapdragon 850 / Snapdragon X)* |
| **Memoria RAM** | `4 GB` o más |
| **Almacenamiento** | `64 GB` de espacio libre o más en el disco de instalación |
| **Firmware del sistema** | UEFI con capacidad de **Arranque Seguro** (*Secure Boot*) |
| **Seguridad (TPM)** | Módulo de plataforma segura (**TPM**) versión 2.0 *(integrado como Intel PTT o AMD fTPM)* |
| **Tarjeta gráfica** | Compatible con **DirectX 12** o posterior y controlador **WDDM 2.0** |
| **Pantalla** | Alta definición (`720p`), mayor a `9 pulgadas` en diagonal y `8 bits` por canal de color |
| **Conexión / Sesión** | Conexión a Internet y cuenta de Microsoft obligatorias para la configuración inicial |

---
El problema es que en el Hardware inicial pedía desactivar el TPM, pero para la instalación de W11 es obligatorio tener la versión 2.0.

**Hardware inicial:**
* 2 vCPU.
* 4 GiB de RAM.
* Disco de 80 GiB.
* Firmware UEFI.
* TPM virtual desactivado.
