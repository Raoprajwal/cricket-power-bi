# 🏏 Cricket Team Selection Dashboard — "Give Me the Best 11 from This Planet"

## 📌 Objective

This project focuses on selecting the **best playing XI** in cricket based on specific performance parameters. The goal is to form a team that can:

- **Score an average of 180+ runs**
- **Defend a total of 150 runs**

Selection is based on clearly defined **roles** and **metrics** for each player type.

---

## 👨‍💻 About Me

**Name**: Prajwal Rao  
**Course**: MSc Business Analytics  
**Institute**: MAHE, Manipal  
**Email**: prajwalrao02@gmail.com

---

## 🧠 Project Overview

### Tools Used
- **Python** (Jupyter Notebook): Data cleaning and transformation
- **Power BI**: Data visualization and dashboard building

---


---

## 🧼 Data Cleaning (Python)

Performed using `data_cleaning.ipynb`:

- Removed null and duplicate records
- Cleaned column types and values
- Created calculated columns:
  - Boundary Percentage = (4s * 4 + 6s * 6) / Total Runs × 100
  - Dot Ball Percentage = Dot Balls / Total Balls Bowled × 100
- Filtered players by innings played and performance relevance
- Exported cleaned dataset to `cricket_dataset.csv`

---

## 📊 Power BI Dashboard

Developed using `cricket project new(code basics).pbix`.

### Features:
- Interactive filters for role, team, and player
- Role-specific metrics aligned with project scope
- Clean, structured layout to compare players side-by-side

### Player Roles and Criteria:
| Role                  | Key Criteria |
|-----------------------|--------------|
| **Openers**           | Avg > 30, SR > 140, Boundaries > 50%, Pos < 4 |
| **Anchors**           | Avg > 40, SR > 125, Balls Faced > 20, Pos > 2 |
| **Finishers**         | Avg > 25, SR > 130, Balls Faced > 12, Pos > 4 |
| **All-Rounders**      | Bat Avg > 15, SR > 140, Eco < 7, SR < 20, Pos > 4 |
| **Fast Bowlers**      | Eco < 7, SR < 16, Dot Ball% > 40, Bowling Style = Fast |

> ✅ These criteria are directly derived from the project requirement document: [`Paramaeter Scoping.pdf`](./Paramaeter%20Scoping.pdf)

---

## 🚀 How to Run

1. Clone this repo:
   ```bash
   git clone [https://github.com/your-username/cricket-team-selection.git](https://github.com/Raoprajwal/cricket-power-bi/edit/main/README.md)
   


