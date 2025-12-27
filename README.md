# 🔥 F.I.R.O - Fire Intelligence & Rapid Outlook (Demo)

A smarter, faster response to wildfires: a digital twin that simulates fire behavior in real time

## 🚀 How to Run
1. Download or clone the project.
2. Make sure `map.png` is in the same folder as the HTML file.
3. Open the `.html` file in any modern browser (Chrome, Edge, Firefox).

## 🕹️ How to Use
1. Click anywhere on the map to place a fire ignition point.
2. Adjust:
   - 🌡️ Temperature  
   - 💧 Humidity  
   - 💨 Wind speed & direction  
   - ⚙️ Simulation speed
3. Press **Start** to run the simulation.
4. Use **Pause** to stop and **Reset** to clear everything.

## 🗺️ How It Works (Quick)
- The map is a grid of terrain cells (forest, grass, shrub, barren, water).
- Fire spreads cell-to-cell based on:
  - Fuel type
  - Wind direction & speed
  - Temperature
  - Humidity
- Water tiles do not burn and block spread.
- Stats update in real time.

## 📌 Notes
- This is a proof-of-concept, not a full fletched wildfire prediction model.
- Everything runs fully client-side with vanilla HTML, CSS, and JavaScript.
