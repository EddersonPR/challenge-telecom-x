# 📡 Telecom X Latam - Análisis de Churn de Clientes

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Numpy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge&logo=python&logoColor=white)
![Google Colab](https://img.shields.io/badge/Google%20Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white)
![Visual Studio Code](https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

Análisis exploratorio de datos (EDA) sobre **deserción de clientes en Telecom X Latam**. Este proyecto busca comprender los factores que impulsan el churn y generar insights accionables para:

- 📉 Reducir la tasa de abandono
- 🎯 Priorizar segmentos de alto riesgo
- 🤖 Sentar las bases para modelos predictivos de churn

---

## 📑 Índice
1. [📖 Descripción](#-descripción)
2. [🎯 Objetivo](#-objetivo)
3. [📊 Principales hallazgos](#-principales-hallazgos)
4. [🚀 Tecnologías utilizadas](#-tecnologías-utilizadas)
6. [📊 Acceso al análisis](#-acceso-al-análisis)
7. [💡 Recomendaciones estratégicas](#-recomendaciones-estratégicas)
8. [📜 Licencia](#-licencia)
9. [✨ Autor](#-autor)

---

## 📖 Descripción

**Telecom X Latam** enfrenta una tasa de deserción del **26.6%**, lo que representa un impacto significativo en los ingresos de la compañía. Este proyecto aborda el desafío mediante un análisis exploratorio exhaustivo de **7,032 clientes** y **23 variables**, utilizando Python y sus principales bibliotecas de ciencia de datos.

El análisis identifica patrones claros de deserción relacionados con:
- ⏱️ Experiencia temprana del cliente (primeros 6 meses críticos)
- 📝 Tipo de contrato y método de pago
- 🌐 Servicios contratados (especialmente fibra óptica)
- 👥 Perfil demográfico y comportamiento de uso

A partir de estos hallazgos, el equipo de Data Science puede desarrollar **modelos predictivos** y **estrategias de retención** basadas en evidencia.

---

## 🎯 Objetivo

✔️ **Identificar los factores clave** que impulsan la deserción de clientes  
✔️ **Cuantificar el impacto** de cada variable en la tasa de churn  
✔️ **Segmentar clientes** de alto riesgo para acciones preventivas  
✔️ **Proponer recomendaciones estratégicas** fundamentadas en datos  
✔️ **Establecer bases sólidas** para modelos predictivos de machine learning

---

## 📊 Principales hallazgos

### 🔴 Tasa de deserción global: **26.6%**

### ⏰ Momento crítico
- **53% del churn** ocurre en los primeros **6 meses**
- La antigüedad muestra correlación negativa moderada con el abandono
- Superar los 6 meses aumenta drásticamente la probabilidad de permanencia

### 👤 Perfil de alto riesgo
| Factor | Tasa de Churn |
|--------|---------------|
| Contrato mensual | 42.7% |
| Fibra óptica | 41.9% |
| Adultos mayores | 41.7% |
| Cheque electrónico | 45.3% |
| Sin soporte técnico | 2.7x mayor |

### 💰 Impacto financiero
- El churn afecta **desproporcionadamente** a clientes de alto cargo mensual
- Mediana de cargo: **$80** (desertores) vs **$63** (no desertores)
- El abandono temprano de clientes premium representa el **mayor riesgo** para ingresos

### 📌 Insight clave
> La deserción **no es aleatoria**: responde a patrones claros de experiencia temprana, tipo de contrato y composición del servicio.

---

## 🚀 Tecnologías utilizadas

- 🐍 **Python 3.x** – Lenguaje principal de análisis
- 📊 **Pandas** – Manipulación y análisis de datos
- 📈 **Matplotlib / Seaborn** – Visualización de datos y gráficos estadísticos
- 🔢 **NumPy** – Operaciones numéricas y estadísticas
- 📓 **Jupyter Notebook** – Desarrollo interactivo del análisis
- ☁️ **Google Colab** – Ejecución en la nube
- 💻 **Visual Studio Code** – Desarrollo y edición de código
- 🌐 **Git / GitHub** – Control de versiones y colaboración

---

## 📊 Acceso al análisis

### 📘 Notebook interactivo
🔗 **Google Colab:**  
[📊 Telecom X LATAM - Análisis Completo de Churn](https://colab.research.google.com/github/EddersonPR/challenge-telecom-x/blob/main/TelecomX_LATAM.ipynb)

## 💡 Recomendaciones estratégicas

### 🚀 Acciones de corto plazo (operativas)

1. **Programa de onboarding intensivo** en los primeros 90 días
2. **Seguimiento proactivo** a clientes de fibra óptica
3. **Incentivos para migrar** de contrato mensual a anual
4. **Promover métodos de pago automáticos** (tarjeta/transferencia)

### 🎯 Acciones de retención

**Alertas preventivas para clientes con:**
- ⏱️ Antigüedad < 6 meses
- 💰 Cargo mensual alto
- 🚫 Sin soporte técnico contratado
- 📝 Contrato próximo a vencer

**Ofertas personalizadas** antes del vencimiento contractual

### 🤖 Data Science - Variables clave para modelo predictivo

1. Antigüedad del cliente
2. Tipo de contrato
3. Servicio de internet contratado
4. Cargo mensual
5. Soporte técnico (Sí/No)
6. Adulto mayor (Sí/No)
7. Método de pago

---

## 📜 Licencia

Este proyecto se comparte bajo la licencia **MIT**.  
Puedes usarlo, modificarlo y distribuirlo libremente citando la fuente.

```
MIT License - Copyright (c) 2025 Edderson Pomacanchari Ramos
```

---

## ✨ Autor

**Edderson Pomacanchari Ramos**  
Data Analyst | Python Developer

📧 **Contacto:**  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/eddersonpr/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/EddersonPR)

---

## 🙏 Agradecimientos

Este proyecto fue desarrollado como parte del challenge de análisis de datos, con el objetivo de aplicar técnicas de EDA y storytelling con datos para resolver problemas reales de negocio.

---

⭐ **Si este proyecto te resulta útil, considera darle una estrella en GitHub**