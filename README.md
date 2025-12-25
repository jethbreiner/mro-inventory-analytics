# MRO Inventory Analytics (Power BI + Python)

## Contexto 
Proyecto de portafolio orientado a Mantenimiento (MRO): control y optimización de inventarios, análisis de rotación/obsolescencia/cobertura, y automatización de reportes para revisión semanal.

## Qué resuelve (preguntas de negocio)
- ¿Qué repuestos están en riesgo de quiebre (stockout)?
- ¿Qué repuestos están sobrestock?
- ¿Qué ítems muestran baja rotación / obsolescencia potencial?
- ¿Cuál es la cobertura (días/semanas) según consumo histórico?
- ¿Qué diferencias aparecen en conteo cíclico vs. kardex (simulado)?

## Entregables
- Dashboard (Power BI): stock, consumo, pedidos, valor inventario.
- Reporte automático (Python): limpieza, KPIs y export (CSV/Excel).

## Datos
- Dataset sintético (no confidencial) generado para simular consumos, compras y movimientos MRO.
- Estructura: movimientos (entradas/salidas), maestro de materiales, consumo histórico, órdenes de compra.

## Stack
Power BI (Power Query, DAX), Python (pandas), Excel (opcional), SQL básico (opcional).

## Cómo ejecutar
1) `pip install -r requirements.txt`
2) `python src/etl_build_dataset.py`
3) Abrir `powerbi/dashboard.pbix` (o ver capturas en `/docs`)
