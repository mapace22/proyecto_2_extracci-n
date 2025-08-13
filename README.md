# proyecto_2_extracci-n
Análisis y extracción de datos de clientes para Store 1 | Python: funciones, bucles y condicionales

# Proyecto: Análisis y Extracción de Datos de Clientes para Store 1

## Descripción del Proyecto
Este proyecto se centra en la aplicación de técnicas de programación en Python para analizar y extraer información de una lista de datos de clientes de "Store 1". A partir de las bases establecidas en el proyecto anterior (limpieza de datos), se desarrollaron funciones y lógica avanzada para responder a preguntas de negocio específicas y gestionar los datos de manera más eficiente.

## Objetivos del Análisis
- Crear funciones reutilizables para la limpieza de datos, demostrando la capacidad de escribir código modular y escalable.
- Manejar estructuras de datos complejas (listas anidadas) para procesar información de múltiples usuarios.
- Calcular métricas de negocio como los ingresos totales.
- Filtrar y segmentar clientes basados en criterios múltiples (edad, gasto total y categorías de compra).
- Demostrar habilidades en el uso de bucles (`for`, `while`) y condicionales (`if`) para la manipulación de datos.

## Tecnologías Utilizadas
- **Python**: El lenguaje de programación principal.
- **Funciones**: Creación de funciones (`def`) para encapsular lógica de limpieza de datos.
- **Bucles y Condicionales**: Uso de `for loops`, `while loops` e `if statements` para iterar y filtrar datos.
- **Operaciones en Listas**: `append()`, `insert()`, `pop()` y `sum()`.
- **f-strings**: Para la generación de mensajes dinámicos.
- **random**: Uso de la librería para simular datos.

## Pasos Clave del Análisis
1. **Desarrollo de Funciones**: 
   - Se creó una función `clean_user()` para automatizar la limpieza de nombres, edades y categorías de los usuarios.
   - Esta función asegura que los datos estén estandarizados antes de cualquier análisis.

2. **Análisis de Ingresos**:
   - Se utilizó un bucle `for` para iterar sobre todos los usuarios.
   - Se calculó el total de ingresos generados para la empresa.

3. **Simulación de Compras**:
   - Se implementó un bucle `while` para simular compras adicionales.
   - La lógica continuaba hasta que un cliente alcanzaba un gasto objetivo.

4. **Segmentación de Clientes**:
   - Se combinaron bucles y condicionales para identificar clientes según criterios:
     - Clientes menores de 30 años
     - Clientes menores de 30 años con gasto superior a $1000
     - Clientes que compraron categorías específicas como "clothes" (ropa)

5. **Extracción de Datos por Categoría**:
   - Se desarrolló la función `get_client_by_cat()` para extraer:
     - ID
     - Nombre
     - Edad
     - Gasto total
   - Proporciona una herramienta de análisis poderosa para la dirección.

## Conclusiones
Este proyecto demuestra un dominio intermedio de Python aplicado a la ciencia de datos. Las funciones desarrolladas, combinadas con el uso de estructuras de control, permiten transformar datos brutos en información valiosa de negocio, lo que representa una habilidad fundamental para cualquier analista de datos.
