# fuzzy-tsukamoto-batik-production
Analysis of the accuracy level of the Fuzzy Tsukamoto method to determine the production quantity of batik sarongs using Python

## Description
This repository contains a project that analyzes the **accuracy of the Fuzzy Tsukamoto method** in determining the optimal production quantity of batik sarongs.  
The fuzzy approach is applied as a **decision support system** to assist production planning based on demand and inventory conditions.

The analysis is implemented using **Python** and executed through **Google Colab**.

---

## Objectives
- To determine batik sarong production quantity using the Fuzzy Tsukamoto method  
- To evaluate the accuracy of fuzzy-based production results compared to actual data  
- To demonstrate the application of a Fuzzy Inference System in production planning  

---

## Variables
### Input Variables
- Permintaan
- Persediaan
- Harga Bahan Baku
- Jumlah Tenaga Kerja 

### Output Variable
- Jumlah Produksi 

---

## Methodology
1. Fuzzification of input variables  
2. Inference using the Tsukamoto method  
3. Defuzzification using the Weighted average method  
4. Comparison between fuzzy results and actual production data  
5. Accuracy measurement using Mean Absolute Percentage Error (MAPE)  

---

## Tools & Libraries
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- scikit-fuzzy  

---

## How to Use (Google Colab)

### 1. Open the Notebook
- Open the file `fuzzy-tsukamoto-batik-production.ipynb` in this GitHub repository
- Click **Open in Colab**

---

### 2. Install Required Libraries
Run the following cell in Google Colab

---

### 3. Run the Analysis

Execute all notebook cells sequentially

The system will calculate production quantity using the Fuzzy Tsukamoto method

Calculation results and accuracy analysis will be displayed as outputs and visualizations

---

## Data and Calculation Results

The input data and calculation results used in this analysis can be accessed through the following Google Spreadsheet:

https://docs.google.com/spreadsheets/d/1DFTsDaQU5aqR97HlKPUtYSCmmJpKToagtQS4y1LXsL8/edit

---

## Results Summary

The results show that the Fuzzy Tsukamoto method is able to generate production quantity estimates that are close to actual data, indicating that this method is suitable as a decision support tool for batik sarong production planning.

---

## Future Work

Comparison with other fuzzy methods such as Sugeno and Tsukamoto

Addition of more input variables

Optimization of the fuzzy rule base

---

## Author

Muhammad Dwiko Rizqi
Bachelor of Mathematics
Data Analysis Enthusiast
