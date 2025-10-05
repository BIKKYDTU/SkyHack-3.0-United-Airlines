✈️SkyHack-3.0-United-Airlines

✈️ United Airlines – Flight Difficulty Score (SkyHack 3.0)

Team Name: Bikky Kumar & Amritesh Raj
Team Members:

Bikky Kumar (Roll No: 2K22/SE/45)

Amritesh Raj (Roll No: 2K22/SE/17)
Institution: Delhi Technological University (DTU)
Hackathon: United Airlines SkyHack 3.0 – Data Analytics Challenge

🎯 Project Objective

Frontline teams at United Airlines are responsible for ensuring that every flight departs on time and operates smoothly. However, operational complexity varies due to multiple factors such as:

Short ground time (tight turns)

High passenger load

Excess checked or transfer baggage

Special Service Requests (SSR)

This project builds a Flight Difficulty Score (FDS) to quantify flight complexity, identify operational drivers, and help planners act proactively.

📁 Folder Structure
skyhack/
│
├── 📄 Report/
│   └── Flight_Difficulty_Score_Team_Bikky_Amritesh.pptx
│
├── 📊 Data/
│   └── test_bikky.csv
│
├── 💻 Code/
│   ├── main_notebook_script.ipynb
│   └── README.txt
│
└── out/
    ├── flights_clean.csv
    ├── destinations_summary.csv
    ├── destination_driver_ranks.csv
    └── destination_recommendations.csv

⚙️ How to Run

Option 1 — Local Execution

main_notebook_script.ipynb


Option 2 — Google Colab
Run all cells in your notebook:
🔗 https://colab.research.google.com/drive/1nTZN0fiuGIlP1Vz8ipQZeZIi-QyCPx-n?usp=sharing
📊 Output Files
File	Purpose
flights_clean.csv	Cleaned flight data
test_bikky.csv	Final file with Flight Difficulty Scores
destinations_summary.csv	Destination-level analysis
destination_driver_ranks.csv	Driver importance ranking
destination_recommendations.csv	Actionable insights
🧩 Key Features in FDS
Feature	Meaning	Weight
bags_per_min	Baggage load per min	30%
pax_per_min	Passenger load per min	25%
transfer_ratio	% of transfer bags	15%
ssr_per_100pax	SSR requests per 100 pax	15%
is_tight_turn	Tight turnaround	10%
is_international	International route	5%
🚀 Insights & Recommendations

Tight-turn flights with heavy baggage are most complex.

International SSR-heavy flights delay more frequently.

Add ramp crew for tight turns, pre-stage GSE, assign SSR staff, and start boarding early.

🧠 Tools

Python: pandas, numpy, seaborn, matplotlib

Google Colab: exploration & visualizations

Excel / PPT: reporting

Git / ZIP packaging: submission

📬 Contact

Team: Bikky Kumar & Amritesh Raj
Email : bikkykumar_se22a11_32@dtu.ac.in
 | amriteshraj_se22a11_09@dtu.ac.in

Institute: DTU, Delhi
Path: /content/drive/MyDrive/skyhack
