WEBSITE LINK - https://v0-vercel-ai-project-ruby-three.vercel.app/
VR STORE- https://v0.dev/chat/fork-of-vercel-ai-project-F8XVgQQB8Jo?b=b_GSQ55wSQorn&f=1#qWdEqz19r0WToTnzo4zCM6zRSEIAdvyO
YOUTUBE VISEO - https://youtu.be/LHUvUEHrERg?si=mpT66vjKKZPkA6Z5

SMART DYNAMIC PRICING ENGINE
---
# 🛒 Smart Dynamic Pricing Advisor for Perishable Goods – Walmart Sparkathon

A full-stack AI-powered dashboard for **dynamic pricing, waste reduction, and inventory optimization** tailored for **Walmart India**. Features a **clickable Indian state map**, real-time price suggestions, ML explainability, demand simulations, and sustainability insights.

---

## 🌟 Project Highlights

| Feature                        | Description |
|-------------------------------|-------------|
| 🧠 **Dynamic ML Pricing**     | Regression + Q-learning suggest optimal price discounts |
| 🗺️ **Clickable India Map**    | Select a state to get localized predictions |
| 📅 **Month-wise Filtering**    | Choose a month to view relevant pricing policies |
| 📂 **Smart CSV Upload**       | Upload real-world inventory data – app auto-validates |
| 📉 **Demand & Waste Simulator** | Forecast demand, revenue, and waste under various discount strategies |
| 🌱 **Sustainability Metrics** | CO₂ & water saved per product via reduced waste |
| 🔁 **Reordering Logic**       | Suggests when and how much to restock based on trends |
| 🧾 **POS Simulation**         | Simulate live checkout with price recommendation |
| 📈 **Pricing Forecast Curve** | See price decline forecast over expiry timeline |
| 🧠 **Explainable AI (SHAP)**  | Visualize what influenced pricing decisions |

---

## 📁 Folder Structure

dynamic_pricing_bundle/
│
├── smart_dynamic_pricing_app.py # Main Streamlit app
├── shap_values.pkl # SHAP model file (optional)
├── q_table.npy # Trained Q-learning policy table
├── assets/
│ └── walmart_india_stores.csv # Walmart store coordinates (state-wise)
├── data/
│ └── Grocery_Inventory.csv # Sample input data
│
├── README.md # You're here

yaml
Copy
Edit

---

## 🛠️ How to Run the App Locally

### 1. 📦 Install Requirements
```bash
pip install streamlit pandas numpy matplotlib seaborn folium shap scikit-learn streamlit-folium
2. ▶️ Run the App
bash
Copy
Edit
streamlit run smart_dynamic_pricing_app.py
🧾 Input Data Format
Your inventory CSV must contain these columns:

csv
Copy
Edit
Product_Name, State, Month, Sales_Volume, Stock_Quantity, Unit_Price, Expiration_Date, Inventory_Turnover_Rate
📌 If any column is missing, the app will ask you to correct it before continuing.

🗺️ Interactive State Selection (India)
The app uses a GeoJSON file of Indian states.

You can click any state on the map to automatically:

Filter Walmart stores in that state.

Show predictions for that region and selected month.

🔄 Workflow
User uploads inventory data

Selects a state by clicking the map

Picks a month from dropdown

App runs ML + RL to:

Predict price

Suggest discount

Simulate revenue, waste, demand

Recommend reorder if needed

All results shown via charts, KPIs, maps, and explainability visuals

🧠 Tech Stack
Streamlit: Frontend UI

RandomForestRegressor: ML pricing model

Q-learning (Q-table): Reinforcement learning for dynamic discounts

SHAP: Explainable AI

Folium + streamlit-folium: Interactive India map

Pandas/Numpy/Matplotlib/Seaborn: Analytics & Visualization

💼 Business Impact
Reduce food waste 📉

Increase revenue 💰

Improve operational efficiency 🏪

Promote sustainable retailing 🌱

🧪 Want to Contribute?
Improve demand simulation with real POS curves

Add integration with real-time inventory APIs

Add SKU-level forecasting models

📬 Contact
For queries or collaboration:
ADITYA SINGH
✉️ adityas23100@iiitnr.edu.in


