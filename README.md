# Trabajo 5: Fuga de clientes

Una empresa de telecomunicaciones ha observado un gran número de abandonos durante el último mes por parte de sus clientes, por ello, ha recopilado toda la información que dispone de sus clientes y pretende establecer medidas para evitar que esta fuga se repita.

Las tareas requeridas por parte de esta empresa son las siguientes:

* Realizar un análisis exploratorio de los datos detallando aquellos aspectos más relevantes que hayáis encontrado.
* Construir un modelo de clasificación que indique si el cliente va a salir de la empresa a partir del próximo mes o no.
* Desarrollar un cuadro de mando con Dash que resuma los aspectos más relevantes que hayáis extraido en el análisis exploratorio y permita evaluar si hay nuevos clientes con riesgo de fuga.

¿Qué medidas preventivas basadas en los datos le recomendaríais a la empresa para que sus clientes no abandonen la empresa?

## Información de los datos:
Existen tres tipos de fuentes de datos, los servicios que el cliente ha firmado, la información de la cuenta del cliente e información demográfica del cliente. Las variables son:

* customerID: Identificador del cliente
* gender: Hombre o Mujer
* SeniorCitizen: Si el cliente está jubilado o no
* Partner: Si el cliente tiene un compañero o no
* Dependent: Si el cliente tiene dependientes o no
* Tenure: Número de meses que el cliente se ha quedado en la compañía.
* PhoneService: Si el cliente tiene un servicio de teléfono o no
* MultiplesLines: Si el cliente tiene más de una linea de teléfono o no.
* InternetService: Tipo de servicio de cliente (3 categorías DSL, Fiber Optic, No)
* OnlineSecurity: Si el cliente tiene seguridad online o no.
* OnlineBackup: Si el cliente tiene alguna copia de seguridad online.
* DeviceProtection: Si el cliente tiene alguna protección en los dispositivos.
* TechSupport: Si el cliente tiene soporte técnico o no.
* StreamingTV: Si el cliente tiene televisión en streaming o no.
* StreamingMovies: Si el cliente tiene películas en streaming o no.
* Contract: Términos de duración del contrato del cliente (Month-to-month, One year, Two year)
* PaperlessBilling: Si el cliente prefiere la factura sin papel o no.
* PaymentMethod: Método de pago del cliente (Electronic check, Mailed check, Bank Transfer (automatic), Credit Card(automatic))
* MonthlyCharges: Cantidad que se le carga a un cliente de forma mensual.
* TotalCharges: Cantidad total que se le ha cobrado al cliente.
* Churn: Abandona la compañía o no.
