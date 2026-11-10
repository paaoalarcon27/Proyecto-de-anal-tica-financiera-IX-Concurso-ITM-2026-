# Proyecto de analítica financiera | IX Concurso ITM 2026 |

> **Plantilla de trabajo para estudiantes.** Crea una copia de este archivo en el repositorio de tu equipo y reemplaza los textos entre corchetes. Conserva las preguntas como apoyo durante la investigación. No publiques claves de acceso ni información privada.

**Curso:** Lenguajes de Programación · Ingeniería Financiera  
**Concurso:** 12 de noviembre de 2026  
**Simulacro:** 10 de noviembre de 2026  
**Tecnología:** [Python + Streamlit / R + Shiny / otra interfaz en Python o R]

## 1. Identificación del proyecto

- **Nombre de la aplicación:** Kapital
- **Equipo e integrantes:** Lina Paola Alarcon Arboleda
- **Enlace a la aplicación:** [Pendiente / URL]
- **Repositorio del proyecto:** [URL]
- **Última actualización:** [AAAA-MM-DD]

## 2. ¿Qué queremos investigar? · S25

**Investiga:** ¿qué significa analizar el comportamiento histórico de un activo financiero? ¿Qué preguntas pueden responderse con datos de mercado y cuáles no?
**¿Qué significa analizar el comportamiento histórico de un activo financiero?**
Significa estudiar cómo ha cambiado el precio de un activo financiero a lo largo del tiempo, utilizando datos como precios de apertura, cierre, máximos, mínimos y volumen de negociación.
Esto permite identificar tendencias, medir rentabilidad, observar variaciones y evaluar el riesgo que ha presentado un activo.

**¿Qué podemos responder y qué no?**
Sí podemos responder cuánto ha subido o bajado una acción, cuál tuvo mayor rentabilidad, cuál presentó más volatilidad y cuáles fueron sus mayores caídas.
No podemos responder con certeza cuánto costará una acción en el futuro, si una inversión garantizará ganancias o qué decisión debe tomar cada inversionista según sus circunstancias.
Los datos históricos permiten estudiar lo que ocurrió, pero no garantizan que vuelva a ocurrir.

**Situación o fenómeno de interés:**
La industria de los semiconductores cumple un papel fundamental en el desarrollo tecnológico, ya que sus productos se utilizan en computadores, dispositivos móviles, centros de datos, inteligencia artificial y otros sistemas electrónicos.

Durante los últimos años, esta industria ha experimentado importantes transformaciones impulsadas por la innovación tecnológica y el crecimiento de la demanda de procesamiento de datos e inteligencia artificial.

Por esta razón, se busca comprender cómo se ha reflejado este comportamiento en el mercado bursátil, mediante el análisis histórico de tres empresas del sector: NVIDIA (NVDA), Advanced Micro Devices (AMD) y Qualcomm (QCOM), durante el período comprendido entre 2021 y 2025.
- **Pregunta principal:**
- ¿Cuál de las tres empresas del sector de semiconductores, NVIDIA, AMD o Qualcomm, presentó el mejor equilibrio entre rentabilidad y riesgo durante el período 2021-2025?
- **Objetivo del análisis:**
- Analizar y comparar el comportamiento histórico de las acciones de NVIDIA, AMD y Qualcomm durante el período 2021-2025, mediante indicadores financieros que permitan evaluar su rentabilidad, volatilidad, comportamiento de precios y niveles de riesgo, con el propósito de identificar cuál presentó el mejor desempeño ajustado al riesgo.
- **Importancia financiera:**
- El análisis es importante porque permite comprender cómo se comportan las empresas de una misma industria en el mercado bursátil, identificar diferencias en sus resultados y evaluar los riesgos asociados a sus acciones.

Además, permite estudiar cómo los cambios tecnológicos, la innovación y las condiciones del mercado pueden coincidir con variaciones en los precios de las acciones.

