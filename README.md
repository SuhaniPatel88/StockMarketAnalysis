# Stock Market Analysis

This repository demonstrates preprocessing and analysis of stock prices for **Tata Motors**, **Maruti Suzuki**, and **Mahindra and Mahindra**. All these steps are performed in the notebook file provided, and visualizations from the data analysis(along with the codes) are compiled in a separate PDF.

---

## Repository Structure

- **CSV Files:** Raw data for all three stocks:
  - `MandM.csv`
  - `Maruti.csv`
  - `Tata.csv`

- **Cleaned Data:** Cleaned and processed versions of each CSV
  - `cleaned_files/MandM.csv`
  - `cleaned_files/Maruti.csv`
  - `cleaned_files/Tata.csv`

- **Notebook:**  
  - `master_file.ipynb` – Contains data cleaning and analysis steps for all stocks.  
    *Note: The notebook focuses on data processing and does not include the final graph outputs inline.*

- **Graphs PDF:**  
  - `Master_File_DAV.pdf` – Consolidates all visualizations and charts generated from the analysis.

---

## Getting Started

1. **Clone the repository**

    ```bash
    git clone https://github.com/SuhaniPatel88/StockMarketAnalysis.git
    cd StockMarketAnalysis
    ```

2. **Create a virtual environment**

    It’s recommended to use a virtual environment before installing dependencies:

    ```bash
    python -m venv venv
    source venv/bin/activate   # On Windows: venv\Scripts\activate
    ```

3. **Install requirements**

    ```bash
    pip install -r requirements.txt
    ```

4. **Run the notebook**

    You can use either **VS Code** or **Jupyter Notebook** to run `master_file.ipynb`.  
    If you wish to use Jupyter:

    ```bash
    jupyter notebook
    ```
    > *Open `master_file.ipynb` and execute the cells to reproduce the analysis.*

