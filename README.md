# Next-Gen-Predictions-for-Diamond-Price
Explore our advanced predictive model for forecasting diamond prices. Utilizing cutting-edge data analytics and machine learning, this project offers precise insights into future market trends, helping stakeholders make informed decisions in the dynamic diamond industry.

## Data Source
The data for this project is taken from Kaggle. 

## Data Description
The data taken from Kaggle includes multiple columns about the diamonds.
### There are 10 independent variables (including id):

* id - unique identifier of each diamond
* carat - Carat (ct.) refers to the unique unit of weight measurement used exclusively to weigh gemstones and diamonds.
* cut - Quality of Diamond Cut
* color - Color of Diamond
* clarity - Diamond clarity is a measure of the purity and rarity of the stone, graded by the visibility of these characteristics under 10-power magnification.
* depth - The depth of diamond is its height (in millimeters) measured from the culet (bottom tip) to the table (flat, top surface)
* table - A diamond's table is the facet which can be seen when the stone is viewed face up.
* x - Diamond X dimension
* y - Diamond Y dimension
* x - Diamond Z dimension
### Target variable:
* price - Price of the given Diamond.

## Data Cleaning
* Remove Duplicates - Identified and removed duplicate records to ensure each 
entry in the dataset is unique, preventing redundancy and maintaining data 
integrity.

* Outlier Removal - We identify and address outliers that could skew results and impact model accuracy. 
By applying methods Interquartile Range (IQR), we ensure that extreme values are handled 
appropriately, enhancing the reliability of our dataset.

* Data Scaling - To normalize data and ensure consistent feature contribution, we implement scaling techniques StandardScaler. This step 
transforms data into a uniform range, improving model performance and convergence.

