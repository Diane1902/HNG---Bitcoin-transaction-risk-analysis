<img width="1873" height="906" alt="Screenshot 2026-09-25 103225" src="https://github.com/user-attachments/assets/1a0a673e-673b-4ff5-a13a-0d79bd5a0e0d" />


<img width="642" height="416" alt="Screenshot 2026-09-25 103202" src="https://github.com/user-attachments/assets/ffc7f7a2-8613-4582-8ce6-046e718bf60d" />   <img width="1860" height="887" alt="image" src="https://github.com/user-attachments/assets/4564fbf6-7106-451b-80d1-ac25cdbb6b09" />



# HNG---Bitcoin-transaction-risk-analysis
Network analysis of Bitcoin transactions to identify potential fraud and AML risk indicators using the Elliptic dataset.
# Bitcoin Transaction Risk Analysis

## Project Overview

This project explores Bitcoin transaction patterns using network analysis to identify behaviors that may warrant further fraud and AML investigation.

Using the Elliptic Bitcoin transaction dataset, I analyzed transaction relationships and network structures to identify potential risk indicators such as layering and fan-out patterns.

## Key Findings

- 12,569 nodes analyzed
- 18,878 transaction relationships
- 127 confirmed illicit nodes
- 3,994 confirmed licit nodes
- 8,448 unlabeled nodes
- 993 layering flags
- 638 fan-out flags

## Analysis Highlights

The analysis identified transactions with highly concentrated inflows and large-scale fund distribution across multiple destinations.

These patterns were treated as risk indicators rather than proof of fraudulent activity.

## Tools & Technologies

- Python
- Pandas
- NetworkX
- Matplotlib
- Data Analysis
- Network Analysis
- Fraud Detection
- AML Analytics

## Dashboard

The project includes a risk dashboard showing:

- Bitcoin transaction network
- High-risk nodes
- Transaction activity over time
- Illicit, licit and unknown classifications
- Layering and fan-out risk indicators

## Disclaimer

Risk indicators identified in this analysis do not independently establish fraud or money laundering. They are intended to support further investigation and demonstrate analytical approaches to transaction monitoring.
