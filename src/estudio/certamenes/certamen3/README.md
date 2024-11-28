# Introducción a la Macroeconomía

## ¿Qué es la macroeconomía?

Rama de la aeconomia que estudia en su conjunto, es decir, a nivel país, enfocado en su funcionamiento y comportamiento. Se centra en variables como el PIB, la inflación, el desempleo, entre otros.

## Conceptos claves de detabe en la macroecnomía
1. Crecimiento y producción de la economiía:
2. Tasass de interés:
3. Exportaciones netas del país :
4. Inglación:
5. Desempleo/Empleo:

## Variables Flujo vs Stock

* Flujo: Se mide en en **periodos de tiempo** deterniados (día, mes, año).
    - Ejemplo: Ingresos, inversiones, PIB, inflacion, etc.
* Stock: Se mide en un momento específico, atemporal.
    - Ejemplo: Población, riqueza, stock de capital, oferta monetaria, etc.

*Un cambio en una variable de stock es una variable de*


# Conceptos

## Tasas de crecimiento

La tasa de crecimiento porcentual, **mide cuanto ha cambiado una variable entre dos periodos consecutivos de tiempo**

```math
\Delta \% X_t = \frac{(X_t - X_{t-1})}{X_{t-1}} \cdot 100
```

- Positivo: Tasa de Crecimiento Positiva
- Negativo: Tasa de Crecimiento Negativa

Ejemplo práctico:

Supongamos que estás analizando el ingreso mensual de una persona:
- En el mes actual: 
```math
t:\   X_t = 1100
```
- En el mes anterior: 
```math
t-1:\ X_{t-1} = 1000
```

Aplicamos la fórmula:
```math
\Delta \% X_t = \frac{(1100 - 1000)}{1000} \cdot 100 = 10\%
```

Esto significa que el ingreso creció un **10%** con respecto al mes anterior.

## Inflación

Incremento generalizado sostenido de precios de los bienesy servicios de la economia de un país durante un periodo determinado. Este factor se mide con el **Índice de Precios al Consumidor (IPC)**, utilizado para observar las variaciones en el precio de las canastas basicasa de bienes y servicios que consumen los hogares, la cual cambia cada 5 años. Si el IPC aumenta de forma sostenida, estamos ante una situacion de inflación.

### Efectos de la inflacion

- Disminuye el valor del dinero: Con el mismo salario, se pueden comprar menos bienes y servicios.
- Gastos Indexados: Costos que se ajustan a la inflacion como la UF, dividendos, arriendos, etc.
- Mayor inpacto en personas más vulnerables


## Analisis de Series Temporales

- Nominal: Valores sin ajustar por inflación.
- Real: Valores ajustados por inflación

- Nuestro poder adquisitivo solo aumenta si el porcentaje de inflación es menor al porcentaje de aumento de nuestro salario.

Se calcula como:
```math
Valor Real = Valor Nominal - Inflacion
```
Ejemplo práctico:

Supongamos que el IPC es de 5% y el salario de una persona es de $1000. Calculamos el salario real:
```math
Salario Real = 1000 - (1000 \cdot 0.05) = 1000 - 50 = 950
```

## PIB (Producto Interno Bruto)

Midel el nivel de producción de bienes y servicios de un país en un periodo de tiempo determinado (es una variable de flujo), se esta se utiliza para comprender el crecimiento económico de un país.

### PIB Nominal

Mide los bienes y servicios producidos en una economía durante un *período (Δt) especifico en el mercado (aislado)*. Incluye los efectos de la inflación o deflación.

```math
PIB\ Nominal = \sum (Cantidad \times Precio\ actual)
```

### PIB Real

Mide los bienes y servicios producidos en una economía durante un *período (Δt) especifico en el mercado*. **No incluye** los efectos de la inflación o deflación, para lo cual se necesita utilizar un *año base* de referencia, utilizando asi los precios de los productos en ese año, para todo calculo.

```math
PIB\ Real = \sum (Cantidad \times Precio\ del\ año\ base)
```

### Deflactor del PIB

Mide cuanto an aumentado los precios

```math
Deflactor\ del\ PIB = \frac{PIB\ Nominal}{PIB\ Real} \times 100
```

Interpretación del Deflactor del PIB:
- **Deflactor = 100**: No hay cambio en los precios entre el periodo actual y el año base.
- **Deflactor > 100**: Los precios han aumentado (inflación) desde el año base.
- **Deflactor < 100**: Los precios han disminuido (deflación) desde el año base.

### Diferencias clave entre PIB Nominal, Real y Deflactor del PIB:

