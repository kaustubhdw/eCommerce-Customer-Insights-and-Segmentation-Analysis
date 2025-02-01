# eCommerce Customer Insights and Segmentation Analysis

This project analyzes eCommerce transactions to uncover valuable insights, develop a lookalike model, and perform customer segmentation using clustering techniques. The aim is to understand customer behavior, optimize marketing strategies, and enhance business performance.

## Project Structure

The project comprises three main tasks:

1. **Exploratory Data Analysis (EDA) and Business Insights**:
   - Analyze customer demographics, product performance, and transaction trends.
   - Derive key business insights to inform strategic decisions.

2. **Lookalike Model**:
   - Develop a model to recommend similar customers based on their profiles and transaction history.
   - Generate similarity scores for each recommendation.

3. **Customer Segmentation / Clustering**:
   - Perform customer segmentation using clustering techniques.
   - Evaluate clusters using the Davies-Bouldin Index and visualize the results.

## Dataset

The project utilizes three datasets:

1. `Customers.csv`: Contains customer information.
2. `Products.csv`: Contains product information.
3. `Transactions.csv`: Contains transaction information.

## Deliverables

- Jupyter Notebooks with detailed analyses for each task.
- PDF reports summarizing business insights and clustering results.
- `Lookalike.csv` containing top lookalike customer recommendations and their similarity scores.

## Technologies Used

- Python
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

## Getting Started

1. **Clone the repository**:

   ```sh
   git clone https://github.com/kaustubhdw/eCommerce-Customer-Insights-and-Segmentation-Analysis.git
   cd eCommerce-Customer-Insights-and-Segmentation-Analysis
   ```

2. **Install the required libraries**:

   ```sh
   pip install pandas matplotlib seaborn scikit-learn
   ```

3. **Run the Jupyter Notebooks**:

   ```sh
   jupyter notebook Kaustubh_Dwivedi_EDA.ipynb
   jupyter notebook Kaustubh_Dwivedi_Lookalike.ipynb
   jupyter notebook Kaustubh_Dwivedi_Clustering.ipynb
   ```

## Usage

For command-line execution:

- **Exploratory Data Analysis**:

  ```sh
  python run_eda.py
  ```

- **Lookalike Model**:

  ```sh
  python run_lookalike.py
  ```

- **Customer Segmentation**:

  ```sh
  python run_clustering.py
  ```

## Contributing

Feel free to submit issues or pull requests if you find any bugs or have suggestions for improvements.

