# 📊 Challenge TelecomX - Análisis de Evasión de Clientes

<div align="center">

![TelecomX](https://img.shields.io/badge/TelecomX-Churn%20Analysis-blue?style=for-the-badge)
![Python](https://img.shields.io/badge/Python-3.8+-green?style=for-the-badge&logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-orange?style=for-the-badge&logo=pandas)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-red?style=for-the-badge)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?style=for-the-badge&logo=jupyter)

**Challenge de Alura sobre Extracción, Transformación y Carga de Datos**

[🔗 Ver Repositorio](https://github.com/jmlc643/challenge-telecom-x) | [📊 Ver Notebook](TelecomX_Latam.ipynb) | [📄 Diccionario de Datos](TelecomX_diccionario.md)

</div>

---

## 🎯 **Descripción del Proyecto**

Este proyecto forma parte del **Challenge de Alura** sobre **Ingeniería de Datos**, enfocado en el análisis de evasión de clientes (Churn) para la empresa ficticia **TelecomX**. El objetivo es identificar patrones de comportamiento que permitan desarrollar estrategias efectivas de retención de clientes.

### **Problema de Negocio**
- **Desafío**: Reducir la tasa de evasión de clientes en TelecomX
- **Impacto**: La pérdida de clientes afecta directamente la rentabilidad
- **Solución**: Análisis predictivo para identificar clientes en riesgo

---

## 📁 **Estructura del Proyecto**

```
challenge-telecom-x/
├── 📊 TelecomX_Latam.ipynb      # Notebook principal con análisis completo
├── 📄 TelecomX_Data.json        # Dataset original en formato JSON
├── 📋 TelecomX_diccionario.md   # Diccionario de datos y variables
├── 📖 README.md                 # Este archivo
└── 📜 LICENSE                   # Licencia del proyecto
```

---

## 🔍 **Metodología ETL**

### **🔹 Extracción**
- Carga de datos desde archivo JSON estructurado
- Normalización de objetos anidados (customer, phone, internet, account)
- Consolidación en DataFrame único para análisis

### **🔹 Transformación**
- **Limpieza de datos**: Eliminación de valores nulos en variable objetivo
- **Estandarización**: Unificación de valores categóricos inconsistentes
- **Validación**: Verificación de integridad y consistencia lógica
- **Enriquecimiento**: Creación de variables derivadas (Cuentas_Diarias)

### **🔹 Carga y Análisis**
- Análisis exploratorio exhaustivo
- Visualizaciones comparativas por segmentos
- Identificación de patrones y factores de riesgo

---

## 📊 **Análisis Realizados**

### **1. Exploración de Datos**
- ✅ Verificación de calidad y consistencia
- ✅ Análisis de distribuciones
- ✅ Identificación de valores atípicos
- ✅ Estadísticas descriptivas completas

### **2. Análisis de Churn por Variables Categóricas**
- 📈 Distribución por tipo de contrato
- 📈 Análisis por método de pago
- 📈 Segmentación demográfica
- 📈 Análisis de servicios contratados

### **3. Análisis de Variables Numéricas**
- 📊 Tiempo de contrato vs Churn
- 📊 Gastos mensuales y totales
- 📊 Relaciones entre variables financieras
- 📊 Identificación de umbrales críticos

---

## 🔑 **Principales Hallazgos**

### **📈 Métricas Clave**
- **Tasa de Churn**: 26.5%
- **Clientes analizados**: 7,043 (después de limpieza)
- **Variables analizadas**: 20+ características

### **🎯 Perfil de Alto Riesgo**
- Contratos mensuales (vs anuales)
- Pago por cheque electrónico
- Clientes nuevos (< 12 meses)
- Sin servicios adicionales de seguridad
- Adultos mayores sin dependientes

### **🛡️ Factores Protectores**
- Contratos de largo plazo
- Múltiples servicios contratados
- Antigüedad > 24 meses
- Métodos de pago automático

---

## 🚀 **Recomendaciones Estratégicas**

### **Acciones Inmediatas**
- 🎯 Programa "Primeros 100 días" para clientes nuevos
- ⚠️ Sistema de alertas automáticas para alto riesgo
- 📞 Equipo especializado en retención

### **Acciones Tácticas**
- 💰 Incentivos para contratos anuales
- 📦 Bundles atractivos con servicios de seguridad
- 🏦 Promoción de débito automático
- 🏆 Programa de lealtad por antigüedad

### **ROI Proyectado**
- **Meta**: Reducir churn del 26.5% al 18%
- **Impacto**: +600 clientes retenidos/año
- **Beneficio estimado**: $2-3M anuales

---

## 🛠️ **Tecnologías Utilizadas**

<div align="center">

| Herramienta | Versión | Propósito |
|-------------|---------|-----------|
| 🐍 **Python** | 3.8+ | Lenguaje principal |
| 🐼 **Pandas** | 1.5+ | Manipulación de datos |
| 📊 **Matplotlib** | 3.5+ | Visualizaciones |
| 🎨 **Seaborn** | 0.11+ | Gráficos estadísticos |
| 📓 **Jupyter** | Latest | Entorno de desarrollo |
| 🔢 **NumPy** | 1.21+ | Cálculos numéricos |

</div>

---

## 📋 **Requisitos de Instalación**

### **Dependencias**
```bash
pip install pandas matplotlib seaborn numpy jupyter
```

### **Ejecución**
```bash
# Clonar repositorio
git clone https://github.com/jmlc643/challenge-telecom-x.git
cd challenge-telecom-x

# Iniciar Jupyter Notebook
jupyter notebook TelecomX_Latam.ipynb
```

---

## 📖 **Documentación**

- **[📊 Notebook Principal](TelecomX_Latam.ipynb)**: Análisis completo paso a paso
- **[📋 Diccionario de Datos](TelecomX_diccionario.md)**: Descripción detallada de variables
- **[🔗 Repositorio GitHub](https://github.com/jmlc643/challenge-telecom-x)**: Código fuente completo

---

## 👨‍💻 **Autor**

**Jose Manuel Lopez Carreño**
- GitHub: [@jmlc643](https://github.com/jmlc643)
- Proyecto: Challenge Alura - Ingeniería de Datos

---

## 📄 **Licencia**

Este proyecto está bajo la Licencia MIT. Ver [LICENSE](LICENSE) para más detalles.

---

## 🤝 **Contribuciones**

Las contribuciones son bienvenidas. Para cambios importantes:

1. Fork el proyecto
2. Crea una rama (`git checkout -b feature/amazing-feature`)
3. Commit tus cambios (`git commit -m 'Add amazing feature'`)
4. Push a la rama (`git push origin feature/amazing-feature`)
5. Abre un Pull Request

---

## 📞 **Contacto**

¿Preguntas sobre el proyecto? ¡No dudes en contactar!

<div align="center">

**Challenge TelecomX - Análisis de Evasión de Clientes** 📊

*Desarrollado con ❤️ como parte del Challenge de Alura*

</div>
