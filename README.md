# Real Estate Price Prediction Project

## Project Overview
This project focuses on collecting, preprocessing, analyzing, and modeling data to predict real estate prices in Ho Chi Minh City. By leveraging data crawling, data integration, and machine learning techniques, we aim to provide insights and predictive capabilities for the housing market.

## Team Members
| **STT** | **Họ và Tên**        | **MSSV**    |
|---------|----------------------|-------------|
| 1       | Võ Hùng Khoa        | 22127202    |
| 2       | Lương Minh Hiển     | 21127273    |
| 3       | Lê Hoàng Long       | 18127047    |


## Directory Structure

### Notebooks
1. **`data_collection.ipynb`**
   - Implements web crawling to gather raw housing market data from [batdongsan.com](https://batdongsan.com).
   - Exports the raw data to `data.csv` for further processing.

2. **`data_preprocessing.ipynb`**
   - Cleans and integrates `data.csv` and `gbd.csv` (official government data).
   - Outputs the processed dataset as `cleaned_data.csv`.

3. **`data_exploration.ipynb`**
   - Performs exploratory data analysis (EDA) on `cleaned_data.csv`.
   - Visualizes trends and patterns, answering key questions about the housing market.

4. **`data_modeling.ipynb`**
   - Develops machine learning models to predict real estate prices.
   - Evaluates the models and presents results.

### Data Files
- **`data.csv`**: Raw crawled data from batdongsan.com.
- **`gbd.csv`**: Government-provided data related to housing.
- **`cleaned_data.csv`**: Integrated and preprocessed dataset, ready for analysis and modeling.

## Objectives
1. **Data Collection**
   - Crawl real estate listings from batdongsan.com.
   - Incorporate relevant government data.

2. **Data Preprocessing**
   - Clean and standardize data.
   - Merge datasets to form a unified dataset (`cleaned_data.csv`).

3. **Exploratory Data Analysis (EDA)**
   - Understand key trends and factors influencing housing prices.
   - Generate visualizations and answer data-driven questions.

4. **Predictive Modeling**
   - Use machine learning algorithms to predict housing prices based on provided features.
   - Optimize models for accuracy and interpretability.

## Getting Started

### Prerequisites
- Python 3.x
- Jupyter Notebook
- Required libraries: pandas, numpy, matplotlib, seaborn, scikit-learn, and BeautifulSoup.

### Instructions
1. Clone the repository.
   ```bash
   git clone https:https://github.com/KhoaUs/Intro_DS.git
   cd Intro_DS
   ```

2. Open and run the notebooks in the following order:
   - `data_collection.ipynb`
   - `data_preprocessing.ipynb`
   - `data_exploration.ipynb`
   - `data_modeling.ipynb`
3. View and interpret the results presented in the EDA and modeling stages.

## Deliverables
- Visualizations and insights into the Ho Chi Minh City housing market.
- Predictive models with metrics demonstrating their performance.

## Acknowledgments
We acknowledge batdongsan.com for providing the data and the government database for additional insights. This project would not have been possible without the collaboration and dedication of our team.

