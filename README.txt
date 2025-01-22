## Requirements
The code requires the following libraries:
- `pandas`
- `numpy`
- `matplotlib`

Ensure these libraries are installed before executing the code. If not, you can install them:
```
pip install pandas numpy matplotlib
```

## Usage

1. **Open the Notebook**  
   It is recommended to open the notebook (`q2main.ipynb`) using Jupyter Notebook:
   ```
   jupyter notebook main.ipynb
   ```

2. **Import Data**  
   Load the required datasets by saving your training and testing files in CSV format:
   - `x_train.csv` for training features
   - `y_train.csv` for training labels
   - `x_test.csv` for testing features
   - `y_test.csv` for testing labels

3. **Executing the Code**  
   In Jupyter Notebook, go to **Kernel** > **Restart & Run All** to execute all cells from the beginning. This will load the datasets, train the model, and display results, including accuracy and confusion matrix.

4. **Modifying Data Load**  
   You may adjust the initial data loading steps if you have alternative data sources or formats. The initial cells perform some manipulations to format dataframes (such as renaming columns for labels), which you may adapt as needed.

## Parameters and Default Values
- **`header=None` for `y_train` and `y_test`**: Specifies no header row in label files.
- **Label Mapping**: Labels are mapped as:
  - `0` = Negative
  - `1` = Neutral
  - `2` = Positive

## Output Interpretation
The final output cells display:
- **Model Accuracy**: Printed to the console after evaluation.
- **Confusion Matrix**: Output includes the count of each prediction type for further analysis.

Each output cell is organized in sections for readability and ease of interpretation.
