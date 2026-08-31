# 🎾 Roger Federer: The Grand Slam Legacy (1999–2020)

![Dashboard Preview](final_pic.png)

An interactive Tableau data visualization exploring the historic Grand Slam career of Roger Federer, mapping all 434 matches played between 1999 and 2020 into a custom trophy-shaped layout.

🔗 **[Live Interactive Dashboard on Tableau Public](https://public.tableau.com/app/profile/boshra.dib/vizzes)**

---

### 📊 Key Insights & Highlights
* **Grand Slam Record:** 434 Matches played — 373 Wins, 61 Losses (**86.0% Win Rate**).
* **Finals Performance:** 20 Titles Won, 11 Losses (**64.5% Finals Win Rate**).
* **Most Successful Slam:** Wimbledon (**8 Titles Won**).
* **Titles by Tournament Breakdown:**
  * 🏆 **Wimbledon:** 8 Titles
  * 🏆 **Australian Open:** 6 Titles
  * 🏆 **US Open:** 5 Titles
  * 🏆 **Roland Garros:** 1 Title
* **Custom Trophy Match Map:** Visualizes all 434 matches as interactive data points arranged in a custom trophy design, color-coded by stage (*Title Win, Semi-Final / Final, R16 / Quarter-Final, Early Rounds*).

---

### 🛠️ Repository Structure & Files
* **`README.md`**: Project overview and documentation.
* **`final_pic.png`**: High-resolution screenshot preview of the finalized Tableau dashboard.
* **`federer_grand_slam_trophy_tableaufinal.csv`**: Processed final dataset containing match details, opponent records, scores, and calculated X/Y coordinates for the trophy visual shape.
* **`app.py`**: Python script (Streamlit app) used to process match data and calculate the parametric coordinates for the trophy design.

---

### ⚙️ Tools & Technologies Used
* **Python (`pandas`, `numpy`, `Streamlit`)**: Data cleaning, filtering Grand Slam matches, and generating trophy layout coordinates.
* **Tableau Public / Desktop**: Dashboard design, custom tooltips, surface filters, and visual formatting.

---

### 📁 Data Source & Credit
* **Source Dataset:** Jeff Sackmann's open-source ATP repository (`tennis_atp`).
* **Visualized by:** Boshra Dib

---

### 🚀 How to Run / Replicate
1. Clone this repository: `git clone https://github.com/boshradib-95/federer-grand-slam-tableau.git`
2. Run `app.py` if you wish to adjust or recalculate the trophy geometric coordinates: `streamlit run app.py`
3. Import `federer_grand_slam_trophy_tableaufinal.csv` into Tableau to interact with or customize the dashboard layout.