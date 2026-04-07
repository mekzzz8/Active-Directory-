# Active Directory Lab: Gestión de Identidades y Troubleshooting Dual

Este proyecto documenta el despliegue, configuración y administración de un entorno de **Active Directory** en Windows Server. La metodología aplicada se centra en el **Troubleshooting Dual**, demostrando la capacidad de resolver incidencias tanto mediante interfaz gráfica (GUI) como a través de automatización con **PowerShell**.



## Objetivos del Proyecto
* **Implementación de Infraestructura:** Configuración de Roles de Dominio (AD DS) y DNS.
* **Gestión de Identidades:** Creación y administración de Usuarios, Grupos y Unidades Organizativas (OU).
* **Hardening y Políticas:** Despliegue de Directivas de Grupo (GPO) para asegurar el entorno.
* **Resolución de Incidencias:** Simulación y solución de los 7 tickets más comunes en entornos corporativos.

## Stack Tecnológico
* **Sistema Operativo:** Windows Server 2022 / 2019.
* **Lenguaje de Automatización:** PowerShell (ActiveDirectory Module).
* **Entorno:** Virtualización (VMware / VirtualBox) con clientes Windows 10/11 Pro.

## Puntos Clave del Laboratorio

### 1. Administración Dual (GUI vs CLI)
El valor diferencial de este laboratorio es la resolución de problemas en dos niveles:
* **Nivel Técnico Soporte:** Uso de herramientas administrativas clásicas (ADUC, DNS Manager).
* **Nivel SysAdmin/Seguridad:** Uso de comandos PowerShell para diagnósticos profundos y ejecución masiva.

### 2. Troubleshooting de Tickets Reales
Se han documentado soluciones para escenarios críticos como:
* **Event ID 4740:** Localización del origen de bloqueos de cuenta.
* **Replicación de DC:** Uso de `repadmin` para asegurar la integridad del bosque.
* **GPO Refresh:** Diagnóstico de aplicación de políticas con `gpupdate /force`.

### 3. Seguridad y Auditoría
* Análisis de **Logs de Seguridad** para detectar inicios de sesión inusuales.
* Implementación de políticas de contraseñas y bloqueos para mitigar ataques de fuerza bruta.

## Estructura del Repositorio
* `/scripts`: Contiene scripts de PowerShell útiles para la administración diaria.
* `/docs`: Guías paso a paso de la instalación y configuración inicial.
* `index.html`: Dashboard interactivo para visualizar los tickets resueltos.

---
## Autor
**Jose Ignacio Navarro**
*Especialista en Sistemas y Ciberseguridad.*
* [LinkedIn](www.linkedin.com/in/jose-ignacio-navarro-de-palencia-garcia-542ba5296)
* [Portfolio Web](https://mekzzz8.github.io/Active-Directory-/)
