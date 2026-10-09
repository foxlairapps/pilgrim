# Ikony provozoven

Sem lze doplňovat samostatné `.webp` obrázky pro hotspoty provozoven.
V JSON definici provozovny (`src/content/settlements/settlement_XXX.json`) nastav `hotspotImage`, například:

```json
"hotspotImage": "/hotspots/fisher.webp"
```

Pokud je hodnota prázdná nebo obrázek nelze načíst, UI použije původní emoji provozovny jako fallback.
