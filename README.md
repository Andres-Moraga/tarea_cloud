# Trabajo ML / Cloud Computing

- Integrantes:
- - Alvaro Gomez
- - Andres Moraga
- - Camilo Silva

El trabajo corresponde a un modelo de Machine Learning que predice la probabilidad de incumplimiento de pago en el crédito otorgado a los clientes.

En el archivo “Tabla_Trabajo_Grupal”, se encuentran la tabla “Desarrollo” con los siguientes campos para el modelamiento de Machine Learning cuyo objetivo es el de predecir la probabilidad de incumplimiento del pago de los clientes :

- Edad: Campo cuantitativo que detalla la edad del cliente.

- Nivel Educacional: Campo categórico que detalla el nivel educacional del cliente. 

- Años Trabajando: Campo cuantitativo con el detalle de los años trabajando del cliente. 

- Ingresos: Campo cuantitativo que detalla el monto encriptado del ingreso del cliente. 

- Deuda Comercial: Campo cuantitativo que detalla la deuda comercial del cliente. 

- Deuda Crédito: Campo cuantitativo que detalla la deuda consumo en crédito del cliente. 

- Otras Deudas: Campo cuantitativo que detalla el monto deudas, no comerciales ni consumo del cliente.

- Ratio Ingresos Deudas: Campo cuantitativo que detalla la proporción de ingresos sobre deudas totales del cliente.

- Default: Variable cuantitativa binaria, que detalla el incumplimiento del cliente en el pago (target). De esta manera el incumplimiento de pago de un crédito se define con el valor “1”.

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