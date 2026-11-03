# Indicadores de Control y Estándares de Desempeño

## Objetivo

Definir criterios medibles que permitan evaluar el funcionamiento del prototipo y comprobar si cumple con las funciones previstas para la gestión de materiales y herramientas por obra.

## Indicadores de control

**1. Exactitud del stock**

Se verificará que las existencias registradas coincidan con el cálculo realizado a partir de los movimientos de entrada y salida.

- **Método de medición:** comparar el stock calculado con el stock registrado.
- **Estándar esperado:** 100 % de coincidencia entre las existencias calculadas y las registradas.
- **Prueba prevista:** verificar las existencias de al menos 60 materiales y herramientas.

**2. Registro de movimientos**

Se comprobará que las entradas y salidas de materiales queden registradas con todos los datos necesarios.

- **Método de medición:** calcular el porcentaje de movimientos registrados correctamente sobre el total de movimientos válidos ingresados.
- **Estándar esperado:** 100 % de los movimientos válidos registrados correctamente.
- **Prueba prevista:** registrar al menos 100 movimientos de entrada y salida.

**3. Detección de faltantes**

Se evaluará si el sistema identifica los casos en los que la cantidad disponible no alcanza para cubrir la cantidad requerida.

- **Método de medición:** calcular el porcentaje de casos de faltantes detectados correctamente.
- **Estándar esperado:** detectar el 100 % de los faltantes previstos en las pruebas.
- **Prueba prevista:** realizar al menos 10 pruebas con situaciones de stock insuficiente.

**4. Asociación con la obra**

Se comprobará que cada movimiento esté vinculado con el material y la obra correspondientes.

- **Método de medición:** calcular el porcentaje de movimientos asociados correctamente.
- **Estándar esperado:** 100 % de los movimientos vinculados al material y a la obra correctos.
- **Prueba prevista:** verificar la asociación de los 100 movimientos registrados.

**5. Validación de datos**

Se verificará que el sistema rechace cantidades negativas, salidas superiores al stock disponible y registros sin datos obligatorios.

- **Método de medición:** calcular el porcentaje de registros inválidos rechazados correctamente.
- **Estándar esperado:** rechazar el 100 % de los registros inválidos e informar el motivo al usuario.
- **Prueba prevista:** realizar al menos 10 pruebas con datos incorrectos o incompletos.

## Estándares de desempeño

Para comprobar el funcionamiento del prototipo, se realizarán pruebas con datos simulados de entre 1 y 6 obras, al menos 60 materiales y herramientas y un mínimo de 100 movimientos.

Durante las pruebas se verificará que:

- Las entradas incrementen las existencias y las salidas las disminuyan correctamente.
- No se permita registrar una salida superior al stock disponible.
- Los avisos de faltantes se generen cuando corresponda.
- Los movimientos queden asociados al material y a la obra correctos.
- Los datos inválidos sean rechazados y se informe el motivo al usuario.

Los resultados se registrarán durante las pruebas y se compararán con los estándares establecidos para identificar errores y realizar las correcciones necesarias.

## Alcance de los indicadores

Los valores definidos representan objetivos de cumplimiento para evaluar el prototipo académico. Su cumplimiento deberá comprobarse mediante las pruebas correspondientes; no se consideran resultados obtenidos hasta que las pruebas se ejecuten y documenten.
