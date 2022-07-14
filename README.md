# CRE-Investment-Forecasting-Using-ML

A supervised machine learning model that can accurately predict which cities and property types to invest in based on multivariate analysis, KPI weighting, and a combination of logistic regression / random forest models. This ML model is tested and trained on datasets which have been sourced from [CoStar Analytics](https://www.costar.com/products/analytics) and [Oxford Economics](https://www.oxfordeconomics.com/service-category/real-estate/) in order to create six scenarios that will emulate numerous market conditions:

1. Base Case (control group)
2. Interest Rate Shock
3. Trend Growth                                    
4. Depression
5. Moderate Upside
6. Moderate Downside

#### **A note on using variables**

* All variables with an `mf_` prefix are utilized for multifamily-related variables
* All variables with a `off_` prefix are utilized for office-related variables
* All variables with an `ret_` prefix are utilized for retail-related variables
* All variables with an `ind_` prefix are utilized for industrial-related variables

## Complete Project Documentation Coming Soon

### Documentation will include:

* Model Setup
* Steps Used in Feature Engineering (from Binning to Scaling)
* Development of Logistic Regression & Random Forest Models
* In-Depth Model Evaluation / Analysis
* Use of Class Balancing to Improve Model Accuracy
* Implementaion of `scikit-learn` and `SciPy` Libraries for Model's Train-Test Splits
* Execution of Variable Encoding (to Aid the ML Algorithm)
* Plotting & Analyzing the ROC Curve / Confusion Matrix
* Optimizing the Model's Bias & Variance to Improve Performance on Test Data

### **Note:** This is a large scale ML model and it is currently a work in progress which is solely operating on my local machine at this time. Raw code files and documentation will be released as soon as this project is completed.

* Also, each raw dataframe contains literally millions of datapoints **per asset type**, and there are four asset types. The dataframe for multifamily properties alone features exactly 57,438,193 individual datapoints.
