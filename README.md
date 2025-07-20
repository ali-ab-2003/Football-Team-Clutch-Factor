# ⚽ Penalty Pressure Prediction (Clutch Factor)

This project analyzes FIFA World Cup penalty shootouts to evaluate how teams perform under pressure. By studying penalty conversion rates, elimination outcomes, and contextual data, we compute a **Clutch Factor** — a metric representing how reliable a team is when the stakes are highest.

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://github.com/ali-ab-2003/Football-Team-Clutch-Factor/blob/main/Clutch_Factor_Analysis.ipynb)

---

## 📂 Dataset

- Source: [Kaggle - World Cup Penalty Shootouts](https://www.kaggle.com/datasets/pablollanderos33/world-cup-penalty-shootouts)
- Key Columns:
  - `Game_id`
  - `Team`
  - `Zone` (Left, Center, Right)
  - `Foot` (Right, Left)
  - `Keeper` (Direction guessed by keeper)
  - `OnTarget` (Was the shot on target?)
  - `Goal` (Was it a goal?)
  - `Penalty_Number` (Sequence in the shootout)
  - `Elimination` (Was the team eliminated by this shot?)

---

## 🧠 Objective

- Quantify each team's ability to perform under elimination pressure.
- Identify patterns and trends in shootout outcomes.
- Visualize the data to support insights.

---

## 🔍 Methodology

- Cleaned and filtered the dataset for consistency.
- Removed outliers (teams with very few shootouts distorting stats).
- Aggregated team-level stats:
  - Total penalties
  - Total elimination-pressure penalties
  - Goals under elimination
- Defined **Clutch Factor** as:

This project is open-source under the MIT License.