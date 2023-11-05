# modelos_de_prediccion
Una cadena de gimnasios esta intentando interactuar con sus usuarios a través de datos analiticos.

Con estos datos recabados de los usarios se analizarán y se determinaran que factores son los más determinantes que influyen en que el usuario se vaya del gimnasio. Esto se realizará utilizando modelos de predicción RandomForest y Regresión Logística.

Es dataset utilizado es:
#### gym_data = pd.read_csv('/datasets/gym_churn_us.csv')
* gender                             Genero 
* Near_Location                      Si el cliente vive lejos o cerca del local  
* Partner                            Si el cliente tiene patrocinador
* Promo_friends                      Si el cliente se afilió a través de un amigo 
* Phone                              Número de telefono
* Contract_period                    Periodo de contrato 
* Group_visits                       Visitas en grupo  
* Age                                Edad 
* Avg_additional_charges_total       Promedio de cargos adicionales
* Month_to_end_contract              Mes de finalización de contrato
* Lifetime                           Tiempo de duración
* Avg_class_frequency_total          Frecuencia promedio de clases total
* Avg_class_frequency_current_month  Frecuencia promedio de clases del mes en curso
* Churn                              Avandono 
