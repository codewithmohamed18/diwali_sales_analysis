<!-- ───────────────  README.md  ─────────────── -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=180&section=header&text=Diwali%20Sales%20Analytics&fontSize=50&fontColor=ffffff&animation=twinkling&desc=Python%20|%20Pandas%20|%20Seaborn%20|%20Business%20Intelligence&descAlignY=65"/>
</p>

<p align="center">
  <a href="https://codewithmohamed18.github.io/diwali_sales_analysis/" target="_blank">
    <img src="https://img.shields.io/badge/Live-Demo-2563eb?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Live Demo"/>
  </a>
  <img src="https://img.shields.io/badge/Python-3.9+-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Status-Completed-success?style=for-the-badge"/>
</p>

---

## 🪔 1-Line Pitch
**Turned 36 Diwali-sales records into ₹7.79 Lacs of actionable insight** – discovering that *Auto-products* drive 97 % revenue, *26-35 yr female customers* from *Andhra Pradesh* are the most profitable segment, and *Government-sector* buyers have the highest per-capita spend.

---

## 📊 Interactive Report
🔗 **[codewithmohamed18.github.io/diwali_sales_analysis](https://codewithmohamed18.github.io/diwali_sales_analysis/)**

The site is a **single-file, mobile-first dashboard** (HTML + CSS + Chart.js) statically hosted on GitHub Pages → loads in <1 s, needs no server, and works offline once cached.

---

## 🖼️ Screenshot Carousel
| Revenue by Category | Geographic Distribution | Customer Demographics |
|:-------------------:|:-----------------------:|:---------------------:|
| ![1](https://raw.githubusercontent.com/codewithmohamed18/diwali_sales_analysis/main/images/1.png) | ![2](https://raw.githubusercontent.com/codewithmohamed18/diwali_sales_analysis/main/images/2.png) | ![3](https://raw.githubusercontent.com/codewithmohamed18/diwali_sales_analysis/main/images/3.png) |

| Age-Group Analysis | Professional Segments | Regional Performance |
|:------------------:|:---------------------:|:--------------------:|
| ![4](https://raw.githubusercontent.com/codewithmohamed18/diwali_sales_analysis/main/images/4.png) | ![5](https://raw.githubusercontent.com/codewithmohamed18/diwali_sales_analysis/main/images/5.png) | ![6](https://raw.githubusercontent.com/codewithmohamed18/diwali_sales_analysis/main/images/6.png) |
---

## 🧠 Key Business Insights
| Insight | Business Value |
|---------|----------------|
| **Auto-products** contribute 97 % of revenue | Focus inventory & marketing budget on this category |
| **Female buyers** generate 64 % of sales | Craft gender-specific campaigns |
| **26-35 age-group** tops ₹3.55 L | Premium pricing & loyalty programmes |
| **Andhra Pradesh** alone brings ₹3.77 L | Double-down on Southern-zone distribution |
| **Government employees** have highest individual spend | B2G partnership channel opportunity |

---

## 🏗️ Technical Architecture

┌─ Jupyter Notebook (EDA, cleaning, modelling)
├─ Python libs: Pandas, NumPy, Seaborn, Matplotlib
├─ Export high-res plots → PNG (300 dpi)
└─ Embed charts in responsive HTML/CSS/JS page
└─ Chart.js for interactive legends & tool-tips




---

## 🚀 Run the Analysis Locally
```bash
# 1. Clone repo
git clone https://github.com/mohamed-khalid3/diwali-sales-analysis.git
cd diwali-sales-analysis

# 2. Create virtual env (optional but recommended)
python -m venv venv
source venv/bin/activate        # Mac/Linux
venv\Scripts\activate           # Windows

# 3. Install dependencies
pip install -r requirements.txt   # pandas, seaborn, matplotlib, jupyter

# 4. Launch notebook
jupyter notebook diwali_sales_analysis.ipynb

```

📁 Repository Structure
```
diwali-sales-analysis/
│
├── diwali_sales_analysis.ipynb    # Main notebook
├── Diwali Sales Data.csv          # Raw dataset
├── plots/                         # 6 high-res charts
│   ├── 1.png … 6.png
├── README.md
├── requirements.txt
└── docs/
    └── index.html                 # Static dashboard (this repo’s GitHub Page)
```
## 🔧 Customisation Ideas
| Idea | How |
|------|-----|
| **Sales Forecast** | Plug in `Prophet` or `SARIMA` on monthly aggregations |
| **Geo Heat-Map** | Swap bar-chart for `folium` / `plotly.express.choropleth` |
| **Deploy elsewhere** | Drag-and-drop the `docs/` folder to Netlify, Vercel, or Cloudflare Pages |
| **PDF Report** | `jupyter nbconvert --to webpdf notebook.ipynb` |
| **Dark-Mode UI** | Toggle a `.dark` class on `<html>` + CSS variables |
| **RFM Segmentation** | Recency-Frequency-Monetary clustering with `scikit-learn` |

## 🤝 Contribution
Pull-requests are welcome!  
Typical adds: RFM analysis, A/B testing simulator, new colour themes, or extra Plotly interactions.

## 📄 License
MIT © 2024 Mohamed Khalid  

## 📬 Contact
| Channel | Link |
|---------|------|
| 📧 Email | [khannihad1@gmail.com](mailto:khannihad1@gmail.com) |
| 💼 LinkedIn | [linkedin.com/in/mohamed-khalid-data](https://linkedin.com/in/mohamed-khalid-data) |
| 🐙 GitHub | [github.com/mohamed-khalid3](https://github.com/mohamed-khalid3) |

<!-- Open-Graph / Twitter -->
<meta property="og:title" content="Diwali Sales Analytics | Python Data-Science Project">
<meta property="og:description" content="Interactive dashboard revealing ₹7.79 L Diwali-sales insights with Python, Pandas & Seaborn.">
<meta property="og:image" content="https://raw.githubusercontent.com/codewithmohamed18/diwali_sales_analysis/main/images/1.png">
<meta property="og:url" content="https://codewithmohamed18.github.io/diwali_sales_analysis/">
<meta property="og:type" content="website">
<meta name="twitter:card" content="summary_large_image">
<meta name="twitter:title" content="Diwali Sales Analytics | Python Data-Science Project">
<meta name="twitter:description" content="Interactive dashboard revealing ₹7.79 L Diwali-sales insights with Python, Pandas & Seaborn.">
<meta name="twitter:image" content="https://raw.githubusercontent.com/codewithmohamed18/diwali_sales_analysis/main/images/1.png">
```
