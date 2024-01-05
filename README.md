# Programming-for-Data-Analysis-Project

Author: Francesco Troja

This repository serves as a key resource for the final project of the **HDip in Computing within ATU University's Data Analytics program**, specifically for the **Programming in Data Analytics** module. It contains a *Jupyter notebook* named `project2.ipynb`, which encapsulates detailed analyses, and supplementary visualizations stored in the plot folder.

## Problem Statement

• Analyse CO2 vs Temperature Anomaly from 800kyrs – present;
• Examine one other (paleo/modern) features (e.g. CH4 or polar ice-coverage);
• Examine Irish context;
• Fuse and analyse data from various data sources and format fused data set as a pandas dataframe and export to csv and json formats;
• For all of the above variables, analyse the data, the trends and the relationships between them (temporal leads/lags/frequency analysis);
• Predict global temperature anomaly over next few decades (synthesise data) and compare to published climate models if atmospheric CO2 trends continue;
• Comment on accelerated warming based on very latest features (e.g. temperature/polar-icecoverage).

## How to download the Repository

Access the provided link: [Project](https://github.com/C-3sc0/Programming-for-Data-Analysis-Project) and select the `<> Code` button. There are two options for accessing the Jupyter Notebook:

- Download it as `ZIP file`;
- clone the repository using the provided `HTTPS link` and integrate it into your local machine.

## Repository's Content

- A file named **README.md**;
- The [`project2.ipynb`](https://github.com/C-3sc0/Programming-for-Data-Analysis-Project/blob/main/project2.ipynb). The file includes an in-depth analysis and commentary on key features related to climate change.;
- The [`Irish-Dataset`](https://github.com/C-3sc0/Programming-for-Data-Analysis-Project/tree/main/Irish-Dataset) directory comprises datasets related to Irish temperature and rainfall records spanning the years 1711 to the present day.
- The [`dataset`](https://github.com/C-3sc0/Programming-for-Data-Analysis-Project/tree/main/dataset) directory comprises datasets related to global perspectives on $CO_2$, temperature anomaly, and $N_2O$ over the past 800,000 years to the present day.
- The [`merged_dataset`](https://github.com/C-3sc0/Programming-for-Data-Analysis-Project/tree/main/merged_dataset) directory comprises a combination of global and Irish datasets that have been fused and converted into both `.CSV` and `.JSON` formats.
- A folder labeled [`plot`](https://github.com/C-3sc0/Programming-for-Data-Analysis-Project/tree/main/plot) where all graphs or images used during the analysis are stored.

## Technologies Used

The project utilizes **Python 3** as its primary technology stack. To execute the code within the Jupyter Notebook, it's essential to have Python 3 or a higher version installed. The official Python package can be obtained from the [Python website](https://www.python.org/downloads/) for download and installation. The utilization of Python 3 ensures compatibility with an extensive array of libraries and tools.
The libraries employed in the current notebook include:

- **Pandas** (The documentation can be found in the following link: [Pandas](https://pandas.pydata.org/docs/));
- **Matplotlib** (The documentation can be found in the following link: [Matplotlib](https://matplotlib.org/stable/index.html));
- Numpy (The documentation can be found in the following link: [Numpy](https://numpy.org/doc/stable/));
- **Scipy** (The documentation can be found in the following link: [Scipy](https://docs.scipy.org/doc/scipy/));
- **Seaborn** (The documentation can be found in the following link: [Seaborn](https://seaborn.pydata.org/));
- **Os** (The documentation can be found in the following link: [Os](https://docs.python.org/3/library/os.path.html)).

The majority of the required libraries are typically pre-installed in the Python environment. In cases where a library is not present, the `pip command``, serving as the Python package installer, can be employed. To facilitate the installation process, open the terminal and execute the following command:

```python
pip install library_name
```

It's important to substitute "library_name" with the actual name of the library intended for installation.

## References

In the notebook, references are appropriately cited within the sections where they're utilized and compiled at the end. While some references might not be directly applied in the notebook, they were consulted to enhance comprehension of the related topics covered.
