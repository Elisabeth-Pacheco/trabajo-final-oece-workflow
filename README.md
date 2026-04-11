# trabajo-final-oece-workflow

## Descripción
Repositorio del Trabajo Final del curso **Fundamentos de Programación para IA Generativa Aplicada**, orientado al diseño de un **workflow reproducible** para la inspección, descarga, auditoría, ensamblaje y visualización de convocatorias públicas del OECE.

## Propósito del proyecto
Este proyecto no se plantea como una simple ampliación cuantitativa de la Tarea 2, sino como una **propuesta de mejora de flujo de trabajo reproducible** aplicada al módulo **“Datos de la Convocatoria o Invitación”** del Portal de Datos Abiertos del OECE.

El objetivo es transformar una fuente administrativa estatal en una arquitectura técnica y documental clara, auditable y presentable, con utilidad para: Ciencias Sociales, Políticas Públicas, Gestión Pública.

## Pregunta del trabajo
**¿Cómo diseñar un workflow reproducible, modular y escalable que permita descargar, auditar, ensamblar y visualizar datos de convocatorias públicas del OECE con utilidad para ciencias sociales, políticas públicas y gestión pública?**

## Objetivo general
Diseñar un workflow reproducible para la descarga, auditoría, ensamblaje y visualización de convocatorias públicas del OECE, en continuidad con la Tarea 2 y con relevancia para ciencias sociales y gestión pública.

## Tipo de propuesta
El Trabajo Final se plantea como una **propuesta técnico-metodológica de workflow reproducible modular**, y su finalidad es integrar en una sola arquitectura operativa: inspección de la fuente, captura automatizada, auditoría técnica, ensamblaje de bases, visualización exploratoria, documentación reproducible del proceso.

## Arquitectura general del workflow
**fuente → inspección → inventario → manifest → descarga → auditoría → lectura → ensamblaje → visualización → exportación**

## Herramientas de IA generativa utilizadas o pertinentes
Las herramientas de IA generativa se emplean como apoyo de diseño, documentación y revisión técnica, especialmente para:
- estructurar el workflow del proyecto;
- apoyar la redacción técnica del notebook, README y presentación;
- revisar consistencia entre objetivos, código y outputs;
- asistir en la explicación pedagógica del flujo de trabajo;
- apoyar la identificación y descripción de herramientas de programación.

## Herramientas de programación implementadas
El proyecto utiliza herramientas de programación orientadas a:
- **web scraping:** `requests`, `BeautifulSoup`, `selenium`, `webdriver-manager`;
- **manejo de datos:** `pandas`, `numpy`, `openpyxl`, `pathlib`;
- **limpieza y normalización:** `re`, `unicodedata`, `json`;
- **visualización:** `matplotlib`;
- **organización reproducible del proyecto:** estructura de carpetas, manifests, bitácoras, tablas de auditoría y resultados exportables.

## Estructura del repositorio
- `00_admin/`: manifests, bitácoras, tablas de control y documentos de administración del workflow.
- `01_insumos/`: insumos ligeros, capturas, referencias y materiales auxiliares.
- `02_fuente_web/`: HTML guardado, enlaces detectados, metadatos y logs de scraping.
- `03_datos_brutos/`: archivos descargados desde el portal, organizados por año.
- `04_datos_procesados/`: auditorías, tablas limpias, tablas unificadas y variables derivadas.
- `05_notebooks/`: notebooks principales del proyecto y antecedentes.
- `06_scripts/`: scripts `.py` exportados o de apoyo.
- `07_resultados/`: tablas, figuras y resúmenes generados por el workflow.
- `08_presentacion/`: presentaciones del proyecto y antecedentes de exposición.
- `09_entrega/`: carpeta reservada para la entrega final consolidada.

## Estado actual del proyecto
El repositorio contiene: la arquitectura base del proyecto; el notebook principal del Trabajo Final; los scripts de respaldo; materiales de la Tarea 2 como antecedente metodológico; presentaciones académicas asociadas al curso.

## Archivos principales
- `05_notebooks/Trabajo_final.ipynb`
- `06_scripts/trabajo_final.py`
- `05_notebooks/Tarea_2.ipynb`
- `06_scripts/tarea_2.py`
- `08_presentacion/trabajo_final_presentacion.pdf`

## Nota sobre reproducibilidad
El entorno principal de ejecución fue Google Colab con Google Drive como soporte operativo. GitHub cumple aquí la función de repositorio público de documentación, organización, versionamiento y presentación reproducible del workflow.

## Autora
**Elisabeth Pacheco Rojas**

## Profesor
**Alfonso Rodriguez**

## Asistente de curso
**Jimena Yali**

## Curso
**Fundamentos de Programación para IA Generativa Aplicada**  
Programa de Especialización en IA Generativa aplicada a CCSS y Gestión Pública
