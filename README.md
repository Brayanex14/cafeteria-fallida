
# Análisis Estructural del Sistema "Carrera de Informática"
## Determinación del Grado de Motricidad y Dependencia de Grado 3

---

## 1. Planteamiento del problema

Se desea determinar el **grado de motricidad y dependencia de tercer orden**
del sistema correspondiente a la *Carrera de Informática*, en relación con su
actividad principal. Para ello se aplica el método **MICMAC** (Matrice
d'Impacts Croisés Multiplication Appliquée à un Classement), extendido al
cálculo de influencias indirectas de longitud 3.

---

## 2. Definición formal

Sea `A` la matriz binaria de influencias directas de orden `n × n`, donde:

    a(i,j) = 1  si la variable i influye directamente sobre la variable j
    a(i,j) = 0  en caso contrario

La matriz de influencias indirectas de **grado 3** se obtiene mediante:

    A³ = A · A · A

A partir de ella se definen, para cada variable `i`:

    Motricidad(i)  = Σ_j (A³)(i,j)      (suma de la fila i)
    Dependencia(i) = Σ_j (A³)(j,i)      (suma de la columna i)

El grado agregado del sistema se calcula como:

    M_sistema = D_sistema = Σ_i Σ_j (A³)(i,j)

---

## 3. Variables del sistema

| # | Variable |
|---:|---|
| 1 | Mercado laboral |
| 2 | Presupuesto |
| 3 | Infraestructura |
| 4 | Calidad docente |
| 5 | Estudiantes inscritos |
| 6 | Rendimiento |
| 7 | Egresados |
| 8 | Empleabilidad |
| 9 | Prestigio |
| 10 | Demanda de ingreso |
| 11 | Brecha con el ideal |
| 12 | Acciones correctivas |

---

## 4. Matriz de influencias indirectas de grado 3 (A³)

| i \ j | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 | 11 | 12 | Σ fila |
|---|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|
| 1  | 0 | 1 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | **2** |
| 2  | 0 | 0 | 0 | 0 | 0 | 0 | 2 | 0 | 0 | 0 | 0 | 0 | **2** |
| 3  | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | **2** |
| 4  | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | **2** |
| 5  | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | **2** |
| 6  | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | **2** |
| 7  | 0 | 1 | 0 | 1 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | **3** |
| 8  | 0 | 0 | 1 | 1 | 1 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | **3** |
| 9  | 0 | 0 | 0 | 0 | 0 | 3 | 0 | 0 | 0 | 0 | 0 | 0 | **3** |
| 10 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 0 | 0 | **1** |
| 11 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 0 | 0 | 0 | **1** |
| 12 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 0 | 0 | **1** |
| **Σ col** | **0** | **2** | **1** | **2** | **1** | **4** | **4** | **3** | **1** | **2** | **3** | **1** | **24** |

El total de influencias indirectas de tercer orden es **24**, lo que arroja un
promedio de **2 influencias por variable**.

---

## 5. Resultados por variable

| # | Variable | Motricidad M⁽³⁾ | Dependencia D⁽³⁾ | Clasificación MICMAC |
|---:|---|---:|---:|---|
| 1 | Mercado laboral | 2 | 0 | Autónoma |
| 2 | Presupuesto | 2 | 2 | Enlace |
| 3 | Infraestructura | 2 | 1 | Motriz débil |
| 4 | Calidad docente | 2 | 2 | Enlace |
| 5 | Estudiantes inscritos | 2 | 1 | Motriz débil |
| 6 | Rendimiento | 2 | 4 | **Dependiente / Resultado** |
| 7 | Egresados | 3 | 4 | **Crítica / Enlace** |
| 8 | Empleabilidad | 3 | 3 | **Crítica / Enlace** |
| 9 | Prestigio | 3 | 1 | **Motriz / Determinante** |
| 10 | Demanda de ingreso | 1 | 2 | Autónoma |
| 11 | Brecha con el ideal | 1 | 3 | **Dependiente / Resultado** |
| 12 | Acciones correctivas | 1 | 1 | Autónoma |

Valores de referencia: `M̄ = D̄ = 24 / 12 = 2`.

---

## 6. Interpretación de resultados

### 6.1 Variables motrices o determinantes
- **Prestigio (9)** — `M⁽³⁾ = 3`, `D⁽³⁾ = 1`.
  Constituye la principal palanca del sistema; su influencia indirecta activa
  los lazos de demanda, presupuesto e infraestructura.

### 6.2 Variables críticas o de enlace
- **Egresados (7)** — `M⁽³⁾ = 3`, `D⁽³⁾ = 4`.
- **Empleabilidad (8)** — `M⁽³⁾ = 3`, `D⁽³⁾ = 3`.

  Ambas articulan el lazo de refuerzo `R` del modelo:

      Egresados → Empleabilidad → Prestigio → Demanda → Inscritos → Egresados

  Son variables de alto impacto y alta sensibilidad, por lo que cualquier
  intervención sobre ellas repercute en la totalidad del sistema.

### 6.3 Variables dependientes o resultado
- **Rendimiento (6)** — `M⁽³⁾ = 2`, `D⁽³⁾ = 4`.
- **Brecha con el ideal (11)** — `M⁽³⁾ = 1`, `D⁽³⁾ = 3`.

  Funcionan como indicadores de salida; no son palancas de intervención sino
  variables de monitoreo.

### 6.4 Variables autónomas
- **Mercado laboral (1)**, **Demanda de ingreso (10)** y
  **Acciones correctivas (12)**: su participación en cadenas de tercer orden
  es marginal, por lo que se consideran relativamente independientes dentro
  del modelo analizado.

---

## 7. Grado del sistema (agregado de tercer orden)

    Motricidad total del sistema   = 24
    Dependencia total del sistema  = 24
    Promedio por variable          = 24 / 12 = 2
    Densidad de tercer orden       = 24 / (12 × 11) ≈ 18.2 %

### Conclusión

El sistema *Carrera de Informática* presenta, en grado 3, una red de
influencias **moderadamente densa** (≈ 18 %), con:

- Un **núcleo crítico** identificado por las variables *Egresados*,
  *Empleabilidad* y *Prestigio*, sobre las cuales debe centrarse la
  estrategia de intervención.
- Un grupo de **variables resultado** (*Rendimiento* y *Brecha con el ideal*)
  útiles como indicadores de desempeño del sistema.
- Un conjunto de **variables autónomas** cuyo efecto indirecto es marginal
  en el horizonte de tercer orden analizado.

---

## 8. Observaciones metodológicas

1. El análisis se realizó sobre la **matriz binaria** de influencias directas
   proporcionada por el usuario.
2. El grado 3 captura únicamente caminos de longitud exactamente igual a 3;
   no incluye influencias de grados 1 ni 2.
3. Para un diagnóstico más robusto se recomienda complementar con los grados
   1, 2 y 4, y con el **plano motricidad–dependencia** (cuadrantes MICMAC).
