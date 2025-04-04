# EJERCICIO DE EVALUACIÓN MÓDULO 3 - PROMO 49
## Diana P. Gómez

### 📌 Descripción del Proyecto

Este proyecto se enfoca en analizar los datos de dos archivos CSV proporcionados por una aerolínea, con el objetivo de estudiar el uso y el perfil de los usuarios que poseen tarjetas de fidelización. A través de un análisis exhaustivo, acompañado de un proceso de limpieza, procesamiento y visualización de datos, presentaremos las conclusiones obtenidas.

### 🛠 Tecnologías Utilizadas

- Python (pandas, numpy, matplotlib, seaborn)
- Jupyter Notebook

### 📂 Estructura del Proyecto

```
📦 directorio-proyecto
├── 📁 files        # CSV utilizados para el análisis
├── 📁 notebooks    # Notebooks de Jupyter con análisis
├── 📁 requirements # requirements.txt para instalar dependencias necesarias
└── README.md       # Este archivo

```

### 🚀 Instalación

1. Clona este repositorio:
    
    ```bash
    git clone https://github.com/Adalab/bda-modulo-3-evaluacion-final-dianapgomez.git
    
    ```
    
2. Instala las dependencias requeridas:
    
    ```bash
    pip install -r requirements.txt
    
    ```
    
3. Abre Jupyter Notebook:
    
    ```bash
    jupyter notebook
    
    ```
###  📊 Descripción de los datos

### Customer Flight Analysis.csv  
Este archivo contiene información sobre la actividad de vuelo de los clientes, incluyendo:  
- Número de vuelos reservados  
- Distancia volada  
- Puntos acumulados y redimidos  
- Costos asociados a los puntos redimidos  

### **Atributos**  
- **`Loyalty Number`**: Identificador único para cada cliente dentro del programa de lealtad de la aerolínea.  
- **`Year`**: Año en el que se registraron las actividades de vuelo.  
- **`Month`**: Mes del año (1-12) en el que ocurrieron las actividades de vuelo.  
- **`Flights Booked`**: Total de vuelos reservados por el cliente en ese mes.  
- **`Flights with Companions`**: Vuelos en los que el cliente viajó con acompañantes.  
- **`Total Flights`**: Número total de vuelos realizados por el cliente, incluyendo reservas anteriores.  
- **`Distance`**: Distancia total volada (en millas o kilómetros) durante el mes.  
- **`Points Accumulated`**: Puntos acumulados en el programa de lealtad según la distancia volada y otros factores.  
- **`Points Redeemed`**: Puntos redimidos en el mes para beneficios como vuelos gratis o mejoras.  
- **`Dollar Cost Points Redeemed`**: Valor en dólares de los puntos redimidos durante el mes.  

---

### Customer Loyalty History.csv  
Este archivo proporciona un perfil detallado de los clientes, incluyendo ubicación, nivel educativo, ingresos, estado civil y detalles sobre su membresía en el programa de lealtad.  

### **Atributos**  
- **`Loyalty Number`**: Identificador único del cliente, permitiendo correlacionar con el archivo de actividad de vuelos.  
- **`Country`**: País de residencia del cliente.  
- **`Province`**: Provincia o estado de residencia (aplicable en países con divisiones provinciales o estatales).  
- **`City`**: Ciudad de residencia del cliente.  
- **`Postal Code`**: Código postal del cliente.  
- **`Gender`**: Género del cliente (`Male` para masculino, `Female` para femenino).  
- **`Education`**: Nivel educativo alcanzado (`Bachelor` para licenciatura, `College` para estudios técnicos, etc.).  
- **`Salary`**: Ingreso anual estimado del cliente.  
- **`Marital Status`**: Estado civil (`Single` para soltero, `Married` para casado, `Divorced` para divorciado, etc.).  
- **`Loyalty Card`**: Tipo de tarjeta de lealtad del cliente (puede indicar distintos niveles o categorías).  
- **`CLV (Customer Lifetime Value)`**: Valor total estimado que el cliente aporta a la empresa durante toda su relación con ella.  
- **`Enrollment Type`**: Tipo de inscripción del cliente en el programa (`Standard`, etc.).  
- **`Enrollment Year`**: Año de inscripción en el programa de lealtad.  
- **`Enrollment Month`**: Mes de inscripción en el programa de lealtad.  
- **`Cancellation Year`**: Año de cancelación de la membresía (si aplica).  
- **`Cancellation Month`**: Mes de cancelación de la membresía (si aplica).  

### 💻 Uso

- Ejecuta un Run All en el jupyter `evaluacion_mod2` que encontrarás en  `notebooks/`.
- Visualiza los resultados clave con las gráficas generadas.
- La documentación y explicaciones se encuentran en el mismo notebook.

### 📝 Licencia

Este proyecto no está licenciado.