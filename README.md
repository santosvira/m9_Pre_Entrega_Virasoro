 RetailPro — Proyecto de Data Analytics

Descripción del proyecto

RetailPro es un proyecto desarrollado durante el curso de Data Analytics de Coderhouse, utilizando una base de datos de ventas de productos tecnológicos.

El objetivo es transformar los datos comerciales en información útil para la toma de decisiones mediante SQL Server, consultas de negocio y herramientas de visualización.

Objetivos del proyecto

- Analizar la facturación y el comportamiento de las ventas.
- Identificar los productos con mayores ingresos.
- Evaluar el comportamiento de compra de los clientes.
- Integrar información de distintas tablas mediante JOIN.
- Preparar los datos para su posterior visualización en Power BI.

Estructura de la base de datos

La base de datos `Ventas_Tech_DB` contiene cuatro tablas principales:

- clientes: información de los clientes.
- productos: catálogo de productos tecnológicos.
- categorias: clasificación de los productos.
- ventas: operaciones comerciales, cantidades, precios y fechas.

 Relaciones entre tablas

- `ventas.id_cliente` → `clientes.id_cliente`
- `ventas.id_producto` → `productos.id_producto`
- `productos.id_categoria` → `categorias.id_categoria`

 Desarrollo del proyecto

 Módulo 3 — Modelo relacional

Creación de las tablas, claves primarias, claves foráneas y relaciones de la base de datos.

 Módulo 4 — Consultas de negocio

Archivo: `m4_consultas_negocio.sql`

Incluye cuatro consultas:

1. Resumen ejecutivo mensual.
2. Ranking de productos por facturación.
3. Identificación de clientes recurrentes.
4. Comparación de facturación respecto del promedio mensual.

 Módulo 5 — Integración de datos

Archivo: `m5_consultas_joins.sql`

Incluye:

1. Vista base mediante INNER JOIN.
2. Identificación de clientes sin compras mediante LEFT JOIN.
3. Identificación de productos sin ventas mediante LEFT JOIN.
4. Consolidación de ventas por quincena mediante UNION ALL.

 Cómo ejecutar los scripts SQL

1. Abrir Microsoft SQL Server Management Studio (SSMS).
2. Conectarse al servidor SQL Server.
3. Verificar que exista la base de datos `Ventas_Tech_DB` con sus tablas y datos.
4. Abrir el archivo `.sql` correspondiente.
5. Seleccionar la base de datos `Ventas_Tech_DB`.
6. Ejecutar las consultas y verificar los resultados.


 Principales indicadores comerciales

A partir de las consultas del Módulo 4 se obtuvieron los siguientes resultados para marzo:

- Facturación total: $6.444,00.
- Cantidad de pedidos: 10.
- Ticket promedio: $644,40.
- Producto con mayor facturación: ID 1, con $3.600,00.

Los resultados corresponden al período disponible y no representan necesariamente tendencias comerciales de largo plazo.

Se utilizó ChatGPT como herramienta de apoyo para:

- Revisar posibles optimizaciones en consultas SQL.
- Identificar hallazgos comerciales a partir de resultados reales.
- Generar y mejorar la documentación del proyecto.

Las sugerencias de IA fueron evaluadas utilizando criterio analítico para comprobar su coherencia con los datos.


Santos Virasoro
 Coderhouse Data Analytics.
