#ReadMe

30:04 
Types of data 
![alt text](image-1.png)

Data cleaning
 ![alt text](image-2.png)
 Required data in the numerical form

 ![alt text](image-3.png)


We use sklearn.impute to fill missing values.
It's basically use when we're on the final stage of our application and building pipelines.


"One-Hot Encoding (OHE)"
        One-hot encoding is a technique used to convert categorical data into a numerical format that machine learning models can process. It represents each category as a binary vector.


"Label Encoding"
        Label Encoding is a technique used to convert categorical data (text labels) into numerical values. Each unique category is assigned an integer value.


Ordinal Encoding is best when the categorical values have a meaningful order.
"When to Use Ordinal Encoding?"
    ✅ Ordered Categories (Ordinal Data)

        Education Levels: Primary < Secondary < Graduate < Postgraduate
        Customer Satisfaction: Bad < Average < Good < Excellent
        Rankings: Bronze < Silver < Gold < Platinum

    🚫 Not for Unordered Categories (Nominal Data)

    Colors: Red, Blue, Green (No natural order) → Use One-Hot Encoding instead.
    

"Outliers in ML"
        An outlier is a data point that significantly differs from the rest of the dataset. It is an unusual value that deviates from the expected pattern of data. Outliers can arise due to measurement errors, data corruption, or rare events.