| Aspecto                      | PIB Nominal                                          | PIB Real                                         | Deflactor del PIB                                               |
| ---------------------------- | ---------------------------------------------------- | ------------------------------------------------ | --------------------------------------------------------------- |
| **Precios**                  | Usa precios actuales                                 | Usa precios constantes (año base)                | Relaciona los precios actuales con los precios del año base.    |
| **Impacto de la inflación**  | Incluye inflación o deflación                        | Elimina el efecto de la inflación                | Mide el nivel de inflación en toda la economía.                 |
| **Comparaciones temporales** | No es adecuado para comparar periodos                | Permite comparaciones directas                   | Ayuda a analizar cómo cambian los precios entre periodos.       |
| **Interpretación**           | Refleja tanto cambios en precios como en producción. | Muestra únicamente los cambios en la producción. | Sirve para entender los cambios en el nivel general de precios. |


### PIB Per Cápita

Mide lo rica que es la poblacion (expresado en dolares) de un país dado el PIB de dicho país. 

```math
PIB\ Per\ Capita = \frac{PIB}{Poblacion}
```

Sin embargo cada país tiene un distinto poder de compra, por lo que para hacer comparaciones internacionales se utiliza el **PPP (Paridad de Poder Adquisitivo)**.

### PIB Per Cápita A PPP

```math
Tipo\ de\ cambio\ PPP = \frac{Unidades\ de\ moneda\ local\ para\ comprar\ la\ canasta\ de\ bienes\ y\ servicios}{Unidades\ de\ moneda\ extranjera\ para\ comprar\ dicha\ canasta}
```

Luego:

```math
PIB\ per\ cápita\ a\ PPP = \frac{PIB\ per\ cápita\ en\ moneda\ local}{Tipo\ de\ cambio\ PPP}
```	

## Formas de calcular el PIB

### Medición por tipo de gasto (enfoque del gasto):

Este es el método más común y calcula el PIB como la suma del gasto en bienes y servicios finales en una economía. La fórmula es:

```math
PIB = C + I + G + (X - M)
```

Componentes:

- **\(C\): Consumo**:
  Gasto de los hogares en bienes y servicios (alimentos, ropa, servicios de salud, etc.).
  
- **\(I\): Inversión**:
  Gasto en bienes de capital como maquinaria, edificios, y construcción residencial. Incluye inventarios acumulados.

- **\(G\): Gasto del gobierno**:
  Incluye el gasto público en bienes y servicios (educación, salud, defensa, etc.), pero no transferencias como pensiones o subsidios.

- **\(X\): Exportaciones**:
  Valor de los bienes y servicios producidos dentro del país y vendidos al extranjero.

- **\(M\): Importaciones**:
  Valor de los bienes y servicios producidos en el extranjero y comprados por los residentes del país (resta porque no se producen dentro del país).

Otras formulas relacionadas:

- Demanda Agregada = Consumo + Inversión + Gasto Público + Exportaciones - Importaciones
- Demanda Interna = Consumo + Inversión + Gasto Público

### Medición por valor agregado sectorial (producción)

El valor agregado se define el valor burto de produccion (venta) menos el valor de las compras internas para producir dicho bien (Gasto en Bien Intermedio)

```math
PIB = \sum (Valor\ agregado\ en\ cada\ sector)
```

Ejemplo:  
Si una empresa produce pan:
1. El trigo vale $10.
2. La harina vale $20.
3. El pan final vale $50.

El **valor agregado** sería $50 (valor del pan) - $10 (trigo) - $20 (harina) = $20.

### Medición por ingresos

Este método suma todos los ingresos generados por los factores de producción (trabajo y capital) en una economía. Incluye:  
- **Salarios y sueldos**: Pagos a los trabajadores.
- **Renta**: Alquileres recibidos por el uso de recursos.
- **Beneficios**: Ganancias de las empresas.
- **Impuestos netos sobre la producción**: Impuestos menos subsidios.

```math
PIB = Salarios + Rentas + Beneficios + Impuestos - Subsidios
```


Ejemplo práctico del cálculo del PIB (enfoque gasto):  
Supongamos los siguientes datos anuales:
- Consumo (\(C\)) = 500
- Inversión (\(I\)) = 200
- Gasto del gobierno (\(G\)) = 300
- Exportaciones (\(X\)) = 150
- Importaciones (\(M\)) = 100

```math
PIB = 500 + 200 + 300 + (150 - 100)
\\
PIB = 1050
```

# Producto Nacional Bruto (PNB)

Mide el ingreso total generado por los residentes de un país, sin importar si dicho ingreso proviene de la producción interna o del extranjero. Además, excluye los ingresos generados por extranjeros dentro del país.

```math
PNB = PIB + PNF 
```

## PNF (Producto Neto de los Factores)

