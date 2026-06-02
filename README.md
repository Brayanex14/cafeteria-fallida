# Estructura de Presentación de Proyecto: Conexia
**Plataforma Web de Pasantías y Conexión Laboral en Bolivia**

---

## 1. Definición del producto

**Nombre del Producto/Servicio:** Conexia
**Descripción general:** Conexia es una plataforma web integral diseñada para centralizar, facilitar y transparentar la conexión entre estudiantes universitarios/recién egresados que buscan pasantías y empresas bolivianas que requieren talento joven. Adicionalmente, integra a las Universidades como entidades validadoras.

**Funciones y características principales:**
* **Creación de Perfiles Digitales:** Estudiantes pueden crear una hoja de vida digital estandarizada.
* **Motor de Emparejamiento (*Matchmaking*):** Algoritmo que conecta los requerimientos de la vacante con las habilidades y carrera del postulante.
* **Módulo de Validación Universitaria:** Nivel de usuario "Super Admin" para universidades que permite auditar y certificar que el estudiante está habilitado para la pasantía, evitando falsificación de documentos.
* **Modelo *Freemium*:** Cuentas gratuitas para estudiantes y funciones avanzadas de pago (Premium/Pro) para empresas que desean destacar anuncios o hacer búsquedas avanzadas de perfiles.

**Beneficios y Valor Agregado:**
El principal factor innovador es la **trazabilidad y certificación**. A diferencia de los portales de empleo tradicionales, Conexia involucra a la institución educativa para validar los perfiles, garantizando a las empresas talento verificado y reduciendo el tiempo de reclutamiento.

---

## 2. Investigación de mercado

**Necesidad y Oportunidad de Negocio:**
En Bolivia existe una gran desconexión entre la academia y el sector empresarial. Los estudiantes tienen dificultades para encontrar pasantías que validen sus materias prácticas, y las empresas gastan muchos recursos filtrando candidatos sin experiencia comprobable.

**Mercado Consumidor y Demanda Potencial:**
* **Usuarios Finales (Estudiantes):** Estudiantes de últimos semestres de universidades públicas y privadas (ej. UPEA, UMSA, UCB, etc.).
* **Clientes (Empresas):** PYMES y corporaciones en el eje troncal de Bolivia (La Paz, El Alto, Cochabamba, Santa Cruz).

**Proyección de la Demanda:**
Para proyectar la demanda potencial de usuarios, se puede utilizar un modelo de regresión lineal simple basado en datos históricos de matriculación universitaria (fuente: CEUB / INE):
$$D_t = a + b \cdot t$$
Donde $D_t$ es la demanda proyectada en el año $t$, $a$ es la demanda base y $b$ es la tasa de crecimiento anual.

**Análisis de Competitividad (Diamante de Porter adaptado):**
1.  **Condiciones de los factores:** Alta disponibilidad de estudiantes buscando prácticas; infraestructura tecnológica (internet, servidores cloud) accesible.
2.  **Condiciones de la demanda:** Demanda creciente de empresas por automatizar su reclutamiento de talentos junior.
3.  **Sectores afines y auxiliares:** Pasarelas de pago locales (Libélula, Multipago), universidades y centros de formación tecnológica.
4.  **Estrategia, estructura y rivalidad:** Existen portales generales (Trabajopolis), pero ninguno especializado en pasantías con validación académica.

---

## 3. Tamaño y localización

**Tamaño (Capacidad productiva):**
Al ser un proyecto de base tecnológica (SaaS), la capacidad productiva está determinada por la infraestructura de servidores y la base de datos (Ej. AWS, Azure o Google Cloud).
* **Capacidad inicial estimada:** Soporte para hasta 10,000 usuarios concurrentes y almacenamiento para 50,000 perfiles/CVs digitales en el primer año.

**Localización:**
* **Macro-localización:** Bolivia.
* **Micro-localización:** Las operaciones administrativas y de soporte técnico tendrán su sede en la ciudad de El Alto / La Paz. La operación del servicio es virtual (nube).

---

## 4. Ingeniería del Proyecto

**a) Diagramas:**
*(Nota para el equipo: Aquí se debe insertar el Flujograma de Procesos. Ejemplo conceptual del flujo)*
`Registro -> Validación Universidad -> Creación Vacante Empresa -> Matchmaking -> Entrevista -> Aceptación/Rechazo`

**b) Descripción detallada del proceso:**
1.  El estudiante se registra con su matrícula universitaria.
2.  La Universidad valida el estado académico del estudiante mediante integración o panel de control.
3.  Las empresas publican vacantes (*Free* o *Premium*).
4.  El algoritmo cruza palabras clave (ej. "Java", "Contabilidad") entre la vacante y el perfil del estudiante.
5.  La empresa gestiona las entrevistas dentro de la plataforma.

**c) Balances y Recursos:**
* **Recursos Tecnológicos:** Dominio, Hosting/Cloud, Certificados SSL, Pasarela de Pagos API.
* **Recursos Humanos:** 2 Desarrolladores Full Stack, 1 Ejecutivo de Ventas/Marketing B2B, 1 Administrador/Soporte.

