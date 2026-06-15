[README.md](https://github.com/user-attachments/files/28953489/README.md)
# WATTMAP — Nigeria Solar Load Calculator

A single-file HTML tool for sizing home solar power systems in Nigeria. Walk through four screens to go from appliance selection to a full system sizing report — no installation, no server, no dependencies.

## What it does

1. **Setup** — Enter property details, supply voltage, days of autonomy, peak sun hours, and oversize factor.
2. **Appliances** — Select from 25+ common household appliances (or add your own custom ones), set quantity, daily usage hours, and adjust wattage per item.
3. **Analysis** — See your total running load, peak surge load, daily energy output, and Consumer Energy Demand (CED), broken down by category with a full formula walkthrough.
4. **Results** — Get a complete sizing report:
   - Inverter type recommendation (pure sine, modified sine, or hybrid) with VA sizing
   - Main circuit breaker rating
   - Battery bank sizing (Ah required, number of units, series/parallel wiring layout) with adjustable depth of discharge per battery chemistry
   - Solar panel array sizing (panel count, series/parallel string layout, MPPT controller rating)
   - Cable sizing table (CSA in mm² and conductor diameter) for every circuit in the system

## How to use it

Open `load-calculator.html` in any web browser. That's it — everything runs client-side, no internet connection or installation required after the page loads.

## Editable inputs

Every key value used in the calculations is adjustable, including:
- Peak sun hours (regional presets + custom entry)
- System voltage (12V/24V/48V presets + custom entry)
- Battery unit size in Ah (presets + custom entry)
- Battery chemistry and depth of discharge (via slider)
- Panel wattage, voltage, and current ratings
- Performance ratio and oversize factor


## Notes

All figures (appliance wattages, cable ratings, panel specs, etc.) are reference defaults and should be verified against datasheets and local electrical codes before use in an actual installation.
