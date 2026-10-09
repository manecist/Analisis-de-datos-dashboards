<a id="inicio"></a>

<div align="center">

<img src="https://readme-typing-svg.herokuapp.com/?lines=An%C3%A1lisis+de+datos+en+salud;Cinco+tableros+en+Power+BI+y+Tableau;KPI+de+salud+p%C3%BAblica+explicados;Una+mirada+de+matrona+a+los+datos+de+Chile&center=true&width=900&height=60&duration=3500&pause=900&color=6B3FD4&size=24" alt="Análisis de datos en salud">

<img src="recursos/logo_maria_cisterna.png" alt="María Cisterna · Matrona · Registro Superintendencia de Salud N° 561993" width="460">

# 📊 Salud sexual y reproductiva en Chile, en datos

### 🩺 Anticonceptivos · ITS · Embarazo y matronería · Ajuar del recién nacido · Cáncer

**María Cisterna Escobar · Matrona** — Registro Superintendencia de Salud N° 561993

<br>

![Power BI](https://img.shields.io/badge/Power%20BI-5%20tableros-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Tableau](https://img.shields.io/badge/Tableau-5%20tableros-E97627?style=for-the-badge&logo=tableau&logoColor=white)
![Excel](https://img.shields.io/badge/Excel-bases%20de%20datos-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)
![KPI](https://img.shields.io/badge/KPI-de%20salud%20p%C3%BAblica-6B3FD4?style=for-the-badge)
![Fuentes](https://img.shields.io/badge/Fuentes-MINSAL%20%C2%B7%20OMS%20%C2%B7%20INE-EE6FB0?style=for-the-badge)

</div>

<p align="center">
<a href="#anticonceptivos">💊 Anticonceptivos en Chile</a> · <a href="#its">🩺 ITS en Chile</a> · <a href="#embarazo">🤰 Embarazo y matronería</a> · <a href="#ajuar">🍼 Ajuar Chile Crece Contigo</a> · <a href="#cancer">🎗️ Cáncer en Chile</a> · <a href="#presentacion">🎤 Presentación</a>
</p>

<p align="center">
<a href="#anticonceptivos"><img src="recursos/mini_anticonceptivos.png" width="170" alt="Anticonceptivos en Chile"></a>
<a href="#its"><img src="recursos/mini_its.png" width="170" alt="ITS en Chile"></a>
<a href="#embarazo"><img src="recursos/mini_embarazo.png" width="170" alt="Embarazo y matronería"></a>
<a href="#ajuar"><img src="recursos/mini_ajuar.png" width="170" alt="Ajuar Chile Crece Contigo"></a>
<a href="#cancer"><img src="recursos/mini_cancer.png" width="170" alt="Cáncer en Chile"></a>
</p>

---

## 📖 Sobre este repositorio

Este repositorio reúne cinco tableros de análisis de datos que hice para responder preguntas reales de salud sexual y reproductiva en Chile, desde mi mirada de matrona. Cada uno parte de una pregunta, junta los datos públicos que existen, los ordena en una base de datos con su fuente y los muestra con **indicadores de salud (KPI)** explicados, gráficos interactivos, ilustraciones con teoría y conclusiones.

> 👀 **¿No tienes Power BI ni Tableau?** No importa: más abajo están **todas las páginas en imágenes**. Haz clic en cualquier miniatura para verla en grande y abre «🎨 Ver en Tableau» para comparar. Para usar los filtros y controles, descarga el `.pbix` (Power BI Desktop, gratis) o el `.twbx` (Tableau Public, gratis).

---

## 🔍 Qué investigué

| | Tablero | Pregunta | Fuentes principales |
|:---:|---|---|---|
| 💊 | Anticonceptivos | ¿Qué método me sirve, qué tan eficaz y seguro es? | OMS, CDC 2024, Trussell, EMA, MINSAL, INJUV, DEIS |
| 🩺 | ITS | ¿Están aumentando y dónde está Chile frente al mundo? | MINSAL, ISP, ONUSIDA, CDC, ECDC, OPS |
| 🤰 | Embarazo y matronería | ¿Qué pasa con el embarazo adolescente y las matronas? | INE, DEIS, Superintendencia de Salud, ONU, Cochrane |
| 🍼 | Ajuar | ¿Llega el ajuar a todas las guaguas y cuánto cuesta? | DIPRES, MINSAL, Cenabast, Chile Crece Contigo, INE |
| 🎗️ | Cáncer | ¿Cuánto aumenta y cómo le ganamos? | DEIS, GLOBOCAN (IARC), ENS, MINSAL, OMS |

---

## 👩‍⚕️ Mi participación

Hice el proceso completo de cada tablero:

- 🔎 Búsqueda y lectura de fuentes oficiales chilenas e internacionales.
- 🧾 Revisión de cada cifra y registro de su origen en la columna `FuenteID`.
- 🗂️ Construcción de las bases de datos en Excel, con una hoja `KPI` y una hoja `Fuentes`.
- 📐 Elección de los KPI: cómo se calculan, qué evalúan, por qué importan y su meta oficial.
- 📊 Modelo de datos y medidas en **Power BI** (segmentadores, fichas que cambian según lo que eliges y simuladores con parámetros).
- 🎨 Las mismas páginas en **Tableau**, con parámetros, filtros y acciones.
- 🌸 Diseño visual propio: fondo, colores, logo con mi registro y textos en lenguaje simple.
- 🎤 Una presentación que resume los cinco tableros, con hallazgos, medidas y conclusiones.

---

## 🛠️ Proceso de trabajo

```text
Pregunta de salud que quiero responder
              ↓
Búsqueda de fuentes oficiales (MINSAL, INE, DEIS, OMS…)
              ↓
Lectura, comparación y verificación de cada cifra
              ↓
Base de datos en Excel con la fuente de cada fila
              ↓
Elección de los KPI y de su meta
              ↓
Tablero en Power BI  ·  mismo tablero en Tableau
              ↓
Revisión de cada página y capturas
              ↓
Hallazgos, medidas y conclusiones
```

---

## 🧠 Lo que aprendí en el proceso

**Sobre los datos de salud**

- 📏 Hay que comparar **tasas**, no casos: Chile, EE.UU. y Europa tienen poblaciones muy distintas.
- 🔬 Más diagnósticos no siempre significa más transmisión: a veces significa que se testea más.
- 📭 Lo que no se mide no se ve: solo 4 de 10 ITS se vigilan en Chile y el último dato de embarazo no planificado es de 2010.
- 🎯 Un método puede ser muy eficaz y aun así fallar en la vida real: por eso muestro uso típico y uso perfecto.
- ⏱️ En cáncer la etapa lo cambia todo: el mismo cáncer de mama tiene 99% o 32% de sobrevida según cuándo se detecta.

**Sobre las herramientas**

- 🧩 Ordenar primero la base de datos hace que Power BI y Tableau muestren lo mismo y se puedan actualizar.
- 🎛️ Un simulador con supuestos explícitos ayuda a conversar sobre políticas sin presentar una proyección como si fuera oficial.
- 💬 Escribir para cualquier persona, no solo para profesionales de salud, obliga a explicar cada número.

---

## 🗂️ Los cinco tableros

| Vista | Tablero | Pregunta que responde | KPI destacados |
|:---:|---|---|---|
| <a href="#anticonceptivos"><img src="recursos/mini_anticonceptivos.png" width="140"></a> | 💊 [Anticonceptivos en Chile](dashboard-anticonceptivos-chile/) | ¿Qué método me sirve y qué tan eficaz es? | Tasa de falla en uso típico · riesgo de trombosis · elegibilidad OMS/CDC · uso de métodos en Chile |
| <a href="#its"><img src="recursos/mini_its.png" width="140"></a> | 🩺 [ITS en Chile](dashboard-its-chile/) | ¿Están aumentando las ITS y dónde está Chile frente al mundo? | 10 ITS · tasa por 100 mil · cascada VIH 95-95-95 · sífilis congénita |
| <a href="#embarazo"><img src="recursos/mini_embarazo.png" width="140"></a> | 🤰 [Embarazo y matronería](dashboard-embarazo-matronas-chile/) | ¿Qué pasa con el embarazo adolescente y las matronas? | Fecundidad de 15 a 19 (ODS 3.7.2) · mortalidad materna (ODS 3.1.1) · matronas por habitante |
| <a href="#ajuar"><img src="recursos/mini_ajuar.png" width="140"></a> | 🍼 [Ajuar Chile Crece Contigo](dashboard-ajuar-chile-crece-contigo/) | ¿Llega el ajuar a todas las guaguas y por qué importa? | Cobertura · costo por set · ejecución presupuestaria |
| <a href="#cancer"><img src="recursos/mini_cancer.png" width="140"></a> | 🎗️ [Cáncer en Chile](dashboard-cancer-chile/) | ¿Cuánto aumenta el cáncer y cómo le ganamos? | Incidencia · razón mortalidad/incidencia · cobertura de tamizaje |

---

<a id="anticonceptivos"></a>

## 💊 Anticonceptivos en Chile

**¿Qué método me sirve y qué tan eficaz es?** · Tasa de falla en uso típico · riesgo de trombosis · elegibilidad OMS/CDC · uso de métodos en Chile

<p align="center"><a href="dashboard-anticonceptivos-chile/capturas/01_resumen_rapido.png"><img src="dashboard-anticonceptivos-chile/capturas/01_resumen_rapido.png" width="820" alt="Anticonceptivos en Chile"></a></p>

🔍 **Qué investigué.** Comparé la eficacia de cada método en uso típico y perfecto, sus riesgos (trombosis, cáncer), los criterios de elegibilidad OMS/CDC 2024 en 73 condiciones, las interacciones con medicamentos y cómo se usan los métodos en Chile.

💡 **Lo que observé**

- 🎯 El implante y el DIU hormonal tienen 0,1 embarazos por 100 mujeres al año; la píldora, 7 en uso típico: la diferencia no es el método sino los olvidos.
- 🧒 Solo 8,8% de las adolescentes inicia con implante o DIU; 2 de cada 3 parten con píldora o inyectable.
- 🛡️ Los métodos combinados tienen 37 condiciones que los desaconsejan; el implante, 6, y el DIU de cobre, 5.
- 💊 14 de 21 medicamentos o situaciones revisadas bajan la eficacia de algún método; ninguna afecta al DIU ni al condón.
- 🩸 El riesgo de trombosis de la píldora con levonorgestrel (5 a 7 por 10.000) es menor que el del embarazo (5 a 20) y el posparto (40 a 65).

> 🎯 **Lo que concluyo:** Elegir bien es más importante que elegir cualquier método: ofrecer primero los métodos de larga duración, sobre todo a adolescentes, es la medida con más impacto.

**📊 Todas las páginas en Power BI** (13) · haz clic para ampliar

<table>
<tr><td align="center" valign="top"><a href="dashboard-anticonceptivos-chile/capturas/01_resumen_rapido.png"><img src="dashboard-anticonceptivos-chile/capturas/mini/01_resumen_rapido.png" width="200" alt="📊 Resumen rápido"></a><br><sub>📊 Resumen rápido</sub></td><td align="center" valign="top"><a href="dashboard-anticonceptivos-chile/capturas/02_metodos_larga_duracion.png"><img src="dashboard-anticonceptivos-chile/capturas/mini/02_metodos_larga_duracion.png" width="200" alt="🌱 Métodos 1: larga duración"></a><br><sub>🌱 Métodos 1: larga duración</sub></td><td align="center" valign="top"><a href="dashboard-anticonceptivos-chile/capturas/03_metodos_corta_duracion.png"><img src="dashboard-anticonceptivos-chile/capturas/mini/03_metodos_corta_duracion.png" width="200" alt="💊 Métodos 2: corta duración"></a><br><sub>💊 Métodos 2: corta duración</sub></td><td align="center" valign="top"><a href="dashboard-anticonceptivos-chile/capturas/04_eficacia.png"><img src="dashboard-anticonceptivos-chile/capturas/mini/04_eficacia.png" width="200" alt="🎯 Eficacia"></a><br><sub>🎯 Eficacia</sub></td></tr>
<tr><td align="center" valign="top"><a href="dashboard-anticonceptivos-chile/capturas/05_seguridad.png"><img src="dashboard-anticonceptivos-chile/capturas/mini/05_seguridad.png" width="200" alt="🛡️ Seguridad"></a><br><sub>🛡️ Seguridad</sub></td><td align="center" valign="top"><a href="dashboard-anticonceptivos-chile/capturas/06_beneficios.png"><img src="dashboard-anticonceptivos-chile/capturas/mini/06_beneficios.png" width="200" alt="✨ Beneficios"></a><br><sub>✨ Beneficios</sub></td><td align="center" valign="top"><a href="dashboard-anticonceptivos-chile/capturas/07_mi_pastilla.png"><img src="dashboard-anticonceptivos-chile/capturas/mini/07_mi_pastilla.png" width="200" alt="🔎 Mi pastilla"></a><br><sub>🔎 Mi pastilla</sub></td><td align="center" valign="top"><a href="dashboard-anticonceptivos-chile/capturas/08_segun_tu_condicion.png"><img src="dashboard-anticonceptivos-chile/capturas/mini/08_segun_tu_condicion.png" width="200" alt="🩺 Según tu condición"></a><br><sub>🩺 Según tu condición</sub></td></tr>
<tr><td align="center" valign="top"><a href="dashboard-anticonceptivos-chile/capturas/09_hormonas.png"><img src="dashboard-anticonceptivos-chile/capturas/mini/09_hormonas.png" width="200" alt="🧬 Hormonas"></a><br><sub>🧬 Hormonas</sub></td><td align="center" valign="top"><a href="dashboard-anticonceptivos-chile/capturas/10_puedo_usarlo.png"><img src="dashboard-anticonceptivos-chile/capturas/mini/10_puedo_usarlo.png" width="200" alt="✅ ¿Puedo usarlo?"></a><br><sub>✅ ¿Puedo usarlo?</sub></td><td align="center" valign="top"><a href="dashboard-anticonceptivos-chile/capturas/11_que_baja_la_eficacia.png"><img src="dashboard-anticonceptivos-chile/capturas/mini/11_que_baja_la_eficacia.png" width="200" alt="⚠️ ¿Qué baja la eficacia?"></a><br><sub>⚠️ ¿Qué baja la eficacia?</sub></td><td align="center" valign="top"><a href="dashboard-anticonceptivos-chile/capturas/12_chile.png"><img src="dashboard-anticonceptivos-chile/capturas/mini/12_chile.png" width="200" alt="🇨🇱 Chile"></a><br><sub>🇨🇱 Chile</sub></td></tr>
<tr><td align="center" valign="top"><a href="dashboard-anticonceptivos-chile/capturas/13_que_mide_cada_kpi.png"><img src="dashboard-anticonceptivos-chile/capturas/mini/13_que_mide_cada_kpi.png" width="200" alt="📐 Qué mide cada KPI"></a><br><sub>📐 Qué mide cada KPI</sub></td></tr>
</table>

<details><summary>🎨 <b>Ver en Tableau</b> (mismas páginas)</summary>

<table>
<tr><td align="center" valign="top"><a href="dashboard-anticonceptivos-chile/capturas/tableau/01_resumen_rapido.png"><img src="dashboard-anticonceptivos-chile/capturas/tableau/01_resumen_rapido.png" width="200" alt="📊 Resumen rápido"></a><br><sub>📊 Resumen rápido</sub></td><td align="center" valign="top"><a href="dashboard-anticonceptivos-chile/capturas/tableau/02_metodos_larga_duracion.png"><img src="dashboard-anticonceptivos-chile/capturas/tableau/02_metodos_larga_duracion.png" width="200" alt="🌱 Métodos 1: larga duración"></a><br><sub>🌱 Métodos 1: larga duración</sub></td><td align="center" valign="top"><a href="dashboard-anticonceptivos-chile/capturas/tableau/03_metodos_corta_duracion.png"><img src="dashboard-anticonceptivos-chile/capturas/tableau/03_metodos_corta_duracion.png" width="200" alt="💊 Métodos 2: corta duración"></a><br><sub>💊 Métodos 2: corta duración</sub></td><td align="center" valign="top"><a href="dashboard-anticonceptivos-chile/capturas/tableau/04_eficacia.png"><img src="dashboard-anticonceptivos-chile/capturas/tableau/04_eficacia.png" width="200" alt="🎯 Eficacia"></a><br><sub>🎯 Eficacia</sub></td></tr>
<tr><td align="center" valign="top"><a href="dashboard-anticonceptivos-chile/capturas/tableau/05_seguridad.png"><img src="dashboard-anticonceptivos-chile/capturas/tableau/05_seguridad.png" width="200" alt="🛡️ Seguridad"></a><br><sub>🛡️ Seguridad</sub></td><td align="center" valign="top"><a href="dashboard-anticonceptivos-chile/capturas/tableau/06_beneficios.png"><img src="dashboard-anticonceptivos-chile/capturas/tableau/06_beneficios.png" width="200" alt="✨ Beneficios"></a><br><sub>✨ Beneficios</sub></td><td align="center" valign="top"><a href="dashboard-anticonceptivos-chile/capturas/tableau/07_mi_pastilla.png"><img src="dashboard-anticonceptivos-chile/capturas/tableau/07_mi_pastilla.png" width="200" alt="🔎 Mi pastilla"></a><br><sub>🔎 Mi pastilla</sub></td><td align="center" valign="top"><a href="dashboard-anticonceptivos-chile/capturas/tableau/08_segun_tu_condicion.png"><img src="dashboard-anticonceptivos-chile/capturas/tableau/08_segun_tu_condicion.png" width="200" alt="🩺 Según tu condición"></a><br><sub>🩺 Según tu condición</sub></td></tr>
<tr><td align="center" valign="top"><a href="dashboard-anticonceptivos-chile/capturas/tableau/09_hormonas.png"><img src="dashboard-anticonceptivos-chile/capturas/tableau/09_hormonas.png" width="200" alt="🧬 Hormonas"></a><br><sub>🧬 Hormonas</sub></td><td align="center" valign="top"><a href="dashboard-anticonceptivos-chile/capturas/tableau/10_puedo_usarlo.png"><img src="dashboard-anticonceptivos-chile/capturas/tableau/10_puedo_usarlo.png" width="200" alt="✅ ¿Puedo usarlo?"></a><br><sub>✅ ¿Puedo usarlo?</sub></td><td align="center" valign="top"><a href="dashboard-anticonceptivos-chile/capturas/tableau/11_que_baja_la_eficacia.png"><img src="dashboard-anticonceptivos-chile/capturas/tableau/11_que_baja_la_eficacia.png" width="200" alt="⚠️ ¿Qué baja la eficacia?"></a><br><sub>⚠️ ¿Qué baja la eficacia?</sub></td><td align="center" valign="top"><a href="dashboard-anticonceptivos-chile/capturas/tableau/12_chile.png"><img src="dashboard-anticonceptivos-chile/capturas/tableau/12_chile.png" width="200" alt="🇨🇱 Chile"></a><br><sub>🇨🇱 Chile</sub></td></tr>
<tr><td align="center" valign="top"><a href="dashboard-anticonceptivos-chile/capturas/tableau/13_que_mide_cada_kpi.png"><img src="dashboard-anticonceptivos-chile/capturas/tableau/13_que_mide_cada_kpi.png" width="200" alt="📐 Qué mide cada KPI"></a><br><sub>📐 Qué mide cada KPI</sub></td></tr>
</table>

</details>

<p>📖 <a href="dashboard-anticonceptivos-chile/">README del tablero</a> &nbsp;·&nbsp; 📥 <a href="dashboard-anticonceptivos-chile/Anticonceptivos_MariaCisterna.pbix">Power BI (.pbix)</a> &nbsp;·&nbsp; 📥 <a href="dashboard-anticonceptivos-chile/Anticonceptivos_MariaCisterna.twbx">Tableau (.twbx)</a> &nbsp;·&nbsp; 🗂️ <a href="dashboard-anticonceptivos-chile/Anticonceptivos_BaseDatos.xlsx">Base de datos</a> &nbsp;·&nbsp; <a href="#inicio">⬆️ Volver arriba</a></p>

---

<a id="its"></a>

## 🩺 ITS en Chile

**¿Están aumentando las ITS y dónde está Chile frente al mundo?** · 10 ITS · tasa por 100 mil · cascada VIH 95-95-95 · sífilis congénita

<p align="center"><a href="dashboard-its-chile/capturas/01_resumen.png"><img src="dashboard-its-chile/capturas/01_resumen.png" width="820" alt="ITS en Chile"></a></p>

🔍 **Qué investigué.** Revisé los boletines de vigilancia del MINSAL y el ISP, la cascada de VIH de ONUSIDA y comparé Chile con Estados Unidos y la Unión Europea. También revisé qué ITS se vigilan en Chile y cuáles no.

💡 **Lo que observé**

- 📈 La sífilis subió 64% desde 2020 y llegó a 55,2 por 100 mil en 2025: casi igual a EE.UU. (62,5) y 5 veces Europa (10,8).
- 🔴 VIH: 95% de las personas conoce su diagnóstico, pero solo 71% está en tratamiento; 21.915 personas diagnosticadas no lo reciben.
- 🔬 Solo 4 de las 10 ITS revisadas son de notificación obligatoria; clamidia, VPH, herpes y tricomoniasis casi no tienen datos en Chile.
- 👥 La sífilis se concentra entre los 20 y 29 años y la gonorrea crece más rápido en mujeres.

> 🎯 **Lo que concluyo:** Las ITS van en sentido contrario al embarazo adolescente: hace falta más testeo, tratamiento oportuno y uso de condón, y medir las ITS que hoy no se vigilan.

**📊 Todas las páginas en Power BI** (8) · haz clic para ampliar

<table>
<tr><td align="center" valign="top"><a href="dashboard-its-chile/capturas/01_resumen.png"><img src="dashboard-its-chile/capturas/mini/01_resumen.png" width="200" alt="📊 Resumen"></a><br><sub>📊 Resumen</sub></td><td align="center" valign="top"><a href="dashboard-its-chile/capturas/02_tendencias.png"><img src="dashboard-its-chile/capturas/mini/02_tendencias.png" width="200" alt="📈 Tendencias"></a><br><sub>📈 Tendencias</sub></td><td align="center" valign="top"><a href="dashboard-its-chile/capturas/03_a_quienes_afecta.png"><img src="dashboard-its-chile/capturas/mini/03_a_quienes_afecta.png" width="200" alt="👥 ¿A quiénes afecta?"></a><br><sub>👥 ¿A quiénes afecta?</sub></td><td align="center" valign="top"><a href="dashboard-its-chile/capturas/04_chile_y_el_mundo.png"><img src="dashboard-its-chile/capturas/mini/04_chile_y_el_mundo.png" width="200" alt="🌍 Chile y el mundo"></a><br><sub>🌍 Chile y el mundo</sub></td></tr>
<tr><td align="center" valign="top"><a href="dashboard-its-chile/capturas/04b_todas_las_its.png"><img src="dashboard-its-chile/capturas/mini/04b_todas_las_its.png" width="200" alt="🧪 Todas las ITS"></a><br><sub>🧪 Todas las ITS</sub></td><td align="center" valign="top"><a href="dashboard-its-chile/capturas/05_guia_de_cada_its.png"><img src="dashboard-its-chile/capturas/mini/05_guia_de_cada_its.png" width="200" alt="📖 Guía de cada ITS"></a><br><sub>📖 Guía de cada ITS</sub></td><td align="center" valign="top"><a href="dashboard-its-chile/capturas/06_simulador_matronas_en_colegios.png"><img src="dashboard-its-chile/capturas/mini/06_simulador_matronas_en_colegios.png" width="200" alt="🏫 Simulador: matronas en colegios"></a><br><sub>🏫 Simulador: matronas en colegios</sub></td><td align="center" valign="top"><a href="dashboard-its-chile/capturas/07_que_mide_cada_kpi.png"><img src="dashboard-its-chile/capturas/mini/07_que_mide_cada_kpi.png" width="200" alt="📐 Qué mide cada KPI"></a><br><sub>📐 Qué mide cada KPI</sub></td></tr>
</table>

<details><summary>🎨 <b>Ver en Tableau</b> (mismas páginas)</summary>

<table>
<tr><td align="center" valign="top"><a href="dashboard-its-chile/capturas/tableau/01_resumen.png"><img src="dashboard-its-chile/capturas/tableau/01_resumen.png" width="200" alt="📊 Resumen"></a><br><sub>📊 Resumen</sub></td><td align="center" valign="top"><a href="dashboard-its-chile/capturas/tableau/02_tendencias.png"><img src="dashboard-its-chile/capturas/tableau/02_tendencias.png" width="200" alt="📈 Tendencias"></a><br><sub>📈 Tendencias</sub></td><td align="center" valign="top"><a href="dashboard-its-chile/capturas/tableau/03_a_quienes_afecta.png"><img src="dashboard-its-chile/capturas/tableau/03_a_quienes_afecta.png" width="200" alt="👥 ¿A quiénes afecta?"></a><br><sub>👥 ¿A quiénes afecta?</sub></td><td align="center" valign="top"><a href="dashboard-its-chile/capturas/tableau/04_chile_y_el_mundo.png"><img src="dashboard-its-chile/capturas/tableau/04_chile_y_el_mundo.png" width="200" alt="🌍 Chile y el mundo"></a><br><sub>🌍 Chile y el mundo</sub></td></tr>
<tr><td align="center" valign="top"><a href="dashboard-its-chile/capturas/tableau/04b_todas_las_its.png"><img src="dashboard-its-chile/capturas/tableau/04b_todas_las_its.png" width="200" alt="🧪 Todas las ITS"></a><br><sub>🧪 Todas las ITS</sub></td><td align="center" valign="top"><a href="dashboard-its-chile/capturas/tableau/05_guia_de_cada_its.png"><img src="dashboard-its-chile/capturas/tableau/05_guia_de_cada_its.png" width="200" alt="📖 Guía de cada ITS"></a><br><sub>📖 Guía de cada ITS</sub></td><td align="center" valign="top"><a href="dashboard-its-chile/capturas/tableau/06_simulador_matronas_en_colegios.png"><img src="dashboard-its-chile/capturas/tableau/06_simulador_matronas_en_colegios.png" width="200" alt="🏫 Simulador: matronas en colegios"></a><br><sub>🏫 Simulador: matronas en colegios</sub></td><td align="center" valign="top"><a href="dashboard-its-chile/capturas/tableau/07_que_mide_cada_kpi.png"><img src="dashboard-its-chile/capturas/tableau/07_que_mide_cada_kpi.png" width="200" alt="📐 Qué mide cada KPI"></a><br><sub>📐 Qué mide cada KPI</sub></td></tr>
</table>

</details>

<p>📖 <a href="dashboard-its-chile/">README del tablero</a> &nbsp;·&nbsp; 📥 <a href="dashboard-its-chile/ITS_Chile_MariaCisterna.pbix">Power BI (.pbix)</a> &nbsp;·&nbsp; 📥 <a href="dashboard-its-chile/ITS_Chile_MariaCisterna.twbx">Tableau (.twbx)</a> &nbsp;·&nbsp; 🗂️ <a href="dashboard-its-chile/ITS_Chile_BaseDatos.xlsx">Base de datos</a> &nbsp;·&nbsp; <a href="#inicio">⬆️ Volver arriba</a></p>

---

<a id="embarazo"></a>

## 🤰 Embarazo y matronería

**¿Qué pasa con el embarazo adolescente y las matronas?** · Fecundidad de 15 a 19 (ODS 3.7.2) · mortalidad materna (ODS 3.1.1) · matronas por habitante

<p align="center"><a href="dashboard-embarazo-matronas-chile/capturas/01_resumen.png"><img src="dashboard-embarazo-matronas-chile/capturas/01_resumen.png" width="820" alt="Embarazo y matronería"></a></p>

🔍 **Qué investigué.** Usé estadísticas vitales del INE y DEIS, el Registro Nacional de Prestadores de la Superintendencia de Salud, estimaciones de ONU/OMS de mortalidad materna y la evidencia Cochrane sobre la continuidad de atención por matronas.

💡 **Lo que observé**

- 👧 La fecundidad de 15 a 19 años bajó de 23,2 a 8,3 por mil entre 2018 y 2025: cayó a un tercio.
- ⚠️ Aún nacen 146 guaguas al año de madres de 10 a 14 años: todo embarazo a esa edad debe investigarse.
- 🩺 Las matronas inscritas crecieron de 13.723 a 23.333 (+70%) entre 2018 y 2025.
- ❤️ La mortalidad materna de Chile (10 por 100 mil nacidos vivos) es de las más bajas de la región.
- 📭 El último dato nacional de embarazo no planificado es de 2010.

> 🎯 **Lo que concluyo:** La prevención funciona y Chile tiene más matronas que nunca: el desafío es ponerlas donde está la prevención, como los colegios, y volver a medir el embarazo no planificado.

**📊 Todas las páginas en Power BI** (8) · haz clic para ampliar

<table>
<tr><td align="center" valign="top"><a href="dashboard-embarazo-matronas-chile/capturas/01_resumen.png"><img src="dashboard-embarazo-matronas-chile/capturas/mini/01_resumen.png" width="200" alt="📊 Resumen"></a><br><sub>📊 Resumen</sub></td><td align="center" valign="top"><a href="dashboard-embarazo-matronas-chile/capturas/02_embarazo_adolescente.png"><img src="dashboard-embarazo-matronas-chile/capturas/mini/02_embarazo_adolescente.png" width="200" alt="👧 Embarazo adolescente"></a><br><sub>👧 Embarazo adolescente</sub></td><td align="center" valign="top"><a href="dashboard-embarazo-matronas-chile/capturas/03_matronas_en_chile.png"><img src="dashboard-embarazo-matronas-chile/capturas/mini/03_matronas_en_chile.png" width="200" alt="🩺 Matronas en Chile"></a><br><sub>🩺 Matronas en Chile</sub></td><td align="center" valign="top"><a href="dashboard-embarazo-matronas-chile/capturas/04_mortalidad_materna_y_neonatal.png"><img src="dashboard-embarazo-matronas-chile/capturas/mini/04_mortalidad_materna_y_neonatal.png" width="200" alt="❤️ Mortalidad materna y neonatal"></a><br><sub>❤️ Mortalidad materna y neonatal</sub></td></tr>
<tr><td align="center" valign="top"><a href="dashboard-embarazo-matronas-chile/capturas/05_lo_que_dice_la_evidencia.png"><img src="dashboard-embarazo-matronas-chile/capturas/mini/05_lo_que_dice_la_evidencia.png" width="200" alt="🔬 Lo que dice la evidencia"></a><br><sub>🔬 Lo que dice la evidencia</sub></td><td align="center" valign="top"><a href="dashboard-embarazo-matronas-chile/capturas/06_propuestas.png"><img src="dashboard-embarazo-matronas-chile/capturas/mini/06_propuestas.png" width="200" alt="💡 Propuestas"></a><br><sub>💡 Propuestas</sub></td><td align="center" valign="top"><a href="dashboard-embarazo-matronas-chile/capturas/07_simulador_matronas_en_colegios.png"><img src="dashboard-embarazo-matronas-chile/capturas/mini/07_simulador_matronas_en_colegios.png" width="200" alt="🏫 Simulador: matronas en colegios"></a><br><sub>🏫 Simulador: matronas en colegios</sub></td><td align="center" valign="top"><a href="dashboard-embarazo-matronas-chile/capturas/08_que_mide_cada_kpi.png"><img src="dashboard-embarazo-matronas-chile/capturas/mini/08_que_mide_cada_kpi.png" width="200" alt="📐 Qué mide cada KPI"></a><br><sub>📐 Qué mide cada KPI</sub></td></tr>
</table>

<details><summary>🎨 <b>Ver en Tableau</b> (mismas páginas)</summary>

<table>
<tr><td align="center" valign="top"><a href="dashboard-embarazo-matronas-chile/capturas/tableau/01_resumen.png"><img src="dashboard-embarazo-matronas-chile/capturas/tableau/01_resumen.png" width="200" alt="📊 Resumen"></a><br><sub>📊 Resumen</sub></td><td align="center" valign="top"><a href="dashboard-embarazo-matronas-chile/capturas/tableau/02_embarazo_adolescente.png"><img src="dashboard-embarazo-matronas-chile/capturas/tableau/02_embarazo_adolescente.png" width="200" alt="👧 Embarazo adolescente"></a><br><sub>👧 Embarazo adolescente</sub></td><td align="center" valign="top"><a href="dashboard-embarazo-matronas-chile/capturas/tableau/03_matronas_en_chile.png"><img src="dashboard-embarazo-matronas-chile/capturas/tableau/03_matronas_en_chile.png" width="200" alt="🩺 Matronas en Chile"></a><br><sub>🩺 Matronas en Chile</sub></td><td align="center" valign="top"><a href="dashboard-embarazo-matronas-chile/capturas/tableau/04_mortalidad_materna_y_neonatal.png"><img src="dashboard-embarazo-matronas-chile/capturas/tableau/04_mortalidad_materna_y_neonatal.png" width="200" alt="❤️ Mortalidad materna y neonatal"></a><br><sub>❤️ Mortalidad materna y neonatal</sub></td></tr>
<tr><td align="center" valign="top"><a href="dashboard-embarazo-matronas-chile/capturas/tableau/05_lo_que_dice_la_evidencia.png"><img src="dashboard-embarazo-matronas-chile/capturas/tableau/05_lo_que_dice_la_evidencia.png" width="200" alt="🔬 Lo que dice la evidencia"></a><br><sub>🔬 Lo que dice la evidencia</sub></td><td align="center" valign="top"><a href="dashboard-embarazo-matronas-chile/capturas/tableau/06_propuestas.png"><img src="dashboard-embarazo-matronas-chile/capturas/tableau/06_propuestas.png" width="200" alt="💡 Propuestas"></a><br><sub>💡 Propuestas</sub></td><td align="center" valign="top"><a href="dashboard-embarazo-matronas-chile/capturas/tableau/07_simulador_matronas_en_colegios.png"><img src="dashboard-embarazo-matronas-chile/capturas/tableau/07_simulador_matronas_en_colegios.png" width="200" alt="🏫 Simulador: matronas en colegios"></a><br><sub>🏫 Simulador: matronas en colegios</sub></td><td align="center" valign="top"><a href="dashboard-embarazo-matronas-chile/capturas/tableau/08_que_mide_cada_kpi.png"><img src="dashboard-embarazo-matronas-chile/capturas/tableau/08_que_mide_cada_kpi.png" width="200" alt="📐 Qué mide cada KPI"></a><br><sub>📐 Qué mide cada KPI</sub></td></tr>
</table>

</details>

<p>📖 <a href="dashboard-embarazo-matronas-chile/">README del tablero</a> &nbsp;·&nbsp; 📥 <a href="dashboard-embarazo-matronas-chile/Embarazo_Matronas_MariaCisterna.pbix">Power BI (.pbix)</a> &nbsp;·&nbsp; 📥 <a href="dashboard-embarazo-matronas-chile/Embarazo_Matronas_MariaCisterna.twbx">Tableau (.twbx)</a> &nbsp;·&nbsp; 🗂️ <a href="dashboard-embarazo-matronas-chile/Embarazo_Matronas_BaseDatos.xlsx">Base de datos</a> &nbsp;·&nbsp; <a href="#inicio">⬆️ Volver arriba</a></p>

---

<a id="ajuar"></a>

## 🍼 Ajuar Chile Crece Contigo

**¿Llega el ajuar a todas las guaguas y por qué importa?** · Cobertura · costo por set · ejecución presupuestaria

<p align="center"><a href="dashboard-ajuar-chile-crece-contigo/capturas/01_resumen.png"><img src="dashboard-ajuar-chile-crece-contigo/capturas/01_resumen.png" width="820" alt="Ajuar Chile Crece Contigo"></a></p>

🔍 **Qué investigué.** Revisé las evaluaciones de DIPRES, la glosa presupuestaria del MINSAL, Cenabast, Chile Crece Contigo y los nacidos vivos del INE para entender cuánto llega el ajuar y cuánto cuesta.

💡 **Lo que observé**

- 🍼 Entre 97% y 99% de las guaguas que nacen en la red pública recibe el set (2019–2022).
- 📉 Los sets entregados bajan (141.883 en 2018, 113.858 en 2022) porque nacen menos guaguas, no porque falle el programa.
- 💰 Cada set cuesta cerca de $67.480 y la ejecución del presupuesto fue 85% en 2018; en 2026 el presupuesto bajó 10,5%.
- 🎓 95,5% de las madres participa en el taller educativo, donde aprende sueño seguro, lactancia y cuidados.

> 🎯 **Lo que concluyo:** El ajuar llega a casi todas las familias de la red pública; cuidar la cadena de compra y el taller es lo que mantiene ese logro.

**📊 Todas las páginas en Power BI** (7) · haz clic para ampliar

<table>
<tr><td align="center" valign="top"><a href="dashboard-ajuar-chile-crece-contigo/capturas/01_resumen.png"><img src="dashboard-ajuar-chile-crece-contigo/capturas/mini/01_resumen.png" width="200" alt="📊 Resumen"></a><br><sub>📊 Resumen</sub></td><td align="center" valign="top"><a href="dashboard-ajuar-chile-crece-contigo/capturas/02_entregas_y_cobertura.png"><img src="dashboard-ajuar-chile-crece-contigo/capturas/mini/02_entregas_y_cobertura.png" width="200" alt="📦 Entregas y cobertura"></a><br><sub>📦 Entregas y cobertura</sub></td><td align="center" valign="top"><a href="dashboard-ajuar-chile-crece-contigo/capturas/03_presupuesto.png"><img src="dashboard-ajuar-chile-crece-contigo/capturas/mini/03_presupuesto.png" width="200" alt="💰 Presupuesto"></a><br><sub>💰 Presupuesto</sub></td><td align="center" valign="top"><a href="dashboard-ajuar-chile-crece-contigo/capturas/04_cadena_logistica.png"><img src="dashboard-ajuar-chile-crece-contigo/capturas/mini/04_cadena_logistica.png" width="200" alt="🔗 Cadena logística"></a><br><sub>🔗 Cadena logística</sub></td></tr>
<tr><td align="center" valign="top"><a href="dashboard-ajuar-chile-crece-contigo/capturas/05_que_contiene.png"><img src="dashboard-ajuar-chile-crece-contigo/capturas/mini/05_que_contiene.png" width="200" alt="🎁 ¿Qué contiene?"></a><br><sub>🎁 ¿Qué contiene?</sub></td><td align="center" valign="top"><a href="dashboard-ajuar-chile-crece-contigo/capturas/06_por_que_es_importante.png"><img src="dashboard-ajuar-chile-crece-contigo/capturas/mini/06_por_que_es_importante.png" width="200" alt="💜 ¿Por qué es importante?"></a><br><sub>💜 ¿Por qué es importante?</sub></td><td align="center" valign="top"><a href="dashboard-ajuar-chile-crece-contigo/capturas/07_que_mide_cada_kpi.png"><img src="dashboard-ajuar-chile-crece-contigo/capturas/mini/07_que_mide_cada_kpi.png" width="200" alt="📐 Qué mide cada KPI"></a><br><sub>📐 Qué mide cada KPI</sub></td></tr>
</table>

<details><summary>🎨 <b>Ver en Tableau</b> (mismas páginas)</summary>

<table>
<tr><td align="center" valign="top"><a href="dashboard-ajuar-chile-crece-contigo/capturas/tableau/01_resumen.png"><img src="dashboard-ajuar-chile-crece-contigo/capturas/tableau/01_resumen.png" width="200" alt="📊 Resumen"></a><br><sub>📊 Resumen</sub></td><td align="center" valign="top"><a href="dashboard-ajuar-chile-crece-contigo/capturas/tableau/02_entregas_y_cobertura.png"><img src="dashboard-ajuar-chile-crece-contigo/capturas/tableau/02_entregas_y_cobertura.png" width="200" alt="📦 Entregas y cobertura"></a><br><sub>📦 Entregas y cobertura</sub></td><td align="center" valign="top"><a href="dashboard-ajuar-chile-crece-contigo/capturas/tableau/03_presupuesto.png"><img src="dashboard-ajuar-chile-crece-contigo/capturas/tableau/03_presupuesto.png" width="200" alt="💰 Presupuesto"></a><br><sub>💰 Presupuesto</sub></td><td align="center" valign="top"><a href="dashboard-ajuar-chile-crece-contigo/capturas/tableau/04_cadena_logistica.png"><img src="dashboard-ajuar-chile-crece-contigo/capturas/tableau/04_cadena_logistica.png" width="200" alt="🔗 Cadena logística"></a><br><sub>🔗 Cadena logística</sub></td></tr>
<tr><td align="center" valign="top"><a href="dashboard-ajuar-chile-crece-contigo/capturas/tableau/05_que_contiene.png"><img src="dashboard-ajuar-chile-crece-contigo/capturas/tableau/05_que_contiene.png" width="200" alt="🎁 ¿Qué contiene?"></a><br><sub>🎁 ¿Qué contiene?</sub></td><td align="center" valign="top"><a href="dashboard-ajuar-chile-crece-contigo/capturas/tableau/06_por_que_es_importante.png"><img src="dashboard-ajuar-chile-crece-contigo/capturas/tableau/06_por_que_es_importante.png" width="200" alt="💜 ¿Por qué es importante?"></a><br><sub>💜 ¿Por qué es importante?</sub></td><td align="center" valign="top"><a href="dashboard-ajuar-chile-crece-contigo/capturas/tableau/07_que_mide_cada_kpi.png"><img src="dashboard-ajuar-chile-crece-contigo/capturas/tableau/07_que_mide_cada_kpi.png" width="200" alt="📐 Qué mide cada KPI"></a><br><sub>📐 Qué mide cada KPI</sub></td></tr>
</table>

</details>

<p>📖 <a href="dashboard-ajuar-chile-crece-contigo/">README del tablero</a> &nbsp;·&nbsp; 📥 <a href="dashboard-ajuar-chile-crece-contigo/Ajuar_PARN_MariaCisterna.pbix">Power BI (.pbix)</a> &nbsp;·&nbsp; 📥 <a href="dashboard-ajuar-chile-crece-contigo/Ajuar_PARN_MariaCisterna.twbx">Tableau (.twbx)</a> &nbsp;·&nbsp; 🗂️ <a href="dashboard-ajuar-chile-crece-contigo/Ajuar_PARN_BaseDatos.xlsx">Base de datos</a> &nbsp;·&nbsp; <a href="#inicio">⬆️ Volver arriba</a></p>

---

<a id="cancer"></a>

## 🎗️ Cáncer en Chile

**¿Cuánto aumenta el cáncer y cómo le ganamos?** · Incidencia · razón mortalidad/incidencia · cobertura de tamizaje

<p align="center"><a href="dashboard-cancer-chile/capturas/01_resumen.png"><img src="dashboard-cancer-chile/capturas/01_resumen.png" width="820" alt="Cáncer en Chile"></a></p>

🔍 **Qué investigué.** Usé las defunciones del DEIS, las estimaciones de GLOBOCAN (IARC), la Encuesta Nacional de Salud y datos de cobertura de mamografía, PAP y vacuna VPH, además de la sobrevida por etapa.

💡 **Lo que observé**

- 🎗️ En 2024 hubo cerca de 59.887 casos nuevos y el cáncer causa 1 de cada 4 muertes en Chile.
- 📈 Las muertes por cáncer aumentaron 71% entre 2001 y 2024, en parte por el envejecimiento de la población.
- 🔍 Solo 37,4% de las mujeres de 50 a 69 años tiene su mamografía al día; la meta es 70%.
- ⏱️ Cáncer de mama detectado localizado: 99% de sobrevida a 5 años; con metástasis: 32%.
- 🛡️ Cerca de 37,8% de los cánceres se asocia a factores que se pueden modificar.

> 🎯 **Lo que concluyo:** En cáncer, llegar a tiempo cambia todo: subir la pesquisa (mamografía, PAP, test VPH) y completar la vacuna VPH es lo que más vidas salva.

**📊 Todas las páginas en Power BI** (9) · haz clic para ampliar

<table>
<tr><td align="center" valign="top"><a href="dashboard-cancer-chile/capturas/01_resumen.png"><img src="dashboard-cancer-chile/capturas/mini/01_resumen.png" width="200" alt="📊 Resumen"></a><br><sub>📊 Resumen</sub></td><td align="center" valign="top"><a href="dashboard-cancer-chile/capturas/02_esta_aumentando.png"><img src="dashboard-cancer-chile/capturas/mini/02_esta_aumentando.png" width="200" alt="📈 ¿Está aumentando?"></a><br><sub>📈 ¿Está aumentando?</sub></td><td align="center" valign="top"><a href="dashboard-cancer-chile/capturas/03_cual_predomina.png"><img src="dashboard-cancer-chile/capturas/mini/03_cual_predomina.png" width="200" alt="⚖️ ¿Cuál predomina?"></a><br><sub>⚖️ ¿Cuál predomina?</sub></td><td align="center" valign="top"><a href="dashboard-cancer-chile/capturas/04_como_prevenirlo.png"><img src="dashboard-cancer-chile/capturas/mini/04_como_prevenirlo.png" width="200" alt="🛡️ Cómo prevenirlo"></a><br><sub>🛡️ Cómo prevenirlo</sub></td></tr>
<tr><td align="center" valign="top"><a href="dashboard-cancer-chile/capturas/05_chile_y_el_mundo.png"><img src="dashboard-cancer-chile/capturas/mini/05_chile_y_el_mundo.png" width="200" alt="🌍 Chile y el mundo"></a><br><sub>🌍 Chile y el mundo</sub></td><td align="center" valign="top"><a href="dashboard-cancer-chile/capturas/06_cancer_de_mama.png"><img src="dashboard-cancer-chile/capturas/mini/06_cancer_de_mama.png" width="200" alt="🌸 Cáncer de mama"></a><br><sub>🌸 Cáncer de mama</sub></td><td align="center" valign="top"><a href="dashboard-cancer-chile/capturas/07_cuello_uterino.png"><img src="dashboard-cancer-chile/capturas/mini/07_cuello_uterino.png" width="200" alt="💠 Cuello uterino"></a><br><sub>💠 Cuello uterino</sub></td><td align="center" valign="top"><a href="dashboard-cancer-chile/capturas/08_detectarlo_a_tiempo.png"><img src="dashboard-cancer-chile/capturas/mini/08_detectarlo_a_tiempo.png" width="200" alt="🔎 Detectarlo a tiempo"></a><br><sub>🔎 Detectarlo a tiempo</sub></td></tr>
<tr><td align="center" valign="top"><a href="dashboard-cancer-chile/capturas/09_que_mide_cada_kpi.png"><img src="dashboard-cancer-chile/capturas/mini/09_que_mide_cada_kpi.png" width="200" alt="📐 Qué mide cada KPI"></a><br><sub>📐 Qué mide cada KPI</sub></td></tr>
</table>

<details><summary>🎨 <b>Ver en Tableau</b> (mismas páginas)</summary>

<table>
<tr><td align="center" valign="top"><a href="dashboard-cancer-chile/capturas/tableau/01_resumen.png"><img src="dashboard-cancer-chile/capturas/tableau/01_resumen.png" width="200" alt="📊 Resumen"></a><br><sub>📊 Resumen</sub></td><td align="center" valign="top"><a href="dashboard-cancer-chile/capturas/tableau/02_esta_aumentando.png"><img src="dashboard-cancer-chile/capturas/tableau/02_esta_aumentando.png" width="200" alt="📈 ¿Está aumentando?"></a><br><sub>📈 ¿Está aumentando?</sub></td><td align="center" valign="top"><a href="dashboard-cancer-chile/capturas/tableau/03_cual_predomina.png"><img src="dashboard-cancer-chile/capturas/tableau/03_cual_predomina.png" width="200" alt="⚖️ ¿Cuál predomina?"></a><br><sub>⚖️ ¿Cuál predomina?</sub></td><td align="center" valign="top"><a href="dashboard-cancer-chile/capturas/tableau/04_como_prevenirlo.png"><img src="dashboard-cancer-chile/capturas/tableau/04_como_prevenirlo.png" width="200" alt="🛡️ Cómo prevenirlo"></a><br><sub>🛡️ Cómo prevenirlo</sub></td></tr>
<tr><td align="center" valign="top"><a href="dashboard-cancer-chile/capturas/tableau/05_chile_y_el_mundo.png"><img src="dashboard-cancer-chile/capturas/tableau/05_chile_y_el_mundo.png" width="200" alt="🌍 Chile y el mundo"></a><br><sub>🌍 Chile y el mundo</sub></td><td align="center" valign="top"><a href="dashboard-cancer-chile/capturas/tableau/06_cancer_de_mama.png"><img src="dashboard-cancer-chile/capturas/tableau/06_cancer_de_mama.png" width="200" alt="🌸 Cáncer de mama"></a><br><sub>🌸 Cáncer de mama</sub></td><td align="center" valign="top"><a href="dashboard-cancer-chile/capturas/tableau/07_cuello_uterino.png"><img src="dashboard-cancer-chile/capturas/tableau/07_cuello_uterino.png" width="200" alt="💠 Cuello uterino"></a><br><sub>💠 Cuello uterino</sub></td><td align="center" valign="top"><a href="dashboard-cancer-chile/capturas/tableau/08_detectarlo_a_tiempo.png"><img src="dashboard-cancer-chile/capturas/tableau/08_detectarlo_a_tiempo.png" width="200" alt="🔎 Detectarlo a tiempo"></a><br><sub>🔎 Detectarlo a tiempo</sub></td></tr>
<tr><td align="center" valign="top"><a href="dashboard-cancer-chile/capturas/tableau/09_que_mide_cada_kpi.png"><img src="dashboard-cancer-chile/capturas/tableau/09_que_mide_cada_kpi.png" width="200" alt="📐 Qué mide cada KPI"></a><br><sub>📐 Qué mide cada KPI</sub></td></tr>
</table>

</details>

<p>📖 <a href="dashboard-cancer-chile/">README del tablero</a> &nbsp;·&nbsp; 📥 <a href="dashboard-cancer-chile/Cancer_Chile_MariaCisterna.pbix">Power BI (.pbix)</a> &nbsp;·&nbsp; 📥 <a href="dashboard-cancer-chile/Cancer_Chile_MariaCisterna.twbx">Tableau (.twbx)</a> &nbsp;·&nbsp; 🗂️ <a href="dashboard-cancer-chile/Cancer_Chile_BaseDatos.xlsx">Base de datos</a> &nbsp;·&nbsp; <a href="#inicio">⬆️ Volver arriba</a></p>

---

<a id="presentacion"></a>

## 🎤 Presentación: los cinco tableros en una mirada

<p align="center"><a href="presentacion/diapositivas/01_portada.png"><img src="presentacion/diapositivas/01_portada.png" width="820" alt="Portada de la presentación"></a></p>

[`Salud_Chile_en_datos_MariaCisterna.pptx`](presentacion/Salud_Chile_en_datos_MariaCisterna.pptx) · 15 diapositivas interactivas: índice con tarjetas que llevan a cada sección, botón **Índice** en cada diapositiva y enlaces a cada tablero. Aquí están todas, haz clic para ampliar:

<table>
<tr><td align="center" valign="top"><a href="presentacion/diapositivas/02_indice.png"><img src="presentacion/diapositivas/mini/02_indice.png" width="260" alt="🧭 Índice interactivo"></a><br><sub>🧭 Índice interactivo</sub></td><td align="center" valign="top"><a href="presentacion/diapositivas/03_cinco_tableros.png"><img src="presentacion/diapositivas/mini/03_cinco_tableros.png" width="260" alt="🗂️ Los 5 tableros"></a><br><sub>🗂️ Los 5 tableros</sub></td><td align="center" valign="top"><a href="presentacion/diapositivas/04_antes_y_ahora.png"><img src="presentacion/diapositivas/mini/04_antes_y_ahora.png" width="260" alt="⏳ Antes y ahora"></a><br><sub>⏳ Antes y ahora</sub></td></tr>
<tr><td align="center" valign="top"><a href="presentacion/diapositivas/05_sifilis.png"><img src="presentacion/diapositivas/mini/05_sifilis.png" width="260" alt="📈 Sífilis: no para de subir"></a><br><sub>📈 Sífilis: no para de subir</sub></td><td align="center" valign="top"><a href="presentacion/diapositivas/06_todas_las_its.png"><img src="presentacion/diapositivas/mini/06_todas_las_its.png" width="260" alt="🧪 Todas las ITS"></a><br><sub>🧪 Todas las ITS</sub></td><td align="center" valign="top"><a href="presentacion/diapositivas/07_chile_mundo_its.png"><img src="presentacion/diapositivas/mini/07_chile_mundo_its.png" width="260" alt="🌍 Chile frente al mundo: ITS"></a><br><sub>🌍 Chile frente al mundo: ITS</sub></td></tr>
<tr><td align="center" valign="top"><a href="presentacion/diapositivas/08_chile_mundo_cancer_materna.png"><img src="presentacion/diapositivas/mini/08_chile_mundo_cancer_materna.png" width="260" alt="🌎 Chile frente al mundo: cáncer y salud materna"></a><br><sub>🌎 Chile frente al mundo: cáncer y salud materna</sub></td><td align="center" valign="top"><a href="presentacion/diapositivas/09_embarazo_matronas.png"><img src="presentacion/diapositivas/mini/09_embarazo_matronas.png" width="260" alt="🤰 Menos embarazo adolescente, más matronas"></a><br><sub>🤰 Menos embarazo adolescente, más matronas</sub></td><td align="center" valign="top"><a href="presentacion/diapositivas/10_cancer_ajuar.png"><img src="presentacion/diapositivas/mini/10_cancer_ajuar.png" width="260" alt="🎗️ Cáncer y ajuar"></a><br><sub>🎗️ Cáncer y ajuar</sub></td></tr>
<tr><td align="center" valign="top"><a href="presentacion/diapositivas/11_metricas_meta.png"><img src="presentacion/diapositivas/mini/11_metricas_meta.png" width="260" alt="🎯 Métricas frente a su meta"></a><br><sub>🎯 Métricas frente a su meta</sub></td><td align="center" valign="top"><a href="presentacion/diapositivas/12_hallazgos.png"><img src="presentacion/diapositivas/mini/12_hallazgos.png" width="260" alt="💡 Hallazgos"></a><br><sub>💡 Hallazgos</sub></td><td align="center" valign="top"><a href="presentacion/diapositivas/13_simulador.png"><img src="presentacion/diapositivas/mini/13_simulador.png" width="260" alt="🏫 Simulador"></a><br><sub>🏫 Simulador</sub></td></tr>
<tr><td align="center" valign="top"><a href="presentacion/diapositivas/14_medidas.png"><img src="presentacion/diapositivas/mini/14_medidas.png" width="260" alt="🛠️ Medidas a tomar"></a><br><sub>🛠️ Medidas a tomar</sub></td><td align="center" valign="top"><a href="presentacion/diapositivas/15_conclusiones.png"><img src="presentacion/diapositivas/mini/15_conclusiones.png" width="260" alt="✅ Conclusiones"></a><br><sub>✅ Conclusiones</sub></td></tr>
</table>

---

## 💡 Hallazgos que cruzan los cinco tableros

| | Hallazgo | Qué muestran los datos |
|:---:|---|---|
| 📉 | **El gran logro** | La fecundidad adolescente bajó de 23,2 a 8,3 por mil (2018–2025). |
| 🚨 | **La alerta** | La sífilis subió 64% desde 2020; Chile casi iguala a EE.UU. y quintuplica a Europa. |
| 💊 | **La brecha de método** | Solo 7% de las adolescentes inicia con implante y 1,5% con DIU, los más eficaces. |
| 👩‍⚕️ | **Más matronas** | 23.333 inscritas (+70% desde 2018), con un rol central en la prevención en APS. |
| 🔍 | **Detectar a tiempo** | Cáncer de mama localizado: 99% de sobrevida; con metástasis: 32%. |
| 🍼 | **El ajuar llega** | 97–99% de cobertura; bajan los sets porque nacen menos guaguas. |

---

## 🛠️ Medidas a tomar

| | Medida | Qué hacer | Indicador para seguirla |
|:---:|---|---|---|
| 🏫 | Matronas en los colegios | Educación sexual integral con acceso a métodos desde los 14 años (Ley 20.418). | Fecundidad de 15 a 19 años |
| 🧪 | Testear y tratar ITS | Test rápido de VIH y sífilis en APS y llevar a tratamiento a las 21.915 personas pendientes. | VIH en tratamiento: 71% → 95% |
| 💊 | Ofrecer primero implante y DIU | Consejería que presente los métodos de larga duración como primera opción. | Inicio con implante o DIU: 9% |
| 🎗️ | Subir la pesquisa de cáncer | Mamografía, test VPH y PAP con citación activa; completar la vacuna VPH. | Mamografía: 37,4% → 70% |
| 🍼 | Cuidar la cadena del ajuar | Más de un oferente en la licitación y taller educativo antes del alta para todas. | Cobertura: 100% |
| 📊 | Medir lo que falta | Encuesta nacional de embarazo no planificado (último dato: 2010) y dotación de matronas. | Datos abiertos |

---

## ✅ Conclusiones

- 💗 **La prevención funciona:** el embarazo adolescente cayó a un tercio en siete años.
- ⚠️ **Las ITS van en sentido contrario:** la sífilis de Chile es 5 veces la de Europa.
- 🔍 **En cáncer, llegar a tiempo cambia todo:** la pesquisa todavía está lejos de su meta.
- 👩‍⚕️ **Chile tiene más matronas que nunca:** el desafío es ponerlas donde está la prevención.

<p align="right"><a href="#inicio">⬆️ Volver arriba</a></p>

---

## 🏫 Simuladores interactivos

<a href="dashboard-its-chile/capturas/06_simulador_matronas_en_colegios.png"><img src="dashboard-its-chile/capturas/mini/06_simulador_matronas_en_colegios.png" width="330" align="right" alt="Simulador"></a>

En **ITS** y en **Embarazo y matronería** hay un simulador: eliges qué porcentaje de colegios tendría una matrona haciendo educación sexual integral, si se entregan anticonceptivos desde los 14 años y cuánto sube el uso de condón, y el tablero calcula cuántos embarazos adolescentes y casos de ITS se evitarían, con los supuestos y su evidencia a la vista.

<br clear="right">

---

## 📐 Cómo elegí los KPI

- 📏 **Tasas** (por 100 mil o por 1.000): permiten comparar años, regiones y países aunque tengan distinta población.
- ✅ **Coberturas:** qué parte de la población objetivo recibe una intervención (mamografía, PAP, vacuna VPH, ajuar).
- ⚖️ **Razones:** comparan grupos (hombres y mujeres) o muertes por cada caso nuevo, que refleja el acceso a diagnóstico y tratamiento.
- 🎯 **Metas oficiales:** ODS, ONUSIDA 95-95-95, OPS (eliminación de la transmisión vertical) y OMS 90-70-90 para cáncer cervicouterino.

---

## 📁 Qué trae cada carpeta

| | Archivo | Qué es |
|:---:|---|---|
| 📊 | `.pbix` | Tablero de **Power BI**, listo para abrir con Power BI Desktop (gratis). |
| 🎨 | `.twbx` | Tablero de **Tableau** con las mismas páginas. |
| 🧩 | `PowerBI_proyecto_pbip.zip` | **Proyecto editable** de Power BI (PBIP). |
| 🗂️ | `_BaseDatos.xlsx` | **Base de datos** con todas las tablas, la hoja `KPI` y la hoja `Fuentes`. |
| 🖼️ | `capturas/` | Imágenes de cada página, en Power BI y en Tableau. |

En `recursos/` están el logo con el registro de la Superintendencia de Salud y el fondo de los tableros (`fondo_tableros.png`).

---

## 🧭 Cómo trabajé los datos

- 🔎 **Fuentes públicas y chilenas primero:** MINSAL, DEIS, INE, ISP, Superintendencia de Salud, Chile Crece Contigo, OMS/OPS e IARC.
- 🧾 **Cada fila dice de dónde viene** (columna `FuenteID`).
- 🚫 **No se inventaron cifras:** si un año no tiene dato público, queda en blanco.
- 💬 **Lenguaje simple:** pensado para que lo entienda cualquier persona, no solo profesionales de salud.

---

## ⚠️ Aviso

Material educativo y de análisis de datos. **No reemplaza la consejería ni el control con un profesional de salud.**

## ©️ Derechos

© 2026 María Cisterna Escobar, matrona. Todos los derechos reservados: puedes ver y compartir el enlace, pero no copiar ni reutilizar el contenido sin autorización. Ver `LICENSE`.
