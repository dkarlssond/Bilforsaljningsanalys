# Bilförsäljnings-Dashboard

Interaktiv Power BI dashboard för analys av begagnad bilförsäljning.
Visar säljare-performance, provision, regional försäljning 
och budget vs faktisk profit.

## Dashboard Preview
![Dashboard](dashboard_overview.png)

## Features
- KPI-kort: Total Sales, Profit, Marginal, Antal försäljningar
- Säljare-ranking med provision och marginal
- Försäljning per region (4 regioner)
- Försäljningstrend (Nov 2023 – Maj 2024)
- Budget vs Faktisk Profit
- Provision per Biltyp
- Marginal per Biltyp
- Add-on Intäkter (Försäkring, Garanti, Lån)

## Affärslogik
- **Provision:** 5% på vinst per bil
- **Add-ons:** Försäkring, garanti och lånekommission
- **Marginal:** Skillnad mellan inköps- och försäljningspris

## Key Numbers
- Total försäljning: 97.4M kronor
- Total profit: 16.8M kronor
- Total provision: 1.8M kronor
- Genomsnittlig marginal: 22.6%
- Antal försäljningar: 589

## Teknologi
- Power BI Desktop
- DAX (SUM, SUMX, FILTER, AVERAGE, COUNTA)
- Star-schema datamodellering
- Power Query

## Filer
- `Bilförsäljning.pbix` — Power BI-fil
- `Bilförsäljning_Data.xlsx` — Rådata
- `dashboard_overview.png` — Screenshot

## Portfolio
- **Projekt 1:** [Controlling Dashboard](https://github.com/dkarissond/powerbi-controlling-dashboard)
- **Projekt 2:** [Aktieanalys](https://github.com/dkarissond/Aktieanalys)
- **Projekt 3:** [Bilforsaljningsanalys](https://github.com/dkarlssond/Bilforsaljningsanalys)
