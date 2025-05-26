# UCLA 2022 Actuarial Case Competition – Bruin Mutual  
*Team 36: Hannah Mok, Jury Camillo, Connor Chia, Mohammad Ameen*

## 📌 Overview
This repository contains our team’s submission for UCLA’s 2022 actuarial case competition. The challenge involved conducting a reserving review across three lines of business:

- Personal Auto Physical Damage  
- Personal Auto Liability  
- Homeowners Property  

We developed a dynamic Excel workbook that processed raw claims data and output diagnostic triangles and reserving estimates using several standard actuarial techniques.

## 🛠 Reserving Methods Applied
We applied the following five reserving methods to evaluate and select the most appropriate approach for each line of business:

- **Paid Chain Ladder**
- **Reported Chain Ladder**
- **Expected Loss Method**
- **Bornhuetter-Ferguson**
- **Case Outstanding**

## 📊 Key Findings
- For **Personal Auto Physical Damage**, we selected the **Paid Chain Ladder** method due to its consistency with stable historical data.
- For **Personal Auto Liability**, pandemic-era volatility skewed some estimates; we again recommended the **Paid Chain Ladder** as the most reliable method.
- For **Homeowners Property**, due to variability and anomalies in the data, we determined the **Paid Chain Ladder** method to provide the most reasonable estimates.
- We **standardized** the Paid Chain Ladder, Bornhuetter-Ferguson, and Case Outstanding methods for future analysis of the auto physical damage line due to its organized and stable data.

## 🚨 Catastrophic Reserving Insights
We discussed challenges specific to CAT (catastrophic) reserving:
- Delays in information gathering due to location and access
- Long duration and uncertainty of catastrophic events
- Legal uncertainties around claim settlements

## 📁 Contents
- `/data`: Raw and processed claims data
- `/output`: Reserving results and triangle visuals
- `/analysis`: Methodology breakdown and calculations
- `/docs`: Case summary and supporting documents

## 🧠 Tools Used
- Microsoft Excel (including VBA/macros if applicable)
- Actuarial methods and insurance reserving principles

## 📌 How to Use
Open the Excel workbook provided in the `/analysis` or root directory to view the automated reserving calculations. Ensure macros are enabled if prompted.

---

Thanks for checking out our submission!  
Feel free to explore the repo or reach out with any questions.