Los resultados pueden proporcionar información útil para comparar alternativas de inversión y comprender que una mayor rentabilidad no necesariamente implica un menor riesgo.
- **Preguntas complementarias:** [Opcionales]
¿Cuál de las tres empresas obtuvo la mayor rentabilidad acumulada entre 2021 y 2025?

¿Qué acción presentó mayor volatilidad durante el período analizado?

¿Cuál experimentó las mayores caídas desde sus máximos históricos?
> **Comprueba:** ¿tu pregunta identifica activos, variables y un período de estudio? ¿Es posible responderla con datos disponibles?

## 3. Activos, datos y alcance · S25

**Investiga:** ¿qué activos se ajustan a tu pregunta? ¿qué datos históricos existen? ¿qué frecuencia, período y fuente utilizarás?

| Activo | Símbolo o ticker | Tipo | Razón para incluirlo |
|---|---|---|---|
| [NVIDIA Corporation] | [NVDA] | [acción] | [Empresa especializada en GPU y soluciones de computación e inteligencia artificial. Se incluye para analizar el comportamiento de sus acciones ante el crecimiento de la demanda tecnológica.] |
| [Advanced Micro Devices] | [AMD] | [acción] | [Empresa dedicada al desarrollo de procesadores y tarjetas gráficas. Se incluye para comparar su rentabilidad y riesgo frente a otras compañías del sector.] |
| [QUALCOMM Incorporated] | [QCOM] | [acción] | [Empresa especializada en semiconductores y tecnologías de conectividad. Se incluye para evaluar el comportamiento de una compañía enfocada principalmente en chips para dispositivos móviles y comunicaciones.] |
- **Fuente de datos:** Yahoo Finance mediante yfinance
- **Período:** 1 de enero de 2021 al 31 de diciembre de 2025
- **Frecuencia:** Datos diarios
- **Variables disponibles:** [Fecha, precio de cierre, volumen...]
- **Limitaciones de los datos:** [Fechas faltantes, zona horaria, ajustes, diferencias de mercado...]
- **Lenguaje:** Python
- **Aplicación:** Streamlit
- **Comparación:** Rentabilidad y riesgo
**Primera prueba:** [Enlace al notebook o archivo que descarga o consulta datos; indica qué funcionó y qué no]

## 4. Metodología de análisis · S25–S26

**Investiga:** ¿qué indicadores permiten responder la pregunta principal? ¿cómo se calculan? ¿qué interpretación y limitaciones tienen?

**¿Cuál de las tres empresas, NVIDIA, AMD o Qualcomm, presentó el mejor equilibrio entre rentabilidad y riesgo durante 2021-2025?**
estos indicadores permiten comparar cuál empresa obtuvo mayor rentabilidad, cuál presentó más fluctuaciones y caídas, y cuál logró el mejor equilibrio entre rentabilidad y riesgo.

<img width="1061" height="534" alt="image" src="https://github.com/user-attachments/assets/14fd82fc-47b1-4235-b68a-d48eb7ce51d6" />

| Indicador / técnica | ¿Qué mide? | ¿Por qué lo necesitamos? | Implementación |
|---|---|---|---|
| [Rentabilidad acumulada] | [Mide el porcentaje de crecimiento o disminución del precio de una acción durante el período analizado.] | [Identificar cuál de las tres empresas generó mayor rentabilidad.] | [Archivo o celda] |
| [Volatilidad anualizada] | [Mide las fluctuaciones de los rendimientos diarios mediante la desviación estándar anualizada.] | [Comparar el nivel de variación y riesgo de las tres acciones.] | [Pendiente / enlace] |
| [Máximo drawdown] | [Mide la mayor caída porcentual de una acción desde un máximo anterior hasta un mínimo posterior.] | [Identificar cuál empresa presentó las caídas más pronunciadas.] | [Archivo o celda] |
| [Ratio de Sharpe] | [Mide la rentabilidad excedente obtenida en relación con la volatilidad asumida.] | [Determinar cuál acción presentó el mejor equilibrio entre rentabilidad y riesgo.] | [Archivo o celda] |
No es necesario utilizar todos los indicadores estudiados en clase. Selecciona y justifica únicamente los pertinentes.

