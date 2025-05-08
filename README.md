# COVID-19 World Data Tracker

This project is a data and visualization tool for measuring the infection and impact of COVID-19 in the globe. Using [Our World in Data](https://ourworldindata.org/coronavirus) data, the notebook is capable of showing data on cumulative cases, deaths, vaccination counts, and deaths per country. 

---

## Goals

- To analyze and compare past worldwide COVID-19 trends
- To graph infection, deaths, and immunization statistics per nation
- To identify top-case countries and mortality rates
- To sharpen data science library and visualization skills with Python

---

## Tools & Libraries Used

- **Python** (v3.13)
- **Jupyter Notebook**
- **Pandas** – data manipulation
- **Matplotlib** – plotting
- **Seaborn** – for advanced data visualization
- **Plotly** – for interactive plots
- **nbconvert** and **Pandoc** – for report exports

---

## ▶️ How to Run the Project

1. Clone or download this repository.
2. Install required libraries if you haven't:

```bash
pip install pandas matplotlib seaborn plotly
```
3.
  ```bash
jupyter notebook tracker.ipynb
```
4. Run the cells sequentially to load, clean, and visualize the data.
5. To export to PDF or DOCX, use:
```bash
jupyter nbconvert tracker.ipynb --to markdown
pandoc tracker.md -o tracker.docx
```
