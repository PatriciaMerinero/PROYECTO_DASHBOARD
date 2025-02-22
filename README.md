
![TARJETA](https://media.gettyimages.com/id/855388884/es/foto/pile-of-credit-cards.jpg?s=1024x1024&w=gi&k=20&c=Igk4blgoeIiHmYy4b9zqVyJQCO0o4UKyEv2U4aq50lU=)




# PROYECTO DATA ANALYTICS, MÓDULO 3: DASHBOARD 💳🚀

**Dashboard de recuperaciones por Fraude (Chargebacks)** 

## 📂 Dataset utilizado
🔗 [Chargeback Transactions Dataset - Kaggle](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
## Descripción DATASET:
## 📊 Descripción del Dataset
Este dataset contiene información sobre **transacciones de chargebacks**, incluyendo datos sobre las disputas, tipo de operación, países involucrados y resultados del proceso.

### 📌 Estructura del dataset
| **Columna**                         | **Descripción**                                           
|--------------------------------------|-----------------------------------------------------------
| `ID del caso`                        | Identificador único del chargeback.                       
| `Fecha de transacción`               | Fecha en que se realizó la transacción.                   
| `Fecha de disputa`                   | Fecha en que se inició la disputa del chargeback.         
| `Monto de la transacción (USD)`      | Monto de la transacción en dólares.                      
| `Tipo de tarjeta`                    | Tipo de tarjeta utilizada (Crédito/Débito).              
| `Tipo de operación`                  | Si la operación incluyó cambio de divisa o no.           
| `Motivo del chargeback`              | Razón por la que se solicitó el chargeback.              
| `Categoría del comercio`             | Tipo de comercio donde se realizó la transacción.        
| `Estado de la disputa`               | Resultado de la disputa (Ganada/Perdida/Pendiente).       
| `País del cliente`                   | País donde se originó la transacción.                     
| `Caso fallido`                        | Indica si el caso fue fallido en términos de recuperación.
| `Tipología de fraude`                | Tipo de fraude identificado.                              
| `Transaction_Amount`                 | Cantidad de la transacción (puede ser redundante).       
| `Merchant_Name`                      | Nombre del comercio donde ocurrió la transacción.        
| `Chargeback_Status`                  | Estado del chargeback en el proceso de disputa.          
| `Recuperación_CBKs`                  | Monto recuperado en la disputa.                         
| `Devoluciones_Comercio`              | Monto devuelto por el comercio.                          
| `Fallido`                             | Monto que no se pudo recuperar.                          
| `ARN de la operación`                | Número único de referencia de la transacción.           
| `Estado del informe`                 | Estado del informe de la disputa.                        
| `Fecha del informe`                  | Fecha en que se generó el informe final.                
| `Fraude evitado (USD)`               | Monto que se logró evitar en fraude.                     
| `País del Merchant`                  | País del comercio donde se realizó la transacción.       

**Los tipos de datos son:**
  - `String`
  - `Fecha`
  - `Float`




## DESCRIPCIÓN DEL PROYECTO📌:
 Mi primer repositorio en GIT. Es un análisis de recuperaciones de Fraude en tarjetas de Crédito/Débito, mediante Chargebacks. Con éste análisis podemos establecer acciones para prevención del Fraude, aplicando reglas mas severas para las transacciones por tipo de comercio o por fechas concretas.También podemos analizar los importes recuperados ya que hay que revisar si compensa solicitar chargebacks por los costes que tienen.
 
## ESTRUCTURA:
El repositorio esta compuesto de:
- 2 archivos csv generados por CHATGPT. Los archivos CSV de chargebacks fueron creados por CHATGPT de manera ficticia para que se pudieran trabajar con datos de ejemplo. 
- Archivo Excel:
  - Archivos csv.
  - Unión archivos csv
  - Tablas dinámicas
  - `Dashboard`
- Informe PDF con las conclusiones y acciones a realizar tras análisis.
  
**Se utilizó Excel para la limpieza inicial de los datos, el análisis y visualización.**

## RESULTADO Y CONCLUSIONES 🔍
- La duración promedio para la resolución de un caso es de 75 días.
- Recuperamos por CBKS un 49% del importe de Fraude. Si compensa el iniciar disputa por Fraude. 
- El comercio devuelve un 26% sin iniciar ninguna disputa.
- Se lleva a pérdidas por Fraude un 25%.

 ![image](https://github.com/user-attachments/assets/cace1aa0-b3e8-4cb3-a497-206f92c83c84)

- El importe evitado es elevado por las acciones de prevención como pueden ser las reglas del motor antifraude.
- La categoría de comercios donde se hace más Fraude es en Hogar y Jardín.

  
- Los lunes son los días de la semana con más Fraude online.
- El mes con más Fraude es febrero.

## 


 
