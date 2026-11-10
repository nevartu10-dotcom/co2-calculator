# Tractor CO₂ Calculator

Mobile web app (PWA) for diesel tractor operators. Records the driven route with phone GPS, shows it on a map, and calculates CO₂ from the diesel used.

- Implement down/up toggle separates working passes from transport
- Worked area = distance with implement down × implement width
- Fuel as total litres or L/h × recording time
- CO₂ = litres × factor (default 2.68 kg/L, editable) → total kg, kg/km, kg/ha
- History with map view and CSV export; demo mode with a simulated field

Open via HTTPS (GitHub Pages) – GPS does not work over plain http. Keep the screen on while recording; browsers stop GPS when the phone locks.