---

## 5. Estructura de costos

La estructura se divide en la etapa pre-operativa (desarrollo) y operativa.

**Costos Fijos (CF):**
No dependen del volumen de vacantes publicadas.
* Alquiler de servidores cloud mensuales.
* Sueldos base del equipo administrativo y soporte.
* Servicios básicos e internet de la oficina central.

**Costos Variables (CV):**
Dependen del nivel de transacciones.
* Comisiones de la pasarela de pagos (porcentaje por cada membresía Premium vendida).
* Costos de almacenamiento adicional por exceso de tráfico.

**Punto de Equilibrio:**
Se calcula para determinar cuántas suscripciones Premium/Pro ($Q$) se deben vender para no ganar ni perder.
Fórmula en unidades:
$$Q_e = \frac{CF}{P - CVU}$$
Donde:
* $CF$ = Costos Fijos Totales
* $P$ = Precio de Venta de la suscripción (sin impuestos)
* $CVU$ = Costo Variable Unitario
* $(P - CVU)$ = Margen de Contribución Unitario

---

## 6. Estado de pérdidas y ganancias

El estado de resultados proyectado a 5 años seguirá la siguiente estructura básica (incorporando la normativa boliviana):

1. **Ingresos Totales por Ventas** (Suscripciones Empresas + Publicidad)
2. (-) **Costo de Ventas / Operación** (Servidores, comisiones pasarela)
3. (=) **Utilidad Bruta**
4. (-) **Gastos Operativos** (Sueldos, alquiler oficina, marketing, depreciación equipos de computación, amortización de software)
5. (=) **Utilidad Antes de Impuestos (UAIT)**
6. (-) **IUE (Impuesto a las Utilidades de las Empresas - 25%)**
7. (=) **Utilidad Neta (Contable)**

---

## 7. Flujo de caja

Se construirá el **Flujo de Caja del Proyecto** y el **Flujo de Caja del Inversionista**.
El esquema a utilizar es:

* **(+) Ingresos Afectos a Impuestos** (Ventas con factura deducido el IVA/IT según corresponda)
* **(-) Egresos Afectos a Impuestos** (Costos variables y fijos operativos)
* **(-) Gastos no desembolsables** (Depreciación de computadoras, Amortización de Activos Intangibles/Software)
* **(=) Utilidad Antes de Impuestos**
* **(-) Impuesto (IUE 25%)**
* **(=) Utilidad después de Impuestos**
* **(+) Ajuste por Gastos no desembolsables** (Se suma nuevamente la depreciación y amortización)
* **(-) Egresos no afectos a impuestos** (Inversión inicial en desarrollo, compra de equipos, capital de trabajo)
* **(+) Beneficios no afectos a impuestos** (Valor de desecho del proyecto, recuperación de capital de trabajo en el último año)
* **(=) FLUJO DE CAJA NETO**

---

## 8. Evaluación del Proyecto (VAN, TIR e IR)

Para determinar si "Conexia" genera valor económico, se utilizará una Tasa de Descuento ($k$) o Costo de Oportunidad del Capital.

**Valor Actual Neto (VAN):**
Mide la riqueza adicional que genera el proyecto. Si $VAN > 0$, el proyecto se acepta.
$$VAN = \sum_{t=1}^{n} \frac{FC_t}{(1+k)^t} - I_0$$
Donde $FC_t$ es el flujo de caja del año $t$, e $I_0$ es la inversión inicial.

**Tasa Interna de Retorno (TIR):**
Es la tasa que hace que el VAN sea cero. Si $TIR > k$, el proyecto es rentable.
$$0 = \sum_{t=1}^{n} \frac{FC_t}{(1+TIR)^t} - I_0$$

**Índice de Rentabilidad (IR) o Relación Beneficio/Costo:**
$$IR = \frac{\sum_{t=1}^{n} \frac{FC_t}{(1+k)^t}}{I_0}$$
Si $IR > 1$, los ingresos actualizados superan a la inversión.

---

## 9. Conclusiones

*(Nota para el equipo: Esta sección se redactará al finalizar los cálculos numéricos de los puntos 5, 6, 7 y 8. A modo de estructura, responderá lo siguiente:)*

1.  **Viabilidad Comercial y Técnica:** Se confirmará que existe demanda insatisfecha y viabilidad tecnológica mediante servidores en la nube.
2.  **Rentabilidad:** "El proyecto Conexia es financieramente rentable dado que su VAN asciende a $X Bs. y posee una TIR del X%, superando la tasa de descuento esperada..."
3.  **Ventajas Competitivas:** La alianza con las Universidades establece una alta barrera de entrada para la competencia.
4.  **Recomendaciones:** Estrategias de penetración rápida de mercado ofreciendo el servicio gratuito a empresas durante los primeros 3 meses (estrategia de adquisición).
