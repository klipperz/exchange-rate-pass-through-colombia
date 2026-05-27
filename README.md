# exchange-rate-pass-through-colombia
# Transmisión del tipo de cambio hacia los precios domésticos en Colombia (2005-2025)

Proyecto de econometría aplicada desarrollado en EViews para analizar el pass-through cambiario hacia los precios domésticos en Colombia mediante un modelo VAR no restringido.

## Objetivo

Analizar cómo los choques en el tipo de cambio nominal COP/USD se transmiten hacia:

- precios de importación,
- precios al productor,
- precios al consumidor.

## Metodología

El análisis se realiza mediante un modelo VAR estimado con datos mensuales para el período 2005-2025.

Se incluyen:

- pruebas de estacionariedad (KPSS),
- selección de rezagos,
- pruebas LM de autocorrelación,
- estabilidad del VAR,
- causalidad de Granger,
- funciones impulso-respuesta acumuladas,
- descomposición de Cholesky,
- intervalos Monte Carlo.

## Variables utilizadas

- TRM (COP/USD)
- Índice de precios de importación
- Índice de precios al productor (IPP)
- Índice de precios al consumidor (IPC)
## Fuente de los datos

-Banco de la república

## Resultados principales

Los resultados muestran un traspaso cambiario:

- alto hacia precios de importación,
- moderado hacia precios al productor,
- bajo hacia precios al consumidor.

Esto sugiere un traspaso incompleto y decreciente a lo largo de la cadena de precios.

## Software

- EViews

## Referencias base

- Rowland (2003)
- McCarthy (2000)
- Goldberg y Knetter (1997)
