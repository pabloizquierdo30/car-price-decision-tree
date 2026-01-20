# car-price-decission-tree
Used car price predictor using Decision Trees. This repo features a complete ML workflow: detailed EDA on mileage and brands, data cleaning, and One-Hot Encoding. Includes a Python-based regression model to estimate vehicle depreciation and a practical function for real-time car valuation. Ideal for supervised learning practice.
car-price-decision-tree/
├── data/
│   ├── dataset_coches_train.csv    # El archivo que cargas en el notebook
│   └── dataset_coches_test.csv     # (Si tienes uno de prueba separado)
├── notebooks/
│   └── 01_eda_and_modeling.ipynb  # Renombra tu "Entrega1_Ejercicio1.ipynb"
├── src/
│   ├── preprocessing.py           # Aquí puedes mover las funciones de limpieza
│   └── tree_model.py              # Funciones para entrenar el árbol
├── models/
│   └── decision_tree_v1.pkl       # El modelo guardado (usando joblib o pickle)
├── README.md                      # Explicación del proyecto (Ver punto 4)
├── .gitignore                     # Para no subir archivos basura
└── requirements.txt               # Librerías necesarias
