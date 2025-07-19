# 📊 Telecom X - Análisis de Evasión de Clientes

[![una-empresa-ficticia-llamada-telecom-x-que.jpg](https://i.postimg.cc/59rqW8v9/una-empresa-ficticia-llamada-telecom-x-que.jpg)](https://postimg.cc/8shrhJtx)
![Static Badge](https://img.shields.io/badge/status-completed-green)
---
## 📑 Índice
- [🧾 Descripción del proyecto](#-descripción-del-proyecto)
- [🔧 Funcionalidades del análisis](#-funcionalidades-del-análisis)
- [📂 Acceso al proyecto](#-acceso-al-proyecto)
- [🛠️ Abre y ejecuta el proyecto](#️-abre-y-ejecuta-el-proyecto)
- [🧰 Tecnologías utilizadas](#-tecnologías-utilizadas)
- [👨‍💻 Autor](#-autor)
- [🪪 Licencia](#-licencia)
---
## 🧾 Descripción del proyecto
Este proyecto forma parte del curso **Aprendiendo a hacer ETL** de la formación ONE (Oracle Next Education) junto a Alura LATAM. El reto consistió en asistir a la empresa ficticia **Telecom X** en la identificación de los factores que explican la pérdida de clientes (churn).

Se trabajó con datos reales extraídos desde una API, donde se abordaron:

- Información demográfica de los clientes
- Tipos de servicios contratados
- Métodos de pago utilizados
- Niveles de facturación y antigüedad

A través de gráficos, limpieza, normalización y análisis exploratorio, se identificaron los patrones más asociados al abandono del servicio y se ofrecieron recomendaciones para reducir la tendencia de abandono del servicio.
---
## 🔧 Funcionalidades del análisis
- `Extracción de datos desde API`: Se importa la información de clientes directamente desde una fuente externa en formato JSON.
- `Transformación y limpieza de datos`: Se normalizan, renombran y limpian variables para eliminar inconsistencias, valores nulos y duplicados.
- `Expansión y enriquecimiento del dataset`: Se desanidan columnas anidadas y se crean nuevas métricas como facturación diaria estimada.
- `Estandarización semántica`: Se traducen y ajustan términos técnicos y valores categóricos a un formato uniforme y legible en español.
- `Análisis exploratorio visual`: Se generan gráficos de pastel, barras, histogramas, violines y cajas para identificar patrones de abandono.
- `Comparación por segmentos`: Se analizan diferencias entre clientes que abandonaron y permanecieron según variables numéricas y categóricas.
- `Hallazgos clave y patrones`: Se interpretan tendencias de comportamiento asociadas al churn con base en visualizaciones y métricas.
- `Recomendaciones accionables`: Se proponen estrategias prácticas para reducir la evasión de clientes con base en los resultados del análisis.
---
## 📂 Acceso al proyecto
Puedes acceder al código fuente del proyecto directamente en este repositorio.  
💡 *El análisis fue realizado en Google Colab con archivos `.ipynb` y gráficos generados con Matplotlib y Seaborn.*
---
## 🛠️ Abre y ejecuta el proyecto
1. Clona el repositorio:
```bash
git clone https://github.com/tu-usuario/telecom-x-churn.git
```
2. Accede a la carpeta:
```bash
cd telecom-x-churn
```
3. Instala las dependencias (requiere Python 3 y pip):
```bash
pip install pandas matplotlib seaborn
```
4. Abre el proyecto en Google Colab o Jupyter Notebook.
---
## 🧰 Tecnologías utilizadas
- Python 3
- Pandas
- Matplotlib
- Seaborn
- Google Colab
## 👤 Autor
[<img src="https://avatars.githubusercontent.com/u/157757330?v=4" width=115><br><sub>Jetsael Villegas</sub>](https://github.com/JetsaelVillegasMendoza)
---
## 📝 Licencia
Este proyecto está licenciado bajo la Licencia MIT - consulta el archivo LICENSE para más detalles.

