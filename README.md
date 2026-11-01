# Logistics Delivery Performance Analysis
## Yuva Intern – Technical Project

### Project objective
Analyse shipment data to understand delivery performance, calculate logistics KPIs, visualize patterns, and demonstrate a baseline delivery-time regression model.

### Dataset
`data/logistics_shipments_synthetic.csv` is a **synthetic demonstration dataset** created for this project. It contains 600 simulated shipment records. It is not company data and must not be represented as real operational evidence.

### Files
- `logistics_analysis.ipynb` – Google Colab/Jupyter notebook with the analysis workflow.
- `data/logistics_shipments_synthetic.csv` – synthetic shipment dataset.
- `Logistics_Report.docx` – strategic planning report (add this file before publishing if desired).
- `visualizations/` – location for exported charts.

### How to run in Google Colab
1. Open https://colab.research.google.com/
2. Select **File → Upload notebook** and upload `logistics_analysis.ipynb`.
3. When the notebook asks for a CSV, upload `data/logistics_shipments_synthetic.csv`.
4. Run all cells from top to bottom.
5. Review the KPI table, regional/carrier summaries, charts, and regression metrics.

### KPIs
- On-time delivery rate = on-time completed deliveries / completed deliveries with a valid promised time × 100.
- Average delivery time = mean(delivered time − dispatch time), in hours.
- Cost per completed delivery = total cost of completed shipments / completed shipments.
- Failed-attempt shipment share = failed-attempt shipments / all shipments × 100.

### Tools
Python, Pandas, NumPy, Matplotlib, scikit-learn, Jupyter Notebook / Google Colab.

### Important limitations
The dataset and resulting findings are illustrative. The regression model uses a random train/test split for learning; operational forecasting should use chronological validation. Route optimization is discussed in the strategy report but not implemented in this notebook because road-network travel times and vehicle/time-window constraints are not supplied.

### Author
[Your Name]
