
# Data Analysis on Emergy Metabolism Dataset

This repository contains a Jupyter Notebook for performing exploratory data analysis (EDA) on the **Emergy Metabolism** dataset, focusing on 281 cities in China from 2000 to 2020. The analysis provides insights into energy, material, and population flows within these cities, with visualizations to help understand trends and correlations.

## Prerequisites

### General Requirements
- **Python 3.8 or higher**
- **Google Colab** (Cloud environment setup)
- **Internet connection** for installing dependencies

### 1. **Local Environment Setup**

To run the analysis locally, follow these steps:

#### Install Python and Jupyter Notebook

1. Install **Python** (version 3.x). You can download it from [python.org](https://www.python.org/downloads/).
   
2. Install **Jupyter Notebook** via `pip`:
   ```bash
   pip install notebook
   ```

3. Install other required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn openpyxl
   ```

#### Cloning the Repository

1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/your_username/your_repository.git
   ```

2. Navigate to the repository:
   ```bash
   cd your_repository
   ```

#### Running the Notebook

1. Start the Jupyter Notebook server:
   ```bash
   jupyter notebook
   ```

2. The Jupyter interface will open in your web browser. Navigate to the `code/EDA_on_Emergy_Metabolism_Corrected.ipynb` notebook and run the cells.

3. If necessary, adjust the path to the dataset (`data/Emergy flows of 281 China's cities 2000-2020.xlsx`) in the notebook to ensure it matches the relative path from the `code` folder:
   ```python
   data_file_path = "../data/Emergy flows of 281 China's cities 2000-2020.xlsx"
   ```

---

### 2. **Cloud Environment Setup**

#### Using GitHub Codespaces

1. Navigate to the repository on GitHub.
2. Click the **Code** button and select **Open with Codespaces**. If you haven't set up a codespace yet, you will need to create one.
3. Once the Codespace is ready, it will open in a cloud-based IDE where you can directly run the notebook.

#### Using Google Colab

1. Navigate to [Google Colab](https://colab.research.google.com/).
2. Select **GitHub** from the **Open** menu and enter the URL of this repository.
3. Select the notebook (`EDA_on_Emergy_Metabolism_Corrected.ipynb`).
4. In Colab, ensure the dataset is properly linked:
   - Either upload the dataset manually or link the `data` folder from your GitHub repository.
   - Make sure the code to load the dataset uses the correct relative path:
     ```python
     data_file_path = "../data/Emergy flows of 281 China's cities 2000-2020.xlsx"
     ```

---

## Dataset

The dataset used in this analysis is the **Emergy Metabolism** dataset, which provides data on the energy, material, and population flows for 281 cities in China from 2000 to 2020. The dataset is located in the `data` folder of the repository.

### File Structure

```
your_repository/
├── code/
│   └── EDA_on_Emergy_Metabolism_Corrected.ipynb  # Jupyter Notebook for EDA
├── data/
│   └── Emergy flows of 281 China's cities 2000-2020.xlsx  # Dataset file
└── README.md  # This file
```

---

## Troubleshooting

- **File Path Errors**: If the notebook cannot find the dataset, ensure the relative file path is correct. If you're using a cloud environment, make sure the dataset is either uploaded to the environment or properly linked to the repository.
- **Missing Dependencies**: If you encounter any missing libraries or modules, you can install them using `pip`, as described in the Local Environment Setup section.

---

## Conclusion

This repository provides a clear methodology for performing exploratory data analysis (EDA) on the Emergy Metabolism dataset. By following the setup instructions for your chosen environment, you should be able to run the analysis and explore the insights from the data.

For further questions or issues, please contact the repository maintainers or open an issue on GitHub.
