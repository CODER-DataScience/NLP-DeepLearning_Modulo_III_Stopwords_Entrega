# NLP & DeepLearning Modulo III Stopwords Entrega
### Práctica: Implementación y evaluación de eliminación de stopwords con spaCy
### NLP - Eliminación de Stopwords con spaCy

## Objetivo
Implementar y evaluar la eliminación de stopwords en un dataset de reseñas, utilizando spaCy. Se comparan resultados con lista estándar y personalizada.

## Pasos
1. **Carga de datos**: Dataset de reseñas de Amazon.
2. **Tokenización básica**: Segmentación de texto con spaCy.
3. **Eliminación de stopwords estándar**: Uso de `STOP_WORDS` de spaCy.
4. **Personalización de stopwords**: Ajuste de lista según contexto.
5. **Comparación de resultados**: Conteo de frecuencias antes y después.
6. **Reflexión**: Impacto en análisis de palabras clave y preparación para clasificación.

## Resultados
- La lista estándar reduce ruido rápidamente.
- La personalización mejora relevancia en contexto de reseñas.
- Limpieza agresiva puede eliminar información útil.

## Conclusión
La eliminación de stopwords mejora precisión y eficiencia, pero debe adaptarse al dominio para no perder información valiosa.
