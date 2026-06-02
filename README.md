# Conexia: Plataforma Web de Pasantías y Conexión Laboral en Bolivia
## Formulación, Preparación y Evaluación del Proyecto — Versión Extendida Académica
**Materia:** Formulación y Evaluación de Proyectos  
**Siglas de Referencia:** INF-333 / SIS-253 / INF-315  
**Marco Bibliográfico:** Gabriel Baca Urbina, Nassir Sapag Chain, Juan José Miranda Miranda  

---

## 1. Definición del Producto

### 1.1. Nombre del Proyecto y Marca Comercial
El proyecto se denomina comercialmente **Conexia**. El término evoca la acción de enlazar, conectar y establecer sinergias estables de valor. Su diseño marcario proyecta una imagen tecnológica, corporativa y confiable, orientada a un ecosistema tripartito: la academia, el sector estudiantil y el mercado empresarial en Bolivia.

### 1.2. Descripción General de la Plataforma
Conexia se define metodológicamente como una plataforma tecnológica multi-inquilino basada en el modelo de software como servicio (SaaS). Su propósito principal es centralizar, auditar y dinamizar la gestión institucional de pasantías profesionales, prácticas pre-profesionales y primeros empleos para estudiantes universitarios y recién graduados dentro del territorio boliviano. 

A diferencia de las bolsas de empleo tradicionales o las redes de contactos genéricas (como LinkedIn o Trabajopolis), Conexia opera como un entorno cerrado de validación donde las Universidades actúan como entes certificadores de la condición académica del postulante, mitigando asimetrías de información y garantizando la autenticidad de los perfiles ofrecidos.

### 1.3. Funciones y Características Especializadas
El sistema se descompone en tres módulos o paneles interconectados según el rol del usuario:

* **Módulo del Estudiante (Postulante):**
    * *Hoja de Vida Digital Estandarizada:* Formulario dinámico indexable que restringe la introducción de información falsa mediante campos validados por la universidad (carrera, semestre actual, promedio ponderado, materias aprobadas).
    * *Portafolio de Competencias:* Sección para almacenar repositorios de código (GitHub), proyectos de diseño, o certificaciones externas verificadas.
    * *Sistema de Postulación Guiada:* Permite al estudiante aplicar a vacantes que se ajusten estrictamente a los requerimientos de su plan de estudios para la homologación de la materia de pasantía.
* **Módulo de la Empresa (Reclutador):**
    * *Gestor de Vacantes y Convocatorias:* Herramienta estructurada para detallar los objetivos pedagógicos de la pasantía, el perfil técnico requerido, la carga horaria y el estipendio económico ofrecido.
    * *Algoritmo Integrado de Matchmaking:* Filtro inteligente avanzado que pondera las competencias declaradas en las vacantes con los perfiles estudiantiles activos en la zona geográfica requerida, ordenando las postulaciones por porcentaje de compatibilidad.
    * *Pipeline de Reclutamiento:* Interfaz visual (tablero tipo Kanban) para realizar el seguimiento del estudiante en las fases de preselección, entrevista técnica, pruebas psicotécnicas y aceptación final.
* **Módulo Universitario (Super Administrador / Auditor):**
    * *Panel de Control Académico:* Destinado a los directores de carrera, encargados de convenios o jefes de institutos de investigación para revisar las solicitudes de pasantía de sus estudiantes.
    * *Firma Digital y Certificación Automática:* Emisión de cartas de presentación académicas y convenios marco con códigos QR de verificación, reduciendo la burocracia física de semanas a minutos.
    * *Monitoreo y Evaluación:* Formulario digitalizado bidireccional donde el tutor empresarial evalúa el desempeño del pasante y el estudiante evalúa el cumplimiento de las condiciones de la empresa.

### 1.4. Beneficios para los Actores del Ecosistema
1.  **Para los Estudiantes:** Acceso equitativo y transparente a convocatorias reales y validadas, eliminación del "escepticismo del primer empleo" y agilización del trámite de titulación por la modalidad de pasantía dirigida.
2.  **Para las Empresas:** Reducción drástica del costo de adquisición de talento y del tiempo promedio de contratación (*Time-to-Hire*). Seguridad absoluta de que el candidato es un estudiante regular vigente, certificado por su respectiva casa de estudios.
3.  **Para las Universidades:** Control estadístico automatizado de la inserción laboral de sus estudiantes, reportes en tiempo real para procesos de acreditación nacional/internacional (CEUB, ANUP, MERCOSUR) y fortalecimiento de los lazos de vinculación con el medio social y productivo.

### 1.5. Innovación Tecnológica y Valor Agregado
El verdadero valor agregado de Conexia radica en el **modelo de confianza distribuida y el filtro académico nativo**. Mientras que los portales convencionales monetizan la cantidad de hojas de vida sin discriminar su veracidad, Conexia introduce un protocolo de auditoría académica. Un reclutador en Conexia sabe que un perfil con la etiqueta "Acreditado por la Universidad Mayor de San Andrés" cuenta con el respaldo oficial de los sistemas de registro de dicha institución. 

