# Vehicle Market Analysis and Segmentation

This repository contains the datasets and execution files for analyzing the vehicle market and identifying optimal strategies for launching new vehicle types. The analysis is divided into two primary objectives:

---

## Objectives

1. **Determine the best type of vehicle to launch in the market**  
   - **Execution File**: `vehicle.ipynb`  
   - **Dataset**: `vehicle dataset.xlsx`  

2. **Identify the target age and income group for vehicle advertisements**  
   - **Execution File**: `segment.ipynb`  
   - **Dataset**: `car_data.csv`

---

## Files in the Repository

### 1. `vehicle.ipynb`
   - **Purpose**: Performs market research and analyzes growth trends for different vehicle types using data from `vehicle dataset.xlsx`.  
   - **Key Insights**:  
     - Calculates CAGR for vehicle types from 2011 to 2024.  
     - Identifies growth trends and determines the most promising vehicle segment.  

### 2. `segment.ipynb`
   - **Purpose**: Segments customers based on age and income groups using `car_data.csv` to identify the optimal target audience for advertisements.  
   - **Key Insights**:  
     - Groups data by gender, age, and income.  
     - Visualizes purchasing patterns using heatmaps.

### 3. `vehicle dataset.xlsx`
   - **Description**: Historical sales data for various vehicle types (Two wheelers, Passenger vehicles, Commercial vehicles, and Three wheelers) used in `vehicle.ipynb`.

### 4. `car_data.csv`
   - **Description**: Customer demographic data, including age, gender, income, and purchasing patterns, used in `segment.ipynb`.

---

## Results

1. **Best Type of Vehicle to Launch**:  
   Based on the analysis in `vehicle.ipynb`, **Passenger Vehicles** are the most promising segment to launch due to their consistent growth rate (CAGR of 4.11%) from 2011 to 2024.

2. **Target Age and Income Group for Advertisements**:  
   As identified in `segment.ipynb`, the optimal customer segment includes:  
   - **Age Group**: 25-35 years  
   - **Income Range**: ₹50,000 - ₹75,000 annually  
   This group exhibits the highest purchasing interest.

---

