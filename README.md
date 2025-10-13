
# 📊 Tableau Projects (ab_nyc · HR_Analysis · retail_sales)
##  <img src="tableau.png" width="800" /> 
- Three end-to-end Tableau workbooks covering real-world analytics scenarios:
- Primary project: retail_sales (listed last alphabetically).
- Data source: All datasets were sourced from Kaggle (links below).

## 🇺🇸 English

### 🔎 What’s inside

- ab_nyc.twbx — NYC Listings Analytics

  - Exploratory analysis of short-term rentals in New York City: price distribution, neighborhood/borough patterns, room types, host activity, and availability dynamics. Typical use cases include market benchmarking and supply segmentation.
  - Dataset (Kaggle): New York City Airbnb Open Data → https://www.kaggle.com/datasets/dgomonov/new-york-city-airbnb-open-data
  - Context: public listing-level data commonly includes neighborhood attributes, room types and availability signals to map supply pockets and pricing clusters.

- HR_Analysis.twbx — People Analytics

  - Workforce snapshot and attrition exploration: headcount, roles, seniority, compensation bands, performance flags, and churn patterns across departments/locations. Designed to surface hotspots and support targeted HR actions.
  - Dataset: sourced from Kaggle (HR dataset). If you’d like to expose the exact link publicly, we can add it here.

- retail_sales.twb — Retail Sales Dashboard (Main)

  - End-to-end workflow integrating multiple CSVs, data cleaning, relationship modeling, calculated fields, and storytelling dashboards for time trends, regional performance, products, and stores. Includes common retail KPIs (e.g., revenue, units, growth rates) and drill-downs (City → Store → Product) to accelerate decision-making.
  - Dataset (Kaggle): Retail Sales Data → https://www.kaggle.com/datasets/berkayalan/retail-sales-data
  - Context: transactional sales data typically provides date/product/store/city granularity to evaluate seasonality, product mix and store-level performance.

### 🧰 Data & modeling (high-level)

- ab_nyc.twbx

  - Data: Kaggle NYC Airbnb dataset (link above).
  - Model: single fact table with geographic dimensions (neighborhood/borough).
  - Views: price & availability distributions, borough comparisons, host activity, top neighborhoods.

- HR_Analysis.twbx

  - Data: HR dataset from Kaggle (employee roster & events).
  - Model: snapshot + event fields for cohorting and slices.
  - Views: headcount KPIs, attrition by segment, role/seniority composition, site/department breakdown.

- retail_sales.twb (Main)

  - Data: Kaggle Retail Sales dataset (link above) + lookups (product/store/city).
  - Prep: cleaning (dates, nulls, formats), standardized naming, relationships on keys.
  - Views: time series (e.g., monthly trends), regional & store performance, product mix, drill-downs.
  - Calculated fields: typical retail indicators (e.g., revenue, units, % growth), enriched tooltips, highlight actions.

### ▶️ How to open

  1.	Install Tableau Desktop (2023.x or newer recommended).
  2.	Open each workbook (.twb/.twbx). If prompted, point to the CSV/data files.
  3.	Use filters/highlighters to slice by date, geography, product, role, etc.
  4.	Explore story points and dashboards; actions are enabled for guided drill-downs.

### ✨ Highlights

  - ab_nyc: geospatial views + room-type mix reveal supply pockets and pricing clusters.
  - HR_Analysis: quick attrition cuts by department/tenure expose retention risks.
  - retail_sales (Main): City → Store → Product drill; consistent KPIs; documented cleaning & relationships for reproducibility.



## 🇮🇹 Italiano

### 🔎 Contenuti

- ab_nyc.twbx — Analisi Annunci NYC

  - Analisi esplorativa degli affitti a breve termine a New York: distribuzione dei prezzi, pattern per quartiere/borough, tipologie di stanza, attività degli host e dinamiche di disponibilità. Utile per benchmark di mercato e segmentazione dell’offerta.
  - Dataset (Kaggle): New York City Airbnb Open Data → https://www.kaggle.com/datasets/dgomonov/new-york-city-airbnb-open-data
  - Contesto: dati a livello di annuncio con attributi di quartiere, tipologie di stanza e segnali di disponibilità per mappare sacche di offerta e cluster di prezzo.

- HR_Analysis.twbx — People Analytics

  - Fotografia della forza lavoro ed esplorazione dell’attrition: organico, ruoli, seniority, fasce retributive, indicatori di performance e pattern di churn per reparto/sede. Pensato per evidenziare aree critiche e supportare azioni HR mirate.
  - Dataset: proveniente da Kaggle (dataset HR). Se desideri pubblicare il link esatto, lo aggiungiamo qui.

- retail_sales.twb — Dashboard Vendite Retail (Principale)

  - Flusso end-to-end con integrazione di più CSV, pulizia dati, modellazione delle relazioni, campi calcolati e dashboard di storytelling per trend temporali, performance regionali, prodotti e negozi. Include KPI retail comuni (es. ricavi, unità, tassi di crescita) e drill-down (Città → Negozio → Prodotto) per decisioni più rapide.
  - Dataset (Kaggle): Retail Sales Data → https://www.kaggle.com/datasets/berkayalan/retail-sales-data
  - Contesto: dati transazionali di vendita con granularità per data/prodotto/negozio/città per analizzare stagionalità, mix prodotti e performance dei punti vendita.

### 🧰 Dati & modellazione (overview)

- ab_nyc.twbx
  - Dati: dataset Kaggle NYC Airbnb (link sopra).
  - Modello: tabella dei fatti con dimensioni geografiche (quartiere/borough).
  - Viste: distribuzioni prezzo/disponibilità, confronti tra borough, attività host, top quartieri.

- HR_Analysis.twbx
  - Dati: dataset HR da Kaggle (anagrafica ed eventi).
  - Modello: snapshot + campi evento per coorti e filtri.
  - Viste: KPI organico, attrition per segmento, composizione ruoli/seniority, breakdown per sede/reparto.

- retail_sales.twb (Principale)
  - Dati: dataset Kaggle Retail Sales (link sopra) + tabelle di riferimento (prodotto/negozio/città).
  - Prep: pulizia (date, null, formati), nomenclatura coerente, relazioni su chiavi.
  - Viste: serie storiche (es. trend mensili), performance per regione/negozio, mix prodotti, drill-down.
  - Campi calcolati: indicatori retail tipici (es. ricavi, unità, % crescita), tooltip arricchiti, azioni di evidenziazione.

### ▶️ Come aprirli

1.	Installa Tableau Desktop (consigliata la 2023.x o superiore).
2.	Apri i workbook (.twb/.twbx). Se richiesto, reimposta i percorsi ai file dati.
3.	Usa filtri/highlighter per segmentare per data, geografia, prodotto, ruolo, ecc.
4.	Esplora story point e dashboard; sono presenti azioni per drill-down guidati.

### ✨ Evidenze

  - ab_nyc: viste geospaziali + mix per tipo stanza evidenziano sacche di offerta e cluster di prezzo.
  - HR_Analysis: tagli rapidi dell’attrition per reparto/anzianità mostrano rischi di retention.
  - retail_sales (Principale): drill Città → Negozio → Prodotto; KPI consistenti; pulizia & relazioni documentate per riproducibilità.