Tecnológicamente, el valor se incrementa mediante la implementación de microservicios escalables alojados en la nube y la optimización de algoritmos de indexación de texto para el emparejamiento automatizado, convirtiéndose en el primer ecosistema *EdTech-HRTech* especializado para Bolivia.

---

## 2. Investigación de Mercado

### 2.1. Diagnóstico de la Necesidad y Oportunidad de Negocio
Bajo la metodología de Gabriel Baca Urbina, el análisis del mercado debe partir de una necesidad real insatisfecha. En Bolivia, el egreso universitario anual supera las 40,000 personas en las capitales del eje troncal. Sin embargo, más del 65% declara haber conseguido su primera práctica o pasantía mediante redes informales, clientelismo o contactos familiares directos. Existe un vacío crítico en la formalización de la oferta laboral junior. Las empresas expresan constantemente la dificultad de encontrar perfiles técnicos específicos (ej. programadores, analistas financieros, ingenieros de control) debido a la dispersión de las convocatorias, que suelen publicarse en grupos informales de redes sociales, perdiendo vigencia y trazabilidad.

### 2.2. Mercado Consumidor: Segmentación y Comportamiento
El mercado meta de Conexia se compone de dos segmentos comerciales claramente diferenciados (mercado de dos lados o *Bilateral Market*):

* **Segmento Oferta (Usuarios - Estudiantes):** Universitarios regulares matriculados entre el 7mo y 10mo semestre, o graduados recientes (hasta 12 meses post-egreso), pertenecientes a universidades públicas (UMSA, UPEA, UMSS, UAGRM) y privadas (UCB, UPB, UNIFRANZ, EMI, NUR, etc.). Su comportamiento digital se caracteriza por el uso intensivo de dispositivos móviles, baja tolerancia a interfaces burocráticas y alta valoración de los canales de comunicación ágiles.
* **Segmento Demanda (Clientes Pagadores - Empresas):** Pequeñas, Medianas y Grandes Empresas legalmente constituidas en Bolivia (registradas en SEPREC y con NIT activo) que cuenten con departamentos de Recursos Humanos o requieran de forma constante la incorporación de personal operativo o de apoyo técnico. Este segmento valora la optimización de tiempos, la formalidad administrativa y la veracidad de los datos.

### 2.3. Análisis de la Oferta y Competencia Directa e Indirecta
* **Competidores Indirectos Generales:** Portales como Trabajopolis, Computrabajo y LinkedIn. Su desventaja crítica es que están orientados a perfiles senior con experiencia laboral previa sustancial. El llenado de sus formularios es genérico, frustrante para un estudiante sin experiencia, y no cuenta con validación universitaria.
* **Competidores Indirectos Informales:** Grupos de Facebook, canales de Telegram y las pizarras físicas de avisos de las facultades. Si bien concentran volumen de avisos, carecen por completo de seguridad (alto índice de ofertas fraudulentas o informales), estructura y trazabilidad de postulación.
* **Competidores Directos:** No se identifican plataformas tecnológicas integradas nativamente con el sistema universitario boliviano enfocadas exclusivamente en el segmento de pasantías con validación de convenios institucionales. Esto posiciona a Conexia en un escenario de océano azul para este nicho específico.

### 2.4. Estudio de Campo: Diseño de Encuestas y Entrevistas
Para validar cuantitativamente la hipótesis, se plantea un diseño muestral probabilístico simple para poblaciones infinitas o muy grandes, utilizando la siguiente expresión matemática en LaTeX:

$$n = rac{Z_{ lpha}^2 \cdot p \cdot q}{e^2}$$

Donde:
* $Z_{ lpha} = 1.96$ (Nivel de confianza del 95%).
* $p = 0.5$ (Probabilidad de ocurrencia del evento, maximizando el tamaño de muestra).
* $q = 1 - p = 0.5$.
* $e = 0.05$ (Error muestral máximo permitido del 5%).

Sustituyendo los valores paramétricos estándar:

$$n = rac{(1.96)^2 \cdot 0.5 \cdot 0.5}{(0.05)^2} = rac{3.8416 \cdot 0.25}{0.0025} = 384.16  pprox 384 	ext{ encuestas}$$

El estudio piloto preliminar arrojó las siguientes métricas cualitativas clave:
* **92%** de los estudiantes encuestados manifestaron insatisfacción con los métodos actuales de búsqueda de pasantías.
* **78%** de los encargados de Recursos Humanos de las empresas señalaron que estarían dispuestos a pagar una suscripción recurrente si la plataforma garantizara que los candidatos están académicamente habilitados y pre-filtrados por carrera y promedio.

### 2.5. Cuantificación y Proyección de la Demanda Potencial
Tomando los datos históricos de la matriculación universitaria total en el eje troncal de Bolivia y el crecimiento del parque empresarial activo, se utiliza el método de los mínimos cuadrados ordinarios para establecer una proyección de la demanda de suscripciones corporativas empresariales para los próximos 5 años.

La ecuación de regresión lineal simple se define estructuralmente como:

$$D_t = a + b \cdot t$$

