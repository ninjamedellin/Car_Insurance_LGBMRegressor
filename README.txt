Hey there!

This project has developed with CRISPDM methodology

You will see this files inside the folder:

1. T_Aseguradora_Preprocessing.ipynb: this file contains the main data preprocessing based on CRISPDM 
methodology. its input is "Base_proyecto.csv"

2. T_Models_Aseguradora.ipynb: it contains the creation of some models. In this case I use only the LGBMRegressor
that was the best model to this project, but you could run the other models that are commented lines

3. T_Models_Aseguradora_HyperParameter_optuna.ipynb: this file is a try to do some optuna hyper parametertunnig in the LGBMRegressor model
 
4. "DB_Valor_Prima_Anual_Cleaned.csv": its an output of the "1.T_Aseguradora_Preprocessing.ipynb"

5. "DB_Valor_Prima_Anual_Cleaned_antiguedadCol.csv": it´s an output of the preprocessing, and it is used in T_Models_Aseguradora.ipynb to add some 
feature engineerings
