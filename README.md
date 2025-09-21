# 🏀 NBA Player Efficiency Analysis

A comprehensive data science project analyzing NBA player performance through the lens of Player Efficiency Rating (PER) using 2024-25 season data.

## 📊 Project Overview

This project explores NBA player statistics to calculate and analyze Player Efficiency Rating (PER), providing insights into player performance, statistical distributions, and efficiency patterns across the league.

## 🎯 Objectives

- **Calculate Player Efficiency Rating (PER)** using weighted statistical formulas
- **Perform exploratory data analysis** on NBA player statistics
- **Visualize statistical distributions** and identify performance patterns
- **Analyze correlations** between different basketball metrics
- **Create insights** about player efficiency and basketball analytics

## 🛠️ Tech Stack

- **Python** - Primary programming language
- **pandas** - Data manipulation and analysis
- **matplotlib & seaborn** - Data visualization
- **NBA API** - Data source for player statistics
- **Jupyter Notebook** - Interactive development environment

## 📁 Project Structure

```
📦 nba-analytics
├── 📄 NBA_Player_Efficiency_Analysis.ipynb  # Main analysis notebook
├── 📄 README.md                             # Project documentation
└── 📄 requirements.txt                      # Python dependencies
```

## 🚀 Getting Started

### Prerequisites

```bash
conda create -n nba_analysis python=3.10
conda activate nba_analysis
```

### Installation

```bash
# Clone the repository
git clone https://github.com/your-username/nba-analytics.git
cd nba-analytics

# Install dependencies
conda install pandas matplotlib seaborn jupyter
pip install nba_api
```

### Usage

```bash
# Start Jupyter Notebook
jupyter notebook

# Open NBA_Player_Efficiency_Analysis.ipynb
```

## 📈 Key Features

### **Data Collection**
- Fetches 2024-25 NBA season statistics using the NBA API
- Filters players with meaningful playing time (10+ minutes, 10+ games)
- Converts raw stats to per-game averages for analysis

### **Statistical Analysis**
- **Distribution Analysis**: Histograms and box plots of key performance metrics
- **Correlation Analysis**: Heatmap showing relationships between basketball statistics
- **Scatter Plot Analysis**: Volume vs efficiency trade-offs

### **PER Calculation**
- Implementation of weighted Player Efficiency Rating formula
- Accounts for positive actions (points, rebounds, assists, steals, blocks)
- Penalizes negative actions (missed shots, turnovers, fouls)
- Normalizes performance per minute played

## 🔍 Key Findings

### **Distribution Patterns**
- Most counting stats show right-skewed distributions
- Shooting percentages follow normal distributions around league averages
- Elite performers represent small percentages of the player population

### **Efficiency Insights**
- Strong correlation between playing time and statistical production
- Volume and efficiency show weak correlation - high scorers don't necessarily shoot better
- Playmakers face inevitable turnover costs for their ball-handling responsibilities

### **Position Specialization**
- Clear clustering in rebounding vs shot-blocking (interior players)
- Bimodal shooting patterns reflect modern NBA specialization
- Role players and stars show distinct statistical profiles

## 📊 Sample Visualizations

The project includes comprehensive data visualizations:
- **Histograms** of per-game statistics distributions
- **Box plots** showing quartiles and outliers
- **Correlation heatmap** revealing statistical relationships
- **Scatter plots** exploring efficiency vs volume trade-offs

## 🎓 Learning Outcomes

This project demonstrates proficiency in:
- **Data Science Workflow**: Collection, cleaning, analysis, visualization
- **Basketball Analytics**: Domain-specific knowledge application
- **Statistical Analysis**: Distribution analysis, correlation studies
- **Python Libraries**: pandas, matplotlib, seaborn, NBA API
- **Data Storytelling**: Extracting insights from complex datasets

## 🔮 Future Enhancements

- **Advanced PER**: Implement pace and league-adjusted PER calculations
- **Player Comparisons**: Interactive tool for comparing individual players
- **Predictive Modeling**: Forecast player performance based on efficiency metrics
- **Team Analysis**: Extend analysis to team-level efficiency patterns
- **Historical Trends**: Multi-season analysis of efficiency evolution

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request or open an Issue for any improvements or suggestions.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **NBA API** for providing comprehensive basketball statistics
- **Basketball Reference** for PER calculation methodology
- **Python Data Science Community** for excellent tools and libraries

---

**Built with ❤️ for basketball analytics and data science**