### Visualizaciones previstas

| Gráfico | Pregunta que ayuda a responder | Variables | Interpretación esperada |
|---|---|---|---|
| [Gráfico 1] | [¿Cuál de las tres empresas presentó el mayor crecimiento durante 2021–2025?] | [Fecha, precios ajustados y empresas (NVDA, AMD y QCOM).] | [Permite observar que NVIDIA presentó el mayor crecimiento, seguida de AMD y Qualcomm. También muestra las fluctuaciones de los precios durante el período.] |
| [Gráfico 2] | [¿Cuál empresa obtuvo la mayor rentabilidad acumulada durante el período de estudio?] | [(X): Empresas de semiconductores AMD, NVIDIA y Qualcomm (Y): Rentabilidad acumulada, expresada en porcentaje %.] | [Permite comparar de forma directa el desempeño financiero de las tres compañías. Se concluye que NVIDIA obtuvo el crecimiento más alto con diferencia (1326.2%), seguida por AMD en segundo lugar (132.03%) y Qualcomm con el menor rendimiento acumulado (28.28%).] |

**Grafico 1 Evolución histórica de las acciones (base 100).**

<img width="959" height="473" alt="image" src="https://github.com/user-attachments/assets/5f6ec810-ca43-469d-8b51-41ed4053dd2b" />

**Gráfico 2 Gráfico de barras de rentabilidad acumulada por empresa.**

<img width="958" height="476" alt="image" src="https://github.com/user-attachments/assets/c89a15a6-df29-48f1-928c-0f0c60b19001" />


**Primer resultado verificable:** [Enlace a un cálculo o gráfico realizado con datos reales y una interpretación breve]

## 5. Diseño de la aplicación · S25

**Investiga:** ¿cómo se construyen controles, gráficos y métricas con la herramienta elegida? ¿qué sucede cuando el usuario modifica una selección?

- **Usuarios previstos:** Estudiantes de finanzas, inversionistas y personas interesadas en analizar y comparar el comportamiento de empresas del sector de semiconductores.
- **Entradas y filtros:** 
Selección de activos: NVIDIA (NVDA), AMD y Qualcomm (QCOM).
Tasa libre de riesgo anual para el cálculo del ratio de Sharpe.
Período de análisis: 2021–2025.
- **Secciones de la interfaz:**
- Panorama general: evolución histórica de los precios de las acciones y comparación de indicadores.
Rentabilidad: comparación de la rentabilidad acumulada.
Riesgo: visualización de volatilidad, máximo drawdown y ratio de Sharpe.
Metodología: explicación de los indicadores utilizados y las fuentes de información.
- **Resultados visibles:**
Gráficos de evolución de precios.
Gráficos comparativos de rentabilidad y riesgo.
Tabla con los cuatro indicadores financieros.
Explicaciones sobre el significado de cada indicador.
- **Interacción principal:**
El usuario puede seleccionar una o varias empresas y modificar la tasa libre de riesgo. Cuando cambia una selección, la aplicación actualiza los datos, cálculos, gráficos y tablas de acuerdo con los activos seleccionados.
**Flujo previsto:**  
Selección de activos y parámetros → Obtención de datos de Yahoo Finance → Preparación y cálculos financieros → Visualización de resultados → Interpretación y comparación.

**Boceto o esquema:** 
Se utilizará como referencia el diseño de la aplicación KAPITAL desarrollado en Streamlit, con una interfaz clara, fondo claro, elementos en tonos azul petróleo y verde azulado, menú lateral y secciones de análisis financiero.
**Decisión técnica:** 
Se eligió Python por sus herramientas para el análisis de datos financieros y la automatización de cálculos. Para construir la aplicación se utilizará Streamlit, que permite crear interfaces interactivas; Pandas y NumPy para procesar datos y calcular indicadores; y Plotly para elaborar gráficos interactivos. Los precios históricos se obtendrán mediante Yahoo Finance utilizando la biblioteca yfinance.
## 6. Construcción y pruebas · S26 (5 de noviembre)

