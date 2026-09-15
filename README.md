<img width="1000" height="470" alt="download (3)" src="https://github.com/user-attachments/assets/77e650de-6bcb-4b0c-acae-e6563a204a98" />
<img width="1078" height="470" alt="download (2)" src="https://github.com/user-attachments/assets/0b96ac43-2321-4d89-88f5-2c7d49f2205a" />
<img width="1103" height="470" alt="download (1)" src="https://github.com/user-attachments/assets/54eb47ce-d894-4dfa-9f24-1e97fd4122c0" />
High-Frequency Market Microstructure Engine: Order Flow Toxicity & Hawkes Processes

This repository contains an end-to-end quantitative microstructure engine designed to analyze L2 Limit Order Book dynamics, measure order flow toxicity, and model self-exciting order cascades in high-frequency trading environments.

The framework first implements vector-based Order Flow Imbalance volume delta calculations at top-of-book price levels to compute instantaneous order flow pressure and predict short-term price movements. It then utilizes Volume-Synchronized Probability of Toxicity logic with volume-bucketing aggregation to measure directional volume imbalance, effectively quantifying adverse selection risk from informed trading algorithms. Additionally, the system models micro-shock clustering and algorithmic cascade intensity using a Hawkes self-exciting point process framework, evaluating system criticality via a branching ratio of 0.80 to capture structural feedback loops prior to liquidity depletion.

The core pipeline is built in Python using NumPy, Pandas, DuckDB, and SciPy for data processing and quantitative analytics, with Matplotlib and Seaborn used for visual analytics.
