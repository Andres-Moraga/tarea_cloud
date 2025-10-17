# Trabajo ML / Cloud Computing

- Integrantes:
- Alvaro Gomez
- Andres Moraga
- Camilo Silva

El trabajo corresponde a un modelo de Machine Learning que predice la probabilidad de incumplimiento de pago en el crédito otorgado a los clientes.


# Requirements

\- Python3

\- pandas

\- numpy

\- matplotlib

\- seaborn

\- sklearn



Instalar los requerimientos usando:

```

pip3 install -r requirements.txt

```

# Metodología

De acuerdo al análisis descriptivo realizado en el archivo “01_Análisis_descriptivo”, la decisión tomada es que se aplicarán los siguientes modelos 

Modelos utilizados:

-	Regresión logística con balanceo de clases usando solo las variables con mayor poder discriminativo (‘Edad’, ‘Años_Trabajando’, ‘Deuda_Comercial’ y ‘Ratio_Ingresos_Deudas’).
-	RandomForest con todas las variables
-	HistGradientBoosting con todas las variables


De acuerdo al análisis descriptivo realizado en el archivo “01_Análisis_descriptivo”, la decisión tomada es que se aplicarán los siguientes modelos

## Changelog v0.1

- Se agregaron los archivos .py y el modelo .pkl