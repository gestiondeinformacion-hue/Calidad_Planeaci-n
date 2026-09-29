Inventario de Calidad y Planeación
Aplicación web interactiva desarrollada para visualizar la estructura organizacional y explorar el inventario documental e indicadores corporativos en tiempo real, directamente a partir de una hoja de cálculo en Excel.

📌 Descripción del Proyecto
El sistema toma como fuente de datos el archivo INVENTARIO DOCUMENTACIÓN E INDICADORES VF.xlsx y genera un organigrama dinámico e interactivo. Permite navegar visualmente por los diferentes procesos de la organización, consultar la distribución documental por macroproceso, filtrar por tipo de documento o líder responsable, y consultar las fórmulas de cálculo de los indicadores asociados.

🚀 Características Principales
Organigrama Interactivo con Zoom y Desplazamiento: Controles de navegación visual (acercar, alejar, restablecer) y soporte para arrastrar la pantalla (panning).

Conteo Automatizado (Badges): Burbujas dinámicas que indican la cantidad exacta de documentos asignados a cada proceso del organigrama.

Consolidación Inteligente de Datos (Celdas Combinadas): Agrupación por código y nombre único de documento, evitando duplicados al contabilizar procedimientos que contienen múltiples indicadores.

Navegación Multinivel por Modales:

Resumen por Macroproceso: Desglose del total de activos documentales al hacer clic en un proceso.

Detalle de Documentos y Filtros: Vista filtrable por Tipo de Documento (Procedimiento, Formato, Manual, Instructivo, etc.) y Líder Responsable.

Visualizador de Indicadores: Cada tarjeta muestra la lista de indicadores asociados con un botón dedicado para consultar la fórmula detallada en una ventana emergente.

Lectura en Tiempo Real: Procesamiento dinámico del archivo Excel directamente en el navegador del cliente mediante SheetJS (xlsx).

📁 Estructura del Repositorio
Plaintext
.
├── index.html                                  # Código fuente principal (Estructura, Estilos CSS y Lógica JS)
├── INVENTARIO DOCUMENTACIÓN E INDICADORES VF.xlsx  # Fuente de datos en Excel
├── Logo.png                                    # Logotipo institucional
└── README.md                                   # Documentación del proyecto
🛠️ Tecnologías Utilizadas
HTML5 & CSS3: Diseño responsivo con variables CSS, arquitectura de modales y layout en flexbox/grid.

JavaScript (ES6+): Manipulación del DOM, filtros dinámicos y manejo de modales interactivos.

SheetJS (xlsx.js): Lectura y análisis cliente de archivos .xlsx.
