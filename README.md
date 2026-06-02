# 4. Ingeniería del Proyecto: Balances de Recursos (Conexia)

A continuación, se sistematizan los requerimientos físicos, humanos, tecnológicos y de servicios necesarios para garantizar la operación ininterrumpida de la plataforma **Conexia** durante su primer año de funcionamiento. La estructura ha sido adaptada estrictamente para un proyecto de base tecnológica (SaaS), aplicando los lineamientos de evaluación de proyectos (Baca Urbina, Sapag) y la normativa tributaria boliviana vigente.

---

### 4.1. Balance de Personal (Mano de Obra)
Este cuadro detalla el requerimiento de talento humano. Se clasifica en **Mano de Obra Directa (MOD)**, referida al personal técnico indispensable para el desarrollo, mantenimiento y operatividad del software; y **Mano de Obra Indirecta (MOI)**, referida al personal administrativo y comercial que sostiene el negocio.

| Clasificación | Descripción del Puesto | Nro. de Puestos | Salario Mensual (Bs.) | Salario de Proceso de Producción (Mensual) (Bs.) | Salario Anual Total (Bs.) |
| :--- | :--- | :---: | :---: | :---: | :---: |
| **Mano de Obra Directa (MOD)** | Desarrollador Senior / Arquitecto Cloud | 1 | 8,500.00 | 8,500.00 | 102,000.00 |
| **Mano de Obra Directa (MOD)** | Desarrollador Junior / Frontend | 1 | 4,500.00 | 4,500.00 | 54,000.00 |
| **Mano de Obra Directa (MOD)** | Administrador de Base de Datos / Soporte | 1 | 4,000.00 | 4,000.00 | 48,000.00 |
| *Subtotal MOD* | | *3* | | *17,000.00* | *204,000.00* |
| **Mano de Obra Indirecta (MOI)** | Administrador General / Rep. Legal | 1 | 5,500.00 | 5,500.00 | 66,000.00 |
| **Mano de Obra Indirecta (MOI)** | Ejecutivo de Ventas B2B / Marketing | 1 | 4,500.00 | 4,500.00 | 54,000.00 |
| *Subtotal MOI* | | *2* | | *10,000.00* | *120,000.00* |
| **TOTAL PERSONAL** | | **5** | | **27,000.00** | **324,000.00** |

---

### 4.2. Balance de Equipos de Computación y Tecnología (Inversión Fija)
Este balance contempla los activos físicos tecnológicos. Para el cálculo de la depreciación se asume una **vida útil de 4 años (25% anual)** según el Anexo del DS 24051 para Equipos de Computación. El valor de salvamento se estima en un 15% del costo original por obsolescencia tecnológica.

| Clasificación Operativa | Descripción del Equipo | Cantidad | Costo Unitario (Bs.) | Costo Total (Bs.) | Vida Útil (Años) | Depreciación Anual (Bs.) | Valor de Salvamento (Bs.) |
| :--- | :--- | :---: | :---: | :---: | :---: | :---: | :---: |
| **Costos Fijos** | Laptop Alto Rendimiento (Core i7, 16GB RAM) | 3 | 8,500.00 | 25,500.00 | 4 | 6,375.00 | 3,825.00 |
| **Costos Fijos** | Laptop Administrativa (Core i5, 8GB RAM) | 2 | 5,500.00 | 11,000.00 | 4 | 2,750.00 | 1,650.00 |
| **Costos Fijos** | Monitores Externos 24" para desarrollo | 3 | 1,200.00 | 3,600.00 | 4 | 900.00 | 540.00 |
| **Costos Fijos** | Router Empresarial Doble Banda | 1 | 1,500.00 | 1,500.00 | 4 | 375.00 | 225.00 |
| **Costos Fijos** | Disco Duro Externo de Respaldo (4TB) | 2 | 800.00 | 1,600.00 | 4 | 400.00 | 240.00 |
| **TOTAL EQUIPOS** | | **11** | | **43,200.00** | | **10,800.00** | **6,480.00** |

---

### 4.3. Balance de Muebles y Enseres (Inversión Fija)
Inventario del mobiliario requerido para equipar la oficina administrativa y técnica. Se aplica una **vida útil de 10 años (10% anual)** conforme a la normativa contable boliviana. Se estima un valor de salvamento del 20%.

