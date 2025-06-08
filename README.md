# SNSF Research Funding Dashboard

An interactive and insightful dashboard built using **Streamlit** to explore the Swiss National Science Foundation (SNSF) research funding dataset. This tool allows users to analyze trends, explore research topics, visualize diversity, and discover AI research and collaboration networks.

## Features

- **Overview**: Summary metrics for grants, funding, researchers, and institutions.
- **Explore Trends**: Interactive filters to analyze funding trends by year, discipline, and institution.
- **Research Topics**: NLP-powered keyword analysis with bar charts and word clouds.
- **Diversity Insights**: Visualizations of gender representation and funding disparities.
- **Collaboration Network**: Network graph of top researchers based on grant co-applications.
- **AI Research Insights**: Identify AI-related funding, trends, and key researchers.

## Folder Structure
```plaintext
├── datasets/
│   ├── Grant.csv
│   ├── Person.csv
│   ├── Institute.csv
│   ├── GrantToPerson.csv
│   ├── GrantToDiscipline.csv
│   ├── Discipline.csv
│   ├── GrantToKeyword.csv
│   ├── Keyword.csv
│   └── sna1.png
├── Dashboard.py
├── README.md
└── requirements.txt

## Installation
Clone the repository:
git clone https://github.com/AnmolSrivastav/GrantGaze.git
cd GrantGaze

Create and activate a virtual environment:
  On Windows:
    python -m venv venv
    venv\Scripts\activate
  
  On macOS/Linux:
    python3 -m venv venv
    source venv/bin/activate

Install the dependencies:
pip install -r requirements.txt

Running the Dashboard
Start the Streamlit app by running:
streamlit run Dashboard.py

Then open http://localhost:8501 in your browser to view and interact with the dashboard.

