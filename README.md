# Sectoral Balances and Flow of Funds (2007–2025)[span_0](start_span)[span_0](end_span)

An interactive **D3.js** dashboard designed to analyze macroeconomic trends and sectoral balance dynamics across six major global economies (Italy, USA, Luxembourg, Norway, Ireland, and China) over the 2007–2025 timeframe[span_1](start_span)[span_1](end_span).

---

## 📌 Theoretical Framework
The project is built upon the fundamental accounting identity of sectoral balances[span_2](start_span)[span_2](end_span):

$$(S - I) \equiv (T - G - TR) + CA$$

Where:
- **(S − I)**: Private sector net balance (Savings − Investment)[span_3](start_span)[span_3](end_span)
- **(T − G − TR)**: Primary public sector balance (Taxes − Government Spending − Transfers)[span_4](start_span)[span_4](end_span)
- **CA**: Current Account balance[span_5](start_span)[span_5](end_span)

### Reading the Diagram
- **X-Axis**: Current Account balance (CA) as a % of GDP[span_6](start_span)[span_6](end_span).
- **Y-Axis**: Primary public sector balance as a % of GDP[span_7](start_span)[span_7](end_span).
- **Bisector ($S = I$)**: Represents the private sector break-even line[span_8](start_span)[span_8](end_span). The vertical distance from a point to the bisector measures the private sector balance[span_9](start_span)[span_9](end_span):
  - **Below the bisector**: Private sector surplus ($S > I$)[span_10](start_span)[span_10](end_span).
  - **Above the bisector**: Private sector deficit ($S < I$)[span_11](start_span)[span_11](end_span).

---

## 🚀 Key Features
- **Dynamic Scatter Plot (D3.js)**: Continuous tracking of historical country trajectories by interpolating data across 5 anchor points (2007, 2010, 2015, 2020, 2025)[span_12](start_span)[span_12](end_span).
- **Animation & Timeline Controls**: Automatic playback ("Play/Pause"), step-by-step navigation, and interactive timeline slider (2007–2025)[span_13](start_span)[span_13](end_span).
- **Multiple Country Isolation**: Select individual countries or isolate multiple countries (`Ctrl/Cmd + Click`) to highlight specific trajectories for targeted comparison[span_14](start_span)[span_14](end_span).
- **Real-Time Stats & Sparklines**: Real-time average calculations for sectors and dynamic sparkline charts in the sidebar[span_15](start_span)[span_15](end_span).
- **2007 vs 2025 Comparison**: Summary view showing percentage point variations in private balances for each country[span_16](start_span)[span_16](end_span).
- **Interactive Data Table**: Automatic column highlighting corresponding to the selected year[span_17](start_span)[span_17](end_span).
- **Graphic Export**: Download the current diagram view as a vector `.svg` file[span_18](start_span)[span_18](end_span).
- **Keyboard Shortcuts**:
  - `Space`: Play / Pause animation[span_19](start_span)[span_19](end_span)
  - `←` / `→`: Navigate to previous / next year[span_20](start_span)[span_20](end_span)
  - `R`: Reset animation to the initial year[span_21](start_span)[span_21](end_span)
  - `Esc`: Reset isolation filters[span_22](start_span)[span_22](end_span)

---

## 🛠️ Tech Stack & Data Sources
- **Frontend**: HTML5, CSS3 (Custom Properties, Dark Theme), JavaScript ES6+[span_23](start_span)[span_23](end_span)
- **Data Visualization**: [D3.js (v7)](https://d3js.org/)[span_24](start_span)[span_24](end_span)
- **Data Sources**: Eurostat, OECD, IMF WEO[span_25](start_span)[span_25](end_span)
