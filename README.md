# Classification-on-Thyroid-Data

The aim of this project is to classify patients with different types of thyroid related diseases given their age, sex, and medical information – including test results for thyroid hormone levels in blood.

The data was obtained from a UCI machine learning repository. The latter contains numerous text files with different subsets of the data. One of them holds information concerning 9172 unique patients as well as a medical diagnosis chosen out of 20 possible classes, making up 7 distinct diagnosis types. This study focuses on three of the diagnoses:

* negative
* hypothyroid
* hyperthyroid

## Data Description
In order to accurately analyse the data, it is crucial to understand its nature and the subject at hand.

The thyroid, an endocrine gland, creates and produces hormones that play a role in many different systems throughout your body. When your thyroid makes either too much or too little of these important hormones, it’s called a thyroid disease.

As previously mentioned, some of the variables in the dataset store hormonal measurements: TSH, T3, Total T4 (TT4), and Free T4 Index (FTI). 

1. An elevated **TSH** level suggests insufficient production of thyroid hormone by the thyroid gland, indicating primary hypothyroidism. Conversely, a decreased TSH level typically signifies an excessive production of thyroid hormone, indicative of hyperthyroidism.
  TSH normal values are 0.5 to 5.0 mIU/L

2. The **Total T3** test assesses both the bound and free forms of triiodothyronine. Elevated Total T3 levels are commonly observed in individuals with hyperthyroidism. Utilizing T3 tests can aid in confirming a diagnosis of hyperthyroidism and gauging the severity of the condition.
   A normal Total T3 level in adults ranges from 80-220 ng/dL

3. A **Total T4 test** evaluates the levels of both bound and free thyroxine (T4) hormone present in the bloodstream. Medications and medical conditions altering thyroid hormone binding proteins can influence Total T4 readings. Elevated thyroid hormone binding proteins, attributed to factors like estrogen, oral contraceptive pills, pregnancy, liver disease, and hepatitis C virus infection, lead to a higher Total T4. Conversely, decreased thyroid hormone binding proteins, often caused by testosterone, androgens, and anabolic steroids, result in a lower Total T4.
   A normal Total T4 level in adults ranges from 5.0 to 12.0μg/dL

5. **T4U tests** measure thyroxine (T4) utilization rate in the body. They can help measure how well the body is utilizing T4 hormone.

6. A **Free T4 Index** measures what is not bound and able to freely enter and affect the body tissues. Tests measuring free T4 index (FTI) usually more accurately reflect how the thyroid gland is functioning.
   FT4 normal values are 0.7 to 1.9ng/dL

References and credit:
Quinlan,Ross. (1987). Thyroid Disease. UCI Machine Learning Repository. https://doi.org/10.24432/C5D010.
