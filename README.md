# 📊 Análisis de Hábitos de Compra - Instacart

Análisis exploratorio de datos de Instacart para identificar patrones de comportamiento de clientes, tendencias de compra por horarios y días, productos más populares y comportamiento de recompra en plataforma de delivery de comestibles.

## 🛠️ Tecnologías Utilizadas

- **Python 3.8+**
- **Pandas** - Manipulación y análisis de datos
- **NumPy** - Operaciones numéricas
- **Matplotlib** - Visualización de datos
- **Seaborn** - Visualizaciones estadísticas avanzadas
- **Jupyter Notebook** - Entorno de desarrollo interactivo

## 📋 Descripción del Proyecto

Este proyecto analiza datos reales de Instacart (plataforma de delivery de comestibles) para extraer insights sobre el comportamiento de compra de los clientes. El dataset incluye información sobre pedidos, productos, departamentos y patrones temporales de compra.

### Objetivos principales:
- Analizar patrones temporales de pedidos (horas del día, días de la semana)
- Identificar productos más populares y frecuentemente reordenados
- Estudiar comportamiento de recompra de clientes
- Examinar distribución de artículos por pedido
- Generar insights accionables para estrategias de negocio

## 📊 Estructura de Datos

El proyecto utiliza 5 datasets principales:

- **`instacart_orders.csv`** - Información de pedidos (32,434 registros)
- **`products.csv`** - Catálogo de productos (49,677 productos)
- **`order_products.csv`** - Relación pedidos-productos (1,384,617 registros)
- **`aisles.csv`** - Categorías de pasillos (134 pasillos)
- **`departments.csv`** - Departamentos de productos (21 departamentos)

### Variables clave analizadas:
- `order_hour_of_day` - Hora del pedido (0-23)
- `order_dow` - Día de la semana (0-6)
- `days_since_prior_order` - Días desde pedido anterior
- `reordered` - Indicador de recompra
- `add_to_cart_order` - Orden de adición al carrito

## ⚙️ Funcionalidades Implementadas

### Limpieza y Preprocesamiento:
- Detección y manejo de valores duplicados
- Tratamiento de valores ausentes
- Validación de rangos de datos
- Unión de datasets relacionales

### Análisis Exploratorio:
- **Análisis temporal:** Patrones por hora y día de la semana
- **Análisis de productos:** Top 20 productos más pedidos
- **Comportamiento de recompra:** Productos más reordenados
- **Análisis de carritos:** Distribución de artículos por pedido
- **Patrones de clientes:** Frecuencia de pedidos por usuario

### Visualizaciones:
- Histogramas de distribución temporal
- Gráficos de barras de productos populares
- Análisis comparativo miércoles vs sábados
- Distribución de tiempo entre pedidos

## 🚀 Instalación y Uso

### Prerrequisitos:
```bash
pip install pandas numpy matplotlib seaborn jupyter
