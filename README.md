# JabaliSalvajeTP1

Yo estoy con el análisis de las variables de train independientemente del target, en particular con text, describiendo la distribución del largo tando en caracteres como en palabras.

Resumo como creo que debería ser la estructura del informe completo y sugiero quién (M o J) se encarga de cada item:

1. [M] Intro, Vistazo general de train y test: info, describe, estructura y tipo de datos, anomalías (yo)

2. Analisis de variables por separado en train y test:

  2.1. [M] kw: calidad, distribución, caracteristicas (yo)
  
  2.2. [J] location: calidad, distribución, caracteristicas: p ej heterogeneidad(paises, ciudades...se podría estandarizar?), alguna tendencia?
  
  2.3. [M] text: calidad, distribución, caracteristicas. Largo en caracteres y en palabras, palabras individuales (hay correlaciones internas?).
  
  2.4. [M] target: solo chequear porcentaje de 0s y 1s...
  
3. Cruce de variables:

  3.1. [J] kw vs loc: train y test
  
  3.2. [M] kw vs text (largo caracteres, largo palabras, correlación palabras): train y test
  
  3.3. [J] loc vs text (idem): train y test
  
  3.4. [M] kw vs target (lo hice yo, falta describirlo): train
  
  3.5. [J] loc vs target: train
  
  
  No creo que lleguemos a hacer todo esto, pero tratemos de dejarlo al menos planteado o esbozado.
  Qué te parece?
