# Ballon d'Or Predictor 2024-2025
Python pipeline analyzing FBref player stats to predict and visualize the Ballon d'Or rankings.

A data-driven machine learning/statistical model built in Python to predict the Ballon d'Or rankings using FBref player statistics.

## Methodology & Features
- **Data Source:** FBref 2024-2025 player stats dataset (`players_data-2024_2025.csv`).
- **Position-Based Normalization:** Min-Max scaling tailored by position categories (Forward, Midfielder, Defender, Goalkeeper) using 90-minute metrics (`Gls_per_90`, `Ast_per_90`, `xG_per_90`).
- **Ballon d'Or Index (BOI):** Weighted scoring logic adjusted for offensive efficiency.
- **Club Prestige Multiplier:** A 1.2x boost factor applied to top European clubs (Real Madrid, PSG, Manchester City, Bayern Munich, Liverpool, Barcelona).

## Tech Stack
- **Language:** Python
- **Libraries:** Pandas, Matplotlib, Seaborn

## Key Results
The model successfully predicted **Ousmane Dembélé** as the #1 player, matching the official real-world winner, alongside accurate hits on Mohamed Salah and Kylian Mbappé in the Top 10.
