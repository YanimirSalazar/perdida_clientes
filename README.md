# perdida_clientes
Esta investigación tiene como propósito aprender a predecir la probabilidad de pérdida (para el próximo mes) para cada cliente, elaborar retratos de usuarios típicos, analizar los factores que más impactan la pérdida, sacar conclusiones básicas y elaborar recomendaciones para mejorar la atención al cliente.
## Data:

- *gender* — género del cliente.
- *Near_Location* — si el usuario vive o trabaja en el vecindario donde se encuentra el gimnasio        
- *Partner*  — si el usuario es un trabajador de una compañía asociada (el gimnasio tiene empresas asociadas cuyos empleados obtienen descuentos; en esos casos el gimnasio almacena información sobre los empleadores de los clientes)  
- *Promo_friends*— si el usuario originalmente se inscribió mediante una oferta "trae a un amigo" (se utilizó el código promocional de un amigo cuando pagaron el primer abono).      
- *Phone*  — si el usuario aportó el número de teléfono  
- *Contract_period* — 1 mes, 3 meses, 6 meses o 1 año
- `Group_visits` — si el usuario participa en sesiones grupales.     
- *Age*  — Edad del cliente
- *Avg_additional_charges_total* — cantidad total de dinero gastado en otros servicios del gimnasio: cafetería, productos deportivos, cosméticos, masajes, etc. 
- *Month_to_end_contract* — Meses para finalizar contrato.
- *Lifetime* — el tiempo (en meses) desde que el usuario llegó por primera vez al gimnasio        
- *Avg_class_frequency_total*  — frecuencia media de visitas por semana a lo largo de la vida del cliente  
- *Avg_class_frequency_current_month* — frecuencia media de visitas por semana durante el mes en curso
- *Churn* — la cancelación para el mes en cuestión.

## Libraries used:

pandas

matplotlib.pyplot

plotly 

seaborn

numpy

sklearn.model_selection import train_test_split

sklearn.linear_model import LogisticRegression

sklearn.metrics import accuracy_score, precision_score, recall_score, f1_score

sklearn.ensemble import RandomForestClassifier, GradientBoostingClassifier

sklearn.preprocessing import StandardScaler

sklearn.metrics import roc_auc_score

sklearn.cluster import KMeans

scipy.cluster.hierarchy import dendrogram, linkage
