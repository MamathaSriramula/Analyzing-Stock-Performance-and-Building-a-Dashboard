# Analyzing Stock Performance and Building a Dashboard

## **Project Overview**

This project focuses on analyzing the historical stock performance and revenue data of **Tesla (TSLA)** and **GameStop (GME)**. Using a combination of **data extraction, web scraping, and visualization techniques**, the project presents insights into how these companies have performed over time. A simple dashboard or plotting functions are also provided to visualize trends.

---

## **Key Objectives**

1. **Extract Stock Data**

   * Use `yfinance` to download the full historical data for **Tesla** and **GameStop**.
   * Reset indices and save the data into CSV files.

2. **Web Scraping Revenue Data**

   * Use `requests` and `BeautifulSoup` to extract **quarterly revenue** data for both Tesla and GameStop from Macrotrends.

3. **Data Visualization**

   * Define a reusable `make_graph` function to plot stock prices and trends.
   * Plot Tesla and GameStop stock data with appropriate labels and titles.

4. **Comparative Analysis (Optional)**

   * Compare stock performance and revenue trends.
   * Highlight notable changes or patterns in the data.

5. **Dashboard (Optional)**

   * Provide a template using **Streamlit** or **Plotly Dash** to build a simple stock visualization dashboard.

---

## **Project Structure**

* **Question 1:** Extract Tesla stock data (`yfinance`).
* **Question 2:** Web scrape Tesla revenue data.
* **Question 3:** Extract GameStop stock data (`yfinance`).
* **Question 4:** Web scrape GameStop revenue data.
* **Question 5:** Plot Tesla stock graph using `make_graph`.
* **Question 6:** Plot GameStop stock graph using `make_graph`.
* **datasets/**

  * `tesla_data.csv` – Tesla historical stock data.
  * `gme_data.csv` – GameStop historical stock data.
* **notebooks/**

  * Final Assignment notebooks (`Final Assignment.ipynb`, etc.).

---

## **Libraries Used**

* `yfinance` – For fetching stock market data.
* `pandas` – For data manipulation.
* `requests` – For HTTP requests to fetch revenue data.
* `beautifulsoup4` – For parsing HTML content.
* `matplotlib` / `plotly` – For visualization.
* `streamlit` (optional) – For interactive dashboarding.

---

## **How to Run**

1. Install dependencies:

   ```bash
   pip install yfinance pandas requests beautifulsoup4 matplotlib streamlit
   ```
2. Run the Jupyter notebook:

   ```bash
   jupyter notebook "Final Assignment.ipynb"
   ```
3. To launch the dashboard (optional):

   ```bash
   streamlit run dashboard.py
   ```

---

Would you like me to **create and give you a `README.md` file (download link)** with this content formatted and ready to include in your project folder?
