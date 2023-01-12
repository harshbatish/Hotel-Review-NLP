# Hotel-Review-NLP

This project aims to analyse the customer behaviour of giving the ratings to the hotels based on different factors and the text of the reviews given by the customers.

Number of samples taken into consideration while making this project is more than 500 thousand and also has around 17 features.

---
### Data dictionary:

1. __Hotel_Address__
2. __Additional_Number_of_Scoring:__ Don't really know what this column represents, anyways this is not used
3. __Review_Date__
4. __Average_Score:__ Average of the 2nd column
5. __Hotel_Name__
6. __Reviewer_Nationality__
7. __Negative_Review:__ Text of review which is negative
8. __Review_Total_Negative_Word_Counts__
9. __Total_Number_of_Reviews__
10. __Positive_Review:__ Text of review which is positive
11. __Review_Total_Positive_Word_Counts__
12. __Total_Number_of_Reviews_Reviewer_Has_Given__
13. __Reviewer_Score__: _TARGET FEATURE/COLUMN
14. __Tags:__ This column represents what type of room did the reviewer lived in during the visit
15. __days_since_review__
16. __lat:__ Geographical coordinate of the hotel
17. __lng:__ Geographical coordinate of the hotel

---

### Data Files:

1. Data


---

### Structure of the project:

1. __EDA.ipynb__: This notebook converts all the columns into the numerical data. Postive and negative reviews are converted to numerics using TF-IDF.
2. __Modelling.ipynb__: This notebook has 3 types of models to predict the target column which is __rating__ using 3 models: Logostic Regression, KNN, and decision trees. k-fold cross-validation and feature engineering is also done.



---
