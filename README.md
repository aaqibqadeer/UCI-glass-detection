# UCI Glass Detection Dataset

## Outline

- Importing libraries
- Importing Dataset
- Exploring Dataset
- Preparing Dataset
- Cleaning (removing outliers, normalizing)
- Visualization
- Train/Test Split
- Applying Machine Learning Models
- Summary
- Method 2 to solve dataset (Different method to detect glasses)

## Machine Learning Models that we have applied:

1. KNN
2. Logistic Regression
3. Decision Tree
4. SVM (Linear Kernal)
5. SVM (Non Linear Kernal)
6. Random Forest
7. Neural Network
8. Gradient Decent Tree Boosting



## Attribute Information:

1. Id number: 1 to 214 
2. RI: refractive index 
3. Na: Sodium (unit measurement: weight percent in corresponding oxide, as are attributes 4-10) 
4. Mg: Magnesium 
5. Al: Aluminum 
6. Si: Silicon 
7. K: Potassium 
8. Ca: Calcium 
9. Ba: Barium 
10. Fe: Iron 
11. Type of glass: (class attribute)  -- Label attribute
    1. building_windows_float_processed 
    2. building_windows_non_float_processed 
    3. vehicle_windows_float_processed 
    4. vehicle_windows_non_float_processed (none in this database) 
    5. containers 
    6. tableware 
    7. headlamps











### Data Set Information:  
Vina conducted a comparison test of her rule-based system, BEAGLE, the nearest-neighbor algorithm, and discriminant analysis. BEAGLE is a product available through VRS Consulting, Inc.; 4676 Admiralty Way, Suite 206; Marina Del Ray, CA 90292 (213) 827-7890 and FAX: -3189. In determining whether the glass was a type of "float" glass or not, the following results were obtained (# incorrect answers):

Type of Sample -- Beagle -- NN -- DA  
Windows that were float processed (87) -- 10 -- 12 -- 21  
Windows that were not: (76) -- 19 -- 16 -- 22   

The study of classification of types of glass was motivated by criminological investigation. At the scene of the crime, the glass left can be used as evidence...if it is correctly identified!




### Source:  

**Creator:**  
B. German  
Central Research Establishment  
Home Office Forensic Science Service   
Aldermaston, Reading, Berkshire RG7 4PN   

**Donor:**  
Vina Spiehler, Ph.D., DABFT   
Diagnostic Products Corporation   
(213) 776-0180 (ext 3014)  

https://archive.ics.uci.edu/ml/datasets/glass+identification
