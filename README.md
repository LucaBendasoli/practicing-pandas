# Practicing Pandas

This repository contains a Jupyter Notebook that I used for practicing data manipulation and analysis using the Pandas library in Python.

## Project Structure

- **main.ipynb**: The main Jupyter Notebook containing the exercises and solutions.
- **pandas_practice_dataset.csv**: The dataset used for the exercises.
- **requirements.txt**: A list of Python dependencies required for the project.
- **.gitignore**: Specifies files and directories to be ignored by Git.
- **.gitattributes**: Specifies attributes for pathnames.

## Setup

1. Clone the repository:
    ```sh
    git clone https://github.com/LucaBendasoli/practicing-pandas.git
    ```

2. Navigate to the project directory:
    ```sh
    cd practicing-pandas
    ```

3. Install the required dependencies:
    ```sh
    pip install -r requirements.txt
    ```

4. Start Jupyter Notebook:
    ```sh
    jupyter notebook
    ```

5. Open main.ipynb in Jupyter Notebook to start practicing.

## Exercises

The notebook contains exercises to practice Pandas operations. Each exercise is labeled with a question number and includes the corresponding solution. Here are some examples:

- **Question 1**: Select specific rows and columns using iloc.
    ```python
    # Answer to the question 1
    df.iloc[:10, [1, 2, 4]]
    ```

- **Question 2**: Filter rows based on a condition.
    ```python
    # Answer to the question 2
    df[df['Income'] > 50000]
    ```

- **Question 3**: Complex filtering with multiple conditions.
    ```python
    # Answering question 3
    df[((df['Age'] > 30) & (df['Income'] > 70000)) & ((df['City'] == "Los Angeles") | (df['City'] == "New York"))]
    ```

- **Question 4**: Select specific columns and filter rows based on a range of values.
    ```python
    # Answering question 4
    df[(df['ID'] >= 5) & (df['ID'] <= 15)]['Name Income Purchase_Amount'.split()]
    ```
