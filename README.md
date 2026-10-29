# Machine Learning for Bankruptcy Prediction 

## Can accounting data from US public companies predict whether they will go bankrupt within the following year? 

#### Dataset
SoWIDE Lab, University of Parma, https://github.com/sowide/bankruptcy_dataset 
#### License
Creative Commons Attribution 4.0 International (CC BY 4.0) 
#### Citation
Lombardo, G., Pellegrino, M., Adosoglou, G., Cagnoni, S., Pardalos, P. M. & Poggi, A. (2022). Machine Learning for Bankruptcy Prediction in the American Stock Market: Dataset and Benchmarks. Future Internet, 14(8), 244. https://doi.org/10.3390/fi14080244 

The data isn't in this repository. Download `dataset_paper.zip` from the dataset above and unzip it, then copy `financial_train.csv`, `financial_validation.csv` and `financial_test.csv` into a folder called `data/raw/`.

#### Folder Structure

    data/raw/                                Data files to download
    notebooks/my_audit.ipynb                 Data audit
    notebooks/my_baseline.ipynb              Baseline model
    requirements.txt                         Python packages needed


#### Setup Steps
Using Python 3.11 on macOS. I used Anaconda which already has everything needed. Otherwise install the packages with:

    pip install -r requirements.txt

#### To Run
From the project folder, start JupyterLab:

    jupyter lab

Then open the `notebooks` folder, open each notebook and run Kernel -> Restart Kernel and Run All Cells.

#### Assistance declaration
I used Claude to help with my code, it fixed errors I had and gave example code with explanations for parts I couldn't write, which I re-typed and checked myself. I also used it to help compare datasets, and spot problems within the data.
