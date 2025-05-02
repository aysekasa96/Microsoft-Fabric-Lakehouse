# Microsoft Fabric Lakehouse

Dit project richt zich op het bouwen en beheren van een **Lakehouse** met **Microsoft Fabric**. Het Lakehouse-model combineert de voordelen van **Data Lake** en **Data Warehouse**, waardoor grootschalige data-analyse efficiënter wordt.

## 🚀 Projectinhoud

Binnen dit project heb ik de volgende stappen uitgevoerd:

1. **Werkruimte aanmaken:** Een nieuwe werkruimte aangemaakt in Microsoft Fabric.
2. **Lakehouse creëren:** Een Lakehouse opgezet in OneLake-opslag.
3. **Gegevens uploaden:** CSV-bestanden geüpload naar het Lakehouse.
4. **Gegevens laden in tabellen:** Omgezet naar **Delta Lake**-formaat voor SQL-query’s.
5. **SQL-query’s uitvoeren:** Queries uitgevoerd via de SQL Analytics Endpoint.
6. **Rapporten en visualisaties maken:** Data gevisualiseerd in Power BI.

## 🛠️ Gebruikte technologieën

- **Microsoft Fabric**
- **OneLake**
- **Delta Lake**
- **Apache Spark**
- **Power BI**
- **SQL Analytics**

## 📂 Bestandsstructuur

```plaintext
├── data/
│   ├── sales.csv  # Voorbeeldgegevens
├── scripts/
│   ├── query.sql  # SQL-query’s
│   ├── transform.py  # Python-code voor datatransformatie
├── reports/
│   ├── sales_report.pbix  # Power BI-rapport
├── README.md
