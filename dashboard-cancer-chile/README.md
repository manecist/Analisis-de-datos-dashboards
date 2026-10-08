<p align="center"><img src="recursos/logo_maria_cisterna.png" alt="María Cisterna · Matrona" width="420"></p>

# 🎗️ Cáncer en Chile: cuánto aumenta y cómo ganarle

**María Cisterna Escobar · Matrona** — Registro Superintendencia de Salud N° 561993

![Power BI](https://img.shields.io/badge/Power%20BI-tablero-F2C811?logo=powerbi&logoColor=black) ![Excel](https://img.shields.io/badge/Excel-base%20de%20datos-217346?logo=microsoftexcel&logoColor=white) ![Fuentes](https://img.shields.io/badge/fuentes-p%C3%BAblicas-6B3FD4)

---

## ✨ ¿Qué muestra?

Cuántos casos y muertes por cáncer hay en Chile, cómo han aumentado, cuál predomina en hombres y en mujeres, cómo prevenir cada uno y qué examen lo detecta a tiempo. Incluye la comparación de Chile con el mundo y los cánceres de mama, cuello uterino, endometrio, ovario, testículo y próstata.

> 🌙 **Historia de datos interactiva:** está en la página `historia-cancer.html` de mi portafolio (repositorio **matrona**).

Cada página parte con sus indicadores clave (KPI) e incluye las cintas de cada cáncer explicadas: rosada (mama), turquesa y blanca (cuello uterino), lila (testículo), celeste (próstata), verde azulado (ovario) y durazno (endometrio).

---

## 📌 Indicadores clave

| | Indicador | Qué significa |
|:---:|:---:|---|
| 🎗️ | **59.887** | casos nuevos de cáncer al año en Chile |
| 📈 | **+71%** | más muertes por cáncer entre 2001 y 2024 |
| 🧔 | **Próstata** | el más frecuente en hombres y en todo Chile |
| 🌸 | **Mama** | el más frecuente en mujeres |
| 🛡️ | **4 de cada 10** | cánceres se asocian a factores que se pueden cambiar |
| 🔎 | **99%** | sobrevive a 5 años si el cáncer de mama se detecta localizado |

---

## 🖼️ Vista del tablero

### Resumen

![Resumen](capturas/01_resumen.png)

### ¿Está aumentando?

![¿Está aumentando?](capturas/02_esta_aumentando.png)

### ¿Cuál predomina?

![¿Cuál predomina?](capturas/03_cual_predomina.png)

### Cómo prevenirlo

![Cómo prevenirlo](capturas/04_como_prevenirlo.png)

### Chile y el mundo

![Chile y el mundo](capturas/05_chile_y_el_mundo.png)

### Cáncer de mama

![Cáncer de mama](capturas/06_cancer_de_mama.png)

### Cuello uterino

![Cuello uterino](capturas/07_cuello_uterino.png)

### Detectarlo a tiempo

![Detectarlo a tiempo](capturas/08_detectarlo_a_tiempo.png)

---

## 📁 Archivos

| | Archivo | Qué es |
|---|---|---|
| 🗂️ | `Cancer_Chile_BaseDatos.xlsx` | **Base de datos** con todas las tablas y la hoja `Fuentes`. |
| 📊 | `Cancer_Chile_MariaCisterna.pbix` | Tablero de **Power BI**. Ábrelo con Power BI Desktop (gratis). |
| 🧩 | `PowerBI_proyecto_pbip.zip` | **Proyecto editable** de Power BI (PBIP): descomprime y abre el `.pbip`. |

---

## 🧭 Páginas del tablero

1. **Resumen**
2. **¿Está aumentando?**
3. **¿Cuál predomina?**
4. **Cómo prevenirlo**
5. **Chile y el mundo**
6. **Cáncer de mama**
7. **Cuello uterino**
8. **Detectarlo a tiempo**
9. **Fuentes**

---

## 🛠️ Cómo abrirlo

1. Descarga el repositorio: botón verde **Code → Download ZIP** y descomprímelo.
2. Abre `Cancer_Chile_MariaCisterna.pbix` con **Power BI Desktop** (se descarga gratis desde Microsoft Store).
3. Si quieres actualizar los datos con tu copia del Excel: **Transformar datos → Administrar parámetros → RutaBaseDatos**, pega la ruta del `.xlsx` en tu computador y aprieta **Actualizar**.

> 💡 **Tip:** las páginas con lista a la izquierda son interactivas: elige una opción y el tablero cambia.

---

## 🗂️ Base de datos

`Cancer_Chile_BaseDatos.xlsx` trae estas hojas: `Globocan2024`, `MamaMuertes`, `CervixTasa`, `CervixMuertes`, `Pesquisa`, `Fuentes`, `ChileMundo`, `SobrevidaEtapa`, `SimuladorSupuestos`, `TopIncidencia`, `TopMortalidad`, `PorSexo`, `MuertesSerie`, `Prevencion`.

Cada fila indica su fuente en la columna `FuenteID`. Si un año no tiene dato público, queda vacío: **no se inventaron cifras**.

---

## 📚 Fuentes

- **C1** · GLOBOCAN 2024 (IARC/OMS, sept. 2026): Chile, Latinoamérica y el Caribe, Mundo — [enlace](https://gco.iarc.who.int/media/globocan/factsheets/populations/152-chile-fact-sheet.pdf)
- **C2** · MINSAL: reducción 56% mortalidad cáncer cervicouterino (2025) — [enlace](https://www.minsal.cl/ministra-aguilera-destaca-reduccion-del-56-en-mortalidad-por-cancer-cervicouterino-gracias-a-politicas-de-estado/)
- **C3** · BCN 2023: Cáncer de mama y mamografías en Chile — [enlace](https://obtienearchivo.bcn.cl/obtienearchivo?id=repositorio/10221/34431/1/202307_BCN_Cancer_de_mama_y_mamografias.pdf)
- **C4** · DEIS vía 24horas (16-10-2024) — [enlace](https://www.24horas.cl/tendencias/tecnologia-y-ciencias/muertes-por-cancer-de-mama-aumentan-un-12-87-en-chile)
- **C5** · Observatorio del Cáncer vía La Tercera (21-10-2025) — [enlace](https://www.latercera.com/nacional/noticia/observatorio-del-cancer-revela-cifras-decidoras-solo-4-de-cada-10-mujeres-de-50-a-69-anos-tienen-su-mamografia-al-dia/)
- **C6** · DEIS vía Vergara 240 UDP — [enlace](https://vergara240.udp.cl/chile-790-muertes-anuales-cancer-cervicouterino/)
- **C7** · MINSAL Guía GES Cáncer de testículo — [enlace](https://diprece.minsal.cl/le-informamos/auge/acceso-guias-clinicas/guias-clinicas-desarrolladas-utilizando-manual-metodologico/cancer-de-testiculos-en-personas-de-15-anos-y-mas/descripcion-y-epidemiologia/)
- **C11** · IARC Handbooks vol. 15 (2016) y vol. 10 (2005): tamizaje de mama y cervicouterino — [enlace](https://publications.iarc.who.int/)
- **C12** · American Cancer Society / SEER: sobrevida a 5 años por etapa — [enlace](https://www.cancer.org/research/cancer-facts-statistics.html)
- **C13** · GLOBOCAN 2024 vía Observatorio del Cáncer: Radiografía del cáncer en Chile — [enlace](https://www.observatoriodelcancer.cl/post/radiograf%C3%ADa-del-c%C3%A1ncer-en-chile-qu%C3%A9-revelan-las-cifras-de-globocan-2024)
- **C14** · INE Estadísticas Vitales 2019 vía La Tercera: el cáncer es por primera vez la principal causa de muerte — [enlace](https://www.latercera.com/la-tercera-sabado/noticia/cancer-es-por-primera-vez-la-principal-causa-de-muerte-en-chile/KIPWS6M5HNHMJCE27GVGYJS52U/)
- **C15** · INE: 25,9% de las muertes en 2017 se produjo por tumores — [enlace](https://www.ine.gob.cl/sala-de-prensa/prensa/general/noticia/2020/02/04/c%C3%A1ncer-en-chile-25-9-de-las-muertes-en-2017-se-produjo-por-tumores)
- **C16** · DEIS-MINSAL vía El Mercurio y GesNova Salud: defunciones por tumores 2023 y 2024 (preliminar) — [enlace](https://gesnovasalud.com/en-2024-se-agudizo-el-alza-de-muertes-por-cancer-y-patologias-del-sistema-circulatorio/)
- **C17** · OMS/IARC, Nature Medicine 2026: 37,8% de los cánceres se asocia a factores de riesgo modificables — [enlace](https://www.24horas.cl/conciencia-24-7/ciencia/oms-cuatro-diez-canceres-podrian-prevenirse)
- **C18** · IARC (GLOBOCAN 2018) vía AFP/24horas: proyección de casos y muertes en Chile a 2040 — [enlace](https://www.24horas.cl/tendencias/salud-bienestar/las-preocupantes-cifras-del-aumento-de-cancer-en-chile-3048324)

---

## ⚠️ Aviso

Material educativo y de análisis de datos. **No reemplaza la consejería ni el control con un profesional de salud.**

## ©️ Derechos

© 2026 María Cisterna Escobar, matrona. Todos los derechos reservados: puedes ver y compartir el enlace, pero no copiar ni reutilizar el contenido sin autorización. Ver `LICENSE`.
