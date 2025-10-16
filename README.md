# 📈 Análisis de Rentabilidad de Marketing para Showz (Venta de Entradas)

## 🎯 Objetivo del Proyecto

El propósito de este proyecto es **optimizar la inversión en marketing** de Showz, una empresa de venta de entradas para eventos. A través del análisis de datos de visitas, pedidos y gastos, se busca identificar los canales de adquisición de clientes más rentables y proporcionar recomendaciones estratégicas al departamento de marketing.

**Preguntas Clave Resueltas:**

* ¿Cómo utilizan los clientes el servicio (frecuencia, duración de sesión)?
* ¿Cuándo se convierten los usuarios en clientes (tiempo a la primera compra)?
* ¿Cuál es el valor de por vida del cliente (**LTV**) por cohorte y canal?
* ¿Cuán rentables son las inversiones en marketing (**ROMI**) por canal?

## 📊 Metodología y Análisis de Cohortes

Se implementó un **Análisis de Cohortes** utilizando la semana/mes de la primera visita/compra como criterio para la segmentación. Esto permitió el seguimiento de métricas clave a lo largo del tiempo para determinar la efectividad y rentabilidad de cada canal de adquisición.

### 🔑 Métricas Calculadas

| Categoría | Métrica | Definición |
| :--- | :--- | :--- |
| **Adquisición** | **DAU/WAU/MAU** | Usuarios activos diarios, semanales y mensuales promedio. |
| | **Duración de Sesión** | Tiempo promedio que un usuario pasa en el servicio. |
| **Ventas** | **Conversion Rate** | Porcentaje de usuarios que realizan una compra. |
| | **Tasa de Retención** | Frecuencia con la que los usuarios regresan (Sticky Factor). |
| | **LTV (Lifetime Value)** | Ingresos promedio que genera un cliente durante su vida. |
| **Marketing** | **CAC (Customer Acquisition Cost)** | Costo promedio de adquirir un nuevo cliente por canal. |
| | **ROMI (Return on Marketing Investment)** | Rentabilidad de la inversión en marketing. |

## 🛠️ Tecnologías y Herramientas

* **Lenguaje:** Python
* **Librerías:** Pandas (Manipulación y análisis de datos), NumPy, Matplotlib, Seaborn (Visualización).

## ✨ Conclusiones y Recomendaciones Clave

Basado en el análisis de las métricas anuales, se concluye que la inversión en marketing **no se distribuye de manera eficiente**.

### 🌟 Recomendaciones para Inversión:

1.  **Aumentar Inversión en Fuentes 1 y 2:** Estos canales demostraron ser los **más rentables** con un ROMI que indica un retorno sólido de la inversión.
2.  **Reducir Soporte en Fuentes 3, 9 y 10:** Estos canales presentan el ROMI más bajo, lo que sugiere que son menos efectivos en la adquisición de clientes rentables.
3.  **Mantener Operaciones Estables:** Las tasas de conversión y las métricas de uso (DAU, WAU, MAU, duración de sesión) se mantienen estables, lo que indica una base de usuarios saludable. No se requiere una acción drástica para mejorar estas áreas.

---

## 📁 Estructura del Repositorio
├── Análisis de negocio.ipynb # Notebook principal con todo el análisis y visualizaciones. ├── visits_log_us.csv # Registros de visitas al servidor. ├── orders_log_us.csv # Datos de pedidos realizados. ├── costs_us.csv # Estadísticas de gastos de marketing. └── README.md # 

## 📧 Contacto

Dagoberto Mares - [![Gmail Badge](https://img.shields.io/badge/-dagobertomares0@gmail.com-c14438?style=flat&logo=Gmail&logoColor=white&link=mailto:dagobertomares0@gmail.com)](mailto:dagobertomares0@gmail.com)  - [![Linkedin Badge](https://img.shields.io/badge/-dagobertomares-0072b1?style=flat&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/dagoberto-mares/)](https://www.linkedin.com/in/dagoberto-mares/)