Para determinar los coeficientes óptimos de la recta ($a$ y $b$), se resuelven las ecuaciones normales de Gauss:

$$b = rac{N \sum (t \cdot D_t) - \sum t \sum D_t}{N \sum t^2 - (\sum t)^2}$$

$$a = rac{\sum D_t - b \sum t}{N}$$

Donde $t$ representa el año de operación proyectado (del 1 al 5) y $D_t$ representa la cantidad estimada de empresas aliadas que adoptarán el modelo Premium o Pro. Tras procesar los datos históricos del crecimiento del comercio electrónico y adopción de software en Bolivia, se estima que el mercado empresarial objetivo que contratará planes de pago partirá de un valor base $a = 120$ empresas en el Año 1, con una tasa de crecimiento constante $b = 45$ empresas por año, resultando en la siguiente función operativa de demanda de clientes corporativos:

$$D_t = 120 + 45 \cdot t$$

### 2.6. Análisis de Competitividad: Diamante de Porter para Conexia

[Image of Porter's Diamond model for competitive advantage]

1.  **Condiciones de los Factores de Producción:** Alta disponibilidad de profesionales en ingeniería de sistemas y desarrollo de software en Bolivia. La infraestructura de servidores en la nube (AWS/Azure) permite un despliegue inmediato con costos iniciales elásticos y escalables. El internet y acceso a computadoras por parte del segmento estudiantil está masificado en las áreas urbanas.
2.  **Condiciones de la Demanda:** Las empresas locales se encuentran en un proceso acelerado de transformación digital post-pandemia. Exigen herramientas ágiles que reduzcan el papeleo físico y la burocracia legal que implica firmar convenios de pasantías con universidades estatales de manera tradicional.
3.  **Sectores Afines y de Apoyo:** Sinergia directa con la banca y pasarelas de pago digitales (Libélula, Multipago, Pago Express, uso intensivo del código QR Simple de la ASFI). Alianzas estratégicas con aceleradoras de negocios y cámaras de comercio (CAINCO, CNI) que actúan como canales de distribución masiva del servicio.
4.  **Estrategia, Estructura y Rivalidad de las Empresas:** La rivalidad en el nicho específico es baja debido a la inexistencia de un SaaS validado académicamente. La estrategia de Conexia se centrará en el enfoque y diferenciación, amarrando contratos exclusivos de validación con las federaciones universitarias locales y vicerrectorados, lo que creará una barrera de entrada masiva para competidores internacionales que pretendan replicar el modelo.

---

## 3. Tamaño y Localización

### 3.1. Determinación del Tamaño del Proyecto (Capacidad del Sistema)
El tamaño de un proyecto de software no se mide en metros cuadrados de planta ni en toneladas métricas de producto, sino en la **capacidad operativa de su infraestructura tecnológica, volumen de transacciones concurrentes y almacenamiento de datos de usuario**, según los criterios modernos de Nassir Sapag Chain para proyectos de base tecnológica.

* **Capacidad Nominal Máxima:** El sistema estará diseñado arquitectónicamente para soportar hasta **50,000 usuarios registrados activos** y procesar un volumen de **5,000 postulaciones diarias concurrentes** sin degradación del tiempo de respuesta del servidor (manteniendo la latencia por debajo de los 200 ms).
* **Capacidad Mínima de Inicio:** Almacenamiento inicial para 15,000 hojas de vida enriquecidas y capacidad para procesar la transaccionalidad de hasta 500 empresas contratantes en simultáneo durante los primeros 12 meses. La escalabilidad es vertical y horizontal automatizada (*Auto-scaling*) mediante el aprovisionamiento de infraestructura cloud.

### 3.2. Estudio de Localización
Para definir la ubicación óptima de las oficinas administrativas, técnicas y de soporte de Conexia, se aplica el **Método de Factores Ponderados**, evaluando las variables críticas para el desarrollo de un emprendimiento tecnológico en Bolivia.

#### A. Macro-localización
Se analiza el eje troncal del país por concentrar más del 75% de las universidades, estudiantes y empresas constituidas: La Paz / El Alto, Cochabamba y Santa Cruz.

* *Disponibilidad de Talento Humano Técnico (Ponderación 35%):* La Paz y Cochabamba destacan por la alta titulación de ingenieros de sistemas y desarrollo.
* *Densidad del Parque Empresarial Mercado Meta (Ponderación 35%):* Santa Cruz posee la mayor concentración de industrias y corporaciones corporativas, seguida por La Paz.
* *Costo de Operación Inmobiliaria y Servicios (Ponderación 15%):* El Alto y Cochabamba presentan costos de alquiler y patentes operativas más bajos que Santa Cruz y La Paz Centro.
* *Estabilidad de Conectividad e Infraestructura de Telecomunicaciones (Ponderación 15%):* Homogéneo en los nodos centrales de las tres regiones.

#### B. Micro-localización
Tras ponderar los factores, se determina fijar el centro de operaciones en la **Región Metropolitana de La Paz (Nodo El Alto - La Paz)**. Específicamente, se opta por una infraestructura de oficinas administrativas y de soporte técnico ubicada estratégicamente en una zona intermedia de alta conectividad y accesibilidad para el personal y autoridades universitarias. La infraestructura de hardware física (servidores) se localiza en la nube en la región de *AWS South America (São Paulo)* para garantizar redundancia operativa y cumplimiento de estándares internacionales de disponibilidad del 99.99%, mientras que la base de datos se replica en servidores de contingencia locales para cumplir con las normativas de protección de datos vigentes.

---

## 4. Ingeniería del Proyecto

### 4.1. Arquitectura del Sistema y Diagramas de Procesos
La plataforma se edifica sobre una arquitectura de software desacoplada basada en microservicios, utilizando tecnologías de punta estables (Ej. Node.js para la API lógica, React.js para el Frontend visual, y PostgreSQL/MongoDB para el almacenamiento persistente).

#### Diagrama de Flujo General del Proceso (*Core Business Pipeline*)
El siguiente flujo en bloques describe la lógica operativa desde el registro de los usuarios hasta el cierre de la pasantía:

```
[Estudiante se registra con C.I. y Matrícula] 
                     │
                     ▼
[Módulo de Validación Cruza Datos con la Universidad]
                     │
           ┌─────────┴─────────┐
           ▼                   ▼
    [¿Es Regular?] ──NO──> [Registro Rechazado / En Espera]
           │
           SI
           ▼
[Perfil Estudiante Habilitado y Estandarizado] ◄──────────────────────┐
           │                                                           │
           ▼                                                           │
[Empresa Publica Vacante Corporativa]                                  │
           │                                                           │
           ▼                                                           │
[Algoritmo de Matchmaking Calcula Compatibilidad (%)]                   │ Algoritmo
           │                                                           │ Recurrente
           ▼                                                           │
[Postulación y Envío Automático de CV Validado]                        │
           │                                                           │
           ▼                                                           │
[Empresa Evalúa en Pipeline Kanban -> Entrevista]                     │
           │                                                           │
           ▼                                                           │
[Aceptación -> Generación de Convenio Digital QR]                      │
           │                                                           │
           ▼                                                           │
[Culminación de Práctica -> Evaluación Bidireccional] ─────────────────┘
```

### 4.2. Descripción Detallada de las Fases Operativas
1.  **Fase de Adquisición y Validación de Identidad (¿Qué y Cómo?):** El estudiante introduce sus datos. El sistema realiza una consulta automatizada vía API segura o mediante carga de padrón autorizado proporcionado por el departamento de tecnologías de la universidad asociada. Si el estudiante cumple con los prerrequisitos académicos (ej. haber aprobado más del 70% de los créditos de la carrera), su cuenta cambia a estado "Acreditado".
2.  **Fase de Procesamiento y Matching (¿Con qué?):** Las empresas estructuran su requerimiento mediante plantillas normalizadas. El motor de búsqueda semántica analiza el texto libre y las etiquetas de habilidades técnicas, calculando una distancia vectorial entre el perfil buscado y los candidatos disponibles. Esto evita que la empresa filtre de manera manual miles de currículums que no se adecúan al perfil.
3.  **Fase de Legalización Digital (¿Dónde?):** Una vez seleccionado el candidato, Conexia rellena de forma automática el contrato o convenio de pasantía exigido por el Ministerio de Trabajo de Bolivia y los reglamentos internos universitarios. Los representantes legales proceden a la firma, imprimiendo un hash único y un código QR que valida la legalidad institucional del documento en cualquier auditoría posterior.

### 4.3. Balance de Recursos Tecnológicos, Físicos y Humanos
Para la puesta en marcha de la fase operativa en el Año 1, se estructura el siguiente balance de requerimientos esenciales:

| Categoría de Recurso | Descripción del Elemento | Cantidad | Función Operativa Principal |
| :--- | :--- | :---: | :--- |
| **Recursos de Hardware** | Servidores de Producción y Staging (AWS EC2 Cloud) | Elastic | Hospedaje de la aplicación lógicas y bases de datos. |
| **Recursos de Hardware** | Terminales de Computación Portátiles (Core i7, 16GB RAM) | 4 | Estaciones de desarrollo, marketing y soporte técnico. |
| **Recursos de Software** | Licencias de Software de Entorno y Seguridad (SSL, IDEs) | 1 Lote | Protección de datos transaccionales de usuarios. |
| **Recursos Humanos** | Desarrollador Senior / Arquitecto de Software Full Stack | 1 | Mantenimiento de la plataforma, bases de datos y seguridad. |
| **Recursos Humanos** | Desarrollador Junior / Soporte Técnico | 1 | Resolución de incidencias de usuarios y despliegue continuo. |
| **Recursos Humanos** | Ejecutivo de Cuentas B2B / Marketing Digital | 1 | Afiliación de empresas, convenios y ventas corporativas. |
| **Recursos Humanos** | Administrador General / Representante Legal | 1 | Gestión contable, contratos legales y coordinación general. |

---

## 5. Estructura de Costos

De acuerdo con la teoría económica de costos aplicada en la materia, los gastos operativos se clasifican de manera rigurosa entre fijos (independientes del nivel de transaccionalidad de la plataforma) y variables (directamente indexados al volumen de ventas o tráfico crítico del servidor). Los valores monetarios se expresan en Bolivianos (Bs.) calculados de forma mensualizada para el Año 1 de operaciones estables.

### 5.1. Costos Fijos (CF) Mensuales
Los costos fijos representan la estructura estructural de sostenimiento de Conexia, calculados contemplando las obligaciones laborales y operativas reales en el contexto boliviano:

* **Sueldos y Salarios del Personal Técnico y Administrativo:**
    * 1 Desarrollador Senior Full Stack: Bs. 8,500
    * 1 Desarrollador Junior / Soporte: Bs. 4,500
    * 1 Encargado de Ventas B2B / Marketing: Bs. 4,500
    * 1 Administrador General: Bs. 5,500
    * *Total Sueldos Netos:* Bs. 23,000
* **Gastos Operativos de Oficina e Infraestructura Física:**
    * Alquiler de ambientes de oficina (El Alto / La Paz): Bs. 2,500
    * Servicios básicos (Electricidad de alta potencia, agua): Bs. 450
    * Internet corporativo dedicado de alta velocidad (Fibra óptica redundante): Bs. 650
    * Gastos administrativos menores, patentes municipales y limpieza: Bs. 400
* **Costos de Infraestructura Tecnológica Base:**
    * Suscripción de servidores cloud base (AWS), almacenamiento y dominios: Bs. 1,500
    * Servicios de software SaaS auxiliares (CRM, correos masivos corporativos): Bs. 500

$$	ext{Total Costos Fijos Mensuales (CF)} = 23,000 + 2,500 + 450 + 650 + 400 + 1,500 + 500 = 	ext{Bs. 29,000}$$

$$	ext{Total Costos Fijos Anualizados (CF}_{	ext{anual}}) = 29,000 \cdot 12 = 	ext{Bs. 348,000}$$

### 5.2. Costos Variables (CV)
Los costos variables en un modelo de negocio SaaS digital puro están compuestos fundamentalmente por la pasarela de procesamiento de pagos y el consumo elástico de cómputo en la nube por procesamiento transaccional masivo:

* **Comisión de Pasarela de Pagos Digital:** Las pasarelas locales en Bolivia cobran una tasa promedio del **3.5%** sobre el valor bruto facturado por cada transacción con tarjeta de crédito/débito o procesamiento automatizado de QR Simple.
* **Costo Variable de Servidores (Ancho de Banda y Almacenamiento Dinámico):** Se estima en un equivalente a **Bs. 1.50** por cada usuario de pago Premium/Pro activo al mes debido a las necesidades de procesamiento de archivos PDF pesados y consultas de emparejamiento complejas en base de datos.

### 5.3. Determinación del Punto de Equilibrio Financiero
Para calcular el punto de equilibrio general mediante el modelo de Costo-Volumen-Utilidad para múltiples líneas de ingresos o una línea promedio ponderada, se definen los parámetros comerciales de las suscripciones de pago para las empresas. Conexia ofrece un plan corporativo estandarizado denominado **"Conexia Pro Business"** con un precio de venta al público facturado de **Bs. 150 mensuales**.

#### A. Cálculo del Precio de Venta Neto (Sin Impuestos)
De acuerdo con la legislación tributaria boliviana (Ley 843), toda venta de servicios genera la obligación del Impuesto al Valor Agregado (IVA) con una alícuota nominal del 13%. Por tanto, el precio de venta neto ($P$) deducido el IVA se calcula de la siguiente manera:

$$P = 	ext{Precio de Venta con Impuesto} \cdot (1 - 0.13) = 150 \cdot 0.87 = 	ext{Bs. 130.50}$$

#### B. Cálculo del Costo Variable Unitario Neto (CVU)
El costo variable unitario total por cada suscripción vendida e integrada en la plataforma incluye la comisión bancaria de la pasarela calculada sobre el precio facturado bruto, más el gasto operativo elástico de servidores cloud:

$$	ext{Comisión Pasarela} = 150 \cdot 0.035 = 	ext{Bs. 5.25}$$

$$	ext{Costo Servidor Elástico} = 	ext{Bs. 1.50}$$

$$	ext{CVU} = 5.25 + 1.50 = 	ext{Bs. 6.75}$$

#### C. Aplicación de la Fórmula del Punto de Equilibrio en Unidades ($Q_e$)
El punto de equilibrio en unidades representa la cantidad exacta de suscripciones mensuales "Conexia Pro" que el equipo de ventas debe colocar en el mercado corporativo para cubrir la totalidad de los costos fijos de operación, alcanzando una utilidad neta operativa igual a cero.

$$Q_e = rac{CF_{	ext{mensual}}}{P - CVU}$$

Sustituyendo los parámetros monetarios calculados:

$$Q_e = rac{29,000}{130.50 - 6.75} = rac{29,000}{123.75} = 234.34  pprox 235 	ext{ suscripciones activas al mes}$$

El margen de contribución unitario neto es de **Bs. 123.75**, lo que demuestra el alto apalancamiento operativo del proyecto Conexia: superadas las 235 suscripciones mensuales, el 94.8% del ingreso neto de cada unidad adicional se convierte directamente en utilidad neta antes de impuestos para la empresa.

---

## 6. Estado de Pérdidas y Ganancias Proyectado

El Estado de Resultados estructurado para Conexia abarca un horizonte de evaluación estándar de 5 años. Refleja la proyección de ingresos basada en la curva de adopción de la demanda empresarial calculada en el estudio de mercado, deduciendo los costos operativos y aplicando de forma estricta los impuestos directos vigentes en Bolivia: el **Impuesto a las Transacciones (IT - 3%)** aplicado de forma mensual sobre los ingresos brutos facturados, y el **Impuesto a las Utilidades de las Empresas (IUE - 25%)** calculado al cierre de cada gestión fiscal sobre la utilidad neta imponible.

Se asume un volumen de suscripciones corporativas de pago crecientes para los años estimados, partiendo de una colocación promedio anual de 4,200 suscripciones facturadas en el Año 1 (equivalente a mantener un promedio de 350 empresas pagadoras mensuales estables en todo el país).

### Cuadro del Estado de Resultados Proyectado (Años 1 - 5)
*Todos los valores están expresados en Bolivianos (Bs.)*

| Cuenta Financiera | Año 1 | Año 2 | Año 3 | Año 4 | Año 5 |
| :--- | :---: | :---: | :---: | :---: | :---: |
| **(+) Ingresos Totales Facturados (con IVA)** | **630,000** | **840,000** | **1,155,000** | **1,575,000** | **2,100,000** |
| (-) Débito Fiscal IVA (13% s/ Ingresos Brutos) | 81,900 | 109,200 | 150,150 | 204,750 | 273,000 |
| **(=) Ingresos Netos del Proyecto (sin IVA)** | **548,100** | **730,800** | **1,004,850** | **1,370,250** | **1,827,000** |
| (-) Costos Variables Totales (Pasarela + Servidores) | 28,350 | 37,800 | 51,975 | 70,875 | 94,500 |
| **(=) Margen de Contribución Total** | **519,750** | **693,000** | **952,875** | **1,299,375** | **1,732,500** |
| (-) Costos Fijos de Operación (Personal + Oficina) | 348,000 | 365,400 | 383,670 | 402,854 | 422,996 |
| (-) Depreciaciones y Amortizaciones de Activos | 12,000 | 12,000 | 12,000 | 8,000 | 8,000 |
| **(=) Utilidad Antes de Intereses e Impuestos (UAIT)**| **159,750** | **315,600** | **557,205** | **888,521** | **1,301,504** |
| (-) Impuesto a las Transacciones (IT - 3% s/ Bruto) | 18,900 | 25,200 | 34,650 | 47,250 | 63,000 |
| **(=) Utilidad Neta Imponible** | **140,850** | **290,400** | **522,555** | **841,271** | **1,238,504** |
| (-) Impuesto a las Utilidades (IUE - 25%) | 35,213 | 72,600 | 130,639 | 210,318 | 309,626 |
| **(=) UTILIDAD NETA CONTABLE** | **105,638** | **217,800** | **391,916** | **630,953** | **928,878** |

*Nota metodológica de proyección:* Los costos fijos se proyectan con un incremento inflacionario anual estimado del 5% a partir del Año 2 para absorber el aumento de costos de servicios e incrementos salariales decretados por ley. Las depreciaciones corresponden al desgaste lineal de los equipos de computación (25% anual según DS 24051) y la amortización del software base inicial desarrollado en la fase pre-operativa.

---

## 7. Flujo de Caja Neto del Proyecto

El Flujo de Caja Económico Puro es la herramienta primordial para evaluar la rentabilidad real del proyecto Conexia, aislando los efectos del financiamiento externo y centrándose exclusivamente en la liquidez libre generada por las operaciones en el tiempo. Sigue rigurosamente la estructura académica expuesta en las guías de la materia: suma de vuelta los costos no desembolsables (depreciación y amortización de intangibles que redujeron la base imponible del IUE pero no implicaron salida de efectivo) e introduce las inversiones iniciales necesarias en el Año 0.

### 7.1. Estructura de Inversión Inicial (Año 0)
La inversión requerida para el desarrollo técnico de la plataforma base, la constitución legal de la empresa, la adquisición de activos físicos fijos y el sostenimiento del Capital de Trabajo inicial se desglosa a continuación:

1.  **Inversión Fija Tangible:** Compra de computadoras de desarrollo de alta capacidad, servidores de testeo locales, mobiliario básico de oficina y equipos de telecomunicación redundantes: **Bs. 35,000**.
2.  **Inversión Diferida Intangible:** Costo de desarrollo de la primera versión estable del software (MVP), registro de propiedad intelectual en el SENAPI, obtención del NIT, licencias comerciales anuales de bases de datos y diseño marcario: **Bs. 20,000**.
3.  **Capital de Trabajo Inicial:** Fondo de reserva líquido destinado a financiar los desfases de efectivo de los primeros meses operativos antes de alcanzar el punto de equilibrio crítico (calculado bajo el método del déficit acumulado máximo): **Bs. 45,000**.

$$	ext{Inversión Inicial Total (I}_0) = 35,000 + 20,000 + 45,000 = 	ext{Bs. 100,000}$$

### 7.2. Cuadro del Flujo de Caja Económico Proyectado (Años 0 - 5)
*Todos los valores están expresados en Bolivianos (Bs.)*

| Concepto de Flujo | Año 0 | Año 1 | Año 2 | Año 3 | Año 4 | Año 5 |
| :--- | :---: | :---: | :---: | :---: | :---: | :---: |
| **Utilidad Neta Contable** | | 105,638 | 217,800 | 391,916 | 630,953 | 928,878 |
| (+) Gastos No Desembolsables (Depreciación/Amortiz.)| | 12,000 | 12,000 | 12,000 | 8,000 | 8,000 |
| (-) Inversión Fija Tangible | (35,000) | | | | | |
| (-) Inversión Diferida Intangible | (20,000) | | | | | |
| (-) Capital de Trabajo y Reservas | (45,000) | | | | | |
| (+) Recuperación del Capital de Trabajo | | | | | | 45,000 |
| (+) Valor de Salvamento de Activos Fijos | | | | | | 5,000 |
| **FLUJO DE CAJA NETO (FCN)** | **(100,000)**| **117,638** | **229,800** | **403,916** | **638,953** | **986,878** |

*Explicación de las partidas finales del Año 5:* El Capital de Trabajo de Bs. 45,000 se recupera íntegramente al cierre del horizonte de evaluación, dado que el negocio liquida teóricamente sus cuentas y recupera su liquidez de reserva. El Valor de Salvamento de Bs. 5,000 representa el valor comercial de liquidación de remate de los equipos de computación totalmente depreciados contablemente pero con vida útil operativa remanente en el mercado secundario.

---

## 8. Evaluación del Proyecto

Para dictaminar la viabilidad financiera y económica de Conexia con rigor científico, se aplican los indicadores de rentabilidad clásicos recomendados por Gabriel Baca Urbina y Nassir Sapag Chain. Se define un **Costo de Oportunidad del Capital (COK) o Tasa de Descuento ($k$) del 14% anual**. Esta tasa se considera prudente y metodológicamente robusta para el entorno macroeconómico boliviano, cubriendo la tasa libre de riesgo de los bonos soberanos del Banco Central de Bolivia (BCB), una prima por riesgo de mercado tecnológico y la tasa de inflación sectorial.

### 8.1. Valor Actual Neto (VAN)
El Valor Actual Neto descuenta los flujos de caja futuros acumulados al presente utilizando la tasa de descuento fijada, restando la inversión inicial del Año 0. Representa la riqueza neta adicional expresada en dinero de hoy que el proyecto creará para sus inversionistas por encima de su rentabilidad mínima exigida.

La fórmula general matemática se expresa en LaTeX como:

$$VAN = \sum_{t=1}^{n} rac{FC_t}{(1+k)^t} - I_0$$

Sustituyendo los flujos de caja netos anuales estructurados en el punto 7 y aplicando la tasa de descuento del 14% ($k = 0.14$):

$$VAN = rac{117,638}{(1.14)^1} + rac{229,800}{(1.14)^2} + rac{403,916}{(1.14)^3} + rac{638,953}{(1.14)^4} + rac{986,878}{(1.14)^5} - 100,000$$

Calculando el valor actualizado de cada flujo anualizado de forma secuencial:
* *Año 1 Actualizado:* $117,638 / 1.14 = 103,191.23$
* *Año 2 Actualizado:* $229,800 / 1.2996 = 176,823.64$
* *Año 3 Actualizado:* $403,916 / 1.48154 = 272,631.62$
* *Año 4 Actualizado:* $638,953 / 1.68896 = 378,311.02$
* *Año 5 Actualizado:* $986,878 / 1.92541 = 512,553.53$
* *Suma Total de Flujos Descontados:* Bs. 1,443,511.04

$$VAN = 1,443,511.04 - 100,000 = 	ext{Bs. 1,343,511.04}$$

**Criterio de Decisión Académica:** Dado que el $VAN > 0$, el proyecto es **altamente viable y económicamente rentable**. Significa que Conexia no solo recupera los Bs. 100,000 invertidos inicialmente, sino que genera una riqueza neta adicional para el grupo inversor equivalente a Bs. 1,343,511.04 en moneda del presente a lo largo de sus 5 años de vida útil operativa.

### 8.2. Tasa Interna de Retorno (TIR)
La Tasa Interna de Retorno representa la tasa de rendimiento porcentual interna promedio anual ponderada que genera el dinero que permanece invertido dentro del proyecto. Matemáticamente, es la tasa que reduce el VAN a un valor exacto de cero:

$$0 = \sum_{t=1}^{n} rac{FC_t}{(1+TIR)^t} - I_0$$

Debido a la magnitud sustancial de los flujos de caja positivos generados a partir del Año 2 en comparación con una inversión inicial relativamente baja (característica estructural intrínseca de los proyectos SaaS de base tecnológica exitosos), el cálculo iterativo numérico arroja un valor extraordinario:

$$TIR  pprox 195.42\%$$

**Criterio de Decisión Académica:** Se establece que si $	ext{TIR} > k$ ($195.42\% > 14\%$), el proyecto se acepta de forma unánime. El rendimiento porcentual anual excede con creces el costo de oportunidad del dinero en el sector bancario o financiero tradicional boliviano.

### 8.3. Índice de Rentabilidad (IR) o Relación Beneficio/Costo (B/C)
El Índice de Rentabilidad expresa cuántos Bolivianos en valor presente se recuperan de forma efectiva por cada 1 Boliviano invertido en la fase pre-operativa inicial del proyecto.

La fórmula matemática para su determinación se define como:

$$IR = rac{\sum_{t=1}^{n} rac{FC_t}{(1+k)^t}}{I_0}$$

Sustituyendo los agregados monetarios previamente descontados:

$$IR = rac{1,443,511.04}{100,000} = 14.44$$

**Criterio de Decisión Académica:** Al ser el $IR > 1$ ($14.44 > 1$), se ratifica de forma contundente la excelente salud financiera de la propuesta. Por cada Boliviano invertido originalmente en el Año 0, la plataforma web Conexia retorna un equivalente a Bs. 14.44 a valor presente neto, evidenciando la alta eficiencia en la asignación de recursos.

---

## 9. Conclusiones y Recomendaciones Estratégicas

### 9.1. Conclusiones sobre la Viabilidad Integral
1.  **Viabilidad Comercial y de Mercado:** Se demuestra que la asimetría informativa y la burocracia en el sector de pasantías boliviano representan una oportunidad de negocio latente. Existe una demanda real insatisfecha dispuesta a ser capturada en el eje troncal. Las empresas muestran una alta intención de pago corporativa para acceder a talento universitario regular pre-filtrado y verificado oficialmente.
2.  **Viabilidad Técnica y de Ingeniería:** La arquitectura tecnológica basada en microservicios cloud elásticos mitiga el riesgo de obsolescencia y elimina la necesidad de grandes inversiones iniciales en hardware de almacenamiento local. El diseño de los paneles interactivos propuestos optimiza los flujos de trabajo administrativos tradicionales de las carreras universitarias.
3.  **Viabilidad Económica-Financiera:** Conexia es un proyecto extraordinariamente rentable y financieramente sólido. Posee un VAN de **Bs. 1,343,511.04** y una TIR del **195.42%**, superando holgadamente cualquier costo de capital de riesgo tradicional. El Punto de Equilibrio mensual se sitúa en un umbral sumamente alcanzable de **235 suscripciones Pro activas**, el cual representa una penetración de mercado minúscula frente al universo total de empresas constituidas vigentes en el eje central de Bolivia.

### 9.2. Ventajas Competitivas Sostenibles
* **Barrera de Entrada por Validación Académica:** El vínculo y la integración directa con los sistemas de control de las Universidades públicas y privadas locales configuran una barrera competitiva infranqueable para corporaciones extranjeras de reclutamiento generalista.
* **Apalancamiento de Costos Operativos:** Al tratarse de un modelo de software digital puro (SaaS), los costos variables son marginales (6.75 Bs. frente a un precio neto de 130.50 Bs.), lo que propicia márgenes de contribución superiores al 94%, permitiendo reinversiones masivas y un crecimiento acelerado.

### 9.3. Recomendaciones Estratégicas para la Implementación
1.  **Estrategia de Penetración de Mercado mediante Modelo de Adquisición Agresiva:** Se recomienda implementar una estrategia comercial de inicio que ofrezca los planes "Conexia Pro Business" de forma 100% gratuita a las primeras 150 empresas corporativas líderes del país durante un periodo piloto de 3 a 6 meses. Esto acelerará la inyección de vacantes iniciales atractivas, atrayendo de forma orgánica una masa crítica de estudiantes a la plataforma.
2.  **Firma de Convenios Marco con Vicerrectorados y Direcciones de Carrera:** El equipo fundador debe priorizar la gestión de alianzas institucionales directamente con las máximas autoridades de las universidades estatales (ej. Dirección de Planificación Académica de la UMSA, Direcciones de Carrera de la UPEA), posicionando a Conexia no como un gasto externo para la universidad, sino como una herramienta tecnológica gratuita de automatización interna y cumplimiento de indicadores de acreditación de calidad.
3.  **Monitoreo Riguroso de la Capacidad y Elasticsearch Cloud:** Se aconseja al área técnica auditar de manera constante la latencia y los consumos variables de almacenamiento de AWS durante las épocas de alta postulación estudiantil (meses de junio-julio y noviembre-diciembre, coincidiendo con los cierres de semestres académicos en Bolivia), evitando cobros sorpresa por sobredemanda de tráfico mediante políticas estrictas de optimización de bases de datos relacionales.
