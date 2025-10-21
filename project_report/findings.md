# Greenhouse Analytics — Findings (AUTO-GENERATED)

## Data summary
- Data period: 2025-09-01 00:00:00 to 2025-09-30 23:00:00
- Total datapoints (hourly): 720

## KPI (time in ideal ranges) — latest 7 days averages
- temperature: 32.7% time in ideal range (last 7 days)
- humidity: 50.6% time in ideal range (last 7 days)
- soil_moisture: 100.0% time in ideal range (last 7 days)
- co2: 31.0% time in ideal range (last 7 days)

## Anomalies
- Total anomalies detected: 8
- Sample anomalies (timestamp, temperature, matched_rules):
  - 2025-09-12 07:00:00 | temp=27.14 | rules=iso
  - 2025-09-13 05:00:00 | temp=30.31 | rules=iso
  - 2025-09-16 08:00:00 | temp=20.28 | rules=iso
  - 2025-09-16 16:00:00 | temp=19.08 | rules=iso
  - 2025-09-16 17:00:00 | temp=18.55 | rules=iso

## Forecast (next period)
- Forecast rows saved to: data/temperature_forecast.csv

## Recommendations
- Investigate repeated anomalies at same times — could be sensor drift or scheduled events.
- If temperature frequently exceeds ideal max, consider improving ventilation / shading.
- Use the forecast to preemptively adjust HVAC/irrigation schedules.