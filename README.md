# 📊 IPO Long-Run Performance (BHAR) — Paper Replication

## Overview

Reproducible replication of IPO long-run performance using the **Buy-and-Hold Abnormal Returns (BHAR)** methodology.
Built as a clean data pipeline from raw data → analysis → results.

This project is completed as part of the final project requirement for the course *Special Topics in Finance and Accounting Research*, taught by Professor Karthik Balakrishnan and assisted by Manoj Devarala.

---

## Data

* IPO data: IPO platforms by Chittorgarh.com
* Market data: ProwessDx

---

## Financial Variables Used In Dataset


---

## Method

$$
BHAR_{i,T} = \prod_{t=1}^{T}(1 + R_{i,t}) - \prod_{t=1}^{T}(1 + R_{m,t})
$$

Computed over multiple horizons to evaluate post-IPO performance.

---

## Structure

```bash
notebooks/   # step-by-step analysis  
src/         # modular pipeline (data, BHAR, regression)  
data/        # raw + processed datasets  
outputs/     # tables and figures  
```

---

## How to Run

```bash
pip install -r requirements.txt
```

Run notebooks in order (01 → 05)

---

## Goal

* Replicate key results from IPO literature
* Test robustness using independent data
* Test if similar results were replicated within an Indian sub-context.
---

## Author

Abhinav Siddharth Gudipati
