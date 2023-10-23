This is the readme file for the milestone 2.

Find below the details and instructions for the milestone 2.


# Mini Data Analysis project 2 📊

This project is a data analysis project that aims to explore and analyze `cancer_sample` data and in continuation with the previous data analysis. The analysis involves using R programming 📈 and various data manipulation and modeling techniques to answer specific research questions related to breast cancer diagnosis.

## Project Structure 📂

The project is organized as follows:

- **Data** 📦: The project uses the `cancer_sample` dataset, from the `datateachr` package. This data set contains a sample of quantitative features that were calculated from images of nuclei present in fine needle aspiration biopsies of breast masses from patients at the University of Wisconsin Hospital.

- **Tasks** 📝: The project is divided into several tasks, each of which corresponds to a specific stage in the analysis process. The tasks include data processing, summarization, data tidying, modeling, and data output.

- **Code** 💻: The R code for each task and data analysis process is provided in this project. You can find the code for data processing, summary statistics, modeling, and more.

- **Output** 📄: The project generates output data files, including summary tables and model objects. These output files are saved in the "output" folder.

- **README.md** ℹ️: This file serves as the main project documentation, providing an overview of the project, its structure, and how to replicate the analysis.

## Research Questions 🤔

This project aims to answer the following research questions:

1. **How does the diagnosis of breast cancer vary by the size and shape of the tumor cells?**
   - Tasks: Summarization, visualization, modeling
   - Variables: `area_se`, `concavity_worst`, `diagnosis`

2. **What are the most important predictors of breast cancer diagnosis among the variables in the dataset?**
   - Tasks: Summarization, visualization, modeling
   - Variables: `radius_mean`, `symmetry_mean`, `diagnosis`, `smoothness`

3. **How does the diagnosis of breast cancer vary by age and stage of the patients?**
   - Tasks: Summarization, visualization, modeling
   - Variables: `area_mean`, `concavity_worst`, `diagnosis`

4. **How does the diagnosis of breast cancer vary by the smoothness and concavity of the tumor cells?**
   - Task: Summarization, visualization, modeling
   - Variable: `smoothness`, `concavity_worst`

## Analysis Process 📉

- **Data Preprocessing** 🧹: Data cleaning and selection of relevant columns.
- **Summarization** 📊: Calculation of summary statistics for selected variables.
- **Tidying Data** 🧼: Data reshaping to facilitate analysis.
- **Modeling** 🧪: Linear regression model to explore the relationship between variables.
- **Output Generation** 💾: Save summary tables as CSV and model objects as RDS in the "output" folder.

## Replicating the Analysis 🔄

To replicate the analysis in this project, follow these steps:

1. Download the `cancer_sample` dataset from the `datateachr` package (or use your own data) and load it into R.

2. Install and load the necessary R packages, such as `tidyverse`, `ggplot2`, `broom`, and `here`.

3. Run the R scripts provided in the "Code" section of the project. These scripts perform data processing, summarization, modeling, and output generation.

4. Review the generated output files in the "output" folder to access summary tables and model objects.

5. Use the generated model object to make predictions or perform further analysis.

## Output Files 📦

The project generates the following output files:

- `cancer_predictors.csv` 📊: CSV file containing summary statistics for selected variables.
- `model.RDS` 🧾: RDS file containing the fitted linear regression model for predicting `symmetry_mean`.

## Conclusion 📝

This project showcases the use of R programming for data analysis and modeling, with a focus on `cancer_sample` dataset from the `datateachr` package. The analysis results provide insights into how various variables relate to the diagnosis of breast cancer.

Feel free to explore the code and output files to gain a deeper understanding of the analysis process and results.

For questions or further discussions, please reach out. 📧
