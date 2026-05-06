# Erika Fashion · Produkty B — Kategorie, Trend & Marže

**Live:** https://patrikpilous-dev.github.io/erikafashion-produkty-b/

Agregovaný pohled na kategorie s multi-membership (produkt v X kategoriích → započítává se do všech).
Hierarchie L1 / L2 / L3 z `category` stringu (oddělovač ` > `).

## Sekce
1. KPI souhrn kategorií + Pareto bod
2. TOP 30 nejobrátkovějších kategorií
3. Kategorie po úrovních (přepínač L1 / L2 / L3, TOP 50 podle obratu)
4. Měsíční trend per L2 kategorie (heatmapa, sloučené 2025+2026)
5. Marže × Obrat matrix (bubble chart + tabulka — zlatá vejce)
6. Cenové pásmo per L1 kategorie (decily + sweet spot)
7. Pareto / Long tail (kumulativní podíl obratu)

## Generování
```bash
cd "C:\Users\patri\Claude Code ukládané soubory"
python erikafashion_produkty_dashboard_b.py
```