Actualiza esta sección durante el laboratorio de desarrollo.

- **Componentes implementados:** [Qué funciona realmente]
Interfaz principal de KAPITAL con diseño personalizado.
Menú lateral para seleccionar NVIDIA (NVDA), AMD y Qualcomm (QCOM).
Parámetro para modificar la tasa libre de riesgo.
Obtención de precios históricos mediante Yahoo Finance para el período 2021–2025.
Cálculo de cuatro indicadores: rentabilidad acumulada, volatilidad anualizada, máximo drawdown y ratio de Sharpe.
Secciones de panorama general, rentabilidad, riesgo y metodología.
Gráficos y tablas para comparar los resultados.
- **Cómo ejecutar la aplicación:** [Comandos, dependencias y pasos]
Abrir el proyecto en Google Colab.
Instalar las dependencias necesarias.
Ejecutar las celdas de configuración y creación de la aplicación.
Iniciar el servidor de Streamlit en el puerto 8501.
Crear el enlace público mediante Cloudflare para visualizar la aplicación en el navegador.
- **Dependencias:** [Archivo `requirements.txt`, `renv.lock` u otro]
Se instalaron las siguientes bibliotecas mediante pip:
Streamlit: construcción de la interfaz.
Pandas y NumPy: procesamiento de datos y cálculos financieros.
yfinance: consulta de precios históricos.
Plotly: elaboración de gráficos interactivos.
Pillow: creación y edición de la imagen de portada.
- **Pruebas realizadas:** [Caso probado, resultado esperado y resultado obtenido]
Inicio del servidor Streamlit: resultado obtenido satisfactorio, con respuesta HTTP 200.
Consulta de datos históricos de las tres empresas: la aplicación cargó correctamente.
Visualización de gráficos, tablas e indicadores: funcionamiento correcto.
Modificación de la selección de activos: se comprobó que la aplicación actualiza los resultados.
Consulta de la versión de yfinance: prueba ejecutada correctamente.
- **Errores conocidos y cómo se resolvieron:** [Explicación]
Durante la construcción inicial se presentó un error de sintaxis por un paréntesis de cierre faltante. Se corrigió la instrucción y se volvió a ejecutar la aplicación. También se verificó el funcionamiento del servidor y del enlace público de visualización.
- **Pendientes antes del simulacro:** [Tareas concretas]
Verificar nuevamente los datos y resultados de NVDA, AMD y QCOM.
Comprobar que los filtros actualicen correctamente los indicadores y gráficos.
Revisar la presentación visual y los textos de la aplicación.
Guardar la versión final del código como 04_kapital_final.py.
Comprobar que la aplicación pueda ejecutarse y visualizarse correctamente.

> No afirmes que una función está implementada si aún no ha sido probada.

## 7. Hallazgos e interpretación · S26–S28

Para cada hallazgo importante, registra:

1. **Evidencia:** Gráfico 2. Rentabilidad acumulada por empresa y tabla de indicadores financieros de KAPITAL.
2. **Qué muestra:** NVIDIA presentó la mayor rentabilidad acumulada durante el período 2021–2025, con un 1326,20 %. AMD obtuvo un 132,03 % y Qualcomm un 28,28 %.
3. **Interpretación financiera:**  NVIDIA tuvo el mayor crecimiento del valor de su acción durante el período analizado, superando ampliamente a las otras dos compañías.
4. **Limitaciones:** La rentabilidad histórica no garantiza resultados futuros. El análisis no incluye comisiones, impuestos ni otros costos de inversión.

