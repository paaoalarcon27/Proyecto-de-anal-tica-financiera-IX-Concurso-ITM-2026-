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
| [Gráfico 1] | [Pregunta] | [Variables] | [Qué se podrá observar] |
| [Gráfico 2] | [Pregunta] | [Variables] | [Qué se podrá comparar] |

**Primer resultado verificable:** [Enlace a un cálculo o gráfico realizado con datos reales y una interpretación breve]

## 5. Diseño de la aplicación · S25

**Investiga:** ¿cómo se construyen controles, gráficos y métricas con la herramienta elegida? ¿qué sucede cuando el usuario modifica una selección?

- **Usuarios previstos:** [Quién podría consultar la aplicación]
- **Entradas y filtros:** [Activos, fechas, parámetros...]
- **Secciones de la interfaz:** [Pantalla principal, comparación, riesgo, etc.]
- **Resultados visibles:** [Gráficos, tablas, indicadores y explicaciones]
- **Interacción principal:** [Describe qué cambia cuando el usuario modifica un control]

**Flujo previsto:**  
Selección de activos y parámetros → Obtención de datos → Preparación y cálculos → Visualización → Interpretación.

**Boceto o esquema:** [Inserta una imagen o enlace al diseño, por ejemplo `docs/boceto.png`]

**Decisión técnica:** [¿Por qué usarás Python o R y qué biblioteca de aplicación elegiste?]

## 6. Construcción y pruebas · S26 (5 de noviembre)

Actualiza esta sección durante el laboratorio de desarrollo.

- **Componentes implementados:** [Qué funciona realmente]
- **Cómo ejecutar la aplicación:** [Comandos, dependencias y pasos]
- **Dependencias:** [Archivo `requirements.txt`, `renv.lock` u otro]
- **Pruebas realizadas:** [Caso probado, resultado esperado y resultado obtenido]
- **Errores conocidos y cómo se resolvieron:** [Explicación]
- **Pendientes antes del simulacro:** [Tareas concretas]

> No afirmes que una función está implementada si aún no ha sido probada.

## 7. Hallazgos e interpretación · S26–S28

Para cada hallazgo importante, registra:

1. **Evidencia:** [Gráfico, tabla o indicador con enlace]
2. **Qué muestra:** [Describe el comportamiento observado]
3. **Interpretación financiera:** [Explica su significado en relación con la pregunta]
4. **Limitaciones:** [Qué no puedes concluir de los datos]

**Conclusión provisional o final:** [Respuesta sustentada a la pregunta principal]

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
