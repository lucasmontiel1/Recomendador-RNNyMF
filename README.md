# Recomendador-RNNyMF

# Recomendador Hibrido

Este proyecto implementa un sistema de recomendación híbrido que combina enfoques colaborativos, basados en contenido y basados en conocimientos. El sistema utiliza datos de usuarios, productos y consultas para generar recomendaciones personalizadas.

## Contenido del Repositorio

- **cleaned_code.py**: Archivo que contiene el código limpio y reorganizado del sistema de recomendación híbrido.
- **data**: Carpeta que debería contener los archivos CSV necesarios para ejecutar el código (productos, usuarios, consultas, etc.).
- **model**: Carpeta que almacena el modelo entrenado y cualquier otro archivo relacionado con el modelo.

# Estructura del Código

- Preprocesamiento de Datos: Limpieza y transformación de datos de productos, usuarios y consultas.
- Creación de Mapeos Únicos: Asignación de identificadores únicos a usuarios y productos.
- Matriz de Características de Productos: Construcción de una matriz escasa de productos y sus características.
- Escalado y Particionamiento de Datos: Preparación de datos para entrenamiento y prueba.
- Modelo Híbrido: Implementación de un modelo que combina enfoques colaborativos, basados en contenido y basados en conocimientos.
- Entrenamiento y Evaluación: Entrenamiento del modelo y evaluación en el conjunto de prueba.