**Hallazgo 2. Comparación del riesgo**
**Evidencia:** Tabla de resumen de indicadores financieros de KAPITAL.
**Qué muestra:** La volatilidad anualizada fue de 52,23 % para NVIDIA, 52,41 % para AMD y 38,15 % para Qualcomm. El máximo drawdown fue de -66,34 % para NVIDIA, -65,45 % para AMD y -44,29 % para Qualcomm.
**Interpretación financiera:** NVIDIA y AMD presentaron niveles de volatilidad similares y superiores a Qualcomm. Además, NVIDIA experimentó la mayor caída desde un máximo histórico, lo que evidencia períodos de pérdidas importantes.
**Limitaciones:** La volatilidad y el máximo drawdown describen el comportamiento histórico del riesgo, pero no permiten anticipar con certeza las pérdidas futuras.

**Hallazgo 3. Equilibrio entre rentabilidad y riesgo**
**Evidencia:** Tabla de resumen de indicadores financieros, específicamente el ratio de Sharpe.
**Qué muestra:** NVIDIA obtuvo un ratio de Sharpe de 1,282; AMD de 0,582 y Qualcomm de 0,322. El cálculo se realizó utilizando una tasa libre de riesgo del 0 %.
**Interpretación financiera:** NVIDIA presentó el mejor resultado ajustado al riesgo entre las tres empresas. Esto indica que ofreció una mayor rentabilidad en relación con la volatilidad asumida durante el período estudiado.
**Limitaciones:** El ratio de Sharpe depende de la tasa libre de riesgo utilizada y de los rendimientos históricos. No representa una garantía de rentabilidad futura.
**Conclusión provisional o final:** 
De acuerdo con los resultados obtenidos en KAPITAL, NVIDIA presentó el mejor equilibrio entre rentabilidad y riesgo durante el período 2021–2025. Aunque registró una volatilidad elevada y el mayor máximo drawdown, alcanzó una rentabilidad acumulada del 1326,20 % y un ratio de Sharpe de 1,282, superior al de AMD y Qualcomm.

Por lo tanto, NVIDIA fue la empresa con el mejor desempeño ajustado al riesgo entre las tres compañías analizadas, considerando los indicadores y las condiciones establecidas en este estudio.

> Los resultados históricos no garantizan rendimientos futuros.

## 8. Simulacro · S27 (10 de noviembre)

**Guion de sustentación (3–5 minutos):**
- Problema financiero y activos.
- Datos y metodología.
- Demostración de interactividad.
- Hallazgos e interpretación.
- Conclusión y limitaciones.

**Retroalimentación recibida:** [Observaciones del docente o compañeros]

| Ajuste necesario | Responsable | Estado |
|---|---|---|
| [Ajuste] | [Integrante] | [Pendiente / en proceso / resuelto] |

## 9. Presentación final · S28 (12 de noviembre)

- **Enlace funcional de la aplicación:** [URL]
- **Versión final / commit:** [Enlace]
- **Evidencia de presentación:** [Enlace autorizado]
- **Conclusiones finales:** [Síntesis]
- **Limitaciones y posibles mejoras:** [Descripción]

## 10. Bitácora de trabajo y aportes

| Fecha | Integrante(s) | Investigación o decisión | Avance técnico / evidencia | Próximo paso |
|---|---|---|---|---|
| 2026-11-03 | [Nombre] | [Qué investigamos] | [Enlace a código o documento] | [Acción] |
| 2026-11-05 | [Nombre] | [Decisiones] | [Evidencia] | [Acción] |
| 2026-11-10 | [Nombre] | [Retroalimentación] | [Cambio] | [Acción] |

## Recursos de consulta

- [Libro de programación y analítica financiera del curso](https://github.com/vyolete/proyecto_analitica_financiera)
- [Documentación de yfinance](https://ranaroussi.github.io/yfinance/)
- [Documentación de pandas](https://pandas.pydata.org/docs/)
- [Documentación de Streamlit](https://docs.streamlit.io/)
- [Documentación de Shiny para R](https://shiny.posit.co/r/)

**Uso del documento:** En S25 desarrolla especialmente las secciones 2 a 5 y registra tu primera prueba; en S26, S27 y S28 actualiza el mismo README. No dupliques información en entregas separadas.
