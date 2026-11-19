SME Live Business Intelligence Dashboards

A zero-cost, fully automated ETL (Extract, Transform, Load) pipeline and mobile-first BI dashboard system built for local small businesses (SMEs) in South Africa. 

🔗 **Live Interactive Dashboard (Looker Studio):** [Click here to view the live dashboard](https://datastudio.google.com/s/pzd_75tWuMM)
📄 **Download the Full Dashboard PDF:** [Download PDF](./SME_Dashboards.pdf)

📌 Why I Built This
Small businesses like local salons and food vendors (Kotas) cannot afford expensive Point of Sale (POS) systems or monthly Power BI licenses. I built this system to give them real time visibility into their sales using tools they already have access to: their phones and Google.

The ETL Pipeline (How it works)
1. **Data Collection (Extract):** The business owner fills out a simple Google Form on their phone immediately after making a sale.
2. **Storage:** The raw data is dumped into a Google Sheet.
3. **Data Cleaning (Transform):** A custom Google Apps Script runs in the background, cleaning the data, standardizing product names, and pushing it to a clean "Processed" sheet. 
4. **Visualization (Load):** Looker Studio connects to the clean data and updates the custom dashboard in real-time.

The Dashboards
Instead of complex scatter plots, these dashboards are intentionally designed for business owners who need fast decisions. They feature large KPI cards (Daily Revenue), clear pie charts (Product Mix), and time-series trends (Busiest Days).

*   **SAMs KOTA Grill:** Tracks top-selling items (e.g., Pap & Wors vs. Full House Kota), daily revenue, and busiest days of the week.
*   **KATLEGO Weave & Nails:** Tracks salon revenue, top services (e.g., Weave 16" vs. Braids), and daily performance.


Built by Setlhako N.C.
