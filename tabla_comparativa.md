# 10. Resumen Comparativo Estado Inicial vs. Final

| Elemento | Estado inicial | Estado final |
|---|---|---|
| Número de registros | 6,607 (Valor exacto según lectura inicial) | 6,607 (o $N - \text{duplicados}$) |
| Número de variables | 20 | Matriz prediseñada para ML con dimensiones codificadas |
| Valores faltantes | Presentes en 3+ columnas | 0 (Imputados mediante la moda/pipeline) |
| Registros duplicados | Identificados según exploración | 0 (Eliminados) |
| Variables categóricas transformadas | Texto (object) | Codificadas (OrdinalEncoder / OneHotEncoder) |
| Variables numéricas escaladas | Escalas heterogéneas ($0-100$, $0-50$, etc.) | Estandarizadas con Media = 0 y Varianza = 1 (StandardScaler) |
