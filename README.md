# RayTracerAcceleration (Random Parameter Filtering)

## Integrantes
- Rodrigo Gabriel Salazar Alva

## Descripción

Este proyecto tiene como objetivo mejorar el rendimiento del renderizado del RayTracer basado en físicas [PBRT-v3](https://github.com/mmp/pbrt-v3). Para lograr este objetivo, se implementará la técnica de Random Parameter Filtering (RPF) para reducir el número de muestras requeridas en el proceso de renderizado utilizando el método Monte Carlo.
Motivación

## Motivación

Los sistemas de renderizado basados en Monte Carlo son ampliamente utilizados debido a su capacidad para producir imágenes fotorrealistas, simulando las complejas interacciones de la luz. Sin embargo, la calidad de las imágenes depende del número de muestras utilizadas. Más específicamente, la varianza del ruido en las imágenes disminuye inversamente con el número de muestras. Esto implica que, para obtener imágenes libres de ruido, se requiere un gran número de muestras, lo que resulta en tiempos de renderizado largos. Por lo tanto, surge la necesidad de implementar técnicas que permitan reducir el número de muestras necesarias para obtener imágenes de calidad.