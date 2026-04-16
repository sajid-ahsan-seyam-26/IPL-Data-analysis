# IPL-Data-analysis
IPL Data Analysis Project
This project performs a comprehensive data analysis of the Indian Premier League (IPL) delivery-level dataset using Python. It explores team performances, individual player statistics, and provides visualizations of key cricketing metrics.

🚀 Features
Team Performance Analysis:

Total runs scored by each batting team (Top performer: Royal Challengers Bangalore with 38,916 runs).

Total wickets taken by each bowling team (Top performer: Mumbai Indians with 909 wickets).

Analysis of extra runs conceded by teams.

Player Statistics:

Identification of the top 10 batsmen by total runs (Lead: Ajinkya Saha with 1,043 runs).

Identification of the top 10 bowlers by wickets taken (Lead: Naveen Stubbs with 27 wickets).

Data Insights: Calculation of average runs per ball, standard deviation of runs, and total match statistics using NumPy and Pandas.

Visualizations: Bar charts representing team performance metrics.

🛠️ Technology Stack
Language: Python

Libraries:

pandas: Data manipulation and analysis.

numpy: Numerical computations.

matplotlib: Data visualization.

Environment: Google Colab / Jupyter Notebook

📊 Dataset
The analysis is based on a deliveries.csv file containing detailed information for each ball bowled in IPL matches, including:

Match and Delivery IDs

Batting and Bowling teams

Batsman (striker/non-striker) and Bowler names

Runs (batsman, extra, and total)

Wicket information and dismissal types

📈 Key Findings
Total Runs in Dataset: 313,374

Total Wickets: 7,374

Average Runs per Ball: ~2.34

📂 Project Structure
Plaintext
.
├── IPL_.ipynb          # Main analysis notebook
└── deliveries.csv      # Dataset (required to run the notebook)
⚙️ How to Run
Clone this repository.

Ensure you have the deliveries.csv dataset in the same directory as the notebook.

Open IPL_.ipynb in Google Colab or a local Jupyter environment.

Install the required libraries if not already present:

Bash
pip install pandas numpy matplotlib
Run the cells sequentially to reproduce the analysis.