| Clasificación Operativa | Descripción del Mobiliario | Cantidad | Costo Unitario (Bs.) | Costo Total (Bs.) | Vida Útil (Años) | Depreciación Anual (Bs.) | Valor de Salvamento (Bs.) |
| :--- | :--- | :---: | :---: | :---: | :---: | :---: | :---: |
| **Costos Fijos** | Escritorios de trabajo en L | 5 | 850.00 | 4,250.00 | 10 | 425.00 | 850.00 |
| **Costos Fijos** | Sillas ergonómicas ejecutivas | 5 | 650.00 | 3,250.00 | 10 | 325.00 | 650.00 |
| **Costos Fijos** | Estante metálico para archivos legales | 2 | 900.00 | 1,800.00 | 10 | 180.00 | 360.00 |
| **Costos Fijos** | Mesa de reuniones (4 personas) | 1 | 1,200.00 | 1,200.00 | 10 | 120.00 | 240.00 |
| **Costos Fijos** | Pizarra acrílica (Módulo Kanban físico) | 1 | 250.00 | 250.00 | 10 | 25.00 | 50.00 |
| **TOTAL MUEBLES** | | **14** | | **10,750.00** | | **1,075.00** | **2,150.00** |

---

### 4.4. Balance de Insumos y Servicios Cloud (Operación Digital)
Este cuadro abstrae el concepto clásico de "materia prima", sustituyéndolo por la infraestructura de TI consumida mensualmente. Se agrupa en **Insumos Variables** (aquellos cuyo consumo aumenta proporcionalmente al tráfico y número de usuarios) e **Insumos Fijos** (licencias base que no dependen del volumen de transacciones).

| Clasificación | Descripción del Servicio / Insumo Cloud | Unidad de Medida | Costo de Proceso de Producción (Consumo Mensual Estimado) | Costo Unitario (Bs.) | Costo Anual Total (Bs.) |
| :--- | :--- | :--- | :--- | :---: | :---: |
| **Costos Variables (CVD)** | Almacenamiento S3 (Repositorio CVs y PDFs) | Gigabytes (GB) | 300 GB / mes | 0.50 | 1,800.00 |
| **Costos Variables (CVD)** | Ancho de banda de transferencia de salida | Gigabytes (GB) | 800 GB / mes | 0.80 | 7,680.00 |
| **Costos Variables (CVD)** | Consumo API Pasarela Pagos (Comisión est.) | Transacciones | 400 Tx / mes | 3.50 | 16,800.00 |
| *Subtotal Variables* | | | | | *26,280.00* |
| **Costos Fijos (CFD)** | Instancia Servidor de Producción (AWS EC2) | Mes | 1 Instancia / mes | 800.00 | 9,600.00 |
| **Costos Fijos (CFD)** | Licencia Base de Datos (MongoDB Atlas) | Mes | 1 Licencia / mes | 350.00 | 4,200.00 |
| **Costos Fijos (CFD)** | Dominio web regional (.com.bo) | Año | 1 Renovación / año | 980.00 | 980.00 |
| **Costos Fijos (CFD)** | Certificados de Seguridad (SSL Wildcard) | Año | 1 Renovación / año | 450.00 | 450.00 |
| *Subtotal Fijos* | | | | | *15,230.00* |
| **TOTAL INSUMOS CLOUD** | | | | | **41,510.00** |

---

### 4.5. Balance de Activos Diferidos (Inversión Intangible Pre-operativa)
Los activos diferidos representan los gastos realizados antes de iniciar operaciones que, por su naturaleza, no pueden tocarse físicamente (intangibles) pero otorgan derechos legales o comerciales a la empresa.

| Clasificación Operativa | Descripción del Gasto / Trámite | Cantidad | Costo Unitario (Bs.) | Costo Total (Bs.) |
| :--- | :--- | :---: | :---: | :---: |
| **Costos Fijos** | Constitución Legal y Registro (SEPREC, Notaría) | 1 | 2,500.00 | 2,500.00 |
| **Costos Fijos** | Registro de Marca y Propiedad Intelectual (SENAPI) | 1 | 1,800.00 | 1,800.00 |
| **Costos Fijos** | Licencias iniciales de Software de Desarrollo (IDEs) | 1 Lote | 3,000.00 | 3,000.00 |
| **Costos Fijos** | Desarrollo inicial de la plataforma (Fase Beta / MVP)* | 1 | 18,000.00 | 18,000.00 |
| **Costos Fijos** | Gastos de organización y puesta en marcha | 1 Lote | 2,500.00 | 2,500.00 |
| **TOTAL DIFERIDOS** | | | | **27,800.00** |

*(Nota: El desarrollo del MVP se cataloga como activo diferido amortizable, dado que es una inversión pre-operativa indispensable para que el negocio exista).*
