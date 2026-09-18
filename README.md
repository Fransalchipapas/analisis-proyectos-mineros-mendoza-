# Análisis de los Proyectos Mineros de la Provincia de Mendoza

## objetivo:

El objetivo es poder analizar las características, distribución y comportamiento de los proyectos mineros de la
provincia de Mendoza mediante técnicas que nos dan resultados 
Así podremos entrenar y testear modelos de aprendizaje 
obteniendo así patrones y perfiles dentro de la actividad minera


## Objetivos específicos

1. Reunir y documentar datasets públicos relacionados con proyectos y actividad minera.
2. Filtrar o integrar la información necesaria para concentrar el análisis en Mendoza.
3. Realizar un análisis exploratorio de datos (AED/EDA) utilizando Pandas y visualizaciones.
4. Limpiar y transformar las variables necesarias.
5. Preparar los datos para regresión y clasificación.
6. Comparar modelos supervisados mediante métricas apropiadas y controlar el overfitting mediante partición de datos y ajuste de hiperparámetros.
7. Desarrollar un modelo de clustering para identificar grupos o perfiles de proyectos, explicando el criterio utilizado.
8. Documentar las decisiones, resultados y limitaciones del proyecto.

> Nota: los objetivos concretos de regresión y clasificación se definirán después de inspeccionar las columnas y la calidad de los datasets reales. No se crearán objetivos artificiales solo para cumplir una técnica.

## Fuentes iniciales previstas

- SIACAM / Datos Argentina — Cartera de Proyectos Mineros.
- Datos Abiertos Mendoza — Padrón Minero.
- SIACAM / Datos Argentina — Comercio de Minerales / Exportaciones.

Las URLs exactas, versiones y fechas de descarga se registrarán en `docs/fuentes.md`.

## Tecnologías

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Estructura

```text
proyecto_proyectos_mineros_mendoza/
├── data/
│   ├── raw/
│   └── processed/
├── notebooks/
├── src/
├── models/
├── reports/
│   └── figures/
├── docs/
├── .gitignore
├── README.md
└── requirements.txt
```

## Orden de trabajo

1. Selección y documentación de datasets.
2. AED / EDA.
3. Limpieza y transformación.
4. Preparación de variables.
5. Regresión.
6. Clasificación.
7. Clustering.
8. Evaluación y conclusiones.

## Creamos el repositorio en GitHub
```text
Empezamos creando el repositorio:                      git init
Guardamos la primera version en ese repositorio local: git add .
                                                       git commit -m "Inicializar proyecto"
Vamos a GitHub y creamos el repositorio nuevo:         (https://github.com/Fransalchipapas/analisis-proyectos-mineros-mendoza-.git)
Conectamos el repositorio desde la terminal:           git remote add origin https://github.com/Fransalchipapas/analisis-proyectos-mineros-mendoza-.git
Renombramos la rama actual del main                    git branch -M main 
Subimos los comits locales a GitHub                    git push -u origin main
```
## Estructura simple del proyecto
| notebooks/             |           
|------------------------|          
| Exploración            |
| Experimentos           |
| Graficos               |
| Comparación de modelos |
| Interpretación         |
         |
         |
        \/
| src/        |
|-------------|
| carga.py    |
| limpieza.py |
| features.py |
| models.py   |
|utilidades.py|
