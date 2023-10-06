# Data_Prep

## FedEx Project - DATA PREP

### Overview
The FedEx Data Preparation Project focuses on making the dataset ready for analysis and modeling to achieve on-time delivery and minimize package misplacement for FedEx shipments.

### Dataset
- **Name**: fedex.csv
- **Dimensions**: 3604175 rows, 15 columns
- **Dependent Variable**: Delivery_Status

### Objective
- Deliver packages on time.
- Minimize misplacement of packages.

### Constraints
- Ensure on-time delivery with minimal differences between actual and planned shipment times.
- Optimize delivery routes between source and destination.

### Requirements
- Jupyter Notebook

### Data Preprocessing

#### Business Moments
- Important insights related to the business context of the dataset influenced data preparation decisions.

#### Data Cleaning
- Handled missing values using imputation methods.
- Removed duplicates from the dataset.
- Addressed outliers using appropriate techniques.
- Typecasted and converted data types as needed.
- Handled NaN (Not-a-Number) values in the dataset.

#### Data Scaling and Transformation
- Applied scaling techniques (e.g., Robust Scaling, Min-Max Scaling).
- Utilized Box-Cox transformation with specific lambda values.
- Performed one-hot encoding for categorical variables.
- Applied feature engineering, including discretization.
- Employed encoding methods for categorical variables.
- Implemented various transformation techniques.
- Described the scaling techniques applied to the data.