Mide el ingreso de los factores de producción de un país en el extranjero, menos el ingreso de los factores de producción extranjeros en el país.

```math
PNF = Ingresos\ de\ factores\ nacionales\ en\ el\ extranjero - Ingresos\ de\ factores\ extranjeros\ en\ el\ país
```

## Ingreso Nacional Bruto Disponible (YNBD)

Mide el ingreso disponible de los residentes de un país, es decir, el ingreso que pueden gastar o ahorrar.

```math
YNBD = PNB + TN 
```

## TN (Transferencias Netas)

Mide el flujo de transferencias entre un país y el extranjero.

```math
TN = Transferencias\ recibidas\ del\ extranjero - Transferencias\ enviadas\ al\ extranjero
```

# Diferencias entre PIB y PNB

| Aspecto        | **PIB (Producto Interno Bruto)**                                                                | **PNB (Producto Nacional Bruto)**                                                                                           |
| -------------- | ----------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------- |
| **Definición** | Mide el valor total de los bienes y servicios producidos dentro de un país.                     | Mide el valor total de los bienes y servicios producidos por los ciudadanos de un país, independientemente de su ubicación. |
| **Cobertura**  | Solo incluye la producción dentro de las fronteras nacionales.                                  | Incluye la producción de los ciudadanos nacionales, tanto dentro como fuera del país.                                       |
| **Incluye**    | Bienes y servicios generados por factores productivos nacionales y extranjeros dentro del país. | Bienes y servicios generados por factores productivos nacionales, incluso si están en el extranjero.                        |
| **Excluye**    | Ingresos generados por ciudadanos nacionales en el extranjero.                                  | Ingresos generados por extranjeros dentro del país.                                                                         |
| **Relación**   | El PIB es una métrica más territorial.                                                          | El PNB es una métrica más personal o nacional.                                                                              |
| **Fórmula**    | Se calcula considerando solo la producción interna.                                             | Se calcula como: PNB = PIB + Producto Neto de los Factores (PNF).                                                           |
| **Uso común**  | Comparar la producción económica dentro de diferentes países.                                   | Evaluar la capacidad productiva global de los ciudadanos de un país.                                                        |








### **Propensión Marginal a Consumir (PMC):**  
La PMC mide cuánto del ingreso adicional una persona dedica al consumo. Si alguien recibe $100 extra y gasta $80, su PMC es:  
\[
PMC = \frac{\Delta C}{\Delta Y}
\]  
donde \(\Delta C\) es el cambio en el consumo y \(\Delta Y\) es el cambio en el ingreso. Por ejemplo, si \(\Delta C = 80\) y \(\Delta Y = 100\), entonces \(PMC = 0.8\). Una PMC alta significa que la gente gasta la mayor parte de sus ingresos adicionales, impulsando la demanda agregada.

---

### **Propensión Marginal a Ahorrar (PMS):**  
La PMS mide cuánto del ingreso adicional una persona decide ahorrar. Se calcula como:  
\[
PMS = 1 - PMC
\]  
Por ejemplo, si la PMC es 0.8, entonces la PMS es \(1 - 0.8 = 0.2\). Una PMS alta indica que la gente prefiere ahorrar en lugar de consumir, lo que puede ralentizar el impacto de políticas que buscan estimular la economía a través del gasto.

---

### **Multiplicador Keynesiano (\(k\)):**  
El multiplicador mide cuánto se amplifica un cambio en el gasto autónomo en el PIB total. Se define como:  
\[
k = \frac{1}{1 - PMC} = \frac{1}{PMS}
\]  
Por ejemplo, si \(PMC = 0.8\), entonces \(k = \frac{1}{1 - 0.8} = 5\). Esto significa que cada dólar adicional de gasto genera $5 en el PIB. Un \(k\) alto implica un gran efecto expansivo del gasto en la economía, mientras que un \(k\) bajo indica que el impacto es limitado.

---

### **Relación entre PMC, PMS y el Multiplicador Keynesiano:**  
- **Alta PMC** → Mayor multiplicador (\(k\)) → Mayor impacto del gasto en el PIB.  
- **Alta PMS** → Menor multiplicador (\(k\)) → Menor impacto del gasto en el PIB.

---

### **PIB (Producto Interno Bruto):**  
Es la suma del valor de todos los bienes y servicios finales producidos en una economía durante un periodo. Se calcula como:  
\[
PIB = C + I + G + (X - M)
\]  
donde:
- \(C\): Consumo.
- \(I\): Inversión.
- \(G\): Gasto del gobierno.
- \(X - M\): Exportaciones netas (exportaciones menos importaciones).  

El PIB refleja la actividad económica total, y su crecimiento depende de cómo factores como el consumo y la inversión reaccionan al ingreso adicional.
