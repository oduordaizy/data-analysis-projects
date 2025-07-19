# Setup Guide

## 🚀 Getting Started

This guide will help you set up and run the data analyst projects in this workspace.

## 📋 Prerequisites

### Required Software
- **Python 3.8+** - For data analysis and Jupyter notebooks
- **Git** - For version control
- **Microsoft Excel** - For viewing Excel files
- **Tableau Desktop** - For viewing Tableau workbooks (optional)
- **Power BI Desktop** - For viewing Power BI files (optional)

### Recommended Software
- **VS Code** or **PyCharm** - For code editing
- **Anaconda** or **Miniconda** - For Python environment management
- **Jupyter Lab** - For interactive data analysis

## 🛠️ Installation Steps

### 1. Clone the Repository
```bash
git clone https://github.com/oduordaizy/data-analysis-projects.git
cd data-analyst-projects
```

### 2. Set Up Python Environment

#### Option A: Using pip
```bash
# Create virtual environment
python -m venv venv

# Activate virtual environment
# On Windows:
venv\Scripts\activate
# On macOS/Linux:
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt
```

#### Option B: Using Conda
```bash
# Create conda environment
conda create -n data-analysis python=3.9

# Activate environment
conda activate data-analysis

# Install dependencies
pip install -r requirements.txt
```

### 3. Verify Installation
```bash
# Check Python version
python --version

# Check installed packages
pip list

# Test Jupyter
jupyter --version
```

## 📁 Project Structure

```
data-analyst-projects/
├── README.md                    # Main portfolio overview
├── SETUP.md                     # This setup guide
├── requirements.txt             # Python dependencies
├── .gitignore                   # Git ignore rules
├── bank-loans/                  # Financial analysis project
├── car-sales-analysis/          # Automotive sales project
├── covid-19-data-analysis/      # Healthcare data project
└── marketing-analytics/         # Marketing analysis project
```

## 🎯 Running Projects

### Python/Jupyter Projects

#### COVID-19 Data Analysis
```bash
cd covid-19-data-analysis
jupyter notebook "Covid 19 Analysis.ipynb"
```

#### Marketing Analytics
```bash
cd marketing-analytics
jupyter notebook "marketing-analysis.ipynb.ipynb"
```

### Dashboard Projects

#### Car Sales Analysis (Tableau)
1. Open `car-sales-analysis/Car Sales Dashboard.twb` in Tableau Desktop
2. Or view online: [Tableau Public Dashboard](https://public.tableau.com/app/profile/sharayu.ukirde/viz/CarSalesDashboard_17380434452130/HOME?publish=yes)

#### Marketing Analytics (Power BI)
1. Open `marketing-analytics/Marketing Analytics dashboard.pbix` in Power BI Desktop
2. Refresh data connections if needed

#### Bank Loans Analysis (Excel)
1. Open `bank-loans/bank-loans-excel-workbook.xlsx` in Microsoft Excel
2. Enable macros if prompted

## 🔧 Configuration

### Jupyter Configuration
```bash
# Generate Jupyter config
jupyter notebook --generate-config

# Set password for Jupyter (optional)
jupyter notebook password
```

### Git Configuration
```bash
# Set your Git identity
git config --global user.name "Your Name"
git config --global user.email "oduordaizy@gmail.com"
```

## 📊 Data Sources

### Project-Specific Data
- **Bank Loans**: Internal financial data
- **Car Sales**: Automotive transaction data
- **COVID-19**: Public health datasets
- **Marketing Analytics**: Maven Analytics Challenge dataset

### External Data Sources
- [Maven Analytics](https://www.mavenanalytics.io/) - Marketing datasets
- [Kaggle](https://www.kaggle.com/) - Various datasets
- [UCI Machine Learning Repository](https://archive.ics.uci.edu/) - Academic datasets

## 🐛 Troubleshooting

### Common Issues

#### Python Environment Issues
```bash
# If packages not found
pip install --upgrade pip
pip install -r requirements.txt --force-reinstall

# If Jupyter not found
pip install jupyter notebook
```

#### File Permission Issues
```bash
# On Windows, run PowerShell as Administrator
# On macOS/Linux
chmod +x setup.sh
```

#### Large File Issues
```bash
# If Git fails on large files
git lfs install
git lfs track "*.xlsx"
git lfs track "*.pbix"
```

### Getting Help
1. Check the project-specific README files
2. Review error messages carefully
3. Search for solutions online
4. Create an issue in the repository

## 📈 Next Steps

### For Beginners
1. Start with the COVID-19 analysis (Python/Jupyter)
2. Review the README files for each project
3. Practice with the provided datasets
4. Experiment with different analysis techniques

### For Advanced Users
1. Explore all projects and methodologies
2. Try different visualization tools
3. Apply your own datasets
4. Contribute improvements to the projects

### For Portfolio Development
1. Customize the README files with your information
2. Add your own projects and analyses
3. Update contact information and links
4. Showcase your skills and achievements

## 📞 Support

If you encounter any issues or have questions:

- **Documentation**: Check the README files in each project
- **Issues**: Create an issue in the repository
- **Email**: [oduordaizy@gmail.com](mailto:oduordaizy@gmail.com)

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

**Happy Analyzing! 🎉** 