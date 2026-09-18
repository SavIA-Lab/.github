<div align="center">
  <!-- Reemplaza el src con la URL del banner oficial de SavIA-Lab -->
  <img src="https://www.fia.cl/wp-content/uploads/2022/02/logo_sabialab.webp" alt="SavIA Lab Banner" width="100%" />

  <h1>SavIA-Lab</h1>
  <p><b>Laboratorio de Soluciones Avanzadas en Virtualización e Inteligencia Artificial</b></p>
  <p><i>Universidad El Bosque | Bogotá, Colombia</i></p>
</div>

---

Dirigido por la **Dra. Sandra Janneth Perdomo Lara**, SavIA-Lab es un centro de investigación enfocado en la innovación tecnológica y el desarrollo de Inteligencia Artificial aplicada a la resolución de desafíos críticos en el sector salud.

## Áreas de Investigación y Desarrollo

* **Inteligencia Artificial en Salud:** Creación de sistemas de soporte para la toma de decisiones clínicas y diagnóstico automatizado.
* **Oncología de Precisión y Patología Digital:** Proyectos interdisciplinarios enfocados en la detección temprana de cáncer (cuello uterino, mama y colorrectal) utilizando biomarcadores moleculares e imágenes médicas.
* **Bioingeniería y Tecnologías Point-of-Care:** Desarrollo de soluciones accesibles para la práctica clínica y la salud pública, incluyendo bioimpresión 3D.
* **Genómica y Bioinformática:** Análisis de datos complejos para la investigación biomédica traslacional.

---

## SavIA Admin: Infraestructura Unificada

**SavIA Admin** es el software de gestión interna desarrollado por **SavIA Control**. Su propósito es centralizar la administración de la infraestructura tecnológica de SavIA-Lab, actuando como una capa de orquestación y gobierno sobre el ecosistema físico y lógico del laboratorio.

**Objetivo Institucional:** Convertir recursos físicos fragmentados en un entorno de infraestructura institucional único, donde cada recurso de hardware, usuario, proyecto, dataset y ejecución pueda ser identificado, gobernado, monitoreado y auditado desde un único sistema central.

### Capacidades Principales

- **Gestión de Cómputo:** Administración unificada de GPUs, servidores, workstations y nodos de procesamiento.
- **Control de Proyectos y Jobs:** Asignación de cargas de trabajo y seguimiento del ciclo de vida de ejecuciones (*jobs*).
- **Gobernanza de Datos:** Gestión centralizada de almacenamiento, catálogos de metadatos y acceso a *datasets*.
- **Identidad y Seguridad:** Control granular de permisos, autenticación centralizada y políticas de acceso.
- **Observabilidad:** Visibilidad en tiempo real del estado de la infraestructura, métricas de rendimiento y trazabilidad operativa.

### Arquitectura e Integraciones

SavIA Admin opera como una capa superior que conecta herramientas especializadas y consolidadas del ecosistema de alto rendimiento:

| Dominio | Tecnología | Rol dentro de SavIA Admin |
| :--- | :--- | :--- |
| **Scheduling** | ![Slurm](https://img.shields.io/badge/Slurm-005571?style=flat-square) | Planificación y orquestación de cargas de cómputo de alto rendimiento. |
| **Identidad (IAM)** | ![Keycloak](https://img.shields.io/badge/Keycloak-Integrado-blue?style=flat-square) | Gestión unificada de usuarios, autenticación y autorización por roles. |
| **Observabilidad** | ![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square) ![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square) | Recolección de métricas, alertas y paneles de monitoreo. |
| **Almacenamiento** | ![NFS](https://img.shields.io/badge/NFS-Storage-lightgrey?style=flat-square) ![S3](https://img.shields.io/badge/S3-Object_Storage-569A31?style=flat-square) | Abstracción y gestión de volúmenes de almacenamiento en bloque y objetos. |
| **Gobernanza** | **Data Catalogs** | Registro, trazabilidad y control de acceso a conjuntos de datos biomédicos. |

### Hoja de Ruta de Desarrollo

El proyecto SavIA Admin se despliega mediante una estrategia modular iterativa:

1. **Levantamiento y Validación:** Diagnóstico detallado y validación técnica del estado actual del laboratorio.
2. **Definición de Arquitectura:** Diseño de la capa de control, requerimientos de integración y especificación de modelos de datos.
3. **Despliegue de MVPs:** Desarrollo iterativo por módulos, ejecuciones de prueba y validación con usuarios clave.
4. **Operación en Producción:** Despliegue definitivo, migración de componentes y gobernanza activa de la infraestructura.

---

<div align="center">
  <p><i>Transformando datos en salud a través de la inteligencia artificial.</i></p>
  
  <!-- Enlaces de contacto o institucionales de la universidad -->
  <a href="https://www.linkedin.com/in/sandra-janneth-perdomo-lara-9b43b923/">Contacto</a> • 
  <a href="https://unbosque.portalinvestigacion.com/publicaciones">Publicaciones El Bosque</a>
</div>
