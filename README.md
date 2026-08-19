Autor: Alejandra Mollecker

Curso: Herramientas básicas para el Análisis de Datos

# 📊 Tablero de Monitoreo de principales variables de Sala 5

Este repositorio contiene el análisis y monitoreo operativo de las celdas de electrólisis (**cubas**) correspondientes a la **Sala 5 / Serie C**.

---

## 🚀 Resumen Ejecutivo

El dataset analiza **51,293 registros operativos** distribuidos en **67 variables** técnicas, eléctricas y fisicoquímicas, monitoreadas a lo largo de **72 celdas únicas** (IDs 501 a 572).

---

## 📌 Metadatos Principales del Dataset

| Métrica / Parámetro | Valor Registrado |
| :--- | :--- |
| **Total de Registros (Filas)** | 51,293 |
| **Total de Variables (Columnas)** | 67 |
| **Rango Temporal de Monitoreo** | 17/04/2026 – 15/08/2026 |
| **Serie / Unidades Evaluadas** | Serie C (72 Cubas únicas: IDs 501 a 572) |

---

## 🏭 Distribución por Modelo de Cuba (`X_MODELO`)

| Modelo de Cuba | Cantidad de Registros | Porcentaje (%) |
| :--- | :---: | :---: |
| **AP22.0** | 39,484 | 76.98% |
| **al23** | 8,734 | 17.03% |
| **al23.1** | 3,075 | 5.99% |
| **Total** | **51,293** | **100.00%** |

---

## 🔍 Categorización de Variables Principales

Las variables contenidas en el tablero se agrupan funcionalmente en las siguientes dimensiones operativas:

1. **Identificación y Control Temporal:**
   - `CUBA`, `Fecha`, `FT_TURNO`, `TU_SEMI_TURNO`, `TURNO`, `N_VIDA`, `X_MODELO`, `C_SERIE`

2. **Variables Fisicoquímicas y Baño:**
   - `%Al2O3`, `CaF2`, `T Liq` *(Temperatura Liquidus)*, `SH` *(Superheat / Sobrecalentamiento)*, `ALF3`, `ALF3C`, `CAF2`, `CAF2D`

3. **Parámetros Eléctricos y Operativos:**
   - `POTSTATE`, `IPS`, `V_ACD`, `V_TFLUO`, `V_ULT_CU`, `V_APARTAMIENTO`, `ENERGIA_EA`, `MI_EA`, `SMRWFC`

4. **Niveles y Alturas de Capa:**
   - `HB` *(Altura de Baño)*, `HBC`, `HBD`, `HM` *(Altura de Metal)*, `HMC`, `HMD`, `MBLTHE`, `MMTHE`

5. **Adiciones y Alimentación:**
   - `AMALF3`, `AMNA2CO3`, `MTALF3`, `NDAL2O3`, `NDALF3`, `NTEA`, `PEV`, `SOUSAL`

6. **Temperaturas y Variables de Salida:**
   - `TBC`, `TBD`, `TFOIN`, `TFAIN`, `TFED`, `TSID`, `RTH`, `RUCC`, `RUCD`, `SEA`

---

## 🛠️ Requisitos e Instalación

Para explorar o procesar este dataset localmente mediante Python:

```bash
# Clonar el repositorio
git clone https://github.com/tu-usuario/tu-repositorio.git

# Entrar al directorio
cd tu-repositorio

# Instalar dependencias necesarias
pip install pandas numpy matplotlib seaborn
```

---
*Documentación generada automáticamente para el seguimiento operativo de Sala 5.*
