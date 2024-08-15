# Experience vs Salary Classification

This project demonstrates a simple example of using logistic regression to classify salary levels based on work experience. The dataset consists of experience (in years) and salary (in currency units). We convert this regression problem into a classification problem by setting a threshold on the salary, and then we predict whether a given experience leads to a "high salary" or "low salary".

## Dataset

The dataset used in this project is a simple, manually created set:

| Experience (years) | Salary |
|--------------------|--------|
| 1                  | 35000  |
| 2                  | 40000  |
| 3                  | 45000  |
| 4                  | 50000  |
| 5                  | 55000  |

### Binary Classification

- **High Salary**: Salary ≥ 45000 is classified as `1`.
- **Low Salary**: Salary < 45000 is classified as `0`.

## Project Structure

- `experience_vs_salary_classification.ipynb`: Jupyter notebook containing the code for logistic regression, confusion matrix generation, and accuracy calculation.
- `README.md`: Documentation of the project.

## How to Run

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/Experience-vs-Salary-Classification.git
    ```
2. Navigate to the project directory:
    ```bash
    cd Experience-vs-Salary-Classification
    ```
3. Install the necessary Python packages:
    ```bash
    pip install -r requirements.txt
    ```
4. Run the Jupyter notebook to see the model training, prediction, and evaluation:
    ```bash
    jupyter notebook experience_vs_salary_classification.ipynb
    ```

## Dependencies

- `numpy`
- `pandas`
- `scikit-learn`
- `matplotlib`
- `seaborn`

You can install these dependencies using pip:
```bash
pip install numpy pandas scikit-learn matplotlib seaborn
