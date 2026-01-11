# Video Game Analysis - Comprehensive Data Analytics Project

## 📊 Project Overview
A comprehensive data analytics project analyzing video game sales, ratings, and industry trends. This project demonstrates end-to-end data analysis using Python, exploring game genres, platforms, publishers, and market dynamics to extract actionable business insights.

## 🎯 Project Objectives
- Analyze video game sales across regions and time periods
- Identify trends in gaming genres and platforms
- Examine publisher market share and performance
- Understand customer preferences and rating patterns
- Generate predictive insights for the gaming industry

## 📁 Project Structure
```
Video-Game-Analysis/
├── data/
│   ├── raw/
│   │   └── Video_Game_Sales.csv          # Original dataset
│   └── processed/
│       └── cleaned_game_data.csv         # Cleaned and processed data
├── notebooks/
│   ├── 01_Data_Exploration.ipynb         # Initial data analysis
│   ├── 02_Data_Cleaning.ipynb            # Data preprocessing
│   └── 03_Analysis_And_Insights.ipynb    # Statistical analysis
├── scripts/
│   ├── data_loader.py                    # Data loading functions
│   ├── data_cleaner.py                   # Data cleaning utilities
│   ├── analysis.py                       # Analysis functions
│   └── visualization.py                  # Plotting functions
├── visualizations/
│   ├── sales_by_genre.png               # Charts and graphs
│   ├── platform_trends.png
│   └── regional_analysis.png
├── reports/
│   └── analysis_report.md                # Detailed findings
├── requirements.txt                      # Python dependencies
├── .gitignore                            # Git ignore rules
├── LICENSE                               # Project license
└── README.md                             # This file
```

## 📈 Dataset Overview

### Key Columns
- **Name**: Game title
- **Platform**: Gaming platform (PS2, Xbox, Wii, DS, etc.)
- **Year**: Release year
- **Genre**: Game category (Action, Sports, Shooter, etc.)
- **Publisher**: Developing/Publishing company
- **NA_Sales**: North American sales (in millions)
- **EU_Sales**: European sales (in millions)
- **JP_Sales**: Japanese sales (in millions)
- **Other_Sales**: Rest of world sales
- **Global_Sales**: Total worldwide sales
- **Critic_Score**: Critic ratings (0-100)
- **User_Score**: User ratings (0-10)

## 🔍 Analysis Components

### 1. Sales Analysis
- Total sales by region (North America, Europe, Japan, Others)
- Sales trends over time
- Best-performing platforms and genres
- Top publishers by revenue
- Sales distribution analysis

### 2. Genre Analysis
- Most popular game genres
- Genre trends across time periods
- Genre performance by region
- Emerging genres
- Genre profitability analysis

### 3. Platform Analysis
- Market share by platform
- Platform lifecycle analysis
- Peak sales periods for each platform
- Platform-genre combinations
- Cross-platform trends

### 4. Publisher Analysis
- Top publishers by game count
- Publisher market concentration
- Publisher performance metrics
- Emerging vs. established publishers
- Publisher specialization (genre focus)

### 5. Rating Analysis
- Critic vs. user score correlation
- Rating distribution by genre
- Impact of ratings on sales
- High-rated game analysis
- Score trends over time

## 🛠️ Technologies Used

### Data Processing
- **Pandas**: Data manipulation and analysis
- **NumPy**: Numerical computing
- **Scikit-learn**: Data preprocessing and analysis

### Visualization
- **Matplotlib**: Static plotting
- **Seaborn**: Statistical visualizations
- **Plotly**: Interactive charts

### Analysis & Reporting
- **Jupyter Notebook**: Interactive analysis environment
- **Scipy**: Statistical testing
- **Statsmodels**: Statistical modeling

## 📊 Key Findings

### Market Insights
1. **Platform Dominance**: PlayStation and Nintendo platforms dominate the market
2. **Regional Variations**: Significant differences in genre preferences across regions
3. **Genre Trends**: Action and Sports games generate highest sales consistently
4. **Publisher Concentration**: Top 10 publishers account for significant market share
5. **Time Evolution**: Clear evolution in platform preferences over time

### Sales Patterns
- Peak sales period: 2000-2009
- Growing digital market impact
- Regional preferences vary significantly
- Franchise importance in sales

### Rating Insights
- Critic and user scores show moderate correlation
- Quality doesn't always guarantee sales
- Different genres have different rating patterns

## 🚀 Getting Started

### Prerequisites
- Python 3.8+
- Jupyter Notebook
- Required libraries (see requirements.txt)

### Installation
```bash
# Clone the repository
git clone https://github.com/Vishnu27122004/Video-Game-Analysis.git
cd Video-Game-Analysis

# Create virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt
```

### Running Analysis
```bash
# Start Jupyter Notebook
jupyter notebook

# Open and run notebooks in order:
# 1. 01_Data_Exploration.ipynb
# 2. 02_Data_Cleaning.ipynb
# 3. 03_Analysis_And_Insights.ipynb
```

## 📝 Analysis Outputs

### Generated Reports
- Statistical summary of sales data
- Genre and platform trend analysis
- Regional market analysis
- Publisher performance rankings
- Correlation analysis (ratings vs. sales)

### Visualizations
- Sales distribution charts
- Time series trend analysis
- Heatmaps for regional analysis
- Genre comparison plots
- Platform lifecycle curves

## 💡 Key Insights

1. **Market Evolution**: Gaming market shows clear platform shift patterns
2. **Genre Preferences**: Action games consistently lead in sales
3. **Regional Differences**: Japan shows unique genre preferences
4. **Quality vs. Sales**: Popular games don't always have highest critic scores
5. **Publisher Strategy**: Different publishers focus on different genres

## 🔮 Predictive Analysis

### Models Explored
- Linear regression for sales prediction
- Genre-based market forecasting
- Platform adoption curves
- Publisher performance prediction

## 📚 Resources

### Data Source
- Video Game Sales Dataset from Kaggle/vgchartz
- Contains 16,598 games with sales data
- Years covered: 1983-2016

### References
- Gaming industry reports
- Platform analysis studies
- Sales forecasting literature

## 🤝 Contributing
Feel free to fork and submit pull requests for improvements:
1. Fork the repository
2. Create feature branch
3. Commit changes
4. Push to branch
5. Submit pull request

## 📄 License
This project is licensed under the MIT License - see LICENSE file for details.

## 👤 Author
**Vishnu** - [GitHub Profile](https://github.com/Vishnu27122004)

## 📧 Contact
For questions or feedback:
- GitHub Issues
- Email: [vishnupatelreddy2004@gmail.com ]

## 🙏 Acknowledgments
- Video game industry data providers
- VGChartz for sales data
- Gaming community for insights
- VTU for academic support

---
**Last Updated**: January 2026
**Project Status**: Active
**Data Completeness**: 100%
