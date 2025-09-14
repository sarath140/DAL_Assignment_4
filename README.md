# Assignment 4: Gaussian Mixture Models (GMM) and Clustering

- **Name:** Venkata Sarath Chandra Galla
- **Roll Number:** NS25Z287

## Folder Structure
```
DA5401_A4_GMM_Assignment/
├── creditcard.csv
├── DA5401_A4_GMM.ipynb
└── requirements.txt
```

## How to Run
1. Place the raw `creditcard.csv` file in the same folder as the notebook.  
2. (Optional) Create a fresh environment and install dependencies:
   ```bash
   pip install -r requirements.txt
3. Open **DA5401_A4_GMM.ipynb** in Jupyter (Notebook or Lab).
4. 
5. Run all cells sequentially (top → bottom). Plots and tables will render inline.  

## Notebook Contents
- **Part A:** Data exploration, class imbalance analysis, baseline logistic regression  
- **Part B:** Implementing Gaussian Mixture Models (GMM) for clustering   
- **Part C:** Model comparison with precision, recall, and F1-score + visualization and recommendations  

## Reproducibility
- Random seeds fixed for consistent results  
- Stratified train/test split preserves imbalance  
- Test set never resampled (fair comparison)  
- Running with `creditcard.csv` and `requirements.txt` will reproduce results  

