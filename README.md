# Data Necesaria
Para crear un modelo de pricing dinámico, necesitamos simular o recopilar datos relevantes que nos permitan entender la demanda y otros factores que influyen en el precio de los productos. Aquí están los componentes clave de los datos necesarios para un modelo de pricing dinámico:
```python
# Generación de data

# Fechas para la simulación
dates = pd.date_range(start='2018-01-01', end='2023-12-31', freq='D')
n = len(dates)

# Lista de productos (nombre y código)
products = ['Vino tinto reserva', 'Café gourmet en grano', 'Salsa de trufa negra', 'Chips de papa', 'Yogurt griego']
skus = [10000010, 10000020, 10000030, 10000040, 10000050]
```
