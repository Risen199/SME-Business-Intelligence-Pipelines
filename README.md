SME Live Business Intelligence Dashboards

A zero-cost, fully automated ETL (Extract, Transform, Load) pipeline and mobile-first BI dashboard system built for local small businesses (SMEs) in South Africa. 

🔗 **Live Interactive Dashboard (Looker Studio):** [Click here to view the live dashboard](https://datastudio.google.com/s/pzd_75tWuMM)
📄 **Download the Full Dashboard PDF:** [Download PDF](./SME_Dashboards.pdf)

📌 Why I Built This
Small businesses like local salons and food vendors (Kotas) cannot afford expensive Point of Sale (POS) systems or monthly Power BI licenses. I built this system to give them real-time visibility into their sales using tools they already have access to: their phones and Google.

The ETL Pipeline (How it works)
1. **Data Collection (Extract):** The business owner fills out a simple Google Form on their phone immediately after making a sale.
2. **Storage:** The raw data is dumped into a Google Sheet.
3. **Data Cleaning (Transform):** A custom Google Apps Script runs in the background, cleaning the data, standardizing product names, and pushing it to a clean "Processed" sheet. 
4. **Visualization (Load):** Looker Studio connects to the clean data and updates the custom dashboard in real-time.

The Dashboards
Instead of complex scatter plots, these dashboards are intentionally designed for business owners who need fast decisions. They feature large KPI cards (Daily Revenue), clear pie charts (Product Mix), and time-series trends (Busiest Days).

*   **SAMs KOTA Grill:** Tracks top-selling items (e.g., Pap & Wors vs. Full House Kota), daily revenue, and busiest days of the week.
*   **KATLEGO Weave & Nails:** Tracks salon revenue, top services (e.g., Weave 16" vs. Braids), and daily performance.

Screenshots
<img width="746" height="566" alt="Screenshot from 2026-11-19 04-52-01" src="https://github.com/user-attachments/assets/72e418f3-1f5e-427f-9589-97b67ca74177" />
<img width="746" height="566" alt="Screenshot from 2026-11-19 04-52-13" src="https://github.com/user-attachments/assets/622078e2-22a4-4a01-859a-5cba940b4835" />
<img width="746" height="566" alt="Screenshot from 2026-11-19 04-51-52" src="https://github.com/user-attachments/assets/d3739873-4626-44b5-a965-34843625e3e8" />
<img width="746" height="566" alt="Screenshot from 2026-11-19 04-52-26" src="https://github.com/user-attachments/assets/af6733b7-6ed7-4ce1-a5da-001d67d57152" />


Built by Setlhako N.C.
