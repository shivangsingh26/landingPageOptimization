# A/B Testing Project

This project conducts an A/B test on simulated click data. It encompasses data preprocessing, visualization, hypothesis testing, and statistical analysis using a two-sample Z-test. Additionally, the project calculates the confidence interval, checks for practical significance, and visualizes the results.

## Technologies Used
- **Programming Language**: Python
- **Package Management**: Pip

## Libraries Utilized
- **Numpy**: Numerical operations
- **Pandas**: Data manipulation and analysis
- **Seaborn**: Statistical data visualization
- **Matplotlib**: Plotting and data visualization
- **Scipy**: Hypothesis Testing and Statistics

## Project Structure
The project is implemented in a Jupyter notebook (`AB Test.ipynb`) which includes markdown cells for documentation and code cells for execution.

## Steps Involved
1. **Data Preprocessing**: Loading, cleaning, and preparing the data for analysis.
2. **Visualization**: Visualizing the distribution of clicks in the control and experiment groups.
3. **Hypothesis Testing**: Performing a two-sample Z-test to determine if the difference in click-through rates between the control and experiment groups is statistically significant.
4. **Confidence Interval Calculation**: Calculating the confidence interval for the test.
5. **Practical Significance Testing**: Evaluating the practical significance of the results.

## How to Run
1. **Clone the Repository**:
    ```sh
    git clone https://github.com/shivangsingh26/landingPageOptimization.git
    cd ab-testing-project
    ```

2. **Create a Virtual Environment**:
    ```sh
    python -m venv abTest
    ```

3. **Activate the Virtual Environment**:
    - On Windows:
        ```sh
        abTest\Scripts\activate
        ```
    - On macOS/Linux:
        ```sh
        source abTest/bin/activate
        ```

4. **Install the Required Libraries**:
    ```sh
    pip install -r requirements.txt
    ```

5. **Open the Jupyter Notebook**:
    ```sh
    jupyter notebook "AB Test.ipynb"
    ```

6. **Run the Notebook**: Execute the cells in order.

## Results
The results of the A/B test, including the p-value, confidence interval, and practical significance, are presented in the notebook. Various plots, including a Gaussian distribution with the rejection region, are used to visualize the results.

## License
This project is licensed under the terms of the [MIT License](https://opensource.org/licenses/MIT).
