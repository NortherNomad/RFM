# RFM Analysis

This Python script performs RFM (Recency, Frequency, Monetary) analysis on a customer transaction dataset to segment customers based on their behavior.

## Description

The script reads a dataset containing customer transaction information, calculates RFM values for each customer, and segments them into different classes. It then exports the processed data to a CSV file named `final.csv`.

## Steps

1. **Read Data**: Read the dataset from a CSV file (`data.csv`) and preprocess it.
   
2. **Calculate RFM**:
   - **Recency (R)**: Calculate the recency of each customer based on their last order date.
   - **Frequency (F)**: Calculate the frequency of orders for each customer.
   - **Monetary (M)**: Calculate the total monetary value of orders for each customer.

3. **Segmentation**:
   - Segment customers based on their RFM values into different classes.

4. **Export Data**: Save the segmented data to a CSV file named `final.csv`.

## Files

- **data.csv**: Input dataset containing customer transaction information.
- **final.csv**: Processed data after RFM analysis and segmentation.
- **RFM_Analysis.ipynb**: Jupyter Notebook containing the code for RFM analysis.

## Requirements

- pandas
- numpy
- matplotlib

## Usage

1. Ensure you have the required libraries installed (`pandas`, `numpy`, `matplotlib`).
2. Place your dataset (`data.csv`) in the same directory as the script.
3. Run the script.
4. Check the output file `final.csv` for the segmented data.
