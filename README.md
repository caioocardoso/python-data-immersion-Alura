# 📊 Python Data Immersion - Salary Analysis Dashboard

A comprehensive data analysis dashboard built with Streamlit for exploring and visualizing salary data across different roles, experience levels, and employment types in the data science field.

## 🌐 Live Demo

**[🚀 View Live Application](https://python-data-immersion-alura.streamlit.app/)**

## 📋 Project Overview

This interactive dashboard provides insights into salary trends in the data science industry, featuring:

- **Interactive Filtering**: Filter data by year, experience level, employment type, and company size
- **Key Metrics Display**: Average, minimum, maximum salaries, total records, and most frequent employment type
- **Visual Analytics**: Multiple chart types including bar charts, histograms, pie charts, and geographical maps
- **Real-time Data Processing**: Dynamic updates based on selected filters

## 🔍 Features

### 📈 Analytics & Visualizations

1. **Employment Type Analysis**: Horizontal bar chart showing average salaries by employment type
2. **Salary Distribution**: Histogram displaying the distribution of annual salaries
3. **Remote Work Insights**: Pie chart showing the proportion of different remote work arrangements
4. **Geographic Analysis**: Choropleth map displaying average Data Scientist salaries by country

### 🎛️ Interactive Controls

- **Year Filter**: Select specific years or ranges
- **Experience Level**: Filter by Junior, Mid-level, Senior, Executive positions
- **Employment Type**: Full-time, Part-time, Contract, Freelance options
- **Company Size**: Small, Medium, Large company classifications

## 🛠️ Tech Stack

- **Frontend**: [Streamlit](https://streamlit.io/) - Interactive web application framework
- **Data Processing**: [Pandas](https://pandas.pydata.org/) - Data manipulation and analysis
- **Visualization**: [Plotly Express](https://plotly.com/python/plotly-express/) - Interactive plotting library
- **Geographic Data**: [PyCountry](https://pypi.org/project/pycountry/) - Country code conversion
- **Styling**: Custom CSS and Streamlit components

## 📊 Data Source

The dashboard uses salary data from the data science industry, including information about:
- Job titles and roles
- Salary information in USD
- Experience levels
- Employment types
- Company sizes
- Geographic locations
- Remote work ratios

## 🚀 Getting Started

### Prerequisites

- Python 3.7+
- pip package manager

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/caioocardoso/python-data-immersion-Alura.git
   cd python-data-immersion-Alura
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the application**
   ```bash
   streamlit run app.py
   ```

4. **Open your browser**
   - Navigate to `http://localhost:8501`

## 📁 Project Structure

```
python-data-immersion-Alura/
│
├── app.py                    # Main Streamlit application
├── requirements.txt          # Python dependencies
├── dados_imersao_final.csv  # Local data file (if applicable)
└── README.md                # Project documentation
```

## 🎯 Key Insights

The dashboard helps answer questions like:
- What are the salary trends across different experience levels?
- How do employment types affect compensation?
- What's the distribution of remote work in the industry?
- Which countries offer the highest salaries for Data Scientists?
- How do company sizes correlate with salary ranges?

## 🔧 Dependencies

```python
pandas          # Data manipulation
streamlit       # Web application framework
plotly          # Interactive visualizations
matplotlib      # Additional plotting capabilities
seaborn         # Statistical data visualization
pycountry       # Country code handling
```

## 📈 Usage Examples

1. **Filter by Experience**: Select "Senior" level to see salary trends for experienced professionals
2. **Geographic Analysis**: Explore the map to understand regional salary differences
3. **Employment Type Comparison**: Compare salaries between full-time, contract, and freelance positions
4. **Temporal Trends**: Use year filters to analyze salary evolution over time

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

## 📝 License

This project is part of the Alura Data Immersion course and is intended for educational purposes.

## 🙏 Acknowledgments

- **Alura**: For providing the data immersion course and guidance
- **Streamlit Community**: For the excellent documentation and examples
- **Data Science Community**: For maintaining open datasets and tools

---

## Author

**Caio Oliveira Cardoso** - *Student at IFBA*

**Built with ❤️ using Python and Streamlit**

*Last updated: August 2025